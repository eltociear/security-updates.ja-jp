---
TOCTitle: 'MS11-NOV'
Title: 2011 年 11 月のセキュリティ情報
ms:assetid: 'ms11-nov'
ms:contentKeyID: 61229691
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms11-nov(v=Security.10)'
--- 

2011 年 11 月のセキュリティ情報
===============================

公開日: 2011年11月9日

**バージョン:** 1.0

[![](../../images/Dn627270.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627270.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2011 年 11 月公開のセキュリティ情報の一覧です。

2011 年 11 月のセキュリティ情報の公開により、2011 年 11 月 4 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/security/bulletin/advance)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2011 年 11 月 9 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問にお答えするため、2011 年 11 月 9 日午前 11：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[11 月の セキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487958) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、[Microsoft Security Summaries and Webcasts](https://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

### セキュリティ情報に関する情報

概要
----

 
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェアおよびダウンロード先」を参照してください。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >セキュリティ情報タイトルおよび概要</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動の必要性</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-083">MS11-083</a></td>
<td style="border:1px solid black;">TCP/IP の脆弱性により、リモートでコードが実行される (2588516) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が対象システムの閉じられたポートに特別な細工をした UDP パケットの連続フローを送信した場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-085">MS11-085</a></td>
<td style="border:1px solid black;">Windows メールおよび Windows ミーティング スペースの脆弱性により、リモートでコードが実行される (2620704) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされたダイナミック リンク ライブラリ (DLL) ファイルと同じネットワーク ディレクトリにある正当なファイル (.eml ファイルや .wcinv ファイルなど) を開いた場合、リモートでコードが実行される可能性があります。次に、正当なファイルを開いている間に Windows メールまたは Windows ミーティング スペースが DLL ファイルをロードし、それに含まれている任意のコードを実行しようとする可能性があります。攻撃は、ユーザーが信頼されないリモート ファイル システムの場所または WebDAV 共有を訪問して、この場所から影響を受けるアプリケーションでロードされる正当なファイル (.eml ファイルや .wcinv ファイルなど) を開いた場合に実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-086">MS11-086</a></td>
<td style="border:1px solid black;">Active Directory の脆弱性により、特権が昇格される (2630837) <br />
<br />
このセキュリティ更新プログラムは Active Directory、Active Directory Application Mode (ADAM) および Active Directory Lightweight Directory Service (AD LDS) に存在する非公開で報告された脆弱性を解決します。Active Directory が SSL 経由の LDAP (LDAPS) を使用するように構成されている場合、攻撃者が有効なドメイン アカウントに関連付けられている失効した証明書を獲得し、Active Directory ドメインへの認証にその失効した証明書を使用すると、この脆弱性により、特権が昇格される可能性があります。既定では、Active Directory は SSL 経由の LDAP を使用するように構成されていません。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-084">MS11-084</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、サービス拒否が起こる (2617657) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。ユーザーが、電子メール添付ファイルの特別に細工された TrueType フォント ファイルを開いたり、特別に細工された TrueType フォント ファイルを含んでいるネットワーク共有や WebDAV ロケーションに移動した場合、この脆弱性により、サービス拒否が起こる可能性があります。攻撃が行われるには、ユーザーが特別に細工された TrueType フォント ファイルを含んでいる信頼されないリモート ファイル システムの場所または WebDAV 共有を訪問することが攻撃者にとっての必要条件となります。ただし、すべての場合において、攻撃者がこのような操作をユーザーに強制的に実行させる方法はないと考えられます。その代わりに、攻撃者は、一般的にはユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージのリンクをクリックさせて誘導します。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">警告</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。
  
| セキュリティ情報 ID                                                       | 脆弱性のタイトル                                     | CVE の識別番号                                                                   | 最新のソフトウェアのリリースに関するコード実行の Exploitability (悪用可能性) の評価         | 旧バージョンのソフトウェアのリリースに関するコード実行の Exploitability (悪用可能性) の評価 | サービス拒否の悪用可能性の評価 | 注意事項 |  
|---------------------------------------------------------------------------|------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|--------------------------------|----------|  
| [MS11-083](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-083) | 参照カウンターのオーバーフローの脆弱性               | [CVE-2011-2013](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2013) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性 | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性 | 永続的                         | (なし)   |  
| [MS11-085](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-085) | Windows メールの安全でないライブラリのロードの脆弱性 | [CVE-2011-2016](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2016) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | 対象外                         | (なし)   |  
| [MS11-086](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-086) | LDAPS 認証バイパスの脆弱性                           | [CVE-2011-2014](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2014) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | 対象外                         | (なし)   |
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
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
</tr>
<tr>
<th colspan="6">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-083](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-083)
</td>
<td style="border:1px solid black;">
[MS11-085](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-085)
</td>
<td style="border:1px solid black;">
[MS11-086](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-086)
</td>
<td style="border:1px solid black;">
[MS11-084](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[ADAM (Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=8c7c21c5-677d-4a5d-8f2b-8ca7691b6b00&displaylang=ja)  
(KB2616310)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[ADAM (Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=989cca2d-cce1-4f52-b50e-43152693f240&displaylang=ja)  
(KB2616310)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-083](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-083)
</td>
<td style="border:1px solid black;">
[MS11-085](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-085)
</td>
<td style="border:1px solid black;">
[MS11-086](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-086)
</td>
<td style="border:1px solid black;">
[MS11-084](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=08b27ce7-c32e-41e4-ad04-481c5eab17a7&displaylang=ja)  
(KB2601626)  
(重要)  
[ADAM (Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=f116824e-ea48-422d-b284-c9ffa7604bf5&displaylang=ja)  
(KB2616310)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=de5a74f2-2cc8-4677-b495-3a40fe3d6b9e&displaylang=ja)  
(KB2601626)  
(重要)  
[ADAM (Active Directory Application Mode)](https://www.microsoft.com/download/details.aspx?familyid=1af1b734-62c7-4e08-91c8-90b6d026da84&displaylang=ja)  
(KB2616310)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=6168bc67-3d59-450f-bd8a-02d61dabe16b&displaylang=ja)  
(KB2601626)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-083](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-083)
</td>
<td style="border:1px solid black;">
[MS11-085](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-085)
</td>
<td style="border:1px solid black;">
[MS11-086](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-086)
</td>
<td style="border:1px solid black;">
[MS11-084](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fc3fe87c-2493-431d-a904-dec9310f6042&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e08266d8-fffa-40bf-b8f6-10a65ee27524&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=2bd602cf-ae0d-4790-a5d0-6133fd7d01a0&displaylang=ja)  
(KB2601626)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=042c1a8f-834d-4eed-8a59-9e030ccc6d39&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4f2365ed-d50e-44d9-b859-1ec54d3b4d38&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=783521ad-5c50-4194-a582-4e5a1c9999e7&displaylang=ja)  
(KB2601626)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-083](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-083)
</td>
<td style="border:1px solid black;">
[MS11-085](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-085)
</td>
<td style="border:1px solid black;">
[MS11-086](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-086)
</td>
<td style="border:1px solid black;">
[MS11-084](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=79382bf2-d2cb-42ea-92dc-64f949353521&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f82dc413-668c-4ca8-a8c8-db74f05346bc&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Active Directory および Active Directory Lightweight Directory Service (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=b5688923-3914-4f6c-8bc9-036fb4870cc6&displaylang=ja)\*  
(KB2601626)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=71ff3a89-d7ad-4dda-9e59-fab54b21bd5d&displaylang&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=06ad5637-56a1-4478-aaa0-063e877503c9&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Active Directory および Active Directory Lightweight Directory Service (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=51f47181-08f6-4de1-80e5-253355675965&displaylang=ja)\*  
(KB2601626)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b1c0cb05-c284-49b1-ae4f-92813fdf520f&displaylang&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2de5de74-e643-4045-9c22-ff95b0dbcafc&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-083](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-083)
</td>
<td style="border:1px solid black;">
[MS11-085](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-085)
</td>
<td style="border:1px solid black;">
[MS11-086](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-086)
</td>
<td style="border:1px solid black;">
[MS11-084](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[注意](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=4ddb4c2a-bada-49b0-ad78-e07e7e11ced7&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2307fa93-8e45-4841-a5a9-7e89960712f9&displaylang=ja)  
(注意)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=b06f9f55-e3b2-4705-83d0-1b9f5de9d378&displaylang=ja)  
(KB2601626)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=156c1bd9-55bc-482c-874b-61998d1ef153&displaylang=ja)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=05eef5d7-acf6-46e4-abfc-dc83f0a7cae5&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=62603d18-1b21-400c-8eba-202193182960&displaylang=ja)  
(注意)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=790f1d99-96a5-438d-b433-895b692912ce&displaylang=ja)  
(KB2601626)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5c7db930-5495-43f0-928c-d586ac9e80d0&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-083](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-083)
</td>
<td style="border:1px solid black;">
[MS11-085](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-085)
</td>
<td style="border:1px solid black;">
[MS11-086](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-086)
</td>
<td style="border:1px solid black;">
[MS11-084](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[注意](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3f9f74a6-e984-4aab-837c-ef7286e7305f&displaylang&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c9cf6a22-f9ab-427a-9b16-33c60baaabb5&displaylang=ja)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
[Active Directory および Active Directory Lightweight Directory Service (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=cc1e99af-fc67-400b-a82c-171f8c4d1ac9&displaylang=ja)\*  
(KB2601626)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5d810dae-5c52-4155-b5c2-163d27be6e78&displaylang&displaylang=ja)\*\*\*  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b20bfcbd-a515-4074-b56e-b82539fe5bad&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=012777f5-51f2-4944-91af-a9c79b8081a1&displaylang=ja)  
(注意)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=395819e2-1028-44b7-ace4-ca754b1a7543&displaylang=ja)  
(警告)
</td>
</tr>
</table>

<p></p>

 
Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*\*Server Core インストールは影響を受けません。この更新プログラムで解決している脆弱性は、Server Core インストール オプションを使用して Windows Server 2008 または Windows Server 2008 R2 をインストールした場合、この脆弱性による影響を受けるファイルがコンピューターに存在していたとしても、サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 に影響を与えません。しかし、更新プログラムのファイルのバージョン番号は現在コンピューターに存在するファイルのものより新しいため (より新しいバージョン番号を持つため)、この更新プログラムが提供されます。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

検出および適用ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](https://technet.microsoft.com/ja-jp/updatemanagement/bb245732)を参照してください。[セキュリティ TechCenter](https://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](https://www.microsoft.com/ja-jp/security/default.aspx)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](https://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](https://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (たとえば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](https://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および適用のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および適用に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および適用のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](https://support.microsoft.com/kb/961747) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](https://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) の Web サイトを参照してください。

System Center Configuration Manager 2007

Configuration Manager 2007 のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。Configuration Manager 2007 で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

Configuration Manager 2007 の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。Configuration Manager 2007 のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。管理者が Configuration Manager 2007 を使用して更新プログラムを展開する方法の詳細については、[ソフトウェアの更新管理](https://www.microsoft.com/japan/systemcenter/configmgr/products/updatemgmt.mspx)を参照してください。Configuration Manager の詳細については、[System Center Configuration Manager](https://www.microsoft.com/japan/systemcenter/configmgr/default.mspx) を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](https://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager 2007 については、前のセクション「System Center Configuration Manager 2007」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](https://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=ja) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](https://technet.microsoft.com/ja-jp/systemcenter/bb545936.aspx) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](https://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja-nec) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199/ja): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](https://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](https://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からもダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://technet.microsoft.com/ja-jp/security/cc136632.aspx)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](https://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS11-084 で説明している問題を報告してくださった [CERT/CC](https://www.cert.org/) の Will Dorman 氏
-   MS11-085 で説明している問題を報告してくださった EvilCode の Ivan Sanchez 氏
-   MS11-086 で説明している問題を報告してくださった Autosécurité の Xavier Lassoie 氏ならびに Sébastien Godard 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](https://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償でサポートをご提供いたします。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](https://support.microsoft.com/?ln=ja)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](https://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2011/11/09):このセキュリティ情報の概要ページを公開しました。

*Built at 2014-04-18T01:50:00Z-07:00*
