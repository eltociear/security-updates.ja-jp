---
TOCTitle: 'ウイルス情報 : SQL Server および MSDE を標的とした Slammer ワームに関する情報'
Title: 'ウイルス情報 : SQL Server および MSDE を標的とした Slammer ワームに関する情報'
ms:assetid: '6d9f9aeb-5607-4539-9ef3-d021e64611b0'
ms:contentKeyID: 19871884
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362939(v=TechNet.10)'
---

SQL Server および MSDE を標的とした SQL Slammer ワームに関する情報
==================================================================

公開日: 2003年1月26日

[**更新履歴**](https://technet.microsoft.com/ja-jp/library/b895b0ee-772e-4052-b783-97dacdc306e3(v=TechNet.10))

##### トピック

[](#efaa)[はじめに](#efaa)
[](#eeaa)[本ワームの感染が行われてしまう条件](#eeaa)
[](#edaa)[影響を受ける恐れのある製品](#edaa)
[](#ecaa)[本ワームへの対策](#ecaa)
[](#ebaa)[対策による影響](#ebaa)
[](#eaaa)[osql コマンドについて](#eaaa)

### はじめに

日本時間 2003 年 1 月 25 日 午後 2 時頃より Slammer ワームと呼ばれる Microsoft SQL Server 2000 および MSDE 2000 (以下 SQL Server として表記します) を対象としたウイルス感染による被害が発生しました。弊社では、このワームによる影響からお客様の環境を守るため、情報を公開いたします。(別名に W32/SQLSlammer.worm, W32.SQLExp.Worm, W32/SQLSlammer 等があります)

本ワームは SQL Server 2000 に対して、UDP 1434 ポート (SQL Server 2000 解決サービスで使用するポート) に対して UDP の攻撃パケットを送信します。攻撃を受けた SQL Server 2000 は、下の条件を満たしている場合に本ワームに "感染" し、SQL Server 2000 のプロセス内でプログラムコードが実行されてしまいます。"感染" されてしまった SQL Server 2000 のプロセスは、自らが攻撃者となり他のシステムに対して "感染" 活動を開始します。

本ワームは、"感染" 活動を行うことが目的であり、SQL Server 2000 のデータベースの書き換えや感染ファイルの作成などは行われません。しかしながら、感染活動により UDP パケットがネットワークの帯域を消費し、結果的にネットワーク全体のスループットが低下する恐れがあります。 また、感染をしてしまった SQL Server 2000 の CPU 消費が極端に上昇し、コンピュータ全体のパフォーマンスの低下も発生します。

弊社 STPP パートナーであるウイルス対策ソフトウェアベンダー各社からも、本ワームに関する情報が公開されておりますので併せてご参照ください。

-   インターネット セキュリティ システムズ株式会社
    [http://www.isskk.co.jp/support/techinfo/general/X-ForceslammerWorm.html](http://www.isskk.co.jp/support/techinfo/general/x-forceslammerworm.html)![](images/Dd362939.leave-ms(ja-jp,TechNet.10).gif)

-   株式会社シマンテック
    <http://www.symantec.co.jp/region/jp/sarcj/data/w/w32.sqlexp.worm.html>![](images/Dd362939.leave-ms(ja-jp,TechNet.10).gif)

-   トレンドマイクロ株式会社
    [http://www.trendmicro.co.jp/vinfo/virusencyclo/default5.asp?VName=WORM\_SQLP1434.A](http://www.trendmicro.co.jp/vinfo/virusencyclo/default5.asp?vname=worm_sqlp1434.a)![](images/Dd362939.leave-ms(ja-jp,TechNet.10).gif)

-   マカフィー株式会社
    [http://www.mcafee.com/japan/security/virS2003.asp?v=W32/SQLSlammer.worm](http://www.mcafee.com/japan/security/virs2003.asp?v=w32/sqlslammer.worm)![](images/Dd362939.leave-ms(ja-jp,TechNet.10).gif)

[](#mainsection)[ページのトップへ](#mainsection)

### 本ワームの感染が行われてしまう条件

-   SQL Server が使用している UDP 1434 ポートをインターネットとの接続を行っているルータもしくはファイヤウォールで遮断していない場合

-   SQL Server 2000 Service Pack 3 もしくは、[MS02-039 SQL Server 2000 解決サービスのバッファのオーバーランによりコードが実行される (Q323875)](http://www.microsoft.com/japan/technet/security/bulletin/ms02-039.mspx)、または MS02-039 以降に公開された SQL Server 2000 向けセキュリティ修正プログラムを適用していない場合

[](#mainsection)[ページのトップへ](#mainsection)

### 影響を受ける恐れのある製品

-   Microsoft SQL Server 2000 Enterprise Edition

-   Microsoft SQL Server 2000 Standard Edition

-   Microsoft SQL Server 2000 Personal Edition

-   Microsoft SQL Server 2000 Developer Edition

-   Microsoft SQL Server 2000 Desktop Engine (MSDE 2000)

**注意 :** Microsoft SQL Server 4.2J, 6.5, 7.0 は本ワームの影響を受けません。

#### MSDE 2000 を既定でインストールする製品

下記の製品は、MSDE 2000 を既定でインストールします。

-   Microsoft Windows XP Embedded \#1

-   Microsoft Windows XP Embedded with Service Pack 1 \#1

-   Microsoft Server Appliance Kit 2.0 Add-On Pack \#2

-   Microsoft Visio Enterprise Network Tools

-   Microsoft Project Server 2002

-   Microsoft Application Center 2000

\#1: [Microsoft Windows XP Embedded](http://www.microsoft.com/japan/windows/embedded/eval/xpe/default.mspx) は、一般に販売されている [Microsoft Windows XP](http://www.microsoft.com/japan/windowsxp/default.mspx) とは異なる製品です。

\#2: Network Attached Storage (NAS) 製品等に搭載されている Microsoft Server Appliance Kit 2.0 は、Windows 2000 および MSDE 英語版をベースにしておりますので、修正プログラムは、英語版をご利用ください。

**注意 :** 以前本項目に SQL Server 2000 と連携をおこなう**可能性のある**製品の一覧を記載しておりましたが、誤解を受ける可能性があるため、削除をいたしました。影響を受ける MSDE 2000 を既定でインストールする製品一覧に変更いたしました。

MSDE 2000 が同梱されている製品一覧は、[「よくある質問と回答」](https://technet.microsoft.com/ja-jp/library/626ad711-945f-44ed-b8a8-c5865f070574(v=TechNet.10))の「MSDE 2000 はどのような製品に含まれますか？」をご覧ください。

[](#mainsection)[ページのトップへ](#mainsection)

### 本ワームへの対策

本ワームの対策は、感染の有無にかかわらず同じ対策を行うことで、感染を防ぐことが出来ます。 最新の SQL Server 2000 の累積的修正プログラム [MS02-061](http://www.microsoft.com/japan/technet/security/bulletin/ms02-061.mspx) の適用による対策をご紹介しております。 アプリケーションへの影響等が懸念される場合は、[MS02-039](http://www.microsoft.com/japan/technet/security/bulletin/ms02-039.mspx) のみを適用することでも対策可能です。 可能な限り、 MS02-039 の修正を含む MS02-061 または、[SQL Server 2000 Service Pack 3](http://www.microsoft.com/japan/sql/prodinfo/previousversions/downloads/2000/sp3.mspx) 以降の最新のサービスパックの適用をお勧めいたします。

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>SQL Critical Update による対策</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>マイクロソフトは、実行されているコンピュータで Slammer ワームの影響を受ける SQL Server 2000 および MSDE 2000 のインスタンスをスキャンし、影響を受けるファイルを更新する SQL Critical Update をリリースしました。</p>
<p><a href="https://technet.microsoft.com/ja-jp/library/8e036289-2cbb-4d14-96d9-82c5024e5f93(v=TechNet.10)">SQL Critical Update</a></p>  
<p><strong>システム要件</strong></p>  
<ul>  
<li><p>オペレーティングシステム : Windows NT 4.0, Windows 2000, Windows XP</p>  
<p>SQL Server 2000 評価版をご利用のお客様も適用可能です。</p></li>  
</ul>  
<p><strong>制限</strong></p>  
<ul>  
<li><p>SQL Critical Update はWindows 95、Windows 98 または Windows ME では動作しません。</p></li>  
<li><p>SQL Critical Update の使用はクラスタ化された環境ではサポートされません。</p></li>  
<li><p>SQL Critical Update は、確認した脆弱性を常に修正します。単に SQL Server のインスタンスを無効にするための使用はできません。</p></li>
</ul></td>
</tr>
</tbody>
</table>
<p> </p>

**重要 :** Microsoft SQL Server 2000 Service Pack 3 を適用する場合は、お客様のアプリケーションの動作に支障が無いことを十分に検証の上、適用いただきますようお願いいたします。

以下の手順では、MS02-061の修正プログラムの適用方法について解説しています。SQL Server 2000 Service Pack 3 / MSDE 2000 Service Pack 3 の適用に関しては、[SQL Server 2000 SP 3 インストールに関する注意点](http://www.microsoft.com/japan/sql/prodinfo/previousversions/downloads/2000/sp3install.mspx) のページもあわせてご確認ください。

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Step 1: SQL Server が動作しているかを確認する</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>コマンドによる確認方法</strong></p>
<p>SQL Server が動作している場合、他のコンピュータから接続を受け付けるために、1434/UDP ポートが開かれています。ポートが開かれているかは、次のコマンドで確認することができます。</p>  
<p><strong>netstat -an</strong></p>  
<p>コマンドを実行すると以下のような結果が表示されます。結果に UDP 0.0.0.0:1434 と表示された行がある場合は、SQL Server が動作しています。表示の行ない場合は、ワームに感染する恐れはありません。</p>  
<p></p>  
<pre><code>C:\&gt;netstat -an  
Active Connections  
  Proto  Local Address          Foreign Address        State  
  TCP    0.0.0.0:135            0.0.0.0:0              LISTENING  
  TCP    0.0.0.0:445            0.0.0.0:0              LISTENING  
(省略)  
  UDP    0.0.0.0:1434           *:*</code></pre>  
<p><strong>ツールによる確認方法</strong></p>  
<p><strong>SQL Scan ツールによる確認方法</strong></p>  
<p>マイクロソフトは、Slammer ワームの影響を受ける可能性のある SQL Server のインスタンスを検知する SQL Scan というツールをリリースしました。</p>  
<p><strong>注意 :</strong> 本ツールは、英語版のみですが、日本語環境でもご使用いただけます。</p>  
<p><a href="https://technet.microsoft.com/ja-jp/library/a508ea10-a903-4bf6-a57b-e376604b0f14(v=TechNet.10)">SQL Scan ツール (SQL Scan)</a></p>  
<p>このユーティリティは、Windows NT 4.0、Windows 2000、Windows XP またはそれ以降の Microsoft SQL Server 2000 および SQL Server 2000 Desktop Engine (MSDE 2000) のインスタンスを検索し、Slammer ワームの影響を受ける可能性のある SQL Server のインスタンスを検知します。SQL Scan は個々のコンピュータ、Windows ドメインまたは特定の IP アドレスの範囲をスキャンします。</p>  
<p>SQL Scan を実行すると以下のような結果が表示されます。結果に <strong>NON-VULNERABLE</strong> と表示された場合は対策済みです。Slammer ワームによる影響はありません。</p>  
<p>結果に <strong>VULNERABLE</strong> と表示された場合、影響を受ける恐れがあります。</p>  
<p><strong>対策済み</strong></p>  
<pre><code>FOUND: ssnetlib.dll @version=2000.80.479.0  
FOUND: sqlservr.exe @version=2000.80.384.0  
NON-VULNERABLE: server=JPSQL instance=MSSQL$NetSDK version=SP1 language=1041 platform=NT os=5.0  
FOUND: ssnetlib.dll @version=2000.80.311.0  
FOUND: sqlservr.exe @version=2000.80.194.0  
NON-VULNERABLE: server=JPSQL instance=MSSQLSERVER version=RTM language=1041 platform=NT os=5.0</code></pre>  
<p><strong>要対策</strong></p>  
<pre><code>FOUND: ssnetlib.dll @version=2000.80.382.0  
FOUND: sqlservr.exe @version=2000.80.384.0  
VULNERABLE: server=JPSQL instance=MSSQL$NetSDK version=SP1 language=1041 platform=NT os=5.0  
FOUND: ssnetlib.dll @version=2000.80.194.0  
FOUND: sqlservr.exe @version=2000.80.194.0  
VULNERABLE: server=JPSQL instance=MSSQLSERVER version=RTM language=1041 platform=NT os=5.0</code></pre>  
<p><strong>SQL Check ツールによる確認方法</strong></p>  
<p>マイクロソフトは、Slammer ワームの影響を受ける可能性のある SQL Server のインスタンスを検知し、無効にする SQL Check というツールをリリースしました。</p>  
<p><strong>注意 :</strong> 本ツールは、英語版のみですが、日本語環境でもご使用いただけます。</p>  
<p><a href="https://technet.microsoft.com/ja-jp/library/a508ea10-a903-4bf6-a57b-e376604b0f14(v=TechNet.10)">SQL Check ツール</a></p>  
<p>このユーティリティは、実行されているコンピュータで Slammer ワームの影響を受ける SQL Server 2000 および MSDE 2000 のインスタンスをスキャンします。SQL Check は Windows 98、Windows ME、Windows NT 4.0、Windows 2000 および Windows XP を実行しているコンピュータで動作します。Windows NT 4.0、Windows 2000 および Windows XP を実行しているコンピュータで、SQL Check は SQL Server および SQL エージェント サービスを停止、無効にします。Windows 98 および Windows ME を実行しているコンピュータでは、影響を受けるインスタンスを検知しますが、サービスを停止または無効にはしません。</p>
<p><strong>注意 :</strong> <a href="https://technet.microsoft.com/ja-jp/library/999a6538-7e4f-492c-8b0f-70c8dd3a9f05(v=TechNet.10)">HFNetCHK</a> では、SQL に関する修正プログラムの詳細なファイルおよびレジストリ キーの情報が利用できないため、SQL に関する修正プログラムのインストール状態を確認できません。セキュリティ情報 <a href="http://www.microsoft.com/japan/technet/security/bulletin/ms02-039.mspx">MS02-039</a> 適用の確認には、上記のツールをご利用ください。</p></td>
</tr>
</tbody>
</table>
<p> </p>

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Step 2: バージョンの確認</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>SQL Server が動作している場合は、本ワームの影響を受けるバージョンか確認する必要があります。 バージョンは次の方法で確認することができます。</p>
<ol>  
<li><p>[スタート] - [検索] - [ファイルやフォルダ(F)...] をクリックします。</p></li>  
<li><p>&quot;ファイルまたはフォルダの名前に ssnetlib.dll と入力します。</p></li>  
<li><p>[検索開始]ボタンをクリックします。</p></li>  
<li><p>ウインドウの右側に検索結果が表示されます。検索は少し時間がかかる場合があります。</p></li>  
<li><p>ssnetlib.dll の上で右クリックし、 [プロパティ] をクリックします。</p></li>  
<li><p>ssnetlib.dll のプロパティが開きます。</p></li>  
<li><p>[バージョン情報] タブをクリックします。</p></li>  
<li><p>ファイル　バージョンを確認します。</p>  
<p>バージョンが、 2000.xx.xxx.x ではない場合は、影響を受けません。 (SQL Server 2000 ではありません。)<br />  
バージョンが、 2000.80.636.0 よりも古い場合は、影響を受けるため、対策を行う必要があります。<br />  
ただし、以下のバージョンであった場合は Slammer ワーム対策用の修正プログラムが適用されているため、影響を受けません。</p>  
<pre><code>     バージョン          日付  
   ---------------------------------  
   2000.80.311.0   2003/01/28 17:25  
   2000.80.479.0   2003/01/28 17:22</code></pre></li>
</ol></td>
</tr>
</tbody>
</table>
<p> </p>

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Step 3: セキュリティ修正プログラムの入手</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>MS02-061 を適用することで本ワームの感染を防ぐことができます。以下の手順で入手することができます。</p>
<ol>  
<li><p>http://www.microsoft.com/japan/technet/security/bulletin/ms02-061.mspx に接続します。</p></li>  
<li><p>お使いの SQL Server の修正プログラムをダウンロードします。</p>  
<p>ここでは、例としてデスクトップにファイルを保存します。</p></li>  
</ol>  
<p>MS02-039 を適用する場合は、以下の手順で入手することができます。</p>  
<ol>  
<li><p>http://www.microsoft.com/japan/technet/security/bulletin/ms02-039.mspx に接続します。</p></li>  
<li><p>お使いの SQL Server の修正プログラムをダウンロードします。</p>  
<p>ここでは、例としてデスクトップにファイルを保存します。</p></li>  
</ol>  
<p><strong>注意 :</strong> MS02-039および、MS02-061は、SQL Server 2000 Service Pack 2を適用した環境にのみ適用可能です。 SQL Server 2000 Service Pack 2 は<a href="http://www.microsoft.com/japan/sql/prodinfo/previousversions/downloads/2000/sp2.mspx">ここ</a>から入手できます</p>  
<p><em>ヒント : SQL Server 2000 と MSDE のどちらがインストールされているか確認する方法</em></p>  
<ol>  
<li><p>[スタート] - [コントロール パネル] をクリックします。</p></li>  
<li><p>[アプリケーションの追加と削除] または [プログラムの追加と削除] を実行します。</p></li>  
<li><p>Windows 2000/XP では、[プログラムの変更と削除] ボタン、他のWindows では、[インストールと削除]タブをクリックします。</p>  
<p>Windows の右側または下側に、インストールされている製品の一覧が表示されます。</p></li>  
<li><p>製品名は、SQL Server 2000 と MSDE でそれぞれ以下の様になります。</p></li>  
</ol>  
<ul>  
<li><pre><code>表示されている製品名インストールされている製品
  
Microsoft SQL Server 2000             Microsoft SQL 2000 Enterprise Edition, Standard Edition, Personal Edition, Developer Edition  
   
Microsoft SQL Server Desktop Engine   Microsoft SQL Server 2000 Desktop Engine (MSDE)  
                      </code></pre></li>
</ul></td>
</tr>
</tbody>
</table>
<p> </p>

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Step 4: SQL Server の停止</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>ワームの影響を受けないバージョンに SQL Server をアップデートするには、SQL Server を一度停止させる必要があります。ワームの影響により通常の手順で終了しない場合は、以下の手順で停止します。</p>
<ol>  
<li><p>ローカルから管理者権限でログオンします。</p></li>  
<li><p>次のコマンドを入力し、SQL Server に接続します。</p>  
<p><strong>osql -E</strong></p></li>  
<li><p>次のコマンドを実行し、 SQL Server を停止させます。</p>  
<p><strong>shutdown with nowait</strong></p></li>  
<li><p>ワームにより CPU が占有されているため時間がかかることがあります。一時的に”応答なし”の状態になることもありますが、しばらくお待ちください。</p></li>  
<li><p>Step 1 の手順で SQL Server が停止していることを確認します。</p>  
<p>上記の手順で SQL Server が停止しない場合は Windows をシャットダウンします。 シャットダウンも通常より時間がかかる場合があります。シャットダウン後、電源は、Step 5で、ネットワークの切断が完了するまで入れないでください。 ネットワークに接続された状態では、再度感染する恐れがあります。</p></li>
</ol></td>
</tr>
</tbody>
</table>
<p> </p>

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Step 5: ネットワークの切断</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>対策中の再感染を防止するために、ネットワークを以下の手順で切断します。</p>
<ol>  
<li><p>サーバー本体から、LAN ケーブル、電話線 や 無線 LAN のアダプタ(カード)をはずします。</p></li>  
<li><p>本体から、ネットワークにつながっていないことを確認します。</p></li>  
<li><p>Step 4 でシャットダウンした場合は、ネットワークに接続していないことを確認して電源を入れます。</p></li>
</ol></td>
</tr>
</tbody>
</table>
<p> </p>

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Step 6: 対策</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>再度感染しないために、セキュリティ修正プログラムを以下手順で適用します。</p>
<ol>  
<li><p>修正プログラムを展開するためのフォルダを作ります。</p>  
<p>ここでは、例として、デスクトップ上に、&quot;ms02-039&quot; という名前で作成します。</p></li>  
<li><p>Step 3 で入手したセキュリティ修正プログラムをダブルクリックします。</p></li>  
<li><p>&quot;Q323875&quot; ダイアログ ボックスが表示され、使用許諾契約が表示されます。 内容をご確認の上、[はい] ボタンをクリックしてください。</p></li>  
<li><p>&quot;展開されたファイルを保存する場所を指定してください。&quot; と表示されますので、手順 1. で作成したフォルダをしています。フォルダを指定するには、[参照] ボタンをクリックします。</p></li>  
<li><p>ダイアログ ボックスが消え、ファイルが展開の終了します。</p></li>  
<li><p>手順 1. で作成したダイアログ ボックスを開きます。</p></li>  
<li><p>readme.rtf ファイルを開きます。</p></li>  
<li><p>readme.rtf の内容にしたがって、修正プログラムを適用します。 readme.rtf には 2 種類のインストール手順が書かれていますが、SQL Server 2000 Enterprise Edition 以外の環境では、標準インストールを行ってください。</p></li>  
<li><p>「Step 2: バージョンの確認」の手順に従い、ssnetlib.dll のファイル バージョンが 2000.80.636.0 以上になっていることを確認します。</p></li>
</ol></td>
</tr>
</tbody>
</table>
<p> </p>

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Step 7: SQL Server の開始</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><ol>
<li><p>Step 5 で切断した LAN ケーブルなどを、すべて接続します。</p></li>  
<li><p>SQL Server を開始します。</p></li>
</ol></td>
</tr>
</tbody>
</table>
<p> </p>

[](#mainsection)[ページのトップへ](#mainsection)

### 対策による影響

本体策による特別な影響はございません

[](#mainsection)[ページのトップへ](#mainsection)

### osql コマンドについて

osql コマンドは、デフォルトでは以下の場所にインストールされています。

(SQL Server 2000)
**\\Program Files\\Microsoft SQL Server\\80\\Tools\\Binn**

(MSDE)
**\\Program Files\\Microsoft SQL Server\\80\\Tools\\Binn**

オプションの説明 :

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>-E</strong></p></td>
<td style="border:1px solid black;"><p>SQL Server に接続するための現在のユーザーを使用します。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><strong>-U</strong></p></td>
<td style="border:1px solid black;"><p>SQL Server に接続するためのログイン (ユーザー) を指定します。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>-P</strong></p></td>
<td style="border:1px solid black;"><p>ログイン(ユーザー)のパスワードを指定します。<br />
このドキュメントでは、 パスワードなしの sa を使用しているためパスワードの指定を行っておりません。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><strong>-S</strong></p></td>
<td style="border:1px solid black;"><p>SQL Server が動作しているインスタンス (サーバー) を指定します。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>-Q</strong></p></td>
<td style="border:1px solid black;"><p>SQL Server に対して指定したクエリの実行を要求し、実行後に、このコマンドを終了させるオプションです。<br />
&quot;(ダブルコーテーション) で囲まれた部分がクエリ文字列になります。</p></td>
</tr>
</tbody>
</table>
<p> </p>

osql コマンドおよび SQL Server の詳細につきましては、SQL Server に付属する Books Online、ヘルプ、製品マニュアルをご参照ください。

[](#mainsection)[ページのトップへ](#mainsection)

##### 関連リンク

-   [よくある質問と回答](https://technet.microsoft.com/ja-jp/library/626ad711-945f-44ed-b8a8-c5865f070574(v=TechNet.10))
-   [更新履歴](https://technet.microsoft.com/ja-jp/library/b895b0ee-772e-4052-b783-97dacdc306e3(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
