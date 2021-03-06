---
TOCTitle: 'MS16-SEP'
Title: 2016 年 9 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms16-sep'
ms:contentKeyID: 73896133
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms16-sep(v=Security.10)'
---

2016 年 9 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日: 2016 年 9 月 14 日 | 最終更新日: 2017 年 7 月 12 日

**バージョン:** 2.0

このセキュリティ情報の概要は 2016 年 9 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定するときに役立つ情報も提供します。「**関連情報**」の欄を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、「**影響を受けるソフトウェア**」のセクションを参照してください。

<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>セキュリティ情報タイトルおよび概要</strong></td>
<td style="border:1px solid black;"><strong>最大深刻度<br />
と脆弱性の影響</strong></td>
<td style="border:1px solid black;"><strong>再起動の必要性</strong></td>
<td style="border:1px solid black;"><strong>既知の<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>影響を受けるソフトウェア</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=823624">MS16-104</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3183038)<br />
</strong>このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている場合は、攻撃者が影響を受けるコンピューターを制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3185319">3185319</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=823625">MS16-105</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (3183043)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Microsoft Edge を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限を持つユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=824814">MS16-106</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3185848)<br />
</strong>このセキュリティ更新プログラムにより、Microsoft Windows の脆弱性が解決されます。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web サイトにアクセス、または特別に細工された文書を開いた場合に、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=824817">MS16-107</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 用のセキュリティ更新プログラム (3185852)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。最も深刻な脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。システムに関するユーザー権限が低く設定されているアカウントを使用しているユーザーは、管理者ユーザー権限で実行しているユーザーよりも影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services および Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=824829">MS16-108</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 用のセキュリティ更新プログラム (3185883)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Exchange Server に存在する脆弱性を解決します。最も深刻な脆弱性が悪用された場合、攻撃者が特別に細工された添付ファイル付きの電子メールを脆弱な Exchange Server に送信すると、Exchange Server に組み込まれている Oracle Outside In ライブラリでリモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=824768">MS16-109</a></td>
<td style="border:1px solid black;"><strong>Silverlight 用のセキュリティ更新プログラム (3182373)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Silverlight の脆弱性を解決します。この脆弱性により、特別な細工がされた Silverlight アプリケーションが含まれる侵害された Web サイトをユーザーが訪問した場合、リモートでコードが実行される可能性があります。攻撃者は、侵害された Web サイトにユーザーを強制的に訪問させることはできません。その代わり、通常、ユーザーを攻撃者の Web サイトに接続させる電子メールまたはインスタント メッセージ内のリンクをクリックさせようと誘導し、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動は必要ありません</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=821596">MS16-110</a></td>
<td style="border:1px solid black;"><strong>Windows 用のセキュリティ更新プログラム (3178467)<br />
</strong>このセキュリティ更新プログラムにより、Microsoft Windows の脆弱性が解決されます。この脆弱性で最も深刻なケースでは、攻撃者が特別に細工したリクエストを作成し、ターゲットのコンピューターで昇格されたアクセス許可で任意のコードを実行した場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3187754">3187754</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=825142">MS16-111</a></td>
<td style="border:1px solid black;"><strong>Windows カーネル用のセキュリティ更新プログラム (3186973)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、標的のシステムで攻撃者が特別に細工されたアプリケーションを実行した場合、特権の昇格が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3175024">3175024</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=821605">MS16-112</a></td>
<td style="border:1px solid black;"><strong>Windows のロック画面用のセキュリティ更新プログラム (3178469)<br />
</strong>このセキュリティ更新プログラムは Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、Windows のロック画面からウェブ コンテンツを読み込むことを Windows が不適切に許可する場合に特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=824825">MS16-113</a></td>
<td style="border:1px solid black;"><strong>Windows 保護カーネル モード用のセキュリティ更新プログラム (3185876)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の 1 件の脆弱性を解決します。Windows 保護カーネル モードがメモリ内のオブジェクトを不適切に処理した場合、この脆弱性により情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=824826">MS16-114</a></td>
<td style="border:1px solid black;"><strong>SMBv1 サーバー用のセキュリティ更新プログラム (3185879)<br />
</strong>このセキュリティ更新プログラムは Microsoft Windows の脆弱性を解決します。Windows Vista、Windows Server 2008、Windows 7、および Windows Server 2008 R2 のオペレーティング システムで、認証された攻撃者が特別に細工したパケットを感染した Microsoft Server Message Block 1.0 (SMBv1) Server に送信した場合に、リモートでコードが実行される可能性があります。この脆弱性は他のバージョンの SMB Server には影響を及ぼしません。最新のオペレーティング システムは、サービス拒否の影響を受ける可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=825727">MS16-115</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows PDF ライブラリ用のセキュリティ更新プログラム(3188733)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された PDF コンテンツをオンラインで閲覧したり、特別に細工された PDF ドキュメントを開いた場合に、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=825725">MS16-116</a></td>
<td style="border:1px solid black;"><strong>VBScript Scripting Engine 用の OLE オートメーションのセキュリティ更新プログラム (3188724)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性が悪用されると、影響を受けるシステムを使用しているユーザーが悪質または侵害された Web サイトへ誘導された場合に、リモートでコードが実行される可能性があります。このセキュリティ情報で説明されている脆弱性から保護するには、2 つの更新プログラムをインストールする必要があります。このセキュリティ情報、MS16-116 および <a href="https://go.microsoft.com/fwlink/?linkid=823624">MS16-104</a> の更新プログラムです。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows<br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=825603">MS16-117</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player のセキュリティ更新プログラム (3188128)<br />
</strong>このセキュリティ更新プログラムは、すべてのサポートされている Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、および Windows 10 にインストールすることで Adobe Flash Player の脆弱性を解決します。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

Exploitability Index (悪用可能性指標)
-------------------------------------

<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報 ID、CVE ID の順でリストされています。掲示板での重要度評価が緊急または重要である脆弱性のみが含まれています。

**この表はどのように使用しますか?**

この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、「[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259)」を参照してください。

下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE の識別番号**                    

</td>
<td style="border:1px solid black;">
**脆弱性のタイトル**

</td>
<td style="border:1px solid black;">
**最新のソフトウェア リリースでの  
悪用可能性評価**

</td>
<td style="border:1px solid black;">
**過去のソフトウェア リリースでの  
悪用可能性評価**

</td>
<td style="border:1px solid black;">
**サービス拒否  
悪用可能性評価**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-104: Internet Explorer 用の累積的なセキュリティ更新プログラム (3183038)**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3247](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3247)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3291](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3291)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3292](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3292)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3295](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3295)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3297](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3297)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3324](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3324)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3325](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3325)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3351](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3351)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
0 - 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
0 - 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3353](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3353)

</td>
<td style="border:1px solid black;">
Internet Explorer のセキュリティ機能のバイパス

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3375](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3375)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-105: Microsoft Edge 用の累積的なセキュリティ更新プログラム (3183043)**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3247](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3247)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3291](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3291)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3294](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3294)

</td>
<td style="border:1px solid black;">
Microsoft Edge のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3295](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3295)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3297](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3297)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3325](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3325)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3330](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3330)

</td>
<td style="border:1px solid black;">
Microsoft Edge のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3350](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3350)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3351](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3351)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
0 - 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3370](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3370)

</td>
<td style="border:1px solid black;">
PDF ライブラリの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3374](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3374)

</td>
<td style="border:1px solid black;">
PDF ライブラリの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3377](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3377)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-106: Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3185848)**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3348](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3348)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3349](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3349)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE–2016-3354](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3354)

</td>
<td style="border:1px solid black;">
GDI の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE–2016-3355](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3355)

</td>
<td style="border:1px solid black;">
GDI の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE–2016-3356](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3356)

</td>
<td style="border:1px solid black;">
GDI のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-107: Microsoft Office 用のセキュリティ更新プログラム (3185852)**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0137](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0137)

</td>
<td style="border:1px solid black;">
Microsoft APP-V ASLR バイパス

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0141](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0141)

</td>
<td style="border:1px solid black;">
Microsoft の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3357](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3357)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3358](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3358)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3359](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3359)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3360](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3360)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3361](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3361)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3362](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3362)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3363](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3363)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3364](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3364)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3365](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3365)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3366](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3366)

</td>
<td style="border:1px solid black;">
Microsoft Office のなりすましの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3381](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3381)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-108: Microsoft Exchange Server 用のセキュリティ更新プログラム (3185883)**](https://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0138](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0138)

</td>
<td style="border:1px solid black;">
Microsoft Exchange の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3378](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3378)

</td>
<td style="border:1px solid black;">
Microsoft Exchange のオープン リダイレクトの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3379](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3379)

</td>
<td style="border:1px solid black;">
Microsoft Exchange の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-109: Silverlight 用のセキュリティ更新プログラム (3182373)**](https://go.microsoft.com/fwlink/?linkid=824768)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3367](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3367)

</td>
<td style="border:1px solid black;">
Microsoft Silverlight のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-110: Windows 用のセキュリティ更新プログラム (3178467)**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3346](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3346)

</td>
<td style="border:1px solid black;">
Windows のアクセス許可を施行する特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3352](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3352)

</td>
<td style="border:1px solid black;">
Microsoft の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3368](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3368)

</td>
<td style="border:1px solid black;">
Windows のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3369](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3369)

</td>
<td style="border:1px solid black;">
Windows のサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-111: Windows カーネル用のセキュリティ更新プログラム (3186973)**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3305](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3305)

</td>
<td style="border:1px solid black;">
Windows のセッション オブジェクトの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3306](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3306)

</td>
<td style="border:1px solid black;">
Windows のセッション オブジェクトの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3371](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3371)

</td>
<td style="border:1px solid black;">
Windows カーネルの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3372](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3372)

</td>
<td style="border:1px solid black;">
Windows カーネルの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3373](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3373)

</td>
<td style="border:1px solid black;">
Windows カーネルの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-112: ロック画面用のセキュリティ更新プログラム (3178469)**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3302](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3302)

</td>
<td style="border:1px solid black;">
Windows のロック画面の特権の昇格に関する脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-113: Windows 保護カーネル モード用のセキュリティ更新プログラム (3185876)**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3344](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3344)

</td>
<td style="border:1px solid black;">
Windows の保護カーネル モードの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-114: SMBv1 サーバー用のセキュリティ更新プログラム (3185879)**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3345](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3345)

</td>
<td style="border:1px solid black;">
Windows の SMB 認証のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-115: Microsoft Windows PDF ライブラリ用のセキュリティ更新プログラム (3188733)**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3370](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3370)

</td>
<td style="border:1px solid black;">
PDF ライブラリの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3374](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3374)

</td>
<td style="border:1px solid black;">
PDF ライブラリの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-116: VBScript スクリプト エンジン用の OLE オートメーションのセキュリティ更新プログラム (3188724)**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3375](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3375)

</td>
<td style="border:1px solid black;">
スクリプト エンジンの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-117: Adobe Flash Player のセキュリティ更新プログラム (3188128)**](https://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-29](https://helpx.adobe.com/jp/security/products/flash-player/apsb16-29.html)

</td>
<td style="border:1px solid black;">
脆弱性の深刻度および更新プログラムの優先度の評価については、Adobe Security Bulletin [APSB16-29](https://helpx.adobe.com/jp/security/products/flash-player/apsb16-29.html) を参照してください。

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
</tr>
</table>
 

 影響を受けるソフトウェア
-------------------------

<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。

これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。

**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。

 

### Windows オペレーティング システムとコンポーネント (表 1/2)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3185319)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3175024)  
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
Internet Explorer 9   
(3185319)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3185319)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3175024)  
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
Internet Explorer 9   
(3185319)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外                   

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3184471)  
(重要)  
Windows 8.1 for 32-bit Systems  
(3187754)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3178539)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3184471)  
(重要)  
Windows 8.1 for x64-based Systems  
(3187754)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3178539)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3185319)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3178539)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3184471)  
(重要)  
Windows RT 8.1  
(3187754)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3178539)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185611)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3185611)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185611)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3185611)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185614)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185614)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3185614)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185614)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185614)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3185614)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3189866)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3189866)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3189866)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3189866)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3189866)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3189866)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3189866)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3189866)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3189866)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3189866)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3189866)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3189866)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1703 for 32-bit Systems

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
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1703 for 32-bit Systems  
(4025342)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1703 for x64-based Systems

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
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1703 for x64-based Systems  
(4025342)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-104**](https://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](https://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](https://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](https://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](https://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](https://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3185911)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3184471)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3175024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3178539)  
(重要)

</td>
</tr>
</table>
 
 

### Windows オペレーティング システムとコンポーネント (表 2/2)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3184122)  
(緊急)

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
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3184122)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3184122)  
(警告)

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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3184122)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3184122)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3184122)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3184122)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3184122)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3184122)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3184943)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3184122)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3188128)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3184943)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3184122)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3188128)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3184943)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3184122)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3188128)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3184943)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3184122)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3188128)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3184943)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3184122)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3188128)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3185611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3188128)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3185611)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3185611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3188128)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3185614)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3188128)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3185614)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3188128)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3189866)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3189866)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3188128)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3185614)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3189866)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3189866)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3188128)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1703 for 32-bit Systems

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
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1703 for x64-based Systems

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
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-113**](https://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](https://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](https://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](https://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](https://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3184122)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3184122)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3184122)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3184122)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3177186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3184122)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
 

### Microsoft Office スイートおよびソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3118300)  
(緊急)  
Microsoft Excel 2007 Service Pack 3  
(3115459)  
(重要)  
Microsoft Outlook 2007  
(3118303)  
(重要)  
Microsoft PowerPoint 2007 Service Pack 3  
(3114744)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3118309)  
(緊急)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2553432)  
(緊急)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(3118316)  
(重要)  
Microsoft Outlook 2010 Service Pack 2 (32 ビット版)  
(3118313)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32-bit エディション)  
(3115467)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3118309)  
(緊急)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2553432)  
(緊急)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(3118316)  
(重要)  
Microsoft Outlook 2010 Service Pack 2 (64 ビット版)  
(3118313)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64-bit エディション)  
(3115467)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(3118268)  
(緊急)  
Microsoft Office 2013 Service Pack 1 (32 ビット版)<sup>[1]</sup>
(重要)  
Microsoft Excel 2013 Service Pack 1 (32 ビット版)  
(3118284)  
(重要)  
Microsoft Outlook 2013 Service Pack 1 (32 ビット版)  
(3118280)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (32-bit エディション)  
(3115487)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)  
(3118268)  
(緊急)  
Microsoft Office 2013 Service Pack 1 (64 ビット版)<sup>[1]</sup>
(重要)  
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(3118284)  
(重要)  
Microsoft Outlook 2013 Service Pack 1 (64 ビット版)  
(3118280)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (64-bit エディション)  
(3115487)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3118268)  
(緊急)  
Microsoft Excel 2013 RT Service Pack 1  
(3118284)  
(重要)  
Microsoft Outlook 2013 RT Service Pack 1  
(3118280)  
(重要)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3115487)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 ビット版) <sup>[1]</sup>
Microsoft Office 2016 (32 ビット版)  
(3118292)  
(緊急)  
Microsoft Excel 2016 (32 ビット版)  
(3118290)  
(重要)  
Microsoft Outlook 2016 (32 ビット版)  
(3118293)  
(重要)  
Microsoft Visio 2016 (32 ビット版)  
(重要)<sup>[1]</sup>

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)<sup>[1]</sup>
Microsoft Office 2016 (64 ビット版)  
(3118292)  
(緊急)  
Microsoft Excel 2016 (64 ビット版)  
(3118290)  
(重要)  
Microsoft Outlook 2016 (64 ビット版)  
(3118293)  
(重要)  
Microsoft Visio 2016 (64 ビット版)  
(重要)<sup>[1]</sup>

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3186805)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3186807)  
(重要)  
Microsoft PowerPoint 2016 for Mac  
(3186807)  
(重要)  
Microsoft Word 2016 for Mac  
(3186807)  
(緊急)  
Microsoft Outlook 2016 for Mac  
(3186807)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**その他の Office ソフトウェア**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2597974)  
(重要)  
Microsoft Office 互換機能パック Service Pack 3  
(3115462)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3115463)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer  
(3054969)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3118297)  
(緊急)

</td>
</tr>
</table>
 
<sup>[1]</sup>クイック実行 (C2R) バージョンのみの参照用項目です。

 

### Microsoft Office Services および Web Apps

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Excel Services  
(3115112)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)

</td>
<td style="border:1px solid black;">
Excel Services  
(3115112)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3115119)  
(重要)  
Word Automation Services  
(3115466)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(3054862)  
(緊急)  
Excel Automation Services  
(3115169)  
(緊急)  
Word Automation Services  
(3115443)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3115472)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3118270)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-107**](https://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Office Online Server

</td>
<td style="border:1px solid black;">
Office Online Server  
(3118299)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft サーバー ソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-108**](https://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(3184711)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-108**](https://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(3184728)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-108**](https://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3184736)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 12

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 12  
(3184736)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 13

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 13  
(3184736)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-108**](https://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 の累積的な更新プログラム 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 の累積的な更新プログラム 1  
(3184736)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 の累積的な更新プログラム 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 の累積的な更新プログラム 2  
(3184736)  
(重要)

</td>
</tr>
</table>
 
### Microsoft 開発者用ツールおよびソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-109**](https://go.microsoft.com/fwlink/?linkid=824768)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**  

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
Mac にインストールされている Microsoft Silverlight 5  
(3182373)  
(重要)  
Mac にインストールされている Microsoft Silverlight 5 Developer Runtime  
(3182373)  
(重要)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5  
(3182373)  
(重要)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3182373)  
(重要)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5  
(3182373)  
(重要)

</td>
</tr>
</table>
 
 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと、一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび検証を効率化するときに役立ちます。

利用可能なこれらのツールおよびその他のツールの詳細については、[IT 管理者向けセキュリティ ツール](https://technet.microsoft.com/ja-jp/security/cc297183)を参照してください。 

謝辞
----

<span id="sectionToggle4"></span>
マイクロソフトでは、マイクロソフトが責任を負う脆弱性の公開によるお客様の保護に際して、セキュリティ コミュニティの方々からいただいたご助力に感謝いたします。詳細については、[謝辞](https://technet.microsoft.com/ja-jp/library/security/mt674627.aspx)をご覧ください。

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/ja-jp/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](https://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](https://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security update」のキーワード検索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージを Microsoft ダウンロード センターから入手することができます。詳細については、[マイクロソフト サポート技術情報 913086](https://support.microsoft.com/ja-jp/kb/913086) を参照してください。

**IT プロフェッショナル セキュリティ コミュニティ**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うには、[IT プロフェッショナル セキュリティ コミュニティ](https://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。その他のバージョンについては、サポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション: [TechNet セキュリティに関するトラブルシューティングとサポート](https://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ: [ウイルスとセキュリティ サポート ページ](https://support.microsoft.com/ja-jp/contactus/cu_sc_virsec_master)

国ごとのローカル サポート: [その他の地域のサポート](https://support.microsoft.com/ja-jp/common/international.aspx)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation およびその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。Microsoft Corporation、その関連会社およびこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含むすべての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2016/09/14): このセキュリティ情報の概要ページを公開しました。
-   V2.0 (2017/07/12): MS16-111 について、CVE-2016-3305 の影響を受ける Windows 10 Version 1703 for 32-bit Systems と Windows 10 Version 1703 for x64-based Systems を「影響を受けるソフトウェア」の表に追加しました。マイクロソフトは、Windows 10 Version 1703 を実行するお客様が、このセキュリティ情報で説明されている脆弱性から保護するために、更新プログラム 4025342 をインストールすることを推奨します。

*Page generated 2017-07-03 16:05-07:00.*
