---
TOCTitle: 'MS14-AUG'
Title: 2014 年 8 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms14-aug'
ms:contentKeyID: 62755567
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms14-aug(v=Security.10)'
---

2014 年 8 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日:2014 年 8 月 13 日 | 最終更新日:2014 年 12 月 22 日

**バージョン:** 2.1

このセキュリティ情報の概要は 2014 年 8 月公開のセキュリティ情報の一覧です。

2014 年 8 月のセキュリティ情報の公開により、2014 年 8 月 8 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2014 年 8 月 13 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。月例 Webcast の表示、およびその他のセキュリティ情報 Webcast へのリンクについては、[Microsoft Security Bulletin Webcast (英語情報)](https://technet.microsoft.com/security/dn756352) を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェア」を参照してください。

 
<p> </p>  <table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (2976627)<br />
<br />
</strong>このセキュリティ更新プログラムは、Internet Explorer に存在する 1 件の一般に公開された脆弱性および 25 件の非公開で報告された脆弱性を解決します。これらの中で最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507337">MS14-043</a></td>
<td style="border:1px solid black;"><strong>Windows Media Center の脆弱性により、リモートでコードが実行される (2978742)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、Windows Media Center リソースを呼び出す特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=402461">MS14-048</a></td>
<td style="border:1px solid black;"><strong>OneNote の脆弱性により、リモートでコードが実行される (2977201)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft OneNote に存在する 1 件の脆弱性を解決します。影響を受けるバージョンの Microsoft OneNote で特別に細工されたファイルを開くと、脆弱性によってリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507036">MS14-044</a></td>
<td style="border:1px solid black;"><strong>SQL Server の脆弱性により、特権が昇格される (2984340)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft SQL Server に存在する脆弱性を解決します (1 件は SQL Server マスター データ サービスに存在し、もう 1 件は SQL Server リレーショナル データベース管理システムに存在します)。SQL Server マスター データ サービスに影響を及ぼす脆弱性がより深刻であり、ユーザーの Internet Explorer のインスタンスにクライアント側スクリプトを挿入する特別に細工された Web サイトにユーザーがアクセスした場合に、特権の昇格が発生する可能性があります。しかしどのような場合でも、攻撃者は、攻撃者自身が制御するコンテンツをユーザーに強制的に閲覧させることはできません。その代わり、ユーザーに操作を行わせることが攻撃者にとっての必要条件となります。一般的には、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージのリンクをクリックさせ、攻撃者の Web サイトへユーザーを誘導します。または、電子メールで送信した添付ファイルを開かせようとします。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></td>
<td style="border:1px solid black;"><strong>カーネルモード ドライバーの脆弱性により、特権が昇格される (2984615)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 3 件の<strong></strong>Microsoft Windows に存在する脆弱性を解決します。最も深刻な脆弱性では、攻撃者がコンピューターにログオンし、特別に細工したアプリケーションを実行した場合、特権が昇格される可能性があります。これらの脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=396822">MS14-049</a></td>
<td style="border:1px solid black;"><strong>Windows Installer サービスの脆弱性により、特権が昇格される (2962490)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、以前にインストールされたアプリケーションの修復を試みる特別に細工されたアプリケーションを攻撃者が実行した場合、特権の昇格が起こる可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=402463">MS14-050</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Server の脆弱性により、特権が昇格される (2977202)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft SharePoint Server の脆弱性を解決します。認証された攻撃者がこの脆弱性を悪用した場合、特別に細工したアプリを使用して、現在の SharePoint サイト上のユーザーのコンテキストで任意の JavaScript を実行する可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507038">MS14-046</a></td>
<td style="border:1px solid black;"><strong>.NET Framework の脆弱性により、セキュリティ機能のバイパスが起こる (2984625)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft .NET Framework の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された Web サイトにアクセスした場合に、セキュリティ機能のバイパスが起こる可能性があります。Web 閲覧攻撃シナリオでは、この脆弱性を悪用することに成功した攻撃者は、広い範囲の脆弱性からユーザーを保護する Address Space Layout Randomization (ASLR) セキュリティ機能をバイパスする可能性があります。セキュリティ機能のバイパス自体では、任意のコードが実行されることはありません。しかし、攻撃者はこの ASLR バイパスの脆弱性を、リモートでコードが実行される脆弱性など別の脆弱性と組み合わせて使用し、ASLR バイパスを利用することで、任意のコードを実行する可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507336">MS14-047</a></td>
<td style="border:1px solid black;"><strong>LRPC の脆弱性により、セキュリティ機能のバイパスが起こる (2978668)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。攻撃者がこの脆弱性を、ASLR バイパスを利用して任意のコードを実行する別の脆弱性 (リモートでコードが実行される脆弱性など) と組み合わせて使用した場合、この脆弱性によりセキュリティ機能のバイパスが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。
  
<p> </p>  <table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507337">MS14-043</a></td>
<td style="border:1px solid black;">CSyncBasePlayer の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4060">CVE-2014-4060</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507036">MS14-044</a></td>
<td style="border:1px solid black;">SQL マスター データ サービス XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1820">CVE-2014-1820</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507036">MS14-044</a></td>
<td style="border:1px solid black;">Microsoft SQL Server スタック オーバーランの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4061">CVE-2014-4061</a></td>
<td style="border:1px solid black;">3 - 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3 - 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></td>
<td style="border:1px solid black;">Win32k の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0318">CVE-2014-0318</a></td>
<td style="border:1px solid black;">3 - 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3 - 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></td>
<td style="border:1px solid black;">フォント ダブルフェッチの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1819">CVE-2014-1819</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></td>
<td style="border:1px solid black;">Windows カーネル プール割り当ての脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4064">CVE-2014-4064</a></td>
<td style="border:1px solid black;">3 - 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3 - 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507038">MS14-046</a></td>
<td style="border:1px solid black;">.NET ASLR の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4062">CVE-2014-4062</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。<br />
<br />
マイクロソフトは、このセキュリティ情報が最初に公開された際に、この脆弱性が一般で悪用され、お客様が攻撃されていたことを示す情報を受けていませんでした。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507336">MS14-047</a></td>
<td style="border:1px solid black;">LRPC ASLR バイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0316">CVE-2014-0316</a></td>
<td style="border:1px solid black;">3 - 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3 - 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。<br />
<br />
マイクロソフトは、このセキュリティ情報が最初に公開された際に、この脆弱性が一般で悪用され、お客様が攻撃されていたことを示す情報を受けていませんでした。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=402461">MS14-048</a></td>
<td style="border:1px solid black;">OneNote のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2815">CVE-2014-2815</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=396822">MS14-049</a></td>
<td style="border:1px solid black;">Windows Installer の修復の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1814">CVE-2014-1814</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=402463">MS14-050</a></td>
<td style="border:1px solid black;">SharePoint ページ コンテンツの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2816">CVE-2014-2816</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2774">CVE-2014-2774</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2784">CVE-2014-2784</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2796">CVE-2014-2796</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2808">CVE-2014-2808</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2810">CVE-2014-2810</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2811">CVE-2014-2811</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2817">CVE-2014-2817</a></td>
<td style="border:1px solid black;">0 - 悪用の事実を確認済み</td>
<td style="border:1px solid black;">0 - 悪用の事実を確認済み</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">マイクロソフトはこの脆弱性を悪用しようとする限定的な攻撃を確認しました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2818">CVE-2014-2818</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2819">CVE-2014-2819</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2820">CVE-2014-2820</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2821">CVE-2014-2821</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2822">CVE-2014-2822</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2823">CVE-2014-2823</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2824">CVE-2014-2824</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2825">CVE-2014-2825</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2826">CVE-2014-2826</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2827">CVE-2014-2827</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4050">CVE-2014-4050</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4051">CVE-2014-4051</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4052">CVE-2014-4052</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4055">CVE-2014-4055</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4056">CVE-2014-4056</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4057">CVE-2014-4057</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4058">CVE-2014-4058</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4063">CVE-2014-4063</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4067">CVE-2014-4067</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4145">CVE-2014-4145</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6354">CVE-2014-6354</a></td>
<td style="border:1px solid black;">1 - 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">なし</td>
</tr>
</tbody>
</table>
  
影響を受けるソフトウェア  
------------------------
  
<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
**これらの表はどのように使用しますか?**
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。
  
**Windows オペレーティング システムおよびコンポーネント**

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<th colspan="7">
Windows Server 2003
  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
(警告)  
Internet Explorer 7  
(2976627)  
(警告)  
Internet Explorer 8  
(2976627)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2993651)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2918614)  
(重要)

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
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
(警告)  
Internet Explorer 7  
(2976627)  
(警告)  
Internet Explorer 8  
(2976627)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2993651)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2918614)  
(重要)

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
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
(警告)  
Internet Explorer 7  
(2976627)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2993651)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
Internet Explorer 7  
(2976627)  
(緊急)  
Internet Explorer 8  
(2976627)  
(緊急)  
Internet Explorer 9  
(2976627)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2993651)  
(重要)  
Windows Vista Service Pack 2  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
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
Internet Explorer 7  
(2976627)  
(緊急)  
Internet Explorer 8  
(2976627)  
(緊急)  
Internet Explorer 9  
(2976627)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2993651)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
Internet Explorer 7  
(2976627)  
(警告)  
Internet Explorer 8  
(2976627)  
(警告)  
Internet Explorer 9  
(2976627)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2993651)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
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
Internet Explorer 7  
(2976627)  
(警告)  
Internet Explorer 8  
(2976627)  
(警告)  
Internet Explorer 9  
(2976627)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2993651)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
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
Internet Explorer 7  
(2976627)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2993651)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(緊急)  
Internet Explorer 9  
(2976627)  
(緊急)  
Internet Explorer 10  
(2976627)  
(緊急)  
Internet Explorer 11  
(2976627)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(Starter および Home Basic エディションを除くすべてのエディション)  
(2978742)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2993651)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(緊急)  
Internet Explorer 9  
(2976627)  
(緊急)  
Internet Explorer 10  
(2976627)  
(緊急)  
Internet Explorer 11  
(2976627)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(Starter および Home Basic エディションを除くすべてのエディション)  
(2978742)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2993651)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2978668)  
(重要)

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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(警告)  
Internet Explorer 9  
(2976627)  
(警告)  
Internet Explorer 10  
(2976627)  
(警告)  
Internet Explorer 11  
(2976627)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2993651)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2993651)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems (Professional エディションのみ) 上にインストールされている Windows Media Center  
(2978742)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2993651)  
(重要)  
Windows 8 for 32-bit Systems  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(重要)  
Microsoft .NET Framework 3.5  
(2966827)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems (Professional エディションのみ) 上にインストールされている Windows Media Center  
(2978742)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2993651)  
(重要)  
Windows 8 for x64-based Systems  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(重要)  
Microsoft .NET Framework 3.5  
(2966827)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems (Professional エディションのみ) 上にインストールされている Windows Media Center  
(2978742)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2993651)  
(重要)  
Windows 8.1 for 32-bit Systems  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(重要)  
Microsoft .NET Framework 3.5  
(2966828)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems (Professional エディションのみ) 上にインストールされている Windows Media Center  
(2978742)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2993651)  
(重要)  
Windows 8.1 for x64-based Systems  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(重要)  
Microsoft .NET Framework 3.5  
(2966828)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2978668)  
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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
(2976627)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2993651)  
(重要)  
Windows Server 2012  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(重要)  
Microsoft .NET Framework 3.5  
(2966827)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2993651)  
(重要)  
Windows Server 2012 R2  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(重要)  
Microsoft .NET Framework 3.5  
(2966828)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT  
(2993651)  
(重要)  
Windows RT  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2993651)  
(重要)  
Windows RT 8.1  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2978668)  
(重要)

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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2993651)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2918614)  
(重要)

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
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2993651)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2918614)  
(重要)

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
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2993651)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2978668)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2993651)  
(重要)  
Windows Server 2012 (Server Core インストール)  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(重要)  
Microsoft .NET Framework 3.5  
(2966827)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2978668)  
(重要)

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
Windows Server 2012 R2 (Server Core インストール)  
(2993651)  
(重要)  
Windows Server 2012 R2 (Server Core インストール)  
(2976897)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(2918614)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(重要)  
Microsoft .NET Framework 3.5  
(2966828)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(2978668)  
(重要)

</td>
</tr>
</table>
 
**MS14-043 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

**Microsoft Office ソフトウェア**

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<th colspan="2">
**Microsoft Office ソフトウェア**

</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-048**](https://go.microsoft.com/fwlink/?linkid=402461)

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
Microsoft OneNote 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft OneNote 2007 Service Pack 3  
(2596857)  
(重要)

</td>
</tr>
</table>
 
 

**Microsoft SQL Server**

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-044**](https://go.microsoft.com/fwlink/?linkid=507036)

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
Microsoft SQL Server 2008 for 32-bit Systems Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 for 32-bit Systems Service Pack 3  
(GDR)  
(2977321)  
(重要)  
Microsoft SQL Server 2008 for 32-bit Systems Service Pack 3  
(QFE)  
(2977322)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 for x64-based Systems Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 for x64-based Systems Service Pack 3  
(GDR)  
(2977321)  
(重要)  
Microsoft SQL Server 2008 for x64-based Systems Service Pack 3  
(QFE)  
(2977322)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 for Itanium-based Systems Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 for Itanium-based Systems Service Pack 3  
(GDR)  
(2977321)  
(重要)  
Microsoft SQL Server 2008 for Itanium-based Systems Service Pack 3  
(QFE)  
(2977322)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008 R2**

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
Microsoft SQL Server 2008 R2 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for 32-bit Systems Service Pack 2  
(GDR)  
2977320)  
(重要)  
Microsoft SQL Server 2008 R2 for 32-bit Systems Service Pack 2  
(QFE)  
(2977319)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for x64-based Systems Service Pack 2  
(GDR)  
(2977320)  
(重要)  
Microsoft SQL Server 2008 R2 for x64-based Systems Service Pack 2  
(QFE)  
(2977319)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for Itanium-based Systems Service Pack 2  
(GDR)  
(2977320)  
(重要)  
Microsoft SQL Server 2008 R2 for Itanium-based Systems Service Pack 2  
(QFE)  
(2977319)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012**

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
Microsoft SQL Server 2012 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 for 32-bit Systems Service Pack 1  
(GDR)  
(2977326)  
(重要)  
Microsoft SQL Server 2012 for 32-bit Systems Service Pack 1  
(QFE)  
(2977325)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 for x64-based Systems Service Pack 1  
(GDR)  
(2977326)  
(重要)  
Microsoft SQL Server 2012 for x64-based Systems Service Pack 1  
(QFE)  
(2977325)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2014**

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
Microsoft SQL Server 2014 for x64-based Systems

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2014 for x64-based Systems  
(GDR)  
(2977315)  
(重要)  
Microsoft SQL Server 2014 for x64-based Systems  
(QFE)  
(2977316)  
(重要)

</td>
</tr>
</table>
 
 

**Microsoft サーバー ソフトウェア**

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-050**](https://go.microsoft.com/fwlink/?linkid=402463)

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
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013  
(2880994)  
(重要)  
Microsoft SharePoint Foundation 2013  
(2880994)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(2880994)  
(重要)  
Microsoft SharePoint Foundation 2013 Service Pack 1  
(2880994)  
(重要)

</td>
</tr>
</table>
 
 

**その他のソフトウェア**

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Media Center TV Pack for Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

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
Windows Media Center TV Pack for Windows Vista (32 ビット版)

</td>
<td style="border:1px solid black;">
Windows Media Center TV Pack for Windows Vista (32 ビット版)  
(2978742)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Center TV Pack for Windows Vista (64 ビット版)

</td>
<td style="border:1px solid black;">
Windows Media Center TV Pack for Windows Vista (64 ビット版)  
(2978742)  
(緊急)

</td>
</tr>
</table>
 
**MS14-043 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび確認を効率化する手助けをします。

利用可能なこれらのツールおよび他のツールについては、「[セキュリティ ツール](https://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。 

謝辞
----

<span id="sectionToggle4"></span>
この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](https://go.microsoft.com/fwlink/?linkid=21127)を表します。

**MS14-043**

-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して、CSyncBasePlayer の解放後使用の脆弱性 (CVE-2014-4060) を報告してくださった Alisa Esage (@alisaesage) 氏

**MS14-045**

-   フォント ダブルフェッチの脆弱性 (CVE-2014-1819) を報告してくださった [Qihoo 360](https://www.360.cn/) の Wang Yu 氏
-   Windows カーネル プール割り当ての脆弱性 (CVE-2014-4064) を報告してくださった Ilja Van Sprundel 氏

**MS14-047**

-   LRPC ASLR のバイパスの脆弱性 (CVE-2014-0316) を報告してくださった [Alex Ionescu 氏](https://www.alex-ionescu.com/)

**MS14-048**

-   Beyond Security の [SecuriTeam Secure Disclosure](https://www.beyondsecurity.com/ssd.html) プログラムに協力して、OneNote のリモートでコードが実行される脆弱性 (CVE-2014-2815) を報告してくださった Eduardo Prado 氏

**MS14-049**

-   Windows Installer の修復の脆弱性 (CVE-2012-4784) を報告してくださった、[Entisys](https://www.entisys.com/) の Denis Gundarev 氏
-   このセキュリティ情報に組み込まれている多層防御についてマイクロソフトに協力してくださった [Stepfan Kanthak 氏](https://home.arcor.de/skanthak/safer.html)

**MS14-051**

-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2774) を報告してくださった、[HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) の AbdulAziz Hariri 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2784) を報告してくださった、[Qihoo 360](https://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2796) を報告してくださった、[Palo Alto Networks](https://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2808) を報告してくださった、[NSFOCUS Security Team](https://www.nsfocus.com/) の [Chen Zhang (demi6od) 氏](https://github.com/demi6od)
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2810) を報告してくださった、[NSFOCUS Security Team](https://www.nsfocus.com/) の [Chen Zhang (demi6od) 氏](https://github.com/demi6od)
-   [VeriSign iDefense Labs](https://labs.idefense.com/) と協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2811) を報告してくださった IronRock 氏
-   Internet Explorer の特権の昇格の脆弱性 (CVE-2014-2817) を報告してくださった、[Context Information Security](https://www.contextis.com/) の James Forshaw 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2818) を報告してくださった、[HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) の AbdulAziz Hariri 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer の特権の昇格の脆弱性 (CVE-2014-2819) を報告してくださった、[Team509](https://team509.com/) の Zeguang Zhao 氏と [KeenTeam](https://www.k33nteam.org/) (@K33nTeam) の Liang Chen 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2820) を報告してくださった Arthur Gerkis 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2821) を報告してくださった、[Palo Alto Networks](https://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2822) を報告してくださった、[Palo Alto Networks](https://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2823) を報告してくださった、[NSFOCUS Security Team](https://www.nsfocus.com/) の [Chen Zhang (demi6od) 氏](https://github.com/demi6od)
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2824) を報告してくださった、[Qihoo 360](https://www.360.cn/) の Yuki Chen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2825) を報告してくださった、[NSFOCUS Security Team](https://www.nsfocus.com/) の [Chen Zhang (demi6od) 氏](https://github.com/demi6od)
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2826) を報告してくださった、[NSFOCUS Security Team](https://www.nsfocus.com/) の [Chen Zhang (demi6od) 氏](https://github.com/demi6od)
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2827) を報告してくださった [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) の Simon Zuckerbraun 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4050) を報告してくださった [Omair 氏](https://krash.in/)
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4051) を報告してくださった、[Corelan](https://www.corelangcv.com/) の Peter 'corelanc0d3r' Van Eeckhoutte 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4052) を報告してくださった匿名のリサーチャー
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4055) を報告してくださった [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) の Simon Zuckerbraun 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4056) を報告してくださった、[Corelan](https://www.corelangcv.com/) の Peter 'corelanc0d3r' Van Eeckhoutte 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4057) を報告してくださった [Trend Micro](https://www.trendmicro.com/) の Yuki Chen 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4058) を報告してくださった Sky 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4063) を報告してくださった匿名のリサーチャー
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4067) を報告してくださった、[VulnHunt](https://www.vulnhunt.com/) の Wei Wang 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4067) を報告してくださった [lokihardt@ASRT 氏](https://technet.microsoft.com/ja-JP/mailto:lokihardt@asrt)
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4145) を報告してくださった Omair 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-6354) を報告してくださった Omair 氏

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199/ja):Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](https://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](https://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

**IT Pro Security Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](https://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](https://support.microsoft.com/contactus/cu_sc_virsec_master)

国ごとのローカルサポート:[Microsoft サポート](https://support.microsoft.com/common/international.aspx)

### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2014/08/13):このセキュリティ情報の概要ページを公開しました。
-   V2.0 (2014/08/28):このセキュリティ情報ページを更新し、MS14-045 について、サポートされているすべてのリリースの Microsoft Windows 用の更新プログラム 2982791 を、更新プログラム 2993651 に置き換えたことをお知らせしました。詳細については、セキュリティ情報を参照してください。
-   V2.1 (2014/10/09):MS14-051 について、Exploitability Index (悪用可能性指標) に CVE-2014-4145 の Exploitability (悪用可能性) を追加しました。今回の更新は情報のみの変更です。
-   V2.2 (2014/12/22):MS14-051 について、Exploitability Index (悪用可能性指標) に CVE-2014-6354 の Exploitability (悪用可能性) を追加しました。今回の更新は情報のみの変更です。

*Page generated 2014-12-19 12:08Z-08:00.*
