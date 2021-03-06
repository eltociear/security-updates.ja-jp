---
TOCTitle: 'MS10-APR'
Title: 2010 年 4 月のセキュリティ情報
ms:assetid: 'ms10-apr'
ms:contentKeyID: 61229670
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms10-apr(v=Security.10)'
--- 

2010 年 4 月のセキュリティ情報
==============================

公開日: 2010年4月14日 | 最終更新日: 2010年7月14日

**バージョン:** 1.0

[![](../../images/Dn627249.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627249.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------

 
[MS10-019 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-019e.mspx)

[MS10-020 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-020e.mspx)

[MS10-021 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-021e.mspx)

[MS10-022 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-022e.mspx)

[MS10-023 : Publisher の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-023e.mspx)

[MS10-024 : Exchange および Windows SMTP サービスの重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-024e.mspx)

[MS10-025 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-025e.mspx)

[MS10-026 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-026e.mspx)

[MS10-027 : Windows Media Player の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-027e.mspx)

[MS10-028 : Visio の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-028e.mspx)

[MS10-029 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-029e.mspx)

このセキュリティ情報は 2010 年 4 月 14 日に公開したセキュリティ情報の一覧です。

2010 年 4 月 14 日のセキュリティ情報の公開により、2010 年 4 月 9 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2010 年 4 月 14 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2010 年 4 月 14 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[4 月のセキュリティ情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427721&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](https://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----

 
次の表は今月のセキュリティ情報を深刻度順にまとめてたものです。

影響を受けるソフトウェアの詳細は、次の影響を受けるソフトウェアおよびダウンロード先のセクションをご覧ください。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID 番号</th>
<th style="border:1px solid black;" >タイトルおよび概要</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動情報</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-019">MS10-019</a></td>
<td style="border:1px solid black;"><strong>Windows の脆弱性により、リモートでコードが実行される (981210)</strong>
このセキュリティ更新プログラムは、非公開で報告された 2 件の Windows Authenticode の検証の脆弱性を解決します。この脆弱性が悪用された場合、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、影響を受けるコンピューターが完全に制御される可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;"><strong>SMB クライアントの脆弱性により、リモートでコードが実行される (980232)</strong>
このセキュリティ更新プログラムは Microsoft Windows に存在する 1 件の公開された脆弱性およびいくつかの非公開で報告された脆弱性を解決します。この脆弱性で、クライアントが送出した SMB リクエストに対して、攻撃者が特別な細工がされた SMB の応答を返信した場合、リモートでコードが実行される可能性があります。これらの脆弱性が悪用されるには、ユーザーに特別な細工がされた SMB サーバーに対し SMB 接続を開始させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-025">MS10-025</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows Media Services の脆弱性により、リモートでコードが実行される (980858)</strong>
このセキュリティ更新プログラムは Microsoft Windows 2000 Server で実行されている Windows Media Services に存在する非公開で報告された 1 件の脆弱性を解決します。この脆弱性で、攻撃者が特別な細工がされたトランスポート情報パケットを Windows Media Service を実行している Microsoft Windows 2000 に送信した場合、リモートでコードが実行される可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。インターネットに接続したコンピューターについては、最善策として最低限の数のポートしか開かないようにすることを推奨します。Microsoft Windows 2000 Server で、Windows Media Services はオプションのコンポーネントで、既定ではインストールされません。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-026">MS10-026</a></td>
<td style="border:1px solid black;"><strong>MPEG Layer-3 コーデックの脆弱性により、リモートでコードが実行される (977816)</strong>
このセキュリティ更新プログラムは非公開で報告された 1 件の MPEG Layer-3 オーディオ コーデックの脆弱性を解決します。この脆弱性により、ユーザーが、MPEG Layer-3 のオーディオ ストリームが含まれている特別に細工された AVI ファイルを開いた場合、リモートでコードが実行される可能性があります。ユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性がありますシステムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-027">MS10-027</a></td>
<td style="border:1px solid black;"><strong>Windows Media Player の脆弱性により、リモートでコードが実行される (979402)</strong>
このセキュリティ更新プログラムは、非公開で報告された 1 件の Windows Media Player の脆弱性を解決します。この脆弱性で、Windows Media Player が悪意のある Web サイトでホストされている特別な細工がされたメディア コンテンツを開いた場合、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、ローカルのユーザーと同じユーザー権限を取得する可能性があります。コンピューターで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-021">MS10-021</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルの脆弱性により、特権が昇格される (979683)</strong>
このセキュリティ更新プログラムは、非公開で報告された複数の Microsoft Windows に存在する脆弱性を解決します。最も深刻な脆弱性では、攻撃者がローカルでログオンし、特別に細工したアプリケーションを実行した場合、特権の昇格を起こす可能性があります。これらの脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモート、または匿名ユーザーにより、この脆弱性が悪用されることはないと思われます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-022">MS10-022</a></td>
<td style="border:1px solid black;"><strong>VBScript スクリプト エンジンの脆弱性により、リモートでコードが実行される (981169)</strong>
このセキュリティ更新プログラムは Microsoft Windows 上の VBScript に存在する一般に公開された脆弱性を解決します。この脆弱性により、リモートでコードが実行される可能性があります。このセキュリティ更新プログラムは、Microsoft Windows 2000、Windows XP および Windows Server 2003 について、深刻度を「重要」と評価しています。Windows Server 2008、Windows Vista、Windows 7 および Windows Server 2008 R2 については、影響を受けるコードが悪用されることはありませんが、影響を受けるコードが存在しているため、多層防御としてこの更新プログラムが提供されており、深刻度の評価の対象とはなっていません。詳細情報は、このセクションの「影響を受けるソフトウェアおよび影響を受けないソフトウェア」のサブセクションをご覧ください。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-023">MS10-023</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Publisher の脆弱性により、リモートでコードが実行される (981160)</strong>
このセキュリティ更新プログラムは、ユーザーが特別に細工された Publisher のファイルを表示するとリモートでコードが実行される可能性のある、非公開で報告された Microsoft Office Publisher の脆弱性を解決します。攻撃者がこの脆弱性を悪用した場合、ローカルのユーザーと同じユーザー権限を取得する可能性があります。コンピューターで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-024">MS10-024</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange および Windows SMTP サービスの脆弱性により、サービス拒否が起こる (981832)</strong>
このセキュリティ更新プログラムは Microsoft Exchange および Windows SMTP サービスに存在する 1 件の公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。攻撃者が特別に細工した DNS 応答を SMTP サービスを実行しているコンピューターに送信した場合、これらの 2 件の脆弱性のうち、より深刻な脆弱性により、サービス拒否が起こる可能性があります。既定で、SMTP コンポーネントは Windows Server 2003、Windows Server 2003 x64 Edition または Windows XP Professional x64 Edition にインストールされていません。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft Exchange</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-028">MS10-028</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio の脆弱性により、リモートでコードが実行される (980094)</strong>
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Office Visio に存在する脆弱性を解決します。この脆弱性は、特別に細工された画像ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、ローカルのユーザーと同じユーザー権限を取得する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-029">MS10-029</a></td>
<td style="border:1px solid black;"><strong>Windows ISATAP コンポーネントの脆弱性により、なりすましが行われる (978338)</strong>
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。このセキュリティ更新プログラムは、Windows XP、Windows Server 2003、Windows Vista および Windows Server 2008 について、深刻度を「警告」に評価しています。Windows 7 および Windows Server 2008 R2 は、このセキュリティ更新プログラムが適用する機能を含んでいるため、この脆弱性の影響は受けません。詳細情報は、このセクションの「影響を受けるソフトウェアおよび影響を受けないソフトウェア」のサブセクションをご覧ください。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">警告</a><br />
なりすまし</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、悪用の可能性が高いものから順に、次に CVE ID の順に記載しています。セキュリティ情報に記載されている深刻度が緊急または重要の脆弱性のみです。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID 番号</th>
<th style="border:1px solid black;" >脆弱性タイトル</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >Exploitability Index の評価</th>
<th style="border:1px solid black;" >注意事項</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-021">MS10-021</a></td>
<td style="border:1px solid black;">Windows カーネルのメモリ割り当ての脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0236">CVE-2010-0236</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-021">MS10-021</a></td>
<td style="border:1px solid black;">Windows カーネルのシンボリック リンク作成の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0237">CVE-2010-0237</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-028">MS10-028</a></td>
<td style="border:1px solid black;">Visio の属性の検証のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0254">CVE-2010-0254</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-027">MS10-027</a></td>
<td style="border:1px solid black;">Media Player のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0268">CVE-2010-0268</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-025">MS10-025</a></td>
<td style="border:1px solid black;">Media Services スタック ベースのバッファー オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0478">CVE-2010-0478</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-023">MS10-023</a></td>
<td style="border:1px solid black;">Microsoft Office Publisher のファイル変換のテキストボックスの処理のバッファー オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0479">CVE-2010-0479</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-026">MS10-026</a></td>
<td style="border:1px solid black;">MPEG Layer-3 オーディオ デコーダーのスタック オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0480">CVE-2010-0480</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-022">MS10-022</a></td>
<td style="border:1px solid black;">VBScript のヘルプ Keypress の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0483">CVE-2010-0483</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a><br />
<br />
Windows Server 2008、Windows 7 および Windows Server 2008 R2:<br />
<a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/advisory/981169">マイクロソフト セキュリティ アドバイザリ 981169</a> で記載しているとおり、この脆弱性は一般に公開されています。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-028">MS10-028</a></td>
<td style="border:1px solid black;">Visio のインデックスの計算のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0256">CVE-2010-0256</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB クライアントのトランザクションの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0270">CVE-2010-0270</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB クライアントの応答の解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0476">CVE-2010-0476</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-019">MS10-019</a></td>
<td style="border:1px solid black;">WinVerifyTrust Signature Verification の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0486">CVE-2010-0486</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-019">MS10-019</a></td>
<td style="border:1px solid black;">Cabview の破損の検証の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0487">CVE-2010-0487</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB クライアントの不完全な応答の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3676">CVE-2009-3676</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/advisory/977544">マイクロソフト セキュリティ アドバイザリ 977544</a> で記載しているとおり、この脆弱性は一般に公開されています。<br />
<br />
サービス拒否の可能性があります。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-024">MS10-024</a></td>
<td style="border:1px solid black;">SMTP サーバーの MX レコードの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0024">CVE-2010-0024</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">サービス拒否の可能性があります。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB クライアントのメモリの割り当ての脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0269">CVE-2010-0269</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB クライアントのメッセージのサイズの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0477">CVE-2010-0477</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">サービス拒否の可能性があります。</td>
</tr>
</tbody>
</table>

<p></p>

  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
**この表はどのように使用しますか?**
  
この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、脆弱性の深刻度も記載されています。
  
**注:** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="10">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d7538166-35ee-4c6b-be8c-e83a1fc6cd77)  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 5.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=13846177-f25f-4dd4-9fe9-ac43e1d4d73d)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=67ccac04-e5c8-4381-9d1a-9b676dd516a6)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=73b3d681-26bb-49c1-849e-1f72484cb978)  
(緊急)
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f6394fc2-b9d0-46cf-9265-a0d4aeb1448f)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media Player 9 Series](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c0b8b362-a321-4ac9-be98-15c71bb7a043)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c5f4577e-7546-40e9-8bcd-be11c1b260a6)  
(重要)
</td>
<td style="border:1px solid black;">
[VBScript 5.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=421be318-f217-4d12-b7a5-833093189073) <sup>[1]</sup>
(KB981350)  
(重要)  
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=421be318-f217-4d12-b7a5-833093189073)  
(KB981350)  
(重要)  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d5fc47a4-cecb-4817-aafb-45f335061be3)  
(KB981349)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=88a0e872-01de-495b-8eec-d105a970daa7)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="10">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=2a01ddf0-f3ea-47c8-ada2-e69f6c1b5f96)  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6c3ac102-2107-4726-98be-4fbf6b858bfb)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=dec38c02-3d4a-41c5-8954-e57f56b8fa5b)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b1582a74-4a7b-4540-beb1-7c89c86eae87)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 上の Windows Media Player 9 Series](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=5c748c6d-84d1-45a9-8a33-9372eb5504d5)  
(緊急)  
[Windows XP Service Pack 3 上の Windows Media Player 9 Series](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9e4277b4-2dc5-4163-a6aa-7e07dd32b721)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=142710fd-9cd4-4dd0-aaba-2aace03c008f)  
(重要)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 2 上の [VBScript 5.6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=aa8ff157-a7b3-4787-80c9-5bc453f0f1c9)  
(KB981350)  
(重要)  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=cb21d276-65e9-4c8f-96e3-cf6dc36d0133)  
(KB981349)  
(重要)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ba7ef6e5-80ba-4281-a611-6e5be008c1b4)  
(KB981332)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=de447b76-ec89-426b-ac54-3ae3855d1159)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9dc3e1c2-2e9d-4d86-9fce-446c409ad613)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9bbff00c-f8f4-4a44-98f2-18a868986ae1)  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e64e487e-2727-4396-b0c9-6eaf000214d2)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c5a21239-a9a3-4ec5-9de8-7d2fc16fc6b8)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8afca317-a647-44aa-a771-5d85cd5d62ea)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=3c0cb02e-3484-4cdf-8c64-c697ad3e2889)  
(重要)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=896c738d-4058-440f-8d4f-16c678610cd1)  
(KB981350)  
(重要)  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d7e8b930-8708-4f0b-b22b-961c2cbc2673)  
(KB981349)  
(重要)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=153fd9c1-0f8e-4492-87d1-f0381e7feb23)  
(KB981332)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4f9a696d-2712-4777-a642-e78a38336e8a)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d872bd77-f491-4706-8ff5-081ac0bf3d6f)  
(警告)
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0e7e3deb-f078-4953-9642-675ec69267f2)  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7ae9b1d0-0dbe-4abd-b315-10cea4ceccd7)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1189304f-d626-426d-960c-a86dc2d2b528)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9f89746c-181e-4177-a851-ec1826e78b6d)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0a7ea2d0-61ce-4b68-ad82-d917b1a56f9d)  
(重要)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=28b035b8-d56e-4e93-b811-9a82cf1d4ba9)  
(KB981350)  
(重要)  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a142a553-85fc-40e0-9426-8d58f6a4333c)  
(KB981349)  
(重要)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=72754e1b-3d09-4b9d-8794-689c45a37f66)  
(KB981332)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f781e9e4-87d4-4243-9d44-256424d75fec)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=cd007a6c-04b3-490c-aff4-d5af3e69d477)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=99a3f6da-728f-421c-ab41-c4c4751934a4)  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1709fd4e-d7c6-4cbb-8b71-a96b8d6eee58)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=52e4f66b-b76c-46a1-aeff-74efa21fc743)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b97e7ea1-a163-4ce4-8cbc-5f933773c4b2)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1fc66f54-260a-4219-a0b4-056ba9dd0abe)  
(重要)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=339ddf48-8949-4857-9ef6-1ddcc7c5f8b8)  
(KB981350)  
(重要)  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a489b4e3-78d2-411b-b27c-5987b8fc91d1)  
(KB981349)  
(重要)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=72c3013b-f72f-422b-8a89-2246dea4b378)  
(KB981332)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=644ff070-237b-4a73-b2e2-9fffdafa3927)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=19cfddfe-e8da-4564-9730-babfae4a3ebb)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=06832599-1e9b-4792-8c7b-7b5b3a3d6277)  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=811a2b28-655d-4b5d-821e-5a90d556dba3)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b2b6d8b1-63cc-459c-b5fa-1355386273c8)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8dcb8be8-fb78-4518-aa7e-f8b17f7dfb86)  
(重要)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9a8bee82-5f7f-490e-a1eb-481f6d4fc4f5)  
(KB981350)  
(重要)  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7d542ac6-8a5b-4dd7-8688-2b5feb563636)  
(KB981349)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=56c8238d-8b04-4aa5-8719-40550cd7325c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=916f1b09-e79e-4347-9fbc-c0cf07de397d)  
(警告)
</td>
</tr>
<tr>
<th colspan="10">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista、Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a52225a7-6005-4f2b-8291-db20558f23f8)  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6145e2b2-36fd-4360-bd5b-2bd11890fc52)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=25eeaeb3-c0a3-4a02-9912-acd0342648ba)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0e7140bb-42d3-48b3-9f4b-d55b17770de8)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=86d7b054-af4f-4d8a-9873-cb5246466374)  
(重要)  
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=86d7b054-af4f-4d8a-9873-cb5246466374)  
(警告)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ee5c42c6-16bb-48bf-95c2-c188bb17d04b)  
(KB981349)  
(深刻度なし <sup>[2]</sup>)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f2a37dbf-4a95-4e8d-a474-ecacd9aee690)  
(KB981332)  
(深刻度なし <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=196055a6-15d1-4da8-b33d-501e69bf5176)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9ba7468c-23a4-4994-9a5a-22e96ef586f3)  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=5b7efa82-0feb-413a-9f8e-212e7432cd99)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=394c1caa-97e4-47a3-9aac-a4a88508bd31)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b885aef4-3a5d-4c3e-bef6-5efef2965752)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7c84aa24-6331-427a-969c-27f7d39db3d7)  
(重要)  
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7c84aa24-6331-427a-969c-27f7d39db3d7)  
(警告)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ea5c5e9c-0ecd-47bc-912d-5adc00d1aa21)  
(KB981349)  
(深刻度なし <sup>[2]</sup>)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=79093796-4ea9-4c6c-92cc-3fd63c5db918)  
(KB981332)  
(深刻度なし <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7c1d1622-1b67-438d-aae4-1a3954974a36)  
(警告)
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=97ffeec8-8b6d-4a30-97b0-4bff2ba5e91d)\*  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f111735b-68b0-4bcc-9dd8-818a5eca3400)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=51c9c420-4507-4911-a8f5-82331a696882)\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8e9c04c9-898f-4ed2-949d-f4343cc0d9f6)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=25e3ce7f-53a0-4049-a65c-011d2143c4c2)\*  
(警告)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=dbe89813-0a45-463b-928c-1e58f7bb596a)\*\*  
(KB981349)  
(深刻度なし <sup>[2]</sup>)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=527d6376-efc9-436b-835b-219d38bb28f0)\*\*  
(KB981332)  
(深刻度なし <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e29ead69-000a-4982-a25c-f3981eda381a)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=61ece7bc-e9fa-4ede-ba7d-9e5a4c64b9be)\*  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=49f9f740-023a-4291-becf-838a1d282321)\*  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=91c08251-0085-44cb-9e9c-9a1a84374caf)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=61c26a1f-c885-4474-9843-204c41628889)\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d6f2e1ae-48d3-4d2c-b329-32cff00afee5)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8b99e54d-955b-4a06-9a04-b2f4596efd72)\*  
(警告)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9db62357-557d-40cd-9826-b7baa6c9de65)\*\*  
(KB981349)  
(深刻度なし <sup>[2]</sup>)  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0c384dbc-21b7-4cbc-b68f-ced971d9b791)\*\*  
(KB981332)  
(深刻度なし <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8f922e64-e3a6-46fe-9a81-b2813ea6a330)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=72e7c7ea-55ef-457b-a03a-49aa9dea2e84)\*  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=bd60779a-8bb1-4107-a344-9b09a50e96ff)  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=eb116688-1d6e-4e20-948e-1d347af5d985)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=bcf8b919-08a9-487f-8dfd-3ca24328c4f3)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b1f9746d-61a2-406f-b707-60646bd5b5bb)  
(警告)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=84c5aaae-9417-42a1-834f-22c1ad46a12f)  
(KB981349)  
(深刻度なし <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8c48302c-a1d6-41bc-ad24-7ce7332d4842)  
(警告)
</td>
</tr>
<tr>
<th colspan="10">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8d4a6c65-e171-4570-8f3f-118f06910baf)  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f0dbac52-0f0e-40bc-9371-17fa594424d5)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=389184c5-9001-497d-bdf4-81f97ecb617f)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ff58d80c-33ce-4d9e-aaa5-0b1841458931)  
(警告)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c3f76835-0053-4e53-a451-14255e7a4fc0)  
(KB981332)  
(深刻度なし <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=cf8c6721-05c2-4680-93b4-be36f09c6d15)  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b23efe7d-bca4-4d49-9104-6ae39dc5daa9)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f3495dae-71f3-421d-a191-d26965f26ad1)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7f1dc055-2ec9-407a-9e69-da12338587e3)  
(警告)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=998164b7-4b8c-468b-8d39-f242633c8838)  
(KB981332)  
(深刻度なし <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=94dfdaae-8464-4de6-a401-7eb70b3bb34f)\*  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a2979c02-2a80-4b84-bf6c-4798064bdf28)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=cd1a046e-915d-4904-b753-5a24be10c504)\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=28389c1d-2a12-4bef-a59b-726bb6449c8b)\*  
(警告)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c4039d40-a0c7-4183-ab50-04f690d1c5dc)\*\*  
(KB981332)  
(深刻度なし <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=eb27cd2b-d514-4405-8650-259a42e35155)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=40f622d2-48e7-4eb2-9430-bbd218cb5208)  
(KB978601)  
(緊急)  
[Cabinet File Viewer Shell Extension 6.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=5e416d4b-5de7-4688-80c6-245de159e0ce)  
(KB979309)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=541e9e2f-ec1d-42b2-aae5-481c0d435169)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d4ea3984-5183-47f1-814e-29cb6c90ae06)  
(警告)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8174463c-5c5e-4095-90c8-fd1e898d4ba5)  
(KB981332)  
(深刻度なし <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008 および Windows Server 2008 R2 に関する注意**

**\*Server Core インストールは影響を受けます。**サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションに関する詳細情報は、[Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

**\*\*Server Core インストールは影響を受けません。**この更新プログラムが解決している脆弱性は、Server Core インストールオプションを使用してインストールした場合、サポートされているエディションの Windows Server 2008 および Windows Server 2008 R2 に影響を与えません。このインストール オプションに関する詳細情報は MSDN コラム [Server Core](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英語情報) および [Server Core for Windows Server 2008 R2](https://msdn.microsoft.com/en-us/library/ee391631(en-us,vs.85).aspx) (英語情報) をご覧ください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Compare Server Core Installation Option](https://www.microsoft.com/windowsserver2008/en/us/r2-compare-core-installation.aspx) (英語情報) をご覧ください。

**MS10-022 に関する注意**

<sup>[1]</sup> このセキュリティ更新プログラムはインストールされている VBScript 5.1 を VBScript 5.6 にアップグレードします。

<sup>[2]</sup>このセキュリティ情報で説明している脆弱性はこのソフトウェアに影響を与えないため、この更新プログラムに深刻度は適用されません。しかし、マイクロソフトは、将来的に特定される可能性がある新しい攻撃方法を防ぐ多層防御策として、このソフトウェアをご使用のお客様に、このセキュリティ更新プログラムの適用を推奨します。

**MS10-024 に関する注意**

この「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリもご覧ください。同じセキュリティ情報 ID 番号の更新プログラムがあります。このセキュリティ情報は複数のソフトウェア カテゴリに該当しています。

#### Microsoft Office スイートおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft Office スイートおよびソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS10-023**](https://technet.microsoft.com/security/bulletin/ms10-023)
</td>
<td style="border:1px solid black;">
[**MS10-028**](https://technet.microsoft.com/security/bulletin/ms10-028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=943b3830-70d5-46c5-bffc-1b494434b5f7)  
(KB980466)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2002 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=2d563cbc-d8f7-486b-8c54-25d168085376)  
(KB979364)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7c2f4610-77bb-4d72-847b-1a06c523b137)  
(KB980469)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=803a7ea0-a9da-46dd-9548-0177d3774be7)  
(KB979356)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 Service Pack 1 および Microsoft Office Publisher 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=10ca2f71-0ab2-4344-b7fd-bbbd6a783a96)  
(KB980470)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2007 Service Pack 1 および Microsoft Office Visio 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=56fe020f-4444-4a43-aa98-e99a622f6a69)  
(KB979365)  
(重要)
</td>
</tr>
</table>

<p></p>

 

#### Microsoft サーバー ソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2000
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e47c90a0-c9c8-43b7-bec7-34107ddde294)  
(KB976703)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2003
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=bc8391f8-5335-496b-ad4c-bae38509be4a)  
(KB976702)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 Service Pack 1 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6a894b4e-12b6-4a91-9555-d813956b6aac)  
(KB981407)  
(深刻度なし <sup>[1]</sup>)  
[Microsoft Exchange Server 2007 Service Pack 2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b8f7f872-16d5-49d6-9867-adc01351c06f)  
(KB981383)  
(深刻度なし <sup>[1]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7dcf2390-dff7-4e3a-acca-03f4d43fb79a)  
(KB981401)  
(深刻度なし <sup>[1]</sup>)
</td>
</tr>
</table>

<p></p>

 
**MS10-024 に関する注意**

<sup>[1]</sup>このセキュリティ情報で説明している脆弱性はこのソフトウェアに影響を与えないため、この更新プログラムに深刻度は適用されません。しかし、マイクロソフトは、将来的に特定される可能性がある新しい攻撃方法を防ぐ多層防御策として、このソフトウェアをご使用のお客様に、このセキュリティ更新プログラムの適用を推奨します。

この「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリもご覧ください。同じセキュリティ情報 ID 番号の更新プログラムがあります。このセキュリティ情報は複数のソフトウェア カテゴリに該当しています。

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](https://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](https://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](https://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](https://update.microsoft.com/microsoftupdate/)、[Windows Update](https://windowsupdate.microsoft.com/) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](https://support.microsoft.com/kb/323166) をご覧ください。

**注:** 2009 年 8 月 1 日より、マイクロソフトは Office Update および Office Update Inventory Tool のサポートを終了します。Microsoft Office 製品用の最新の更新プログラムを引き続き入手するためには、[Microsoft Update](https://update.microsoft.com/microsoftupdate/) をご利用ください。詳細情報は、[About Microsoft Office Update: Frequently Asked Questions](https://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英語情報) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトはセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [961747](https://support.microsoft.com/kb/961747) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適 用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](https://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](https://technet.microsoft.com/ja-jp/wsus/default.aspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](https://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](https://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](https://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](https://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](https://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](https://support.microsoft.com/kb/894199/): Software Update Services および Windows Server Update Services におけるコンテンツの変更について (2010 年). すべての Windows のコンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services.](https://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報): Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。この様な保護環境を提供するセキュリティ ソフトウェア ベンダーの情報は、[Microsoft Active Protections Program (MAPP) Partners](https://www.microsoft.com/security/msrc/mapp/partners.mspx) (英語情報) に記載されている各社の Web サイトをご覧ください。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](https://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー用プラットフォームの更新プログラムは、[Microsoft Update](https://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報は、サポート技術情報 [913086](https://support.microsoft.com/kb/913086) をご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](https://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](https://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS10-020 で説明している問題について報告してくださった [Visuality Systems Ltd.](https://www.visualitynq.com/) の Mark Rabinovich 氏
-   MS10-020 で説明している 3 つの問題について報告してくださった [stratsec](https://www.stratsec.net/) の Laurent Gaffié 氏
-   MS10-021 で説明している 5 つの問題について報告してくださった [Hispasec](https://www.hispasec.com/) および [Virustotal](https://www.virustotal.com/) の Matthew 'j00ru' Jurczyk 氏および Gynvael Coldwind 氏
-   MS10-021 で説明している 2 つの問題について報告してくださった [Google, Inc.](https://www.google.com/) の Tavis Ormandy 氏
-   MS10-021 で説明している問題について報告してくださった [Obsidium Software](https://www.obsidium.de/) の Martin Tofall 氏
-   MS10-023 で説明している問題について報告してくださった [TippingPoint](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力している Lionel d'Hauenens 氏
-   MS10-025 で説明している問題について報告してくださった [CERT-LEXSI](https://cert.lexsi.com/) の Fabien Perigaud 氏
-   最初に公開した MS10-025 のセキュリティ更新プログラムの品質の問題の詳細を提供してくださった [CERT-LEXSI](https://cert.lexsi.com/) の Fabien Perigaud 氏、[VUPEN Vulnerability Research Team](https://www.vupen.com/)、Vulnerability Research Team、[TELUS Security Labs](https://telussecuritylabs.com/)、[Core Security Technologies](https://www.coresecurity.com/) および [NSFOCUS Security Team](https://www.nsfocus.com/) の The Vulnerability Research Team
-   MS10-026 で説明している問題について報告してくださった [Palo Alto Networks](https://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS10-027 で説明している問題について報告してくださった [TippingPoint](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力している匿名のリサーチャー
-   MS10-028 で説明している 2 つの問題について報告してくださった Fortinet の [FortiGuard Labs](https://www.fortiguard.com/) の Bing Liu 氏
-   MS10-029 で説明している問題について報告してくださった the National EW Research & Simulation Center (Rafael) の Gabi Nakibly 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](https://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](https://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2010/04/14: このセキュリティ情報ページを公開しました。
-   2010/04/15: このセキュリティ情報を更新し、「概要」セクションののS10-025 の再起動の必要性を修正しました。また、Windows Server 2008 および Windows Server 2008 R2 にの MS10-019 の KB978601 の更新にのみ適用する Server Coreの注釈を修正しました。
-   2010/04/22: このセキュリティ情報ページを更新し、お客様に MS10-025 の最初のセキュリティ更新プログラムは、このセキュリティ情報で説明している脆弱性からコンピューターを保護しないことをお知らせしました。改訂版のセキュリティ更新プログラムが提供されるまで、マイクロソフトはお客様に影響を受けるシステムへの影響を緩和するために、MS10-025 で説明している回避策のいずれかを適用することを推奨します。
-   2010/04/28: このセキュリティ情報ページを更新し、MS10-025 の再リリース版のセキュリティ更新プログラムを提供しました。
-   2010/07/14: このセキュリティ情報ページを更新し、MS10-024 のWindows Server 2008 および Windows Server 2008 R2 の再リリース版のセキュリティ更新プログラムを提供しました。

*Built at 2014-04-18T01:50:00Z-07:00*
