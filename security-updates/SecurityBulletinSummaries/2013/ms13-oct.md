---
TOCTitle: 'MS13-OCT'
Title: 2013 年 10 月のセキュリティ情報
ms:assetid: 'ms13-oct'
ms:contentKeyID: 61229716
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms13-oct(v=Security.10)'
---


2013 年 10 月のセキュリティ情報
===============================

公開日: 2013年10月9日 | 最終更新日: 2013年11月7日

**バージョン:** 1.0

[![](../../images/Dn627296.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627296.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2013 年 10 月公開のセキュリティ情報の一覧です。

2013 年 10 月のセキュリティ情報の公開により、2013 年 10 月 4 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフトセキュリティ情報の事前通知](https://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2013 年 10 月 9 日 の午後 (日本時間) に配信予定です。詳細は、「 [今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/security/dd251169.aspx) 」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2013 年 10 月 9 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[10 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557381&culture=en-us) (英語)。この日付以降、この Webcast は[オンデマンド](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538623&culture=en-us)で利用可能となります。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

### セキュリティ情報に関する情報

#### 概要

次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェア」を参照してください。

 
<p> </p>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2879017)<br />
<br />
このセキュリティ更新プログラムは、Internet Explorer に存在する 1 件の一般に公開された脆弱性および 9 件の非公開で報告された脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者により、最も深刻な脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、リモートでコードが実行される (2870008)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 7 件の Microsoft Windows に存在する脆弱性を解決します。このような脆弱性のうち、最も深刻なものが悪用された場合、ユーザーが OpenType または TrueType フォントを含んでいる共有コンテンツを表示したときに、リモートでコードが実行される可能性があります。これらの脆弱性を攻撃者が悪用した場合、影響を受けるコンピューターが完全に制御される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">.NET Framework の脆弱性により、リモートでコードが実行される (2878890)<br />
<br />
このセキュリティ更新プログラムは Microsoft .NET Framework に存在する 2 件の非公開で報告された脆弱性および 1 件の一般に公開された脆弱性を解決します。これらの中で最も深刻な脆弱性では、ユーザーが XBAP アプリケーションをインスタンス化できるブラウザーを使用して、特別に細工した OpenType フォント (OTF) ファイルが含まれている Web サイトを訪問した場合に、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314045">MS13-083</a></td>
<td style="border:1px solid black;">Windows コモン コントロール ライブラリの脆弱性により、リモートでコードが実行される (2864058)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が影響を受けるコンピューターで稼働する ASP.NET Web アプリケーションに特別な細工を施した Web 要求を送信した場合、リモートでコードが実行される可能性があります。攻撃者は、この脆弱性を悪用して、認証なしに任意のコードを実行する可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">Microsoft SharePoint Server の脆弱性により、リモートでコードが実行される (2885089)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Office サーバー ソフトウェアに存在する脆弱性を解決します。ユーザーが Microsoft SharePoint Server、Microsoft Office Services、または Web Apps の影響を受けるバージョンで、特別に細工された Office ファイルを開くと、最も深刻な脆弱性によってリモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Microsoft Excel の脆弱性により、リモートでコードが実行される (2885080)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Office に存在する脆弱性を解決します。ユーザーが Microsoft Excel の影響を受けるバージョン、または影響を受ける Microsoft Office の他のソフトウェアで、特別に細工されたファイルを開くと、脆弱性によってリモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">Microsoft Word の脆弱性により、リモートでコードが実行される (2885084)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Office に存在する脆弱性を解決します。この脆弱性が悪用された場合、Microsoft Word の影響を受けるバージョンまたはその他の影響を受ける Microsoft Office ソフトウェアで、特別に細工されたファイルが開かれると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324590">MS13-087</a></td>
<td style="border:1px solid black;">Silverlight の脆弱性により、情報漏えいが起こる (2890788)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された 1 件の Microsoft Silverlight の脆弱性を解決します。この脆弱性により、攻撃者がこの脆弱性を悪用する特別に細工された Silverlight アプリケーションを含む Web サイトをホストし、ユーザーにその Web サイトを表示するよう誘導した場合、情報が漏えいする可能性があります。また、攻撃者は侵害された Web サイトおよびユーザーが提供したコンテンツや広告を受け入れるまたはホストする Web サイトを利用する可能性があります。このような Web サイトには、この脆弱性を悪用する可能性のある特別に細工されたコンテンツが含まれている場合があります。しかし、すべての場合において、攻撃者がユーザーに Web サイトを強制的に訪問させる方法はありません。その代わり、通常、ユーザーに攻撃者の Web サイトに接続させる電子メール メッセージまたはインスタント メッセンジャー メッセージ内のリンクをクリックさせることにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。バナー広告など、影響を受けるシステムに Web コンテンツを配信する方法を使用して、特別に細工した Web コンテンツの表示を可能にする場合もあります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動不要</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
</tbody>
</table>
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >脆弱性のタイトル</th>
<th style="border:1px solid black;" >CVE の識別番号</th>
<th style="border:1px solid black;" >最新のソフトウェアのリリースに関する Exploitability (悪用可能性) の評価</th>
<th style="border:1px solid black;" >旧バージョンのソフトウェアのリリースに関する Exploitability (悪用可能性) の評価</th>
<th style="border:1px solid black;" >サービス拒否の悪用可能性の評価</th>
<th style="border:1px solid black;" >注意事項</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3871">CVE-2013-3871</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3872">CVE-2013-3872</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3873">CVE-2013-3873</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3874">CVE-2013-3874</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3875">CVE-2013-3875</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3882">CVE-2013-3882</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3885">CVE-2013-3885</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3886">CVE-2013-3886</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3893">CVE-2013-3893</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。<br />
<br />
マイクロソフトは、Internet Explorer 8 および Internet Explorer 9 でこの脆弱性を悪用しようとする標的型攻撃を確認しています。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3897">CVE-2013-3897</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">マイクロソフトは、Internet Explorer 8 でこの脆弱性を悪用しようとする標的型攻撃を確認しています。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">OpenType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">この脆弱性は <a href="https://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a><a href="https://go.microsoft.com/fwlink/?linkid=293350"></a> にも影響を及ぼします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Windows USB 記述子の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3200">CVE-2013-3200</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3879">CVE-2013-3879</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">アプリ コンテナーの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3880">CVE-2013-3880</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性で、特権の昇格を引き起こす可能性があります。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Win32k NULL ページの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3881">CVE-2013-3881</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">DirectX グラフィック カーネル サブシステムの ダブル フェッチの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3888">CVE-2013-3888</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">TrueType フォント CMAP テーブルの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3894">CVE-2013-3894</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">OpenType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="https://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a><a href="https://go.microsoft.com/fwlink/?linkid=293350"></a> にも影響を及ぼします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">エンティティ拡張の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3860">CVE-2013-3860</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">JSON 解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3861">CVE-2013-3861</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。<br />
<br />
この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314045">MS13-083</a></td>
<td style="border:1px solid black;">Comctl32 整数オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3195">CVE-2013-3195</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">Microsoft Excel のメモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="https://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a><a href="https://go.microsoft.com/fwlink/?linkid=293350"></a> にも影響を及ぼします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">パラメーター インジェクションの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3895">CVE-2013-3895</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Microsoft Excel のメモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="https://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a><a href="https://go.microsoft.com/fwlink/?linkid=293350"></a> にも影響を及ぼします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Microsoft Excel のメモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3890">CVE-2013-3890</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">メモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3891">CVE-2013-3891</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">メモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3892">CVE-2013-3892</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324590">MS13-087</a></td>
<td style="border:1px solid black;">Silverlight の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3896">CVE-2013-3896</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性で、セキュリティ機能のバイパスを引き起こす可能性があります。</td>
</tr>
</tbody>
</table>
  
影響を受けるソフトウェア  
------------------------
  
<span></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="5">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(緊急)  
Internet Explorer 7   
(2879017)  
(緊急)  
Internet Explorer 8   
(2879017)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2847311)  
(緊急)  
Windows XP Service Pack 3  
(2862330)  
(重要)  
Windows XP Service Pack 3  
(2862335)  
(重要)  
Windows XP Service Pack 3  
(2868038)  
(重要)  
Windows XP Service Pack 3  
(2883150)  
(緊急)  
Windows XP Service Pack 3  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(緊急)
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
Internet Explorer 6   
(2879017)  
(緊急)  
Internet Explorer 7   
(2879017)  
(緊急)  
Internet Explorer 8   
(2879017)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2847311)  
(緊急)  
Windows XP Professional x64 Edition Service Pack 2  
(2862330)  
(重要)  
Windows XP Professional x64 Edition Service Pack 2  
(2862335)  
(重要)  
Windows XP Professional x64 Edition Service Pack 2  
(2868038)  
(重要)  
Windows XP Professional x64 Edition Service Pack 2  
(2883150)  
(緊急)  
Windows XP Professional x64 Edition Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2864058)  
(緊急)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(警告)  
Internet Explorer 7  
(2879017)  
(警告)  
Internet Explorer 8  
(2879017)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2847311)  
(緊急)  
Windows Server 2003 Service Pack 2  
(2862330)  
(重要)  
Windows Server 2003 Service Pack 2  
(2862335)  
(重要)  
Windows Server 2003 Service Pack 2  
(2868038)  
(重要)  
Windows Server 2003 Service Pack 2  
(2883150)  
(緊急)  
Windows Server 2003 Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2864058)  
(深刻度なし)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(警告)  
Internet Explorer 7  
(2879017)  
(警告)  
Internet Explorer 8  
(2879017)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2847311)  
(緊急)  
Windows Server 2003 x64 Edition Service Pack 2  
(2862330)  
(重要)  
Windows Server 2003 x64 Edition Service Pack 2  
(2862335)  
(重要)  
Windows Server 2003 x64 Edition Service Pack 2  
(2868038)  
(重要)  
Windows Server 2003 x64 Edition Service Pack 2  
(2883150)  
(緊急)  
Windows Server 2003 x64 Edition Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2864058)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(警告)  
Internet Explorer 7  
(2879017)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2847311)  
(緊急)  
Windows Server 2003 with SP2 for Itanium-based Systems  
(2862330)  
(重要)  
Windows Server 2003 with SP2 for Itanium-based Systems  
(2862335)  
(重要)  
Windows Server 2003 with SP2 for Itanium-based Systems  
(2868038)  
(重要)  
Windows Server 2003 with SP2 for Itanium-based Systems  
(2883150)  
(緊急)  
Windows Server 2003 with SP2 for Itanium-based Systems  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(重要)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2864058)  
(緊急)
</td>
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(緊急)  
Internet Explorer 8  
(2879017)  
(緊急)  
Internet Explorer 9   
(2879017)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2847311)  
(緊急)  
Windows Vista Service Pack 2  
(2855844)  
(緊急)  
Windows Vista Service Pack 2  
(2862330)  
(重要)  
Windows Vista Service Pack 2  
(2862335)  
(重要)  
Windows Vista Service Pack 2  
(2864202)  
(重要)  
Windows Vista Service Pack 2  
(2868038)  
(重要)  
Windows Vista Service Pack 2  
(2876284)  
(重要)  
Windows Vista Service Pack 2  
(2883150)  
(緊急)  
Windows Vista Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(緊急)  
Microsoft .NET Framework 4.5  
(2861193)  
(緊急)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2864058)  
(深刻度なし)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(緊急)  
Internet Explorer 8  
(2879017)  
(緊急)  
Internet Explorer 9   
(2879017)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2847311)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(2855844)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(2862330)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(2862335)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(2864202)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(2868038)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(2876284)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(2883150)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(緊急)  
Microsoft .NET Framework 4.5  
(2861193)  
(緊急)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2864058)  
(緊急)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(警告)  
Internet Explorer 8  
(2879017)  
(警告)  
Internet Explorer 9   
(2879017)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2847311)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2855844)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2862330)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2862335)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2864202)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2868038)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2876284)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2883150)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(緊急)  
Microsoft .NET Framework 4.5  
(2861193)  
(緊急)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2864058)  
(深刻度なし)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(警告)  
Internet Explorer 8  
(2879017)  
(警告)  
Internet Explorer 9   
(2879017)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2847311)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(2855844)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(2862330)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(2862335)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(2864202)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(2868038)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(2876284)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(2883150)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4  
(2861188)  
(緊急)  
Microsoft .NET Framework 4.5  
(2861193)  
(緊急)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2864058)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2847311)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2862330)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2862335)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2864202)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2868038)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2876284)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2883150)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(重要)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2864058)  
(緊急)
</td>
</tr>
<tr>
<th colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(緊急)  
Internet Explorer 9   
(2879017)  
(緊急)  
Internet Explorer 10   
(2879017)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2847311)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(2855844)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(2862330)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(2862335)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(2864202)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(2868038)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(2876284)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(2883150)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2864058)  
(深刻度なし)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(緊急)  
Internet Explorer 9   
(2879017)  
(緊急)  
Internet Explorer 10   
(2879017)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2847311)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(2855844)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(2862330)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(2862335)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(2864202)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(2868038)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(2876284)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(2883150)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2864058)  
(緊急)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(警告)  
Internet Explorer 9   
(2879017)  
(警告)  
Internet Explorer 10   
(2879017)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2847311)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2855844)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2862330)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2862335)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2864202)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2868038)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2876284)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2883150)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2864058)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2847311)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2855844)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2862330)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2862335)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2864202)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2868038)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2876284)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2883150)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2864058)  
(緊急)
</td>
</tr>
<tr>
<th colspan="5">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2847311)  
(緊急)  
Windows 8 for 32-bit Systems  
(2862330)  
(重要)  
Windows 8 for 32-bit Systems  
(2862335)  
(重要)  
Windows 8 for 32-bit Systems  
(2863725)  
(重要)  
Windows 8 for 32-bit Systems  
(2864202)  
(重要)  
Windows 8 for 32-bit Systems  
(2868038)  
(重要)  
Windows 8 for 32-bit Systems  
(2883150)  
(緊急)  
Windows 8 for 32-bit Systems  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(緊急)  
Microsoft .NET Framework 3.5  
(2861704)  
(重要)  
Microsoft .NET Framework 3.5  
(2863243)  
(重要)  
Microsoft .NET Framework 4.5  
(2861702)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2864058)  
(深刻度なし)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems  
(2847311)  
(緊急)  
Windows 8 for 64-bit Systems  
(2862330)  
(重要)  
Windows 8 for 64-bit Systems  
(2862335)  
(重要)  
Windows 8 for 64-bit Systems  
(2863725)  
(重要)  
Windows 8 for 64-bit Systems  
(2864202)  
(重要)  
Windows 8 for 64-bit Systems  
(2868038)  
(重要)  
Windows 8 for 64-bit Systems  
(2883150)  
(緊急)  
Windows 8 for 64-bit Systems  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(緊急)  
Microsoft .NET Framework 3.5  
(2861704)  
(重要)  
Microsoft .NET Framework 3.5  
(2863243)  
(重要)  
Microsoft .NET Framework 4.5  
(2861702)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems  
(2864058)  
(緊急)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2847311)  
(緊急)  
Windows Server 2012  
(2862330)  
(重要)  
Windows Server 2012  
(2862335)  
(重要)  
Windows Server 2012  
(2863725)  
(重要)  
Windows Server 2012  
(2864202)  
(重要)  
Windows Server 2012  
(2868038)  
(重要)  
Windows Server 2012  
(2883150)  
(緊急)  
Windows Server 2012  
(2884256)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(緊急)  
Microsoft .NET Framework 3.5  
(2861704)  
(重要)  
Microsoft .NET Framework 3.5  
(2863243)  
(重要)  
Microsoft .NET Framework 4.5  
(2861702)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2864058)  
(緊急)
</td>
</tr>
<tr>
<th colspan="5">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows RT  
(2847311)  
(緊急)  
Windows RT  
(2862330)  
(重要)  
Windows RT  
(2862335)  
(重要)  
Windows RT  
(2863725)  
(重要)  
Windows RT  
(2864202)  
(重要)  
Windows RT  
(2868038)  
(重要)  
Windows RT  
(2883150)  
(緊急)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2861702)  
(重要)
</td>
<td style="border:1px solid black;">
Windows RT  
(2864058)  
(深刻度なし)
</td>
</tr>
<tr>
<th colspan="5">
Windows 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
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
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8.1 for 64-bit Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
</tr>
<tr>
<th colspan="5">
Windows Server 2012 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
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
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
(警告)
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
<th colspan="5">
Windows RT 8.1
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
</tr>
<tr>
<th colspan="5">
Server Core インストール オプション
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-080](https://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](https://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](https://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](https://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2847311)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2862330)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2862335)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2864202)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2876284)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2883150)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2864058)  
(深刻度なし)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2847311)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2862330)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2862335)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2864202)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2876284)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2883150)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2864058)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2847311)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2862330)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2862335)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2864202)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2876284)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2883150)  
(緊急)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(重要)  
Microsoft .NET Framework 4  
(2858302)  
(重要)  
Microsoft .NET Framework 4.5  
(2861208)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2864058)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2847311)  
(緊急)  
Windows Server 2012 (Server Core インストール)  
(2862330)  
(重要)  
Windows Server 2012 (Server Core インストール)  
(2862335)  
(重要)  
Windows Server 2012 (Server Core インストール)  
(2863725)  
(重要)  
Windows Server 2012 (Server Core インストール)  
(2864202)  
(重要)  
Windows Server 2012 (Server Core インストール)  
(2883150)  
(緊急)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861704)  
(重要)  
Microsoft .NET Framework 3.5  
(2863243)  
(重要)  
Microsoft .NET Framework 4.5  
(2861702)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2864058)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)
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
</table>
 
MS13-080 に関する注意

<sup>[1]</sup>Internet Explorer 11 の場合、お客様は Windows RT 8.1、Windows 8.1、および Windows Server 2012 R2 の更新プログラムのロールアップを適用する必要があります。2013 年 10 月 (2883200)。更新プログラム 2883200 のロールアップには、セキュリティ関連の変更とセキュリティ関連ではない変更が両方とも含まれていることに注意してください。詳細および利用可能なダウンロード リンクについては、[マイクロソフト サポート技術情報 2883200](https://support.microsoft.com/kb/2883200/ja) を参照してください。

#### Microsoft Office スイートおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-085](https://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](https://go.microsoft.com/fwlink/?linkid=324027)
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
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft Word 2003 Service Pack 3  
(2826020)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-085](https://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](https://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2827324)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(2760585)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(2760591)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2827330)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-085](https://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](https://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1 (32 ビット版)  
(2826033)  
(重要)  
Microsoft Office 2010 Service Pack 1 (32 ビット版)  
(2826023)  
(重要)  
Microsoft Office 2010 Service Pack 1 (32 ビット版)  
(2826035)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1 (64 ビット版)  
(2826033)  
(重要)  
Microsoft Office 2010 Service Pack 1 (64 ビット版)  
(2826023)  
(重要)  
Microsoft Office 2010 Service Pack 1 (64 ビット版)  
(2826035)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(2826033)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2826023)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2826035)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(2826033)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2826023)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2826035)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-085](https://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](https://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (32 ビット版)  
(2827238)  
(重要)  
Microsoft Office 2013 (32 ビット版)  
(2817623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (64 ビット版)  
(2827238)  
(重要)  
Microsoft Office 2013 (64 ビット版)  
(2817623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2827238)  
(重要)  
Microsoft Office 2013 RT  
(2817623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-085](https://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](https://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(2889496)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
その他の Microsoft Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-085](https://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](https://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2827326)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2827329)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2827328)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>
 

#### Microsoft サーバー ソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (wssloc) (32 ビット版)  
(2596741)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (wssloc) (64 ビット版)  
(2596741)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1 (wssloc)  
(2589365)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2 (wssloc)  
(2589365)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 (wacserver)  
(2827222)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 (pptserver)  
(2760561)  
(重要)
</td>
</tr>
</table>
 
MS13-084 に関する注意

「影響を受けるソフトウェア」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。 このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft Office Services および Web Apps

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)
</td>
<td style="border:1px solid black;">
Excel Services  
(2827327)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)
</td>
<td style="border:1px solid black;">
Excel Services  
(2827327)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Excel Services  
(2826029)  
(重要)  
Word Automation Services  
(2826022)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Excel Services  
(2826029)  
(重要)  
Word Automation Services  
(2826022)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Excel Services  
(2752002)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Word Automation Services  
(2826036)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office Web Apps 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 1  
(2826030)  
(重要)  
Microsoft Excel Web App 2010 Service Pack 1  
(2826028)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2  
(2826030)  
(重要)  
Microsoft Office Web Apps  
Microsoft Excel Web App 2010 Service Pack 2  
(2826028)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office Web Apps 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-084](https://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2827222)  
(重要)
</td>
</tr>
</table>
 
MS13-084 に関する注意

「影響を受けるソフトウェア」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。 このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft 開発者用ツールおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-087](https://go.microsoft.com/fwlink/?linkid=324590)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
Mac にインストールされている Microsoft Silverlight 5  
(2890788)  
(重要)  
Mac にインストールされている Microsoft Silverlight 5 Developer Runtime  
(2890788)  
(重要)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5  
(2890788)  
(重要)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5 Developer Runtime  
(2890788)  
(重要)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5  
(2890788)  
(重要)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5 Developer Runtime  
(2890788)  
(重要)
</td>
</tr>
</table>
 

検出および展開ツールとガイダンス
--------------------------------

<span></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

-   Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。
-   Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。
-   Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび確認を効率化する手助けをします。

利用可能なこれらのツールおよび他のツールについては、「[セキュリティ ツール](https://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199/ja): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](https://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](https://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](https://go.microsoft.com/fwlink/?linkid=21127)を表します。

MS13-080

-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3872) を報告してくださった [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3873) を報告してくださった Yenteasy - Security Research の Jose A. Vazquez 氏
-   [VeriSign iDefense Labs](https://labs.idefense.com/) に協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3874) を報告してくださった匿名のリサーチャー
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3874) を報告してくださった Amol Naik 氏
-   [VeriSign iDefense Labs](https://labs.idefense.com) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3875) を報告してくださった Yenteasy - Security Research の Jose A. Vazquez 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3882) を報告してくださった [Google Security Team](https://www.google.com/) の Ivan Fratric 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3882) を報告してくださった Yenteasy - Security Research の Jose A. Vazquez 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3885) を報告してくださった Yenteasy - Security Research の Jose A. Vazquez 氏
-   [VeriSign iDefense Labs](https://labs.idefense.com) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3886) を報告してくださった Yenteasy - Security Research の Jose A. Vazquez 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3893) について、マイクロソフトに協力してくださった [LAC Co.](https://www.lac.co.jp/) の Yoshihiro Ishikawa 氏
-   National Cyber Security Centre of the Netherlands と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3897) について、マイクロソフトに協力してくださった Hoodie22 氏

MS13-081

-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して OpenType フォントの解析の脆弱性 (CVE-2013-3128) を報告してくださった匿名のリサーチャー
-   Windows USB 記述子の脆弱性 (CVE-2013-3200) を報告してくださった [NCC Group](https://www.nccgroup.com/) の Andy Davis 氏
-   Windows USB 記述子の脆弱性 (CVE-2013-3200) を報告してくださった ANSSI の Lucas Bouillot 氏
-   Win32k NULL ページの脆弱性 (CVE-2013-3881) を報告してくださった [Endgame](https://www.endgame.com/) の Seth Gibson 氏、および Dan Zentner 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して TrueType フォントの CMAP テーブルの脆弱性 (CVE-2013-3895) を報告してくださった ZombiE 氏

MS13-082

-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して OpenType フォントの解析の脆弱性 (CVE-2013-3128) を報告してくださった匿名のリサーチャー
-   エンティティ拡張の脆弱性 (CVE-2013-3860) を報告してくださった [Context Information Security](https://www.contextis.com/) の James Forshaw 氏

MS13-083

-   Comctl32 の整数オーバーフローの脆弱性 (CVE-2013-3195) の問題を報告してくださった TCA, Institute of Software, Chinese Academy of Sciences の孙晓山氏

MS13-084

-   Microsoft Excel のメモリ破損の脆弱性 (CVE-2013-3889) を報告してくださった [Google Security Team](https://www.google.com/) の Mateusz Jurczyk 氏、Ivan Fratric 氏、および Ben Hawkes 氏
-   パラメーター インジェクションの脆弱性 (CVE-2013-3895) を報告してくださった Nutan Kumar Panda 氏
-   このセキュリティ情報に記載されている多層防御の変更についてマイクロソフトに協力してくださった[米国立衛生研究所](https://nih.gov/)の Ari Elias-Bachrach 氏と Angela Kelso 氏

MS13-085

-   Microsoft Excel のメモリ破損の脆弱性 (CVE-2013-3889) を報告してくださった [Google Security Team](https://www.google.com/) の Mateusz Jurczyk 氏、Ivan Fratric 氏、および Ben Hawkes 氏
-   Microsoft Excel のメモリ破損の脆弱性 (CVE-2013-3890) を報告してくださった [Google Security Team](https://www.google.com/) の Mateusz Jurczyk 氏、Ivan Fratric 氏、および Ben Hawkes 氏

MS13-086

-   メモリ破損の脆弱性 (CVE-2013-3891) を報告してくださった Yuhong Bao 氏
-   メモリ破損の脆弱性 (CVE-2013-3892) を報告してくださった [Google Security Team](https://www.google.com/) の Mateusz Jurczyk 氏、Ivan Fratric 氏、および Ben Hawkes 氏

MS13-087

-   Silverlight の脆弱性 (CVE-2013-3896) を報告してくださった Vitaliy Toropov 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](https://technet.microsoft.com/ja-jp/security/bb980617)
-   Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   国ごとのローカルサポート:[Microsoft サポート](https://support.microsoft.com/common/international.aspx)

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2013/10/09):このセキュリティ情報の概要ページを公開しました。
-   V1.2 (2013/11/07): MS13-084 について、Microsoft Office Web Apps Server 2013 (2827222) 更新プログラムの製品名を修正しました。

*Built at 2014-04-18T01:50:00Z-07:00*
