---
TOCTitle: 'MS11-JUL'
Title: 2011 年 7 月のセキュリティ情報
ms:assetid: 'ms11-jul'
ms:contentKeyID: 61229687
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms11-jul(v=Security.10)'
--- 

2011 年 7 月のセキュリティ情報
==============================

公開日: 2011年7月13日

**バージョン:** 1.0

[![](../../images/Dn627266.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627266.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2011 年 7 月公開のセキュリティ情報の一覧です。

2011 年 7 月のセキュリティ情報の公開により、2011 年 7 月 8 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/security/bulletin/advance)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2011 年 7 月 13 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2011 年 7 月 13 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[7 月のセキュリティ情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032487855&eventcategory=4)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](https://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms11-053">MS11-053</a></td>
<td style="border:1px solid black;"><strong>Bluetooth スタックの脆弱性により、リモートでコードが実行される (2566220)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Windows Bluetooth スタックの脆弱性を解決します。この脆弱性により、攻撃者が影響を受けるコンピューターに特別な細工を施した一連の Bluetooth パケットを送信した場合、リモートでコードが実行される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。この脆弱性の影響を受けるのは、Bluetooth 機能搭載のコンピューターだけです。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms11-054">MS11-054</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルモード ドライバーの脆弱性により、特権が昇格される (2555917)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 15 件の Microsoft Windows に存在する脆弱性を解決します。これらの中で最も深刻な脆弱性では、攻撃者がローカルでログオンし、特別に細工したアプリケーションを実行した場合、特権が昇格される可能性があります。これらの脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms11-056">MS11-056</a></td>
<td style="border:1px solid black;"><strong>Windows クライアント/サーバー ランタイム サブシステムの脆弱性により、特権が昇格される (2507938)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft Windows のクライアント/サーバー ランタイム サブシステム (CSRSS) に存在する 5 件の非公開で報告された脆弱性を解決します。これらの脆弱性により、攻撃者がユーザーのシステムにログオンし、特別な細工が施されたアプリケーションを実行した場合、特権が昇格される可能性があります。これらの脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms11-055">MS11-055</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio の脆弱性により、リモートでコードが実行される (2560847)</strong><br />
<br />
このセキュリティ更新プログラムは一般に公開された 1 件の Microsoft Visio の脆弱性を解決します。この脆弱性により、特別な細工が施されたライブラリ ファイルと同じネットワーク ディレクトリにある正当な Visio ファイルをユーザーが開いた場合に、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性のExploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。
  
| セキュリティ情報 ID                                                 | 脆弱性のタイトル                                         | CVE の識別番号                                                                   | 最新のソフトウェアのリリースに関するコード実行の Exploitability (悪用可能性) の評価             | 旧バージョンのソフトウェアのリリースに関するコード実行の Exploitability (悪用可能性) の評価     | サービス拒否の悪用可能性の評価 | 注意事項                                                                                                                         |  
|---------------------------------------------------------------------|----------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|--------------------------------|----------------------------------------------------------------------------------------------------------------------------------|  
| [MS11-053](https://technet.microsoft.com/security/bulletin/ms11-053) | Bluetooth スタックの脆弱性                               | [CVE-2011-1265](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1265) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | 永続的                         | この脆弱性は、Bluetooth 機能搭載のクライアント システム (サポートされるリリースの Windows Vista と Windows 7) にのみ影響します。 |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の解放後使用の脆弱性                              | [CVE-2011-1874](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1874) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の解放後使用の脆弱性                              | [CVE-2011-1875](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1875) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の解放後使用の脆弱性                              | [CVE-2011-1876](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1876) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の解放後使用の脆弱性                              | [CVE-2011-1877](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1877) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の解放後使用の脆弱性                              | [CVE-2011-1878](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1878) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の解放後使用の脆弱性                              | [CVE-2011-1879](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1879) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の NULL ポインター逆参照の脆弱性                  | [CVE-2011-1880](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1880) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の NULL ポインター逆参照の脆弱性                  | [CVE-2011-1881](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1881) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の解放後使用の脆弱性                              | [CVE-2011-1882](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1882) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の解放後使用の脆弱性                              | [CVE-2011-1883](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1883) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の解放後使用の脆弱性                              | [CVE-2011-1884](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1884) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の NULL ポインター逆参照の脆弱性                  | [CVE-2011-1885](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1885) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の不適切なパラメーターによる情報漏えいの脆弱性    | [CVE-2011-1886](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1886) | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | 永続的                         | これは情報漏えいの脆弱性です。                                                                                                   |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の NULL ポインター逆参照の脆弱性                  | [CVE-2011-1887](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1887) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-054](https://technet.microsoft.com/security/bulletin/ms11-054) | Win32k の NULL ポインター逆参照の脆弱性                  | [CVE-2011-1888](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1888) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-055](https://technet.microsoft.com/security/bulletin/ms11-055) | Microsoft Visio の安全でないライブラリのロードの脆弱性   | [CVE-2010-3148](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3148) | 影響なし                                                                                        | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 対象外                         | この脆弱性は一般に公開されていました。                                                                                           |  
| [MS11-056](https://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS ローカル EOP AllocConsole の脆弱性                 | [CVE-2011-1281](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1281) | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 対象外                         | (なし)                                                                                                                           |  
| [MS11-056](https://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS ローカル EOP SrvSetConsoleLocalEUDC の脆弱性       | [CVE-2011-1282](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1282) | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-056](https://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS ローカル EOP SrvSetConsoleNumberOfCommand の脆弱性 | [CVE-2011-1283](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1283) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-056](https://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS ローカル EOP SrvWriteConsoleOutput の脆弱性        | [CVE-2011-1284](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1284) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |  
| [MS11-056](https://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS ローカル EOP SrvWriteConsoleOutputString の脆弱性  | [CVE-2011-1870](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1870) | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 永続的                         | (なし)                                                                                                                           |
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
**これらの表はどのように使用しますか?**
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。
  
**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
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
</tr>
<tr>
<th colspan="4">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-053**](https://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](https://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](https://technet.microsoft.com/security/bulletin/ms11-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d7a47370-f415-46ea-9a82-a943f743c8b6)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=425c705e-94f2-4fa6-9df2-dc71897215fa)  
(重要)
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
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=db89d88f-d0d4-4ed6-8589-bf27557c0304)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c389fa20-677e-49b6-af44-781e5522d08b)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-053**](https://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](https://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](https://technet.microsoft.com/security/bulletin/ms11-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7a26a437-a705-4d48-8389-50f159a39891)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=dff4c67a-8c8b-4d7d-84c7-57429becf0ff)  
(重要)
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
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=95393f89-0b05-4243-95ed-17bcdad24bfb)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1615a995-9a04-440a-ae52-5917738f0ecb)  
(重要)
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
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=3b094bdb-4150-44f2-a638-afd5f41b00a3)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a81c011d-eeea-4383-9efb-df70515ab357)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-053**](https://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](https://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](https://technet.microsoft.com/security/bulletin/ms11-056)
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
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6bff74ac-45f3-4585-92da-316921b458fa) <sup>[1]</sup>
(KB2561109)  
(緊急)  
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a1e5aa7d-5f38-4ce2-9575-4b4cb7520160)  
(KB2532531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c1fe1e53-34d5-497e-8ba2-50caa8dc1158)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a5e192af-dae5-47ef-a9d0-f761a8caa974)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=849d2694-c8b3-4670-8203-912661bccabf) <sup>[1]</sup>
(KB2561109)  
(緊急)  
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4287eeb4-ab29-4727-83f2-260d838b44d4)  
(KB2532531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7bc0a285-cc32-4c6b-abee-d92130d459b7)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1007f5d3-9be1-4f03-a3f0-12ddb555653c)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-053**](https://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](https://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](https://technet.microsoft.com/security/bulletin/ms11-056)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b88d0471-4427-4835-9446-db71116481f0)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=36e3dbaf-36f5-4c74-8f11-ecbef46f58e1)\*  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d3df6184-3e3c-4949-a1ee-293ec68f8149)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b43d2ab5-e281-4c6b-bb37-1f1b5d86ac82)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9e021d69-7f0c-457f-af86-07e760d8f421)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b70209f2-1c51-45af-b3c4-3473aebcdb35)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-053**](https://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](https://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](https://technet.microsoft.com/security/bulletin/ms11-056)
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
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7f811b75-c3ff-411a-aaa9-126dce34cc01)  
(KB2532531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=41db1b2f-f862-43bb-89bc-4b97737e5cb9)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ac3b435c-8caf-40cc-8f13-b52261b3b9e6)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=90b2da71-18f9-46ee-9e3d-b08620ca06aa)  
(KB2532531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=211abdc6-40c7-4bfc-8c2d-be72981f311e)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=64e5f889-fa46-4884-9b22-3ba4e2fba1b9)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-053**](https://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](https://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](https://technet.microsoft.com/security/bulletin/ms11-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4f54e498-3825-407d-a036-1900a65d34f1)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b99a40cf-8a31-43d9-bd0b-a458a533068b)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e7ae39e8-1154-4a13-8598-29d4a6358762)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=784efc20-3a41-42ab-b48d-51fd59d71523)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**Note for Windows Server 2008 および Windows Server 2008 R2**

**\*Server Core インストールは影響を受けます。**サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、[Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

**MS11-053 に関する注意**

<sup>[1]</sup>Windows Vista Service Pack 1 が影響を受けるのは、オプションの Windows Vista Feature Pack for Wireless がインストールされている場合だけです。

#### Microsoft Office スイートおよびソフトウェア

 
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
Microsoft Office スイートおよびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-055**](https://technet.microsoft.com/security/bulletin/ms11-055)
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
Microsoft Visio 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1c7b2a5b-4aa6-4006-90bf-89f8b2b7becd)  
(KB2493523)  
(重要)
</td>
</tr>
</table>

<p></p>

 

検出および適用ツールとガイダンス
--------------------------------

 
**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](https://technet.microsoft.com/ja-jp/updatemanagement/bb245732)を参照してください。[セキュリティ TechCenter](https://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](https://www.microsoft.com/ja-jp/security/default.aspx)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&amp;freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&amp;displaylang=ja)からもダウンロードすることができます。「security\_patch」 のキーワード探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](https://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](https://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (例えば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](https://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

**検出および適用のガイダンス**

マイクロソフトは、セキュリティ更新プログラムの検出および適用に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および適用のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](https://support.microsoft.com/kb/961747) を参照してください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピュータやリモートコンピュータの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)を参照してください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](https://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) の Web サイトを参照してください。

**System?Center Configuration Manager 2007**

Configuration Manager 2007 のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。Configuration Manager 2007 で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

Configuration Manager 2007 の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。Configuration Manager 2007 のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。管理者が Configuration Manager 2007 を使用して更新プログラムを展開する方法の詳細については、[ソフトウェアの更新管理](https://www.microsoft.com/japan/systemcenter/configmgr/products/updatemgmt.mspx)を参照してください。Configuration Manager の詳細については、[System Center Configuration Manager](https://www.microsoft.com/japan/systemcenter/configmgr/default.mspx) を参照してください。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

**注**: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](https://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager 2007 については、前のセクション「System?Center Configuration Manager 2007」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](https://www.microsoft.com/downloads/en/details.aspx?displaylang=ja&familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](https://technet.microsoft.com/ja-jp/systemcenter/bb545936.aspx) を参照してください。

**注**: SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](https://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/ja-jp/details.aspx?displaylang=ja&familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja-nec) で入手可能) を使用して、これらの更新プログラムをインストールできます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [サポート技術情報 894199](https://support.microsoft.com/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について (2011 年) すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](https://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の戦略**

[Security Guidance for Update Management](https://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&amp;freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&amp;displaylang=ja)からもダウンロードできます。「security\_patch」 のキーワード探索によって容易に見つけることができます。
-   コンシューマ プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086) を参照してください。

**IT Pro Security Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://technet.microsoft.com/ja-jp/security/cc136632.aspx)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](https://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS11-054 で説明している 14 件の問題を報告してくださった [Norman](https://www.norman.com) の Tarjei Mandt 氏
-   MS11-054 で説明している問題を報告してくださった[北京大学ソフトウェアおよびマイクロエレクトロニクス学院](https://www.ss.pku.edu.cn/en/)の Liang Yin 氏、Sihan Qing 教授、Weiping Wen 教授、および Husheng Zhou 氏
-   MS11-056 で説明している問題を報告してくださった [Hispasec](https://www.hispasec.com/)[Virustotal](https://www.virustotal.com/) の Matthew 'j00ru' Jurczyk 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](https://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償でサポートをご提供いたします。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](https://support.microsoft.com/)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](https://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社 及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。（Microsoft Corporation、その関連会社 またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行ないません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません (Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます)。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴:

-   V1.0 (2011/07/13): このセキュリティ情報の概要ページを公開しました。

*Built at 2014-04-18T01:50:00Z-07:00*
