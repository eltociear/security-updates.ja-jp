---
TOCTitle: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 D ‐ ユーザー アカウントとグループ アカウント'
Title: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 D ‐ ユーザー アカウントとグループ アカウント'
ms:assetid: '50b1a83f-d25a-4ffe-b601-3adc677fa632'
ms:contentKeyID: 19869613
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277461(v=TechNet.10)'
---

Microsoft Windows 2000 セキュリティ構成ガイド
=============================================

### 付録 D ‐ ユーザー アカウントとグループ アカウント

最終更新日: 2003年2月18日

<table style="width:100%;">
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
<th><p>Windows 2000 にあらかじめ組み込まれているユーザーとグループ</p></th>
<th><p>説明</p></th>
<th><p>スタンドアロンの Professional</p></th>
<th><p>スタンドアロンの Server</p></th>
<th><p>ドメイン コントローラ</p></th>
<th><p>既定のメンバ</p></th>
<th><p>適用されるセキュリティ ターゲットの要件 および/または 変更の理由</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>ローカル ユーザー アカウント</strong></p></td>
<td style="border:1px solid black;"><p><strong>既定のローカル ユーザー アカウント</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Administrator</p></td>
<td style="border:1px solid black;"><p>コンピュータ/ドメインを管理するためにあらかじめ組み込まれているアカウント</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>2 人以上の管理者がこのアカウントを使用することは、FAU_GEN.2 利用者識別情報の関連付けに違反する可能性があります。このユーザー識別アソシエーションには、監査可能な各イベントはイベントを引き起こしたユーザーの識別情報と関連づけられなければならない、と記述されています。</p>
<p><strong>要件:</strong></p>
<p>権限を与えられた管理者のユーザー アカウントを管理者の責任のレベルに見合った管理グループに含めることにより、管理者に役割を割り当てます。それにより、すべての管理措置を監査ログ内で追跡して、特定のユーザー アカウントに辿り着けることが保証されます。Administrator アカウントの名前を変更して、非常時にのみ使用するようにパスワードの安全を図ります。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Guest</p></td>
<td style="border:1px solid black;"><p>コンピュータ/ドメインへのゲスト アクセスのためにあらかじめ組み込まれているアカウント</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>このアカウントを誤って使用すると、FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前の利用者識別 に違反する可能性があります。</p>
<p>既定ではこのアカウントはすべてのシステムにおいて無効にされています。</p>
<p><strong>要件:</strong></p>
<p>このアカウントは無効のままにしておかなければなりません。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>TsInternetUser</p></td>
<td style="border:1px solid black;"><p>ターミナル サービスによって使用されるユーザー アカウントです。このアカウントはターミナル サービスのインターネット コネクタ ライセンスによって使用されます。インターネット コネクタ ライセンスが有効にされると、Windows 2000 ベースのサーバーは匿名の接続のみを 200 件受け付けます。ターミナル サービスのクライアントにログオン ダイアログ ボックスは提示されません。ターミナル サービスのクライアントは TsInternetUser アカウントを用いて自動的にログオンされます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>2 人以上のユーザーがこのアカウントを使用することは、FAU_GEN.2 利用者識別情報の関連付けに違反する可能性があります。</p>
<p><strong>要件:</strong></p>
<p>ターミナル サービスは TOE の目的ではありません。匿名アクセスをサポートするアカウントを許可すべきではありません。したがって、このアカウントを無効にします。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>krbtgt</p></td>
<td style="border:1px solid black;"><p>キー配布センター サービス アカウント。Windows 2000 の Kerberos 認証はチケットを使用して行われます。このチケットは対称キーを使用して暗号化されます。対称キーは要求されたアクセス先のサーバーまたはサービスのパスワードから導出されます。そのようなセッション チケットを要求するために、チケット許可チケット (TGT) という特殊なチケットを Kerberos サービス自体に提示しなければなりません。TGT は krbtgt アカウントのパスワードから導出されたキーを用いて暗号化されます。このキーを知っているのは Kerberos サービスだけです。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>2 人以上のユーザーがこのアカウントを使用することは、FAU_GEN.2 利用者識別情報の関連付けに違反する可能性があります。</p>
<p>既定ではこのアカウントはドメイン コントローラ上で無効にされています。</p>
<p><strong>要件:</strong></p>
<p>他のユーザー アカウントとは異なり、krbtgt アカウントはドメインにログオンするために使用することはできず、実際に有効にすることはできません。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>グローバル グループ</p></td>
<td style="border:1px solid black;"><p>ドメインが作成されたときに、Windows 2000 は Active Directory ストア内に、以下のグローバル グループをあらかじめ作成します。このグローバル グループを使用して、ドメイン全体で、共通なタイプのユーザー アカウントをグループ化します。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>グローバル グループを使用することにより、権限を与えられた管理者の役割および権限を与えられたユーザーの役割にユーザーを割り当てることができます。それらの役割には、ユーザーが割り当てられた先のグローバル グループに基づいて、ドメインレベルの固有のアクセス制限が課されています。グローバル グループは TOE セキュリティ機能要件 の FMT_SMR.1 セキュリティ役割をサポートします。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Cert Publishers</p></td>
<td style="border:1px solid black;"><p>エンタプライズの証明書発行と書き換えエージェントです。エンタプライズ証明機関を稼働させているすべてのコンピュータを含みます。Cert Publishers は Active Directory 内のユーザー オブジェクトに関する証明書を発行する権限を与えられています。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p>評価された構成には Windows 2000 Cert Server は含まれていません。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>DnsUpdateProxy</p></td>
<td style="border:1px solid black;"><p>他のクライアント (たとえば DHCP サーバー) の代りに動的な更新を行うことを許可された DNS クライアントです。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p>TOE は FQDN をサポートするので、このグループのメンバになる必要はありません。</p>
<p><strong>要件:</strong></p>
<p>このグループにアカウントを追加してはいけません。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Domain Admins</p></td>
<td style="border:1px solid black;"><p>このグループはドメイン コントローラの役割を果たしている Windows 2000 のサーバー上でのみ利用することができます。このメンバはドメイン全体を管理する特権を与えられます。既定では、ドメイン コントローラ上のローカル Administrator アカウントがこのグループのメンバになっています。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>Administrator</p></td>
<td style="border:1px solid black;"><p>特定のドメイン内の管理と制御の役割の割り当てをサポートします。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウント (ユーザー) を追加してはいけません。*</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Domain Computers</p></td>
<td style="border:1px solid black;"><p>ドメインのメンバであるすべてのサーバーおよびワークステーションです。ドメイン コントローラは含まれません。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p>ドメイン コンピュータに固有のリソースにアクセスできるようにする、ユーザーの役割の割り当てをサポートします。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Domain Controllers</p></td>
<td style="border:1px solid black;"><p>ドメイン内のすべてのドメイン コントローラ用のグループ アカウントです。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>DC_Name</p></td>
<td style="border:1px solid black;"><p>ドメイン コントローラに固有のリソースにアクセスできるようようにする、ユーザーの役割の割り当てをサポートします。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Domain Guests</p></td>
<td style="border:1px solid black;"><p>このグループはドメイン コントローラの役割を果たしている Windows 2000 のサーバー上でのみ利用することができます。このグループのメンバはネットワークを通じてのみシステムにアクセスすることを許され、既定では非常に限られた特権しか与えられません。このグループには当初はドメインの Guest ユーザー アカウントだけが含まれます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>Guest</p></td>
<td style="border:1px solid black;"><p>Guest/匿名アカウントは FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前のユーザー識別に違反する可能性があります。</p>
<p><strong>要件:</strong></p>
<p>このグループを使用してはいけません。このグループから、Guest も含めて、すべてのアカウントを削除します。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Domain Users</p></td>
<td style="border:1px solid black;"><p>このグループはドメイン コントローラの役割を果たしている Windows 2000 のサーバー上でのみ利用することができます。ドメイン環境においては、Administrator アカウントおよびすべての新しいユーザー アカウントが自動的にこのグループのメンバに入れられます。このグループはドメインおよびドメイン内のすべての Windows コンピュータの Users ローカル グループのメンバでもあります。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>Administrator</p>
<p>Guest</p>
<p>Krbtgt</p>
<p>TsInternetUser</p>
<p>(既定では、すべての新しいユーザーが追加されます。)</p></td>
<td style="border:1px solid black;"><p>ドメインのリソースにアクセスできるようにする、ユーザーの役割の割り当てをサポートします。</p>
<p>Guest/匿名アカウントは 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前のユーザー識別に違反する可能性があります。</p>
<p><strong>要件:</strong></p>
<p>Guest アカウントおよび TsInternetUser アカウントを削除します。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Enterprise Admins</p></td>
<td style="border:1px solid black;"><p>ネットワーク全体にわたって管理と制御を行えるようにします。既定では、ドメイン コントローラの Administrator アカウントがメンバです。このグループは Active Directory 内のフォレスト全体にわたって変更を行う権限を与えられています。その例として、子ドメインの追加が挙げられます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>Administrator (ドメイン コントローラ)</p></td>
<td style="border:1px solid black;"><p>ネットワーク全体にわたる管理と制御の役割の割り当てをサポートします。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Group Policy Creator Owner</p></td>
<td style="border:1px solid black;"><p>このグループのメンバはドメインのグループ ポリシーを修正することができます。このグループは Active Directory 内に新しいグループ ポリシー オブジェクトを作成する権限を与えられています。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>Administrator</p></td>
<td style="border:1px solid black;"><p>ドメイン レベルのグループ ポリシーを維持するように指定された、管理的役割の割り当てをサポートします。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウントを追加してはいけません。*</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Schema Admins</p></td>
<td style="border:1px solid black;"><p>Active Directory スキーマの管理者です。このグループは Active Directory 内のスキーマを変更する権限を与えられています。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>Administrator</p></td>
<td style="border:1px solid black;"><p>Active Directory スキーマを管理するように指定された、管理的役割の割り当てをサポートします。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウントを追加してはいけません。*</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>ドメイン ローカル グループ</p></td>
<td style="border:1px solid black;"><p>このグループは、特にドメイン コントローラ上および Active Directory ストア内でタスクを行うための、特権およびアクセス許可をユーザーに与えます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>このグループは、権限を与えられた管理者の役割および権限を与えられたユーザーの役割に、ユーザーを割り当てられるようにします。その際、ユーザーが割り当てられているドメイン ローカル グループに基づいて、ドメイン コントローラへの固有のアクセス制限が課されます。 このグループは TOE セキュリティ機能要件の FMT_SMR.1 セキュリティ役割をサポートします。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Account Operators</p></td>
<td style="border:1px solid black;"><p>このグループはドメイン コントローラの役割を果たしている Windows 2000 のサーバー上でのみ利用することができます。このグループはシステムおよびドメインに関するユーザー アカウントおよびグループ アカウントを、メンバが管理できるようにします。既定では、このグループは、Active Directory のすべてのコンテナおよび組織単位 (OU) 内のユーザー、グループ、およびコンピュータに関するアカウントを、作成、修正、および削除するアクセス許可を有しています。ただし、Builtin コンテナとドメイン コントローラ OU は対象外です。このグループは Administrators グループおよび Domain Admins グループを修正するアクセス許可は有していません。また、それらのグループのメンバのアカウントを修正するアクセス許可も有していません。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p>ドメイン内のユーザー アカウントを管理するように指定された、管理的な役割の割り当てをサポートします。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウントを追加してはいけません。*</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>このグループのメンバはすべてのドメイン コントローラおよびドメイン自体の上で、すべての管理的なタスクを実行することができます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>Administrator</p>
<p>Domain Admins</p>
<p>Enterprise Admins</p></td>
<td style="border:1px solid black;"><p>ドメイン内のすべてのドメイン コントローラおよびリソースに対する全面的な管理的アクセス権利を有する、管理的な役割の割り当てをサポートします。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウントを追加してはいけません。*</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Backup Operators</p></td>
<td style="border:1px solid black;"><p>このグループのメンバはすべてのドメイン コントローラ上で Windows Backup を使用して、ファイルのバックアップと復元を行うことができます。その際、それらのファイルを保護するアクセス許可の制約を受けません。このグループのメンバはコンピュータにログオンすることもコンピュータをシャットダウンすることもできます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p>このアカウントを誤って使用すると、FDP_ACF.1(a) セキュリティ属性によるアクセス制御に違反する可能性があります。</p>
<p>このグループのメンバは、通常は自分がアクセスしないファイルおよびディレクトリを抽出することができます。このグループに属しているユーザーは、バックアップの目的で、任意のファイルを開くことができ、読み取り用に開いた後で、任意の場所にファイルをリダイレクトすることができます。</p>
<p>既定では、Backup Operators グループに属していなくても、ユーザーは適切なファイルおよびディレクトリへのアクセス許可を有しているファイルを、バックアップおよび復元することができます。</p>
<p>Administrator アカウントは最初からバックアップ権利を全面的に有しています。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウントを追加してはいけません。*</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>DnsAdmins</p></td>
<td style="border:1px solid black;"><p>DNS 管理グループです。このグループは DNS サーバーおよびそのゾーンを全面的に管理する権限を有しています。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p>DNS の管理を担当する管理的な役割の割り当てをサポートします。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウントを追加してはいけません。*</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Guests</p></td>
<td style="border:1px solid black;"><p>このグループはシステム上のリソースに限定的にアクセスできるようにします。このグループのメンバはデスクトップ環境に永続的な変更を加えることはできません。サービスの中には、インストールされると、ユーザーを自動的にこのグループに加えるものがあります。たとえば、IIS は匿名ユーザー アカウントをこのグループに追加します。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>Guest (ローカル)</p>
<p>Domain Guests</p>
<p>TsInternetUser</p></td>
<td style="border:1px solid black;"><p>Guest/匿名アカウントは FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前のユーザー識別 に違反する可能性があります。</p>
<p><strong>要件:</strong></p>
<p>このグループを使用してはいけません。このグループから、Guest も含めて、すべてのアカウントを削除します。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Pre-Windows 2000 Compatible Access</p></td>
<td style="border:1px solid black;"><p>ドメイン内のすべてのユーザーおよびグループに関して読み取りアクセスを許可する、下位互換性グループです。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p><strong>要件:</strong></p>
<p>Windows 2000 以前のシステムとの下位互換性を持つことは、TOE の目的ではありません。したがって、このグループにユーザーを追加してはいけません。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Print Operators</p></td>
<td style="border:1px solid black;"><p>ドメイン コントローラだけに組み込まれているグループです。このグループのメンバはドメイン コントローラ上のネットワーク プリンタをセットアップおよび管理することができます。このグループのメンバは、ドメイン内のプリンタ共有リソースを、作成、変更、および削除する権利を与えられます。また、このグループのメンバは、システムにローカルにログオンすることも、システムをシャットダウンすることもできます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p>ドメイン内の印刷サービスの管理を担当する管理的な役割の割り当てをサポートします。</p>
<p><strong>推奨:</strong></p>
<p>これは管理的機能です。したがって、権限を与えられた管理者だけをこのグループに追加すべきです。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Replicator</p></td>
<td style="border:1px solid black;"><p>ドメイン コントローラ上でのファイルの複製をサポートします。このグループはドメイン コントローラ上のファイル複製サービスによって使用されます。このグループのメンバはファイル複製サービスを構成することができます。ユーザー ログオン スクリプトのようなファイルを Windows 2000 ベースのコンピュータ間で自動的にコピーするために、ディレクトリ レプリケータ サービスが使用されます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.5.3 TFS Data Replication Consistency に示されている要件をサポートするために使用することができます。ドメイン内のディレクトリ複製サービスの管理を担当する管理的な役割の割り当てをサポートします。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウントを追加してはいけません。*</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>RAS and IAS Servers</p></td>
<td style="border:1px solid black;"><p>このグループ内のサーバーはユーザーのリモート アクセス プロパティにアクセスすることができます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Server Operators</p></td>
<td style="border:1px solid black;"><p>このグループはドメイン コントローラの役割を果たしている Windows 2000 のサーバー上でのみ利用することができます。このグループのメンバはサーバー管理タスクを遂行することができます。その例として、共有プリンタ、共有ディレクトリ、およびファイルの作成、変更、および削除が挙げられます。このグループのメンバはファイルのバックアップと復元を行うこと、サーバーのコンソールをロックすること、システムをシャットダウンすることもできます。このグループのメンバはシステムのポリシーを変更することやサービスを起動および停止することはできません。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>サーバーの保守を担当する管理的な役割の割り当てをサポートします。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウントを追加してはいけません。*</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Users</p></td>
<td style="border:1px solid black;"><p>このグループはエンド ユーザーとしてコンピュータを動かすのに必要な権利をユーザーに提供します。その例として、アプリケーションの実行およびファイルの管理が挙げられます。既定では、新しいすべてのローカル ユーザーがこのグループに追加されます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>Authenticated Users</p>
<p>Domain Users</p>
<p>INTERACTIVE</p>
<p>(既定では、新しいすべてのローカル ユーザーがこのグループに追加されます。)</p></td>
<td style="border:1px solid black;"><p>ドメイン コントローラ上のリソースにアクセスする、ユーザーの役割の割り当てをサポートします。</p>
<p><strong>要件:</strong></p>
<p>認証を受けずにアクセスする潜在的な危険があるアカウント (たとえば、Guest) をこのグループに追加してはいけません。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>ローカル グループ</p></td>
<td style="border:1px solid black;"><p>すべてのスタンドアロンの Windows 2000 Server、メンバ サーバー、および Professional ワークステーションにこのグループがあらかじめ組み込まれています。このグループのメンバはグループが属するコンピュータ上でタスクを遂行することができます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>このグループでは、権限を与えられた管理者の役割および権限を与えられたユーザーの役割に、ユーザーを割り当てることができます。それらの役割には、ユーザーが割り当てられた先のローカル グループに基づいて、ローカルに固有のアクセス制限が課されています。このグループは TOE セキュリティ機能要件の FMT_SMR.1 セキュリティ役割をサポートします。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>このグループのメンバはコンピュータ全体を完全に制御することができます。Windows 2000 が稼働しているメンバ サーバーまたはコンピュータがドメインに加えられると、ローカル Administrators グループに Domain Admins グループが追加されます。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>スタンドアロン:</strong></p>
<p>Administrator</p>
<p><strong>ドメイン メンバ:</strong></p>
<p>Administrator</p>
<p>Domain Admins</p></td>
<td style="border:1px solid black;"><p>コンピュータ上のすべてのローカル リソースに対する全面的な管理アクセス権限を持つ、管理的な役割の割り当てをサポートします。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウントを追加してはいけません。*</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Backup Operators</p></td>
<td style="border:1px solid black;"><p>このグループのメンバは Windows Backup を使用して、いつでもコンピュータのバックアップと復元を行うことができます。ファイル システムのセキュリティに制約されることはありません。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p>このアカウントを誤って使用すると、FDP_ACF.1(a) セキュリティ属性によるアクセス制御に違反する可能性があります。</p>
<p>このグループのメンバは、通常は自分がアクセスしないファイルおよびディレクトリを抽出することができます。このグループに属しているユーザーは、バックアップの目的で、任意のファイルを開くことができ、読み取り用に開いた後で、任意の場所にファイルをリダイレクトすることができます。</p>
<p>既定では、Backup Operators グループに属していなくても、ユーザーは適切なファイルおよびデ ィレクトリへのアクセス許可を有しているファイルを、バックアップおよび復元することができます。</p>
<p>Administrator アカウントは最初からバックアップ権利を全面的に有しています。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウントを追加してはいけません。*</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Guests</p></td>
<td style="border:1px solid black;"><p>このグループはシステム上のリソースに限定的にアクセスできるようにします。このグループのメンバはデスクトップ環境に永続的な変更を加えることはできません。</p>
<p>既定では、コンピュータの Guest ユーザー アカウントはこのグループのメンバです。このアカウントは既定では無効にされています。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>スタンドアロン Professional:</strong></p>
<p>Guest</p>
<p><strong>スタンドアロン Server:</strong></p>
<p>Guest</p>
<p>TsInternetUser</p>
<p><strong>ドメイン メンバ:</strong></p>
<p>Add Domain Guests</p></td>
<td style="border:1px solid black;"><p>Guest/匿名アカウントは FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前のユーザー識別に違反する可能性があります。</p>
<p><strong>要件:</strong></p>
<p>このグループを使用してはいけません。このグループから、Guest も含めて、すべてのアカウントを削除します。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Power Users</p></td>
<td style="border:1px solid black;"><p>このグループのメンバであるユーザーはコンピュータ上でローカル ユーザー アカウントを作成して修正し、リソースを共有することができます。ただし、コンピュータを完全に制御する権利は与えられません。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p>特定のコンピュータ上で権利を多く与えられた、ユーザーの役割の割り当てをサポートします。</p>
<p>このグループでは、ローカル ユーザー アカウントの管理およびローカル リソースの管理のような、管理者レベルの特権が与えられます。権限を与えられている管理者ではないユーザーをこのグループのメンバに入れることは、通常は権限のある管理者に与えられる特権をユーザーが持つことになる分だけ、FMT_MTD.1(c) ユーザー属性の管理、FMT_MTD.1(d)、認証データの管理 (ユーザーが作成したアカウント関して)、FMT_MTD.1(e) ロックアウト期間の管理 (ユーザーが作成したアカウント関して)、最小パスワード文字数の管理 (ユーザーが作成したアカウント関して)、および FMT_SMR.1 セキュリティ役割に違反する可能性があります。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウントを追加してはいけません。*</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Replicator</p></td>
<td style="border:1px solid black;"><p>このグループのメンバはファイル複製サービスを構成することができます。ユーザー ログオン スクリプトのようなファイルを Windows 2000 ベースのコンピュータ間で自動的にコピーするために、ディレクトリ レプリケータ サービスが使用されます。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>なし</p></td>
<td style="border:1px solid black;"><p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.5.3 TFS Data Replication Consistency に明示されている要件をサポートするために使用することができます。コンピュータ内でディレクトリ複製サービスの管理を担当する管理的な役割の割り当てをサポートします。</p>
<p><strong>要件:</strong></p>
<p>このグループに非管理的アカウントを追加してはいけません。*</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Users</p></td>
<td style="border:1px solid black;"><p>このグループはエンド ユーザーとしてコンピュータを動かすのに必要な権利をユーザーに提供します。その例として、アプリケーションの実行およびファイルの管理が挙げられます。既定では、新しいすべてのローカル ユーザーがこのグループに追加されます。Windows 2000 が稼働しているメンバ サーバーまたはコンピュータがドメインに加えられると、ローカル User グループに Domain Users グローバル グループ、Authenticated Users 特殊グループ、および INTERACTIVE 特殊グループが追加されます。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>スタンドアロン:</strong></p>
<p>Authenticated Users</p>
<p>INTERACTIVE</p>
<p>(既定では、新しいすべてのローカル ユーザーが追加されます。)</p>
<p><strong>ドメイン メンバ:</strong></p>
<p>Authenticated Users</p>
<p>Domain Users</p>
<p>INTERACTIVE</p>
<p>(既定では、新しいすべてのローカル ユーザーが追加されます。)</p></td>
<td style="border:1px solid black;"><p>コンピュータ上のローカル リソースにアクセス可能なユーザーの役割の割り当てをサポートします。</p>
<p><strong>要件:</strong></p>
<p>認証を受けずにアクセスする潜在的な危険があるアカウント (たとえば、Guest) をこのグループに追加してはいけません。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>システム グループ</p></td>
<td style="border:1px solid black;"><p>システム グループではメンバの所属を修正することはできません。各グループは特定のユーザー クラスまたはオペレーティング システム自体を表します。これらのグループは Windows 2000 システムによって自動的に作成されますが、グループ管理 GUI に表示はされません。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Anonymous Logon</p></td>
<td style="border:1px solid black;"><p>Windows 2000 によって認証されていないユーザー アカウントがこのグループに含まれます。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>認証されていないすべてのユーザー</p></td>
<td style="border:1px solid black;"><p>このアカウントを誤って使用すると、FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前のユーザー識別に違反する可能性があります。</p>
<p><strong>要件:</strong></p>
<p>このアカウントにはリソースへのアクセス許可またはユーザーの権利を与えてはいけません。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Authenticated Users</p></td>
<td style="border:1px solid black;"><p>コンピュータ上または Active Directory サービス内に有効なユーザー アカウントを持つすべてのユーザーがこのグループに含まれます。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>認証されているすべてのユーザー</p></td>
<td style="border:1px solid black;"><p>FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前の利用者識別をサポートします。</p>
<p><strong>推奨:</strong></p>
<p>リソースへの匿名アクセスを防止するために、Everyone グループの代わりに Authenticated Users グループを使用します。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>BATCH</p></td>
<td style="border:1px solid black;"><p>バッチ キュー機能を通じてログオンしたすべてのユーザーがこのグループに含まれます。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>CREATOR OWNER</p></td>
<td style="border:1px solid black;"><p>リソースを作成または所有しているユーザーのユーザー アカウントがこのグループに含まれます。Administrators グループのメンバがリソースを作成した場合は、Administrators グループがそのリソースの所有者となります。このグループは Windows 2000 Server または Professional 上の共有可能なリソースごとに作成されます。継承可能なアクセス制御エントリ (ACE) 内のプレースホルダです。ACE が継承されるとき、この SID がオブジェクトの作成者の SID で置き換えられます。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>このグループのメンバはリソースを作成または所有しているユーザーです。</p></td>
<td style="border:1px solid black;"><p>オブジェクトの所有者の属性の割り当てを通じて、FDP_ACF.1(a) セキュリティ属性によるアクセス制御をサポートします。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>CREATOR GROUP</p></td>
<td style="border:1px solid black;"><p>継承可能な ACE 内のプレースホルダです。ACE が継承されるとき、この SID がオブジェクトの作成者のプライマリ グループの SID で置き換えられます。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>DIALUP</p></td>
<td style="border:1px solid black;"><p>現在ダイアルアップ接続しているユーザーがこのグループに含まれます。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>すべてのダイアルイン ユーザー</p></td>
<td style="border:1px solid black;"><p><strong>要件:</strong></p>
<p>ダイアルアップ サービスは TOE の目的ではありません。したがって、このアカウントにリソースへのアクセス許可またはユーザーの権利を与えてはいけません。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>ENTERPRISE DOMAIN CONTROLLER</p></td>
<td style="border:1px solid black;"><p>Active Directory サービスを利用するフォレスト内のすべてのドメイン コントローラを含むグループです。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Everyone</p></td>
<td style="border:1px solid black;"><p>コンピュータにアクセスするすべてのユーザーがこのグループに含まれます。Windows 2000 では、有効なユーザー アカウントを持たないユーザーは Guest として認証されます。ユーザーは Everyone グループに割り当てられているすべての権利とアクセス許可を自動的に取得します。</p>
<p>匿名ユーザーおよびゲストをはじめ、すべてのユーザーを含むグループです。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>このグループのメンバには、Windows 2000 Server または Professional にアクセスするすべてのユーザーが含まれます。ローカルにアクセスするか、ネットワークを通じてアクセスするか、RAS を通じてアクセスするかを問いません。認証されているユーザーも認証されていないユーザーも含まれます。基本的には、システムにアクセスするあらゆるユーザーが Everyone グループのメンバになります。</p></td>
<td style="border:1px solid black;"><p>このアカウントを誤って使用すると、FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前のユーザー識別 に違反する可能性があります。</p>
<p><strong>要件:</strong></p>
<p>このアカウントにリソースへのアクセス許可またはユーザーの権利を割り当ててはなりません。必要に応じて、Authenticated Users または個々のユーザー アカウントまたはグループを使用します。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>INTERACTIVE</p></td>
<td style="border:1px solid black;"><p>コンピュータにローカルにログオンしたユーザーのユーザー アカウントがこのグループに属します。Interactive グループのメンバは自分達が実際に所在する場所にあるコンピュータ上のリソースにアクセスすることができます。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>Windows 2000 Server または Professional にローカルにログインしたユーザーがこのグループに含まれます。ネットワークを通じて接続されているユーザーはこのグループのメンバになれません。</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>NETWORK</p></td>
<td style="border:1px solid black;"><p>ネットワーク上の他のコンピュータからコンピュータ上の共有リソースに現在接続しているユーザーがこのグループに含まれます。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p>このグループに属するのは、ネットワークを介してリソースに接続したユーザーです。対話型でローカル ログインしたユーザーは含まれません。</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>PROXY</p></td>
<td style="border:1px solid black;"><p>この SID は Windows 2000 では使用されていません。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>RESTRICTED</p></td>
<td style="border:1px solid black;"><p>この SID は Windows 2000 では使用されていません。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>SELF</p></td>
<td style="border:1px solid black;"><p>Active Directory 内のアカウント オブジェクトまたはグループ オブジェクト上の継承可能な ACE 内のプレースホルダです。ACE が継承されるとき、この SID がアカウントを保持するセキュリティ プリンシパルの SID で置き換えられます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>SERVICE</p></td>
<td style="border:1px solid black;"><p>サービスとしてログオンしたすべてのセキュリティ プリンシパルを含むグループです。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>SYSTEM</p></td>
<td style="border:1px solid black;"><p>サービス、ユーティリティ、およびデバイス ドライバを実行するために、オペレーティング システムによって使用されるアカウントです。このアカウントは無制限の能力を持ち、レジストリの SAM のように Administrator でさえも拒否されるリソースにもアクセスすることができます。</p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>このアカウントは、権限のある管理者の管轄外にある TSF 保護機能のようなセキュリティ サービスを実行するために、Windows 2000 によって使用されます。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>TERMINAL SERVER USER</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>要件:</strong></p>
<p>ターミナル サービスのサポートは TOE の目的ではありません。したがって、このアカウントにリソースへのアクセス許可またはユーザーの権利を与えてはいけません。</p></td>
</tr>
</tbody>
</table>
<p> </p>

\* 要件が満たされている限り、セキュリティで保護されたオブジェクトの DACL から対応するグループを削除する必要はありません。

[](#mainsection)[ページのトップへ](#mainsection)

##### 目次

-   [第 1 章 ‐ ハードウェアおよびソフトウェアの環境](https://technet.microsoft.com/ja-jp/library/da7603d8-d1d7-400a-9993-3ac61d633e66(v=TechNet.10))
-   [第 2 章 ‐ オペレーティング システムのインストール](https://technet.microsoft.com/ja-jp/library/ddb614e6-9456-4f76-8dea-4018a51a810d(v=TechNet.10))
-   [第 3 章 ‐ セキュリティで保護された構成](https://technet.microsoft.com/ja-jp/library/95fe8ebd-7386-4e95-aff8-5fca17435788(v=TechNet.10))
-   [第 4 章 ‐ Windows 2000 Common Criteria (共通基準) セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/270098dc-f10b-41de-b26a-c2d795bca536(v=TechNet.10))
-   [参考資料](https://technet.microsoft.com/ja-jp/library/6df170a9-3e6d-42d6-a4c3-0fd3eb71bf77(v=TechNet.10))
-   [付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定](https://technet.microsoft.com/ja-jp/library/1adc2300-c9de-4ee0-bab7-9f8a797b03bc(v=TechNet.10))
-   [付録 B ‐ 監査カテゴリとイベント](https://technet.microsoft.com/ja-jp/library/0fc077e8-8bf5-4b4d-a555-a8c26c9792f0(v=TechNet.10))
-   [付録 C ‐ ユーザー権利と特権](https://technet.microsoft.com/ja-jp/library/9d7407aa-87b7-4564-9659-3e99abe3ac6c(v=TechNet.10))
-   付録 D ‐ ユーザー アカウントとグループ アカウント
-   [付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト](https://technet.microsoft.com/ja-jp/library/b1327283-7a58-409a-9554-59e4bbc01374(v=TechNet.10))
-   [付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/8842dd66-853c-4c8f-bb69-ae750f139356(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
