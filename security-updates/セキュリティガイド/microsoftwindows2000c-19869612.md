---
TOCTitle: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 C ‐ ユーザー権利と特権'
Title: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 C ‐ ユーザー権利と特権'
ms:assetid: '9d7407aa-87b7-4564-9659-3e99abe3ac6c'
ms:contentKeyID: 19869612
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277460(v=TechNet.10)'
---

Microsoft Windows 2000 セキュリティ構成ガイド
=============================================

### 付録 C ‐ ユーザー権利と特権

最終更新日: 2003年2月18日

下の表に、Windows 2000 システムにおける既定のユーザーの権利の割り当てを列挙し、それらに適用される Windows 2000 のセキュリティ ターゲットへの要件を定義し、セキュリティ ターゲットの目的を満たすために必須の変更と実施するよう推奨する変更を示します。

この表には、スタンドアロンの Windows 2000 Professional と Server の両システムおよび Windows 2000 ドメイン コントローラのユーザーに割り当てられている、既定のユーザー権利を示します。また、ドメイン セキュリティ ポリシーにおける既定のユーザー権利も示します (既定ではすべて 「未定義」)。ドメインのメンバに対しては、ドメイン セキュリティ ポリシーにおける割り当てが、ローカル セキュリティ ポリシーよりも優先します。表の中に「必須」と記されている変更は、ST の要件を満たすために必要です。

ユーザー権利/特権の割り当ては、ローカル セキュリティ ポリシーおよびドメイン セキュリティ ポリシーの以下の場所に収められています。

-   Windows 2000 Professional:

    管理ツールのローカル セキュリティ ポリシーのセキュリティの設定\\ローカル ポリシー\\ユーザー権利の割り当て

-   Windows 2000 Server:

    管理ツールのローカル セキュリティ ポリシーのセキュリティの設定\\ローカル ポリシー\\ユーザー権利の割り当て

-   Windows 2000 Domain ドメイン コントローラ:

    管理ツールのドメイン コントローラ セキュリティ ポリシー ウィンドウの設定\\セキュリティの設定\\ローカル ポリシー\\ユーザー権利の割り当て

    管理ツールのドメイン セキュリティ ポリシー ウィンドウの設定\\セキュリティの設定\\ローカル ポリシー\\ユーザー権利の割り当て

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
<th><p>ユーザー権利/特権</p></th>
<th><p>説明</p></th>
<th><p>スタンドアロンの Windows 2000 Professional において権利を割り当てられているグループ</p></th>
<th><p>スタンドアロンの Windows 2000 Server において権利を割り当てられているグループ</p></th>
<th><p>Windows 2000 のドメイン セキュリティ ポリシー において権利を割り当てられているグループ (ドメイン コントローラ内に所在)</p></th>
<th><p>Windows 2000 ドメイン コントローラ において権利を割り当てられているグループ (ドメイン コントローラ セキュリティ ポリシー)</p></th>
<th><p>適用されるセキュリティ ターゲットの要件 および/または 変更の理由</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>ログオン権利</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>ネットワーク経由でコンピュータへアクセス</p>
<p>(SeNetwork<br />
LogonRight)</p></td>
<td style="border:1px solid black;"><p>ネットワークを通じてコンピュータに接続することを許可されるのはだれかを決定します。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Power Users</p>  
<p>Users</p>  
<p>Everyone</p>  
<p><strong>必須の変更</strong> :</p>  
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Power Users</p>  
<p>Users</p>
<p>Authenticated Users</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Power Users</p>  
<p>Users</p>  
<p>Everyone</p>  
<p><strong>必須の変更</strong> :</p>  
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Power Users</p>  
<p>Users</p>
<p>Authenticated Users</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Authenticated Users</p>  
<p>Everyone</p>  
<p><strong>必須の変更</strong> :</p>  
<p>Administrators</p>
<p>Authenticated Users</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FIA_UAU.2.1 認証 および FIA_UID.2 アクション前の利用者認証</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.3 Identification and Authentication for network logons</p>  
<p><strong>変更</strong> :</p>
<p>ゲスト/匿名ログオンを許可しないようにします。(何らかの理由でゲストが有効な場合には) 認証されていないアクセスや匿名アクセスを許す潜在的な可能性のあるアカウントを削除/置換します。「Everyone」を「Authenticated Users」で置き換えます。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>バッチ ジョブとしてログオン</p>
<p>(SeBatch<br />
LogonRight)</p></td>
<td style="border:1px solid black;"><p>バッチ ジョブ機能を使用して、ユーザーがログオンできるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>ローカル ログオン</p>
<p>(SeInteractive<br />
LogonRight)</p></td>
<td style="border:1px solid black;"><p>コンピュータのキーボードからユーザーがローカル ログオンできるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Power Users</p>  
<p>Users</p>  
<p><em>コンピュータ名\\</em>Guest</p>  
<p><strong>必須の変更</strong> :</p>  
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Power Users</p>
<p>Users</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Power Users</p>  
<p>Users</p>  
<p><em>コンピュータ名</em>\\Guest</p>  
<p><em>コンピュータ名\\TsInternetUser</em></p>  
<p><strong>必須の変更</strong> :</p>  
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Power Users</p>
<p>Users</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>Required</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Account Operators</p>  
<p>Backup Operators</p>  
<p>Print Operators</p>  
<p>Server Operators</p>  
<p>TsInternetUser</p>  
<p><strong>必須の変更</strong> :</p>  
<p>Administrators</p>  
<p>Account Operators</p>  
<p>Backup Operators</p>  
<p>Print Operators</p>
<p>Server Operators</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FIA_UAU.2.1 認証 および FIA_UID.2 アクション前の利用者認証</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.3 Identification and Authentication for local logons</p>  
<p><strong>変更</strong> :</p>
<p>ゲスト/匿名ログオンを許可しないようにします。認証されていないアクセスや匿名アクセスを許可するので、ゲスト アカウントを削除します。TsInternetUser アカウントを削除します ・TOE に関してはターミナル サービスを実装しません。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>サービスとしてログオン</p>
<p>(SeService<br />
LogonRight)</p></td>
<td style="border:1px solid black;"><p>セキュリティ プリンシパルがサービスとしてログオンできるようにします。サービスとしてログオンする権利があらかじめ組み込まれている LocalSystem アカウントのもとで実行するように、サービスを構成することができます。他のアカウントのもとで実行するサービスには、権利を割り当てる必要があります。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>ネットワーク経由でコンピュータへアクセスを拒否する</p>
<p>(SeDeny<br />  
Network<br />
LogonRight)</p></td>
<td style="border:1px solid black;"><p>ユーザーまたはグループがネットワークを通じてこのコンピュータに接続することを禁止します。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p>ローカルでログオンを拒否する</p>
<p>(SeDeny<br />  
Interactive<br />
LogonRight)</p></td>
<td style="border:1px solid black;"><p>ユーザーまたはグループがキーボードからローカルにログオンすることを禁止します。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>バッチ ジョブとしてログオンを拒否する</p>
<p>(SeDenyBatch<br />
LogonRight)</p></td>
<td style="border:1px solid black;"><p>ユーザーまたはグループがバッチ キュー機能を使用してログオンすることを禁止します。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p>サービスとしてログオンを拒否する</p>
<p>(SeDeny<br />  
Service<br />
LogonRight)</p></td>
<td style="border:1px solid black;"><p>ユーザーまたはグループがサービスとしてログオンすることを禁止します。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><strong>特権</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p>オペレーティング システムの一部として機能</p>
<p>(SeTcb<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>プロセスをユーザーとして認証できるようにし、結果としてユーザーと同じリソースにプロセスがアクセスできるようにします。このサービスが必要なのは、低レベルの認証サービスだけのはずです。</p>
<p>既定では、ユーザーに関連するものだけにアクセスが限定されない潜在的な可能性があります。なぜならば、呼び出し元のプロセスにより、任意の追加のアクセスがアクセス トークンに入れられる可能性があるからです。さらに、懸念されることは、呼び出し元のプロセスが匿名のトークンを作成して、ありとあらゆるアクセスを行うことができることです。それに加えて、匿名のトークンからは監査ログ中のイベントを追跡するための身元情報が得られません。</p>
<p>LocalSystem アカウントは既定ではこの特権を使用しています。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>既定の設定により、以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FPT_SEP.1.2, ドメイン分離</p>  
<p>この特権を誤って使用すると、FAU_GEN.1 監査データ生成、FAU_GEN.2 ユーザー識別子の関連付け、FIA_USB.1 利用者サブジェクトの結合に違反する可能性があります。</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.5.5 Domain Separation</p>  
<p>LocalSystem 以外のアカウントでこの特権を使用すると、責任あるセキュリティ要件を満たさなくなる可能性があります。匿名のトークンが作成される潜在的な可能性があるからです。</p>  
<p><strong>変更</strong> :</p>
<p>ドメイン ポリシーを「なし」に設定して、ドメインに既定の設定を適用し、FPT_SEP.1.2、FAU_GEN.1、FAU_GEN.2、および FIA_USB.1 を確実にサポートするようにします。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>ドメインにワークステーションを追加</p>
<p>(SeMachine<br />  
Account<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>ユーザーが特定のドメインにコンピュータを追加できるようにします。この特権を有効にするには、ドメイン内のドメイン コントローラ用のローカル セキュリティ ポリシーの一環として割り当てる必要があります。この特権を持つユーザーは対象のドメインに 10 台までのワークステーションを追加することができます。</p>
<p>Windows 2000 においては、この特権の働きは、組織単位向けのコンピュータ オブジェクトの作成許可および Active Directory 内の既定のコンピュータ コンテナと重複しています。コンピュータ オブジェクトの作成許可を持つユーザーは対象のドメインに無制限の数のコンピュータを追加することができます。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Authenticated Users</p>  
<p><strong>必須の変更</strong> :</p>
<p>Domain Admins</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Security Management Functions。権限のある管理者がドメインにコンピュータを追加したりドメインからコンピュータを削除したりできるようにします。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。認証されているユーザーに、ドメインにコンピュータを追加したりドメインからコンピュータを削除したりする特権を付与するために使用することができます。</p>  
<p><strong>変更</strong> :</p>
<p>ドメイン コントローラ セキュリティ ポリシーの既定値を Authenticated Users から Domain Admins に変更して、ドメイン インフラストラクチャの管理と構成の制御を信頼できるようにします。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>ファイルとディレクトリのバックアップ</p>
<p>(SeBackup<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>システムをバックアップするためのファイルとディレクトリへのアクセス許可をユーザーに与えないようにします。この特権を選択するのは、アプリケーションにおいて NTFS バックアップ アプリケーション インタフェースを通じてアクセスを試みるときだけです。それ以外の場合は、ファイルおよびディレクトリへの通常のアクセス許可を適用します。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Server Operators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>この特権を誤って使用すると、FDP_ACF.1(a) セキュリティ属性によるアクセス制御に違反します。ユーザーが ACL の制限を回避できるようになるからです。</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーにバックアップを行う特権を与えるために使用することができます。</p>
<p>既定のもの以外のアカウントにこの特権を割り当ててはいけません。Administrators、Backup Operators、Server Operators のいずれかのグループに属する権限のある管理者だけにこの権利を与えるようにするためです。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>走査チェックのバイパス</p>
<p>(SeChange<br />  
Notify<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>任意の Microsoft Windows のファイル システムまたはレジストリ内でオブジェクトのパスを移動する間に、アクセスする権限のないフォルダをユーザーが通り抜けて行けるようにします。この権限はユーザーがフォルダの内容をリストすることを許可するものではありません。ユーザーがディレクトリを走査することを許可するだけです。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators Power Users</p>  
<p>Users</p>  
<p>Everyone</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators Power Users</p>  
<p>Users</p>  
<p>Everyone</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Authenticated Users</p>  
<p>Everyone</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p>システム時刻の変更</p>
<p>(SeSystem<br />
TimePrivilege)</p></td>
<td style="border:1px solid black;"><p>コンピュータ内蔵の時計の時刻をユーザーが設定できるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators Power Users</p>  
<p><strong>必須の変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators Power Users</p>  
<p><strong>必須の変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須の変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Server Operators</p>  
<p><strong>必須の変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>既定の設定で以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FMT_SMR.1 セキュリティ役割と、FMT_MTD.1.1(g) TSF データの管理</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles、パラグラフ 6.1.5.6 Time Service。承認されているユーザーにシステム時刻を設定する特権を与えるために使用することができます。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>トークン オブジェクトの作成</p>
<p>(SeCreate<br />  
Token<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>NtCreate<br />
Token() または他のトークン作成 API を呼び出すことにより、プロセスがアクセス トークンを作成できるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須の変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須の変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須</strong> :</p>
<p>なし</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>既定の設定では、以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FPT_SEP.1.2 ドメイン分離</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.5.5, Domain Separation</p>  
<p>この特権の使用は監査できません。</p>  
<p>この特権を誤って使用すると、FIA_USB.1 利用者サブジェクトの結合および FAU_GEN.1 監査データの生成に違反する可能性があります。</p>  
<p><strong>変更</strong> :</p>  
<p>この特権に関するドメイン ポリシーを 「なし」に設定して、ドメインに既定の設定を適用し、FPT_SEP.1.2 を確実にサポートするようにします。</p>
<p>プロセスがこの特権を必要とする場合、<em>LocalSystem</em> アカウント (この特権があらかじめ与えられています) を使用するようにします。別のアカウントを作成してこの特権を与えることは避けます。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>永続的共有オブジェクトの作成</p>
<p>(SeCreate<br />  
Permanent<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>Windows 2000 のオブジェクト マネージャ内に、プロセスがディレクトリ オブジェクトを作成できるようにします。この特権は、Windows 2000 のオブジェクト名前空間を拡張する、カーネル モードのコンポーネントにとって役に立ちます。カーネル モードで実行されているコンポーネントには既にこの特権が割り当てられています。したがって、それらのコンポーネントにこの特権を割り当てる必要ありません。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>ページ ファイルの作成</p>
<p>(SeCreate<br />  
Pagefile<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>ユーザーがページ ファイルを作成してサイズを変更できるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須</strong> :</p>
<p>Administrators</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーにページ ファイルの設定を変更する特権を与えるために、使用することができます。</p>  
<p><strong>変更</strong> :</p>
<p>この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理をサポートするとともに、不法なシステム修正を防止するようにします。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>プログラムのデバッグ</p>
<p>(SeDebug<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>ユーザーが任意のプロセスにデバッガを添付できるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>この特権を割り当てると、FAU_GEN.1 監査データの生成 および FDP_ACF.1(a) セキュリティ属性によるアクセス制御 TOE セキュリティ機能要件に違反します。</p>
<p>この特権があると、ACL にかかわらず、ユーザーはオブジェクトにアクセスすることができます。この特権の使用状況を監査することはできません。したがって、管理者も含めて、この特権をだれにも割り当ててはいけません。</p>  
<p><strong>変更</strong> :</p>
<p>既定のすべての特権の割り当てを 「なし」に変更して、FAU_GEN.1 および FDP_ACF.1(a) に確実に準拠するようにします。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>コンピュータとユーザー アカウントに委任時の信頼を付与</p>
<p>(SeEnable<br />  
Delegation<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>Active Directory 内のユーザーまたはコンピュータに関して、委任に対する信頼の設定をユーザーが変更できるようにします。この特権を与えられたユーザーまたはコンピュータはオブジェクトのアカウント制御フラグに対する書き込みアクセス許可も有していなければなりません。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須の変更</strong> :</p>
<p>なし</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。Active Directory 内のユーザーまたはコンピュータに関して、委任に対する信頼の設定を承認されたユーザーに許可するために使用することができます。</p>  
<p>この特権または委任に対する信頼の設定を間違って使用すると、システムに対するトロイの木馬作戦を用いた巧妙な攻撃に、ネットワークが被害を受けやすくなります。そのような攻撃では、クライアントからの着信を装い、クライアントの資格情報を使用して、ネットワーク リソースにアクセスしようとします。</p>  
<p><strong>変更</strong> :</p>
<p>この特権に関するドメイン ポリシーを 「なし」に設定して、承認されていないアクセスおよび修正を防止するようにします。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>リモート コンピュータからの強制シャットダウン</p>
<p>(SeRemote<br />  
Shutdown<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>ネットワーク上のリモート ロケーションからユーザーがコンピュータをシャットダウンできるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>Administrators</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Server Operators</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>セキュリティ監査の生成</p>
<p>(SeAudit<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>プロセスがセキュリティ ログ中にエントリを記録できるようにします。セキュリティ ログは承認されていないシステム アクセスおよびその他のセキュリティ関連活動を追跡するために使用します。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>LocalSystem アカウントを通じて、以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FAU_GEN.1.1 監査データの生成</p>  
<p>この特権をユーザーに与えると、TFS 以外のものによって生成された監査レコードが、監査ログ中に記録されます。この特権の使用状況を監査することはできません。</p>  
<p><strong>変更</strong> :</p>
<p>この特権に関するドメイン ポリシーを 「なし」に設定します。管理者も含めて、この特権をいかなるユーザーにも許可してはいけません。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>クォータの増加</p>
<p>(SeIncrease<br />  
Quota<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>他のプロセスに対するプロパティの書き込み許可を得ているプロセスが、他のプロセスに割り当てられているプロセッサのクォータを増やせるようにします。この特権はシステムをチューニングするのに役立ちます。しかし、サービス拒否攻撃などに、この特権を悪用することが可能です。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須の変更</strong> :</p>
<p>Administrators</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能をサポートするために使用することができます。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>しかし、この機能を管理者のみに限定するようには、ST では特に求められてはいません。</p>  
<p>以下の TOE セキュリティ機能要件をサポートすることができます。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーに、プロセスに割り当てられたプロセッサのクォータを増やす管理能力を与えるために、使用することができます。</p>  
<p>この特権を誤って使用すると、サービス拒否攻撃を招く可能性があります。それはセキュリティ上の深刻な問題です。プロセッサのクォータの管理はパフォーマンスおよび可用性に影響を及ぼすからです。しかし、ST ではサービス拒否攻撃への対処を求めてはいません。</p>  
<p><strong>変更</strong> :</p>
<p>この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理を実施するようにします。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>スケジューリング優先順位の繰り上げ</p>
<p>(SeIncrease<br />  
BasePriority<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>他のプロセスに対するプロパティの書き込み許可を得ているプロセスが、他のプロセスの実行優先度を上げられるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須の変更</strong> :</p>
<p>Administrators</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>しかし、この機能を管理者のみに限定するようには、ST では特に求められてはいません。</p>  
<p>以下の TOE セキュリティ機能をサポートするために使用することができます。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーに、プロセスの実行優先度を上げる管理能力を与えるために、使用することができます。</p>  
<p>この特権を誤って使用すると、サービス拒否攻撃を招く可能性があります。それはセキュリティ上の深刻な問題です。プロセッサのクオータの管理はパフォーマンスおよび可用性に影響を及ぼすからです。しかし、ST ではサービス拒否攻撃への対処を求めてはいません。</p>  
<p><strong>変更</strong> :</p>
<p>この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理を実施するようにします。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>デバイス ドライバのロードとアンロード</p>
<p>(SeLoad<br />  
Driver<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>ユーザーがプラグ アンド プレイ方式のデバイス ドライバをインストールおよびアンインストールできるようにします。この特権はプラグ アンド プレイ方式ではないデバイス ドライバには適用されません。プラグ アンド プレイ方式ではないデバイス ドライバをインストールすることができるのは管理者だけです。デバイス ドライバは信頼された (非常に特権的な) プロセスとして実行されることに注意してください。ユーザーがこの特権を乱用することが可能です。たとえば、有害なプログラムをインストールして、リソースを破壊できるアクセス許可を与えるといったことが可能です。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須の変更</strong> :</p>
<p>Administrators</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーにデバイス ドライバをインストールして構成する管理能力を与えるために使用することができます。</p>  
<p><strong>変更</strong> :</p>
<p>この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理をサポートするようにします。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>メモリ内のページのロック</p>
<p>(SeLock<br />  
Memory<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>プロセスがデータを物理メモリ内に保持できるようにします。それにより、ディスク上の仮想メモリにデータをページングすることが避けられます。この特権を割り当てると、システムのパフォーマンスが相当に低下する可能性があります。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p>監査とセキュリティ ログの管理</p>
<p>(SeSecurity<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>ファイル、Active Directory オブジェクト、レジストリ キーなどの個々のリソースに関して、オブジェクト アクセスの監査オプションを、ユーザーが指定できるようにします。監査ポリシー内で有効に設定されていないと、オブジェクト アクセスの監査は実際には行われません。この特権を持つユーザーは、イベント ビューアからセキュリティ ログを表示して消去することもできます。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須の変更</strong> :</p>
<p>Administrators</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>FAU_SAR.1.1、 監査レビュー</p>  
<p>FAU_SAR.2.1、 限定監査レビュー, FAU_SAR.3, 選択可能監査レビュー, FAU_SEL.1, 選択的監査</p>  
<p>FAU_STG.1.1、 FAU_STG.1.2, 監査記録の保証</p>  
<p>FMT_MOF.1.1(a)、 監査の管理</p>  
<p>FMT_MTD.1.1(a)、 監査記録の管理</p>  
<p>FMT_MTD.1.1(b)、 監査イベントの管理</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles およびパラグラフ 6.1.1 Audit Function。承認されたユーザーに監査データを構成して管理する管理能力を与えるために使用することができます。</p>  
<p><strong>変更</strong> :</p>
<p>この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理をサポートするようにします。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>ファームウェア環境値の修正</p>
<p>(SeSystem<br />  
Environment<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>システム環境変数を修正できるようにします。修正方法は 2 通りあります。具体的には、API を通じてプロセスに行わせる方法と、システム プロパティ アプレットを通じてユーザーが行う方法があります。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>Administrators</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーにシステム環境変数を変更する管理能力を与えるために使用することができます。</p>  
<p><strong>変更</strong> :</p>
<p>この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理をサポートするようにします。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>単一プロセスのプロファイル</p>
<p>(SeProfile<br />  
Single<br />  
Process<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>ユーザーが Microsoft Windows NT および Windows 2000 のパフォーマンス モニタ ツールを使用して、システム プロセスのパフォーマンスを監視できるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Power Users</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Power Users</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートするために使用することができます。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>以下の TOE セキュリティ機能をサポートするために使用することができます。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーに、システム プロセス以外のプロセスのパフォーマンスの診断を行う管理能力を与えるために使用することができます。</p>
<p>しかし、この特権によって得られる能力を活用するようには、ST では特に求められてはいません。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>システム パフォーマンスのプロファイル</p>
<p>(SeSystem<br />  
Profile<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>ユーザーが Microsoft Windows NT および Windows 2000 のパフォーマンス モニタ ツールを使用して、システム プロセス以外のプロセスのパフォーマンスを監視できるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須の変更</strong> :</p>
<p>Administrators</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>以下の TOE セキュリティ機能をサポートします。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles およびパラグラフ 6.1.5.1 System Integrity。承認されたユーザーに、システム プロセスのパフォーマンスの診断を行う管理能力を与えるために使用することができます。</p>  
<p><strong>変更</strong> :</p>
<p>この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理をサポートするようにします。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>ドッキング ステーションからコンピュータを削除</p>
<p>(SeUndock<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>ポータブル コンピュータのユーザーが [スタート] メニューの [PC の取り外し] をクリックすることにより、コンピュータのロックを解除できるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Power Users</p>  
<p>Users</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Power Users</p>  
<p>Users</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>プロセス レベル トークンの置き換え</p>
<p>(SeAssign<br />  
Primary<br />  
Token<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>親プロセスが子プロセスに関連するアクセス トークンを置換できるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>この特権を割り当てることは、以下の TOE セキュリティ機能要件に違反します。</p>
<p>セキュリティ属性によるアクセス制御、FIA_USB.1 利用者サブジェクトの結合、および FAU_GEN.1 監査データの生成</p>  
<p>この特権を監査することはできません。</p>  
<p><strong>変更</strong> :</p>  
<p>ドメイン セキュリティ ポリシーにおける既定の特権の割り当てを「なし」に変更して、ドメインが確実に FDP_ACF.1(a)、FIA_USB.1、および FAU_GEN.1 に準拠するようにします。</p>
<p>どのユーザーにもこの特権を割り当ててはなりません。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>ファイルとディレクトリの復元</p>
<p>(SeRestore<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>バックアップからファイルを復元するときに、ファイルおよびディレクトリへのアクセス許可をユーザーが回避して、オブジェクトの所有者としての有効なセキュリティ プリンシパルを設定できるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Server Operators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>この特権を誤って使用すると、FDP_ACF.1(a) セキュリティ属性によるアクセス制御 に違反します。ユーザーが ACL の制限を回避できるようになるからです。</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーにバックアップから復元する特権を与えるために使用することができます。</p>
<p>既定のもの以外のアカウントにこの特権を割り当ててはいけません。Administrators、Backup Operators、Server Operators のいずれかのグループに属する権限のある管理者だけにこの権利を与えるようにするためです。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>システムのシャットダウン</p>
<p>(SeShutdown<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>ユーザーがローカル コンピュータをシャットダウンできるようにします。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>BACKUP OPERATORS</p>  
<p>Power Users</p>  
<p>Users</p>  
<p><strong>推奨する変更</strong> :</p>  
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Power Users</p>
<p>Authenticated Users</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Power Users</p>  
<p><strong>推奨する変更</strong> :</p>  
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Power Users</p>
<p>Authenticated Users</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p>Account Operators</p>  
<p>Backup Operators</p>  
<p>Server Operators</p>  
<p>Print Operators</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p>ディレクトリ サービス データの同期化</p>
<p>(SeSyncAgent<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>ディレクトリの同期を取るサービスを行えるようにします。この特権はドメイン コントローラ上でのみ該当します。</p>
<p>ドメイン コントローラ上で LDAP ディレクトリ同期サービスを使用するために必要です。この特権の所有者はディレクトリ内のすべてのオブジェクトおよびプロパティを読むことができます。オブジェクトおよびプロパティが保護されていても、妨げられることはありません。既定では、この特権はドメイン コントローラ上の Administrator アカウントおよび LocalSystem アカウントに割り当てられています。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrator</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>ファイルとその他のオブジェクトの所有権の取得</p>
<p>(SeTake<br />  
Ownership<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>システム内のセキュリティで保護可能な任意のオブジェクトの所有権をユーザーが取得できるようにします。その中には、Active Directory オブジェクト、ファイルとフォルダ、プリンタ、レジストリ キー、プロセス、およびスレッドを含みます。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>(未定義)</p>  
<p><strong>必須の変更</strong> :</p>
<p>Administrators</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>Administrators</p>  
<p><strong>必須</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p>以下の TOE セキュリティ機能要件をサポートします。</p>
<p>FMT_SMR.1 セキュリティ役割</p>  
<p>この特権を誤って使用すると、FDP_ACF.1(a) セキュリティ属性によるアクセス制御に違反します。ユーザーが ACL の制限を回避できるようになるからです。</p>  
<p>以下の TOE セキュリティ機能を実装します。</p>  
<p>「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーに、システム内のセキュリティで保護可能な任意のオブジェクトを管理する能力を与えるために使用することができます。</p>  
<p><strong>変更</strong> :</p>
<p>この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理をサポートするようにします。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>読み取りを要求されていないデータのターミナル デバイスからの読み取り</p>
<p>(SeUnsolicited<br />  
Input<br />
Privilege)</p></td>
<td style="border:1px solid black;"><p>読み取りを要求されていないデータをターミナル デバイスからの読み取るために必要です。この特権は陳腐化しており、現在は使用されていません。システムに何の影響も及ぼしません。</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p><strong>既定</strong> :</p>
<p>なし</p>  
<p><strong>推奨する変更</strong> :</p>
<p>変更しない</p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
</tbody>  
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### 目次
  
-   [第 1 章 ‐ ハードウェアおよびソフトウェアの環境](https://technet.microsoft.com/ja-jp/library/da7603d8-d1d7-400a-9993-3ac61d633e66(v=TechNet.10))  
-   [第 2 章 ‐ オペレーティング システムのインストール](https://technet.microsoft.com/ja-jp/library/ddb614e6-9456-4f76-8dea-4018a51a810d(v=TechNet.10))  
-   [第 3 章 ‐ セキュリティで保護された構成](https://technet.microsoft.com/ja-jp/library/95fe8ebd-7386-4e95-aff8-5fca17435788(v=TechNet.10))  
-   [第 4 章 ‐ Windows 2000 Common Criteria (共通基準) セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/270098dc-f10b-41de-b26a-c2d795bca536(v=TechNet.10))  
-   [参考資料](https://technet.microsoft.com/ja-jp/library/6df170a9-3e6d-42d6-a4c3-0fd3eb71bf77(v=TechNet.10))  
-   [付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定](https://technet.microsoft.com/ja-jp/library/1adc2300-c9de-4ee0-bab7-9f8a797b03bc(v=TechNet.10))  
-   [付録 B ‐ 監査カテゴリとイベント](https://technet.microsoft.com/ja-jp/library/0fc077e8-8bf5-4b4d-a555-a8c26c9792f0(v=TechNet.10))  
-   付録 C ‐ ユーザー権利と特権  
-   [付録 D ‐ ユーザー アカウントとグループ アカウント](https://technet.microsoft.com/ja-jp/library/50b1a83f-d25a-4ffe-b601-3adc677fa632(v=TechNet.10))  
-   [付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト](https://technet.microsoft.com/ja-jp/library/b1327283-7a58-409a-9554-59e4bbc01374(v=TechNet.10))  
-   [付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/8842dd66-853c-4c8f-bb69-ae750f139356(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
