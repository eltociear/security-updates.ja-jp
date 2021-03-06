---
TOCTitle: 'MS07-NOV'
Title: 2007 年 11 月のセキュリティ情報
ms:assetid: 'ms07-nov'
ms:contentKeyID: 61229643
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms07-nov(v=Security.10)'
---

 

2007 年 11 月のセキュリティ情報
===============================

公開日: 2007年11月9日 | 最終更新日: 2007年11月14日

**バージョン:** 1.0

イラストを交えたセキュリティ情報はこちらをご覧ください。

絵でみるセキュリティ情報
------------------------

 
[MS07-061 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms07-061e.mspx)

[MS07-062 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms07-062e.mspx)

このセキュリティ情報は、2007 年 11 月に公開したセキュリティ情報の一覧です。

2007 年 11 月のセキュリティ情報の公開により、2007 年 11 月 9 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2007 年 11 月 14 日午前 11：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[11 月のセキュリティ情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344694&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](https://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

日本語版の Webcast 情報は 2007 年 11 月 14 日 の午後 (日本時間) に配信いたします。詳細は、「[今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。11 月より音声版のダウンロードがご利用可能になります。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

#### 概要

今月のセキュリティ情報を深刻度別に下記に示します。

緊急 (1)
--------

 
| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-061                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [MS07-061 Windows URI 処理の脆弱性により、リモートでコードが実行される (943460)](https://technet.microsoft.com/security/bulletin/ms07-061)                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **概要**                     | この更新プログラムは一般に報告された脆弱性を解決します。リモートでコードが実行される脆弱性が、Windows シェルが特別に細工された URI を処理する方法にあります。Windows シェルがこれらの URI を十分に確認しない場合、攻撃者によりこの脆弱性が悪用され、任意のコードが実行される可能性があります。マイクロソフトは Internet Explorer 7 を使用しているコンピュータ上でのみこの脆弱性が悪用される方法を確認していますが、この脆弱性は Windows ファイルである Shell32.dll に存在しています。このファイルは Windows XP および Windows Server 2003 のすべてのサポートされているエディションに含まれています。 |
| **最大深刻度**               | [緊急](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動が必要です。                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **影響を受けるソフトウェア** | **Windows.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |

重要 (1)
--------

 

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-062                                                                                                                                                                                                                                  |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [MS07-062 DNS の脆弱性により、なりすましが行われる (941672)](https://technet.microsoft.com/security/bulletin/ms07-062)                                                                                                                                                     |
| **概要**                     | この深刻度「重要」のセキュリティ更新プログラムは、非公開で報告された脆弱性を解決します。この脆弱性により、攻撃者がDNS リクエストに特別に細工した応答を送信するので、「なりすまし攻撃」または適正な場所からインターネット トラフィックをリダイレクトする可能性があります。 |
| **最大深刻度**               | [重要](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                             |
| **脆弱性の影響**             | なりすまし                                                                                                                                                                                                                                                                |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                           |
| **影響を受けるソフトウェア** | **Windows.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                 |

影響を受けるソフトウェアおよびダウンロード先
--------------------------------------------

 
**この表はどのように使用しますか?**

この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが 記載されている場合、脆弱性の深刻度も記載されています。

**注 :** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。

#### 影響を受けるソフトウェアおよびダウンロード先

![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)このマークをクリックして、更新プログラムをダウンロードしてください。

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
詳細
</th>
<th style="border:1px solid black;" >
詳細
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[MS07-061](https://technet.microsoft.com/security/bulletin/ms07-061)
</td>
<td style="border:1px solid black;">
[MS07-062](https://technet.microsoft.com/security/bulletin/ms07-062)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<th colspan="3">
Windows 影響を受けるソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=c80fcd9b-d0f8-44db-96fc-bf2ead054ff4&displaylang=ja)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=8ba1c2f9-1bde-4e97-b327-21259c5e5104&displaylang=ja)
</td>
<td style="border:1px solid black;">
 
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition:
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f&displaylang=ja)
</td>
<td style="border:1px solid black;">
 
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b&displaylang=ja)
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d&displaylang=ja)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b&displaylang=ja)
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d&displaylang=ja)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326&displaylang=ja)
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e&displaylang=ja)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326&displaylang=ja)
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e&displaylang=ja)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP1 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5&displaylang=ja)
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6&displaylang=ja)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5&displaylang=ja)
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627221.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6&displaylang=ja)
</td>
</tr>
</table>

<p></p>

 

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティセントラル**

組織のサーバー、デスクトップ、モバイル コンピュータに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、 [TechNet 更新プログラム管理](https://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet Security センター](https://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供して います。

コンシューマのお客様は [Security At Home](https://www.microsoft.com/japan/athome/security) をご覧ください。この情報は「最新のセキュ リティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](https://update.microsoft.com/microsoftupdate/)、[Windows Update](https://windowsupdate.microsoft.com/) および [Office Update](https://go.microsoft.com/fwlink/?%20linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/results.aspx?%20displaylang=ja&freetext=security_patch)からダウンロードすることができます。「security\_patch」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の 関連情報を参照するには、サポート技術情報 [323166](https://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、 Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに 役立ちます。詳細情報は、サポート技術情報 [910723](https://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer および Enterprise Update Scan Tool**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピュータやリモートコンピュータの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。 MBSA の詳細情報については、 [Microsoft Baseline Security Analyzer (MBSA) Web サイト](https://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

MBSA 1.2.1 が検出できない特定のセキュリティ更新プログラムの場合、マイクロソフトは、特定のセキュリティ更新プログラム向けに Enterprise Scan Tool (EST) を公開しています。 EST の詳細については、[Enterprise Update Scan Tool](https://support.microsoft.com/kb/894193) をご覧く ださい。

**注意:** 2007 年 10 月 9 日以降、MBSA 1.2.1 で使用されている MSSecure.XML ファイルは更新されなくなります。この日以降、MBSA 1.2.1 で使用されている MSSecure.XML ファイルに新しいセキュリティ更新プログラムは追加されません。また、新しいバージョンの Enterprise Scan Tool はリリースされません。 MBSA の詳細情報については、 [Microsoft Baseline Security Analyzer (MBSA) Web サイト](https://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003、およ び SQL Server 2000 用のセキュリティ更新プログラムに対応しています。Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](https://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧 ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、 管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピュータを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新 プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](https://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用の お客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](https://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](https://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供さ れた更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコン ピュータへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](https://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピュータの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](https://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

今月:

-   マイクロソフトは Microsoft Update (MU) および Windows Server Update Services (WSUS) により、**セキュリティ以外** の優先度の高い更新プログラムを 3 件公開しました。
-   マイクロソフトは Windows Update (WU) で、Windows 用の**セキュリティ以外**の優先度の高い更新プログラムを 0 件公開しました。

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。そのほかの日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](https://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プ ログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [Microsoft ダウンロード センター](https://www.microsoft.com/downloads/search.aspx?displaylang=ja)か らダウンロードすることができます。「security\_patch」 のキーワード探索によって容易に見つけることができます。
-   コンシューマ用プラットフォームの更新プログラムは、[Microsoft Update](https://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード セ ンターから入手することができます。詳細情報は、サポート技術情報 [913086](https://support.microsoft.com/kb/913086) を ご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてそのほかの IT プロフェッショナルとの情報交換を 行うためには、[IT Pro Security Community](https://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](https://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS07-061 に説明されている問題についてマイクロソフトに協力してくださった Jesper Johansson 氏
-   MS07-061 に説明されている問題についてマイクロソフトに協力してくださった [Secunia](https://corporate.secunia.com/) の Carsten H. Eiram 氏
-   MS07-061 に説明されている問題についてマイクロソフトに協力してくださった [Finjan](https://www.finjan.com/) の Aviv Raff 氏
-   MS07-061 に説明されている問題についてマイクロソフトに協力してくださった [GNUCITIZEN](https://www.gnucitizen.org/) の Petko Petkov 氏
-   MS07-062 に説明されている問題を報告してくださった [Scanit](https://www.scanit.be/) の Alla Berzroutchko 氏
-   MS07-062 に説明されている問題を報告してくださった [Trusteer](https://www.trusteer.com/) の Amit Klein 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](https://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原 因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法は [こちら](https://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報 の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または 書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連 会社 及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一 切責任を負いません。(Microsoft Corporation、その関連会社 またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴:

-   2007/11/14: このセキュリティ情報の概要ページを公開しました。

*Built at 2014-04-18T01:50:00Z-07:00*
