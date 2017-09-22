---
TOCTitle: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト'
Title: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト'
ms:assetid: 'b1327283-7a58-409a-9554-59e4bbc01374'
ms:contentKeyID: 19869614
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277462(v=TechNet.10)'
---

Microsoft Windows 2000 セキュリティ構成ガイド
=============================================

### 付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト

最終更新日: 2003年2月18日

![](images/Dd277462.scg00(ja-jp,TechNet.10).gif)

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>完了および検証済み</p></th>
<th><p>WINDOWS 2000 セキュリティ構成チェック リスト (設定は、別途注記されている以外の、すべてのオペレーティング システムのバージョンに当てはまります。)</p></th>
<th><p>必須</p></th>
<th><p>推奨</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong>ファイル システムの構成</strong></p>
<p><strong>セキュリティの目的:</strong> 評価されたセキュリティ機構を構成し、セキュリティ ターゲットの要件を遵守できるようにします。</p>
<p><strong>ファイル システムの種類: NTFS</strong></p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>アカウント ポリシー</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>パスワード ポリシー</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>パスワードの履歴を記録する</em></strong></p>
<p><strong>セキュリティの目的:</strong> パスワードを再利用する頻度に制限を設けます。</p>  
<p><strong>コンピュータの設定: _____ 個のパスワードを記録</strong></p>
<p>(推奨: 24 個のパスワードを記録します。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>パスワードの有効期間</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーがパスワードを変更せずに使い続けられる期間を設定します。</p>  
<p><strong>コンピュータの設定: _____ 日</strong></p>
<p>(推奨: 42 日)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>パスワードの変更禁止期間</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーがパスワードを変更せずに使い続けなければならない期間を設定します。</p>  
<p><strong>コンピュータの設定: _____ 日</strong></p>
<p>(推奨: 2 日)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>パスワードの長さ</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーのパスワードに必要な長さを設定します。</p>
<p>コンピュータの設定: 8 文字</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>パスワードは要求する複雑さを満たす</em></strong></p>
<p><strong>セキュリティの目的:</strong> 複雑 (強力) なパスワードを使用することを求めます。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 有効)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>暗号化を元に戻せる状態でドメインのすべてのユーザーのパスワードを保存する</em></strong></p>
<p><strong>セキュリティの目的:</strong> 有効にしてはなりません。パスワードに関しては暗号強度の弱い暗号化を用います。</p>
<p>コンピュータの設定: 無効</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>アカウント ロックアウト ポリシー</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ロックアウト期間</em></strong></p>
<p><strong>セキュリティの目的:</strong> 無効なパスワードの使用が試みられた後、指定された期間にわたってアカウントをロックアウトします。</p>  
<p><strong>コンピュータの設定: _____ 分</strong></p>
<p>(ST ではこの設定を必要としますが、期間は定められていません。0 に設定するよう推奨します。その場合、管理者がアカウントのロックを解除する必要があります。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>アカウントのロックアウトのしきい値</em></strong></p>
<p><strong>セキュリティの目的:</strong> 無効なログインの試みが何回行われたらアカウントをロックするかを設定します。</p>  
<p><strong>コンピュータの設定: _____ 回の無効なログインの試み</strong></p>
<p>(ST ではこの設定を必要とし、5 を超える値を設定してはならないと指定されています。この値を 5 回に設定するよう推奨します。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ロックアウト カウントのリセット</em></strong></p>
<p><strong>セキュリティの目的:</strong> ロックアウトしきい値を何分間維持した後にリセットするかを設定します。</p>  
<p><strong>コンピュータの設定: _____ 分</strong></p>
<p>(上記の ２ つのポリシー値を設定した場合、この値も設定しなければなりません。推奨する設定値は 30 分です。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>Kerberos ポリシー</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ユーザー ログオンの制限を強制する</em></strong></p>
<p><strong>セキュリティの目的:</strong> すべてのログオン要求をユーザー権利のポリシーに照らして検証します。</p>
<p>コンピュータの設定: 既定の設定 (有効) のままにします。</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>サービス チケットの最長有効期間</em></strong></p>
<p><strong>セキュリティの目的:</strong> サービス チケットが有効な最長の期間を設定します。</p>  
<p><strong>コンピュータの設定: _____ 分</strong></p>
<p>(既定の設定のままとするよう推奨します。ドメインのメンバの場合は 600 分、ドメインのメンバでないコンピュータの場合は 60 分です。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>チケットの最長有効期間</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザー チケットが有効な最長の期間を設定します。</p>  
<p><strong>コンピュータの設定: _____ 時間</strong></p>
<p>(既定の設定のままとするよう推奨します。ドメインのメンバの場合は 10 時間、ドメインのメンバでないコンピュータの場合は 7 時間です。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ユーザー チケットを更新できる最長有効期間</em></strong></p>
<p><strong>セキュリティの目的:</strong> 有効期限が切れたユーザー チケットを更新できる期間を設定します。</p>  
<p><strong>コンピュータの設定: _____ 日</strong></p>
<p>(既定の設定のままとするよう推奨します。ドメインのメンバの場合は 7 日、ドメインのメンバでないコンピュータの場合は 10 日です。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>コンピュータの時計の同期の最長トレランス</em></strong></p>
<p><strong>セキュリティの目的:</strong> ドメイン内のコンピュータ間の同期の最長のトレランスを設定します。</p>
<p><strong>コンピュータの設定: 既定の設定 (ドメインのメンバの場合は 5 分、ドメインのメンバでないコンピュータの場合は 60 分) のままとします</strong> :</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>ローカル ポリシー</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>監査ポリシー</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>アカウント ログオン イベントの監査</em></strong></p>
<p><strong>セキュリティの目的:</strong> アカウントを検証するためにこのコンピュータが使用された、他のコンピュータからのアカウントへのログオン/ログオフのイベントを監査します。アカウントへのログオン イベントはアカウントが実在する場所で生成されます。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 成功   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 失敗</p>
<p>(推奨: 成功、失敗)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>アカウント管理の監査</em></strong></p>
<p><strong>セキュリティの目的:</strong> アカウント管理活動を監査します。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 成功   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 失敗</p>
<p>(推奨: 成功、失敗)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ディレクトリ サービスのアクセスの監査</em></strong></p>
<p><strong>セキュリティの目的:</strong> 独自のシステム アクセス制御リストが指定されている、Active Directory オブジェクトへのアクセスを監査します。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 成功   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 失敗</p>
<p>(推奨: 成功、失敗)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ログオン イベントの監査</em></strong></p>
<p><strong>セキュリティの目的:</strong> コンピュータに対するローカルまたはネットワークを通じたログオン/ログオフのイベントを監査します。ログオン イベントはログオンの試みがなされた場所で生成されます。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 成功   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 失敗</p>
<p>(推奨: 成功、失敗)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>オブジェクト アクセスの監査</em></strong></p>
<p><strong>セキュリティの目的:</strong> 独自のシステム アクセス制御リストが指定されている、オブジェクト (ファイル、フォルダ、レジストリ キー、プリンタなど) へのアクセスを監査します。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 成功   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 失敗</p>
<p>(推奨: 成功、失敗)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ポリシーの変更の監査</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザー権利の割り当てポリシー、監査ポリシー、信頼ポリシーの変更を監査します。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 成功   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 失敗</p>
<p>(推奨: 成功)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>特権使用の監査</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーが権利を行使した各インスタンスを監査します。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 成功   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 失敗</p>
<p>(推奨: 成功、失敗)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>プロセス追跡の監査</em></strong></p>
<p><strong>セキュリティの目的:</strong> 詳細な追跡情報を監査します。具体的には、プログラムの起動、プロセスの終了、重複の処理、間接オブジェクト アクセスなどを対象とします。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 成功   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 失敗</p>
<p>(推奨: 成功、失敗)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>システム イベントの監査</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーがコンピュータを再起動またはシャットダウンしたとき、またはシステムのセキュリティまたはセキュリティ ログに影響を及ぼすイベントが発生したときに監査します。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 成功   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 失敗</p>
<p>(推奨: 成功)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>ユーザーの権利の割り当て</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ネットワーク経由でコンピュータへアクセス</em></strong></p>
<p><strong>セキュリティの目的:</strong> ネットワークを経由してコンピュータに接続することを許可するユーザーを設定します。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg01(ja-jp,TechNet.10).gif" /></p>
<p>(ドメイン ポリシーにおいて Windows 2000 Professional および Server 用に示されているように設定します。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>オペレーティング システムの一部として機能</em></strong></p>
<p><strong>セキュリティの目的:</strong> プロセスがユーザーとして認証されるようにして、ユーザーと同じリソースにアクセスできるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ドメインにワークステーションを追加 (ドメイン コントローラ)</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーがドメインにコンピュータを追加できるようにします。</p>
<p>コンピュータの設定: Authenticated Users アカウントを削除します。この特権を他のアカウントに割り当ててはいけません。既定では、Domain Admins にこの特権が与えられています。</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ファイルとディレクトリのバックアップ</em></strong></p>
<p><strong>セキュリティの目的:</strong> システムをバックアップするために、ファイルおよびディレクトリへのアクセス許可をユーザーが回避できるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>走査チェックのバイパス</em></strong></p>
<p><strong>セキュリティの目的:</strong> フォルダのパスを辿っていく際に、アクセスする権限のないフォルダをユーザーが通過するようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>システム時刻の変更</em></strong></p>
<p><strong>セキュリティの目的:</strong> コンピュータ内蔵の時計の時刻をユーザーが設定できるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ページ ファイルの作成</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーがページ ファイルを作成してサイズを変更できるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>トークン オブジェクトの作成</em></strong></p>
<p><strong>セキュリティの目的:</strong> プロセスがアクセス トークンを作成できるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>永続的共有オブジェクトの作成</em></strong></p>
<p><strong>セキュリティの目的:</strong> Windows 2000 のオブジェクト マネージャ内に、プロセスがディレクトリ オブジェクトを作成できるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>プログラムのデバッグ</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーが任意のプロセスにデバッガを添付できるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ネットワーク経由でコンピュータへアクセスを拒否する</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーまたはグループがネットワークを通じてこのコンピュータに接続することを禁止します。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>バッチ ジョブとしてログオンを拒否する</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーまたはグループがバッチ キュー機能を使用してログオンすることを禁止します。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>サービスとしてログオンを拒否する</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーまたはグループがサービスとしてログオンすることを禁止します。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ローカルでログオンを拒否する</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーまたはグループがキーボードからローカルにログオンすることを禁止します。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>コンピュータとユーザー アカウントに委任時の信頼を付与</em></strong></p>
<p><strong>セキュリティの目的:</strong> Active Directory 内のユーザーまたはコンピュータに関する委任に対する信頼の設定をユーザーが変更できるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>リモート コンピュータからの強制シャットダウン</em></strong></p>
<p><strong>セキュリティの目的:</strong> ネットワーク上のリモート ロケーションからユーザーがコンピュータをシャットダウンできるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>セキュリティ監査の生成</em></strong></p>
<p><strong>セキュリティの目的:</strong> プロセスがセキュリティ ログ中にエントリを生成できるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>クォータの増加</em></strong></p>
<p><strong>セキュリティの目的:</strong> 他のプロセスに対するプロパティの書き込み許可を得ているプロセスが、他のプロセスに割り当てられているプロセッサのクォータを増やせるようにします。</p>  
<p><strong>コンピュータの設定: 既定の割り当て先: Administrators を変更してはいけません</strong> :</p>
<p>(ドメイン ポリシーにおいては、Administrators のみに割り当てます。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>スケジューリング優先順位の繰り上げ</em></strong></p>
<p><strong>セキュリティの目的:</strong> 他のプロセスに対するプロパティの書き込み許可を得ているプロセスが、他のプロセスの実行優先度を上げられるようにします。</p>  
<p><strong>コンピュータの設定: 既定の割り当て先: Administrators を変更してはいけません</strong> :</p>
<p>(ドメイン ポリシーにおいては、Administrators のみに割り当てます。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>デバイス ドライバのロードとアンロード</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーがプラグ アンド プレイ方式のデバイス ドライバをインストールおよびアンインストールできるようにします。</p>  
<p><strong>コンピュータの設定: 既定の割り当て先: Administrators を変更してはいけません</strong> :</p>
<p>(ドメイン ポリシーにおいては、Administrators のみに割り当てます。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>メモリ中のページのロック</em></strong></p>
<p><strong>セキュリティの目的:</strong> プロセスがデータを物理メモリ内に保持し、ディスク上の仮想メモリにデータがページングされることのないようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>バッチ ジョブとしてログオン</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーがバッチ キュー機能を使用してログオンできるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>サービスとしてログオン</em></strong></p>
<p><strong>セキュリティの目的:</strong> セキュリティ プリンシパルがサービスとしてログオンできるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ローカル ログオン</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーがコンピュータのキーボードからローカル ログオンできるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg03(ja-jp,TechNet.10).gif" /></p>
<p>(ドメイン ポリシーにおいて、Windows 2000 Professional および Server 用に示されているように設定します。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>監査とセキュリティ ログの管理</em></strong></p>
<p><strong>セキュリティの目的:</strong> ファイル、Active Directory オブジェクト、レジストリ キーのような個々のリソースに関して、ユーザーがオブジェクト アクセス監査オプションを指定できるようにします。</p>  
<p><strong>コンピュータの設定: 既定の割り当て先: Administrators を変更してはいけません</strong> :</p>
<p>(ドメイン ポリシーにおいては、Administrators のみに割り当てます。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ファームウェア環境値の修正</em></strong></p>
<p><strong>セキュリティの目的:</strong> システム環境変数を修正できるようにします。修正方法は 2 通りあります。API を通じてプロセスに行わせる方法と、システム プロパティ アプレットを通じてユーザーが行う方法があります。</p>  
<p><strong>コンピュータの設定: 既定の割り当て先: Administrators を変更してはいけません</strong> :</p>
<p>(ドメイン ポリシーにおいては、Administrators のみに割り当てます。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>単一プロセスのプロファイル</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーが Microsoft Windows NT および Windows 2000 のパフォーマンス モニタ ツールを使用して、システム プロセス以外のプロセスのパフォーマンスを監視できるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>システム パフォーマンスのプロファイル</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーが Microsoft Windows NT および Windows 2000 のパフォーマンス モニタ ツールを使用して、システム プロセスのパフォーマンスを監視できるようにします。</p>  
<p><strong>コンピュータの設定: 既定の割り当て先: Administrators を変更してはいけません</strong> :</p>
<p>(ドメイン ポリシーにおいては、Administrators のみに割り当てます。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ドッキング ステーションからコンピュータを削除</em></strong></p>
<p><strong>セキュリティの目的:</strong> ポータブル コンピュータのユーザーが [スタート] メニューの [PCの取り外し] をクリックすることにより、コンピュータのロックを解除できるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>プロセス レベル トークンの置き換え</em></strong></p>
<p><strong>セキュリティの目的:</strong> 親プロセスが子プロセスに関連するアクセス トークンを置き換えられるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ファイルとディレクトリの復元</em></strong></p>
<p><strong>セキュリティの目的:</strong> バックアップからファイルを復元するときに、ファイルおよびディレクトリへのアクセス許可をユーザーが回避して、オブジェクトの所有者としての有効なセキュリティ プリンシパルを設定できるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>システムのシャットダウン</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーがローカル コンピュータをシャットダウンできるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: Windows 2000 Professional では、Administrators、Authenticated Users、Backup Operators、Power Users に割り当てます。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ディレクトリ サービス データの同期化</em></strong></p>
<p><strong>セキュリティの目的:</strong> ディレクトリの同期を取るサービスを行えるようにします。</p>  
<p><strong>コンピュータの設定: 割り当て先:</strong></p>  
<p><img src="images/Dd277462.scg02(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 既定の設定のままとします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ファイルとその他のオブジェクトの所有権の取得</em></strong></p>
<p><strong>セキュリティの目的:</strong> システム内のセキュリティで保護可能な任意のオブジェクトの所有権をユーザーが取得できるようにします。</p>  
<p><strong>コンピュータの設定: 既定の割り当て先: Administrators を変更してはいけません</strong> :</p>
<p>(ドメイン ポリシーにおいては、Administrators のみに割り当てます。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>セキュリティ オプション</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>匿名接続の追加を制限する</em></strong></p>
<p><strong>セキュリティの目的:</strong> コンピュータへの匿名の接続に関する制限を設定します。</p>
<p>コンピュータの設定: SAM アカウントおよび共有リソースの列挙を許可してはいけません。</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>サーバー オペレータがタスクのスケジュールを割り当てるのを許可する (ドメイン コントローラのみ)</em></strong></p>
<p><strong>セキュリティの目的:</strong> サーバー オペレータが AT スケジュール機能を用いてジョブを投入することを許可するかどうかを設定します。</p>  
<p><strong>コンピュータの設定: 無効</strong></p>
<p>(AT スケジュール機能は評価された構成の一部ではありません。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>システムをシャットダウンするのにログオンを必要としない</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーがログオンせずにコンピュータをシャットダウンできるようにします。</p>
<p>コンピュータの設定: 無効</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>リムーバブル NTFS メディアを取り出すのを許可する</em></strong></p>
<p><strong>セキュリティの目的:</strong> コンピュータからリムーバブル NTFS メディアを取り出す許可をアカウントに与えるように設定します。</p>  
<p><strong>コンピュータの設定: ポリシー中に定義されているアカウント: _________________________</strong></p>
<p>(推奨: Administrators)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>セッションを切断する前に、ある一定のアイドル時間を必要とする</em></strong></p>
<p><strong>セキュリティの目的:</strong> サーバー メッセージ ブロック (SMB) セッションにおいて、アイドル状態が何分間続いたらセッションを切断するかを設定します。</p>  
<p><strong>コンピュータの設定: _____ 分</strong></p>
<p>(推奨: 既定の設定の 15 分を変更してはいけません。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>グローバル システム オブジェクトへのアクセスを監査する</em></strong></p>
<p><strong>セキュリティの目的:</strong> グローバル システム オブジェクトへのアクセスを監査できるようにします。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 厳格な監査管理プロセスが用意されている場合にのみ、有効にします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>バックアップと復元の特権の使用を監査する</em></strong></p>
<p><strong>セキュリティの目的:</strong> バックアップと復元のユーザー権利を監査できるようにします。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 厳格な監査管理プロセスが用意されている場合にのみ、有効にします。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ログオン時間を経過した場合は自動的にユーザーをログオフする</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、ユーザー アカウントの有効なログオン時間を超えてローカル コンピュータに接続しているユーザーの接続が切断されます。DC 上でのみ設定することができます。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 有効)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ログオン時間が時間切れになった場合、自動的にユーザーをログオフする (ローカル)</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、ユーザー アカウントの有効なログオン時間を超えてローカル コンピュータに接続しているユーザーの接続が切断されます。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 有効)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>システムのシャットダウン時に仮想メモリのページ ファイルをクリアする</em></strong></p>
<p><strong>セキュリティの目的:</strong> システムがシャットダウンされるときに、仮想メモリのページ ファイルをクリアするかどうかを設定します。</p>
<p>コンピュータの設定: 有効</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>常にクライアント側の通信にデジタル署名を行う</em></strong></p>
<p><strong>セキュリティの目的:</strong> クライアント側の通信に常にデジタル署名を行うかどうかを設定します</p>
<p>コンピュータの設定: 無効</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>可能な場合、クライアントの通信にデジタル署名を行う</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、SMB パケット署名を行うことが有効または必要となっている SMB サーバーと通信するときのみ、SMB クライアントにより SMB パケット署名が行われます。</p>
<p>コンピュータの設定: 有効</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>常にサーバーの通信にデジタル署名を行う</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、SMB サーバーは SMB パケットに署名する必要があります。</p>
<p>コンピュータの設定: 無効</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>可能な場合、サーバーの通信にデジタル署名を行う</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、SMB サーバーは必要なときに SMB パケットに署名を行います。</p>
<p>コンピュータの設定: 有効</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ログオンに Ctrl+Alt+Del を必要としない</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーがログオンする前に、 Ctrl+Alt+Del キーを押す必要があるかどうかを設定します。</p>  
<p><strong>コンピュータの設定: 無効</strong></p>
<p>(「無効」に設定しても、実際には Ctrl+Alt+Del の使用が有効/必要になります。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ログオン画面に最後のユーザー名を表示しない</em></strong></p>
<p><strong>セキュリティの目的:</strong> コンピュータに前回ログインしたユーザーの名前を Windows ログオン画面に表示するかどうかを設定します。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 有効)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>LAN Manager 認証レベル</em></strong></p>
<p><strong>セキュリティの目的:</strong> ネットワーク ログオンにどのチャレンジ/レスポンス認証プロトコルを使用するかを設定します。</p>  
<p><strong>コンピュータの設定: 選択されたオプション: _______________________________________</strong></p>
<p>(推奨: SNTLMv2 応答のみ送信する/LM と NTLM を拒否する)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ログオン時のユーザーへのメッセージのテキスト</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーがログオンするときに示されるテキスト メッセージを指定します。</p>  
<p><strong>コンピュータの設定: メッセージ テキスト: __________________________________________________</strong></p>  
<p><strong>__________________________________________________</strong></p>  
<p><strong>__________________________________________________</strong></p>  
<p><strong>__________________________________________________</strong></p>  
<p><strong>__________</strong></p>
<p>(推奨: ローカル ポリシーの要件に応じて、警告内容を設定します。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ログオン時のユーザーへのメッセージのタイトル</em></strong></p>
<p><strong>セキュリティの目的:</strong> ログオンしようとしているユーザーに向けたメッセージ テキストが示されているウィンドウのタイトル バーに表示するタイトルを指定します。</p>  
<p><strong>コンピュータの設定: メッセージ タイトル: _________________________________________</strong></p>
<p>(推奨: ローカル ポリシーの要件に応じて、警告内容を設定します。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ドメイン コントローラが利用できない場合に使用する、前回ログオンのキャッシュ数</em></strong></p>
<p><strong>セキュリティの目的:</strong> キャッシュ化されているアカウント情報を使用して、ユーザーが Windows ドメインにログオンできる回数を設定します。</p>
<p>コンピュータの設定: キャッシュ: 0 回</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>コンピュータ アカウント パスワードのシステム保守をしない</em></strong></p>
<p><strong>セキュリティの目的:</strong> コンピュータ アカウント パスワードを毎週リセットしないようにするかどうかを設定します。このポリシーを有効にすると、毎週パスワードの変更が求められることはなくなります。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   t src=&quot;/japan/technet/security/prodtech/windows2000/w2kccscg/images/box.gif&quot; alt=&quot;box&quot; /&gt; 無効</p>
<p>(推奨: ローカル ポリシーは既定どおり無効に設定されており、ドメイン ポリシーは無効に設定されているかまたは未定義であることを確認します。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ユーザーがプリンタ ドライバをインストールできないようにする</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザー グループのメンバがプリンタ ドライバをインストールできないようにするかどうかを設定します。</p>
<p>コンピュータの設定: 有効</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>パスワードが無効になる前にユーザーに変更を促す</em></strong></p>
<p><strong>セキュリティの目的:</strong> ユーザーのパスワードの有効期限が切れる何日前にユーザーに警告するかを設定します。</p>  
<p><strong>コンピュータの設定: _____ 日</strong></p>
<p>(推奨: 既定値の 14 日が適切です。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>回復コンソール: 自動管理ログオンを許可する</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、パスワードを必要とせずに、回復コンソールから自動的にシステムにログオンします。</p>  
<p><strong>コンピュータの設定: 無効</strong></p>
<p>(回復コンソールは評価された構成の一部ではありません。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>回復コンソール: すべてのドライブとフォルダに、フロッピーのコピーとアクセスを許可する</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、回復コンソールの SET コマンドを使用できるようになります。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: このオプションを有効にしてはなりません。回復コンソールは評価された構成の一部ではありません。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>Administrator アカウント名の変更</em></strong></p>
<p><strong>セキュリティの目的:</strong> Administrator アカウントのセキュリティ識別子 (SID) に別のアカウント名を関連付けます。</p>  
<p><strong>コンピュータの設定:</strong></p>
<p>(推奨: 記録されているアカウント名を変更して、安全にしまっておきます。それをここに記してはなりません。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>Guest アカウント名の変更</em></strong></p>
<p><strong>セキュリティの目的:</strong> Guest アカウントのセキュリティ識別子 (SID) に別のアカウント名を関連付けます。</p>  
<p><strong>コンピュータの設定:</strong></p>
<p>(推奨: 記録されているアカウント名を変更して、安全にしまっておきます。それをここに記してはなりません。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>CD-ROM へのアクセスを、ローカル ログオン ユーザーだけに制限する</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、対話型でログオンしたユーザーだけがリムーバブル CD-ROM メディアにアクセスできるようになります。</p>
<p>コンピュータの設定: 有効</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>フロッピーへのアクセスを、ローカル ログオン ユーザーだけに制限する</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、対話型でログオンしたユーザーだけがリムーバブル フロッピー メディアにアクセスできるようになります。</p>
<p>コンピュータの設定: 有効</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>セキュリティで保護されたチャネル: 常にセキュリティ チャネルのデータをデジタル的に暗号化または署名する</em></strong></p>
<p><strong>セキュリティの目的:</strong> このポリシーを有効にすると、セキュリティで保護されたチャネルを通じて発信されるトラフィックはすべて署名または暗号化されます。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 既定では、このオプションは無効に設定されています。既定の設定を変更してはいけません。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>セキュリティで保護されたチャネル: 可能な場合、セキュリティ チャネルのデータをデジタル的に暗号化または署名する</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、セキュリティで保護されたチャネルを通じて発信されるトラフィックはすべて暗号化されます。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 既定では、このオプションは有効に設定されています。既定の設定を変更してはいけません。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>セキュリティで保護されたチャネル: 可能な場合、セキュリティ チャネルのデータをデジタル的に署名する</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、セキュリティで保護されたチャネルを通じて発信されるトラフィックはすべて署名されます。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 既定では、このオプションは有効に設定されています。既定の設定を変更してはいけません。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>セキュリティで保護されたチャネル: 強力な (Windows 2000 かそれ以降のバージョン) セッション キーを必要とする</em></strong></p>
<p><strong>セキュリティの目的:</strong> このポリシーを有効にすると、セキュリティで保護されたチャネルを通じて発信されるすべてのトラフィックは強力な (Windows 2000 かそれ以降のバージョン) 暗号化キーを必要とします。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 既定では、このオプションは無効に設定されています。通常は既定の設定を変更しません。このオプションを有効にするのは、信頼される側のドメイン内の「すべての」ドメイン コントローラで強力なキーがサポートされている場合のみとすべきです。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>システム パーティションの保護 (RISC プラットフォームのみ)</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、オペレーティング システムが稼働している間は、RISC ベースのシステム パーティション (FAT でなければいけません) に対して管理的アクセスのみが許可されます。</p>  
<p><strong>コンピュータの設定: 未定義</strong></p>
<p>(このポリシーは評価された構成には当てはまりません。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>サード パーティ製の SMB サーバーへ接続するためのパスワードを、暗号化しないで送信する</em></strong></p>
<p><strong>セキュリティの目的:</strong> このポリシーを有効にすると、SMB リダイレクタは、認証中にパスワードを暗号化することがサポートされていない非マイクロソフト SMB サーバーに、クリアテキストのパスワードを送信できるようになります。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 既定では、このオプションは無効に設定されています。既定の設定を変更してはいけません。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>セキュリティ監査のログを記録できない場合は直ちにシステムをシャットダウンする</em></strong></p>
<p><strong>セキュリティの目的:</strong> セキュリティ イベントのログを記録できない場合に、システムを直ちにシャットダウンするかどうかを設定します。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>  
<p>注意: 監査ログを定期的にアーカイブおよびクリアする厳格な手続きを導入した後でのみ、サーバーおよびドメイン コントローラ上で、このセキュリティ ポリシーを使用すべきです。</p>
<p>(推奨: 有効。ログを定期的にアーカイブおよびクリアする必要があります。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>スマート カード取り出し時の動作</em></strong></p>
<p><strong>セキュリティの目的:</strong> ログオンしたユーザーのスマート カードがスマート カード読み取り装置から取り出されたときの対応措置を設定します。</p>  
<p><strong>コンピュータの設定: __________________________________________</strong></p>
<p>(推奨: スマート カードを使用する場合、[ワークステーションをロックする] に設定します。ただし、スマート カード テクノロジを組み込むことは、評価された構成の一部ではありません。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>グローバル システム オブジェクトの既定のアクセス許可を強化する (例: シンボリック リンク)</em></strong></p>
<p><strong>セキュリティの目的:</strong> このポリシーを有効にすると、既定の DACL が強化されます。それにより、管理者でないユーザーが共有オブジェクトを読むことができるようになりますが、自分が作成したのではない共有オブジェクトを修正することはできません。</p>
<p>コンピュータの設定: 有効</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>署名されていないドライバのインストール時の動作</em></strong></p>
<p><strong>セキュリティの目的:</strong> Windows ハードウェア品質研究所によって検証されていないデバイス ドライバをインストールする試みがなされたときの対応措置を設定します。</p>  
<p><strong>コンピュータの設定: __________________________________________</strong></p>
<p>(推奨: [警告するがインストールは許可する] に設定します。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>署名されていないドライバ以外のインストール時の動作</em></strong></p>
<p><strong>セキュリティの目的:</strong> デバイス ドライバ以外の未検証のソフトウェアをインストールする試みがなされたときの対応措置を設定します。</p>  
<p><strong>コンピュータの設定: __________________________________________</strong></p>
<p>(推奨: [警告するがインストールは許可する] に設定します。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>イベント ログ</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>イベント ログの設定</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>アプリケーション ログの最大サイズ</em></strong></p>
<p><strong>セキュリティの目的:</strong> アプリケーション イベント ログの最大サイズを設定します。</p>  
<p><strong>コンピュータの設定: ______________ キロバイト</strong></p>
<p>(推奨: ほとんどの環境において、既定値の 512 キロバイトが適切です。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>セキュリティ ログの最大サイズ</em></strong></p>
<p><strong>セキュリティの目的:</strong> セキュリティ イベント ログの最大サイズを設定します。</p>  
<p><strong>コンピュータの設定: ______________ キロバイト</strong></p>
<p>(推奨: 予想される活動量、利用可能なディスクの空き領域、およびログを手作業でレビュー、アーカイブ、クリアする頻度に基づいて、なるべく大きなログ サイズを設定すべきです。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>システム ログの最大サイズ</em></strong></p>
<p><strong>セキュリティの目的:</strong> システム イベント ログの最大サイズを設定します。</p>  
<p><strong>コンピュータの設定: ______________ キロバイト</strong></p>
<p>(推奨: ほとんどの環境において、既定値の 512 キロバイトが適切です。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>アプリケーション ログのゲスト アクセスの制限</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、匿名ユーザーはアプリケーション イベント ログにアクセスできなくなります。このポリシー オプションはスタンドアロンの Windows 2000 Professional および Server では利用できません。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 有効)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>セキュリティ ログのゲスト アクセスの制限</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、匿名ユーザーはセキュリティ イベント ログにアクセスできなくなります。このポリシー オプションはスタンドアロンの Windows 2000 Professional および Server では利用できません。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 有効)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>システム ログのゲスト アクセスの制限</em></strong></p>
<p><strong>セキュリティの目的:</strong> このオプションを有効にすると、匿名ユーザーはシステム イベント ログにアクセスできなくなります。このポリシー オプションはスタンドアロンの Windows 2000 Professional および Server では利用できません。</p>  
<p><strong>コンピュータの設定:</strong></p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 有効   <img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> 無効</p>
<p>(推奨: 有効)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>アプリケーション ログの保存日数</em></strong></p>
<p><strong>セキュリティの目的:</strong> アプリケーション ログの保存方法が「指定した日数」である場合に、イベントをアプリケーション ログに保存しておくべく日数を設定します。</p>  
<p><strong>コンピュータの設定: _____ 日</strong></p>
<p>(推奨: 既定の設定 (7 日) を変更してはいけません。既定値は、ドメイン ポリシーおよびドメイン コントローラ ポリシーに関しては未定義であり、ログ プロパティにおいては 7 日です。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>セキュリティ ログの保存日数</em></strong></p>
<p><strong>セキュリティの目的:</strong> セキュリティ ログの保存方法が「指定した日数」である場合に、イベントをセキュリティ ログに保存しておくべく日数を設定します。</p>  
<p><strong>コンピュータの設定: _____ 日</strong></p>
<p>(推奨: 既定の設定 (7 日) を変更してはいけません。既定値は、ドメイン ポリシーおよびドメイン コントローラ ポリシーに関しては未定義であり、ログ プロパティにおいては 7 日です。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>システム ログの保存日数</em></strong></p>
<p><strong>セキュリティの目的:</strong> システム ログの保存方法が「指定した日数」である場合に、イベントをシステム ログに保存しておくべく日数を設定します。</p>  
<p><strong>コンピュータの設定: _____ 日</strong></p>
<p>(推奨: 既定の設定 (7 日) を変更してはいけません。既定値は、ドメイン ポリシーおよびドメイン コントローラ ポリシーに関しては未定義であり、ログ プロパティにおいては 7 日です。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>アプリケーション ログの保存方法</em></strong></p>
<p><strong>セキュリティの目的:</strong> アプリケーション ログの保存方法を設定します。</p>  
<p><strong>コンピュータの設定: _____________________________________________________</strong></p>
<p>(推奨: 既定の設定 (7 日) を変更してはいけません。既定値は、ドメイン ポリシーおよびドメイン コントローラ ポリシーに関しては未定義であり、ログ プロパティにおいては 7 日です。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>セキュリティ ログの保存方法</em></strong></p>
<p><strong>セキュリティの目的:</strong> セキュリティ ログの保存方法を設定します。</p>  
<p><strong>コンピュータの設定: _____________________________________________________</strong></p>
<p>(推奨: 既定の設定 (7 日) を変更してはいけません。既定値は、ドメイン ポリシーおよびドメイン コントローラ ポリシーに関しては未定義であり、ログ プロパティにおいては 7 日です。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>システム ログの保存方法</em></strong></p>
<p><strong>セキュリティの目的:</strong> システム ログの保存方法を設定します</p>  
<p><strong>コンピュータの設定: _____________________________________________________</strong></p>
<p>(推奨: 既定の設定 (7 日) を変更してはいけません。既定値は、ドメイン ポリシーおよびドメイン コントローラ ポリシーに関しては未定義であり、ログ プロパティにおいては 7 日です。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>セキュリティの監査ログがいっぱいになったら、コンピュータをシャットダウンする</em></strong></p>
<p><strong>セキュリティの目的:</strong> このポリシーを設定する代りに、[セキュリティ監査のログを記録できない場合は直ちにシステムをシャットダウンする] を使用してください。</p>  
<p><strong>コンピュータの設定:</strong></p>
<p>(推奨: 「未定義」に設定されています。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>システム サービス</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>評価されたサービス</em></strong></p>
<p><strong>セキュリティの目的:</strong> 評価された構成を保つためには、下に列挙するすべてのサービスを有効にして稼働させても構いません。</p>  
<p><img src="images/Dd277462.scg04(ja-jp,TechNet.10).gif" /></p>
<p>(推奨: 上に列挙されている評価されたサービスを無効にしてはいけません。既定の設定が適切です。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>非評価されたサービス</em></strong></p>
<p><strong>セキュリティの目的:</strong> 下に列挙する既定のサービスは評価された構成には受け入れられないので、無効にしなければいけません。</p>  
<p><img src="images/Dd277462.scg05(ja-jp,TechNet.10).gif" /></p>
<p>(<strong>注意:</strong> 評価されたサービスと明示されていないその他のサービスも無効にしなければいけません。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>レジストリへのアクセス許可</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>HKEY_LOCAL_MACHINE</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SOFTWARE</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)</p>  
<p><strong>Power Users:</strong> 特殊 (読み取り、書き込み、削除)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り</p>  
<p><strong>継承メソッド:</strong> 伝達</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SOFTWARE\classes</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p>Authenticated Users: 読み取り</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)</p>  
<p><strong>Power Users:</strong> 特殊 (読み取り、書き込み、削除)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り</p>
<p><strong>継承メソッド:</strong> 伝達</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SOFTWARE\classes\.hlp</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p>Authenticated Users: 読み取り</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)</p>  
<p><strong>Power Users:</strong> 特殊 (読み取り、書き込み、削除)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り</p>  
<p><strong>継承メソッド:</strong> 伝達</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SOFTWARE\classes\helpfile</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p>Authenticated Users: 読み取り</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)</p>  
<p><strong>Power Users:</strong> 特殊 (読み取り、書き込み、削除)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り</p>
<p><strong>継承メソッド:</strong> 伝達</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SOFTWARE\Microsoft\OS/2 Subsystem for NT</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>継承メソッド:</strong> 伝達</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SOFTWARE\Microsoft\Windows NT \CurrentVersion</p>  
<p><strong>Authenticated Users:</strong> 読み取り</p>  
<p><strong>継承メソッド:</strong> 伝達</p>
<p><strong>注意:</strong> Eveyone を Authenticated Users で置き換えます。継承された ACL はすべて残ります。</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SYSTEM\CurrentControlSet\Control \ComputerName</p>
<p><strong>Authenticated Users:</strong> 読み取り</p>  
<p><strong>継承メソッド:</strong> 伝達</p>  
<p><strong>注意:</strong> Eveyone を Authenticated Users で置き換えます。継承された ACL はすべて残ります。</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SYSTEM\currentcontrolset\control \ContentIndex</p>  
<p><strong>Authenticated Users:</strong> 読み取り</p>  
<p><strong>継承メソッド:</strong> 伝達</p>
<p><strong>注意:</strong> Eveyone を Authenticated Users で置き換えます。継承された ACL はすべて残ります。</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SYSTEM\CurrentControlSet\Control \Keyboard Layout</p>
<p><strong>Authenticated Users:</strong> 読み取り</p>  
<p><strong>継承メソッド:</strong> 伝達</p>  
<p><strong>注意:</strong> Eveyone を Authenticated Users で置き換えます。継承された ACL はすべて残ります。</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SYSTEM\CurrentControlSet\Control \Keyboard Layouts</p>  
<p><strong>Authenticated Users:</strong> 読み取り</p>  
<p><strong>継承メソッド:</strong> 伝達</p>
<p><strong>注意:</strong> Eveyone を Authenticated Users で置き換えます。継承された ACL はすべて残ります。</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SYSTEM\CurrentControlSet\Control \Print\Printers</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>Authenticated Users:</strong> 読み取り</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)</p>  
<p><strong>Power Users:</strong> 特殊 (読み取り、書き込み、削除)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><strong>注意:</strong> 継承を削除して、すべての ACL を置き換えます。</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SYSTEM\CurrentControlSet\Control \ProductOptions</p>  
<p><strong>Authenticated Users:</strong> 読み取り</p>  
<p><strong>継承メソッド:</strong> 伝達</p>
<p><strong>注意:</strong> Eveyone を Authenticated Users で置き換えます。継承された ACL はすべて残ります。</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SYSTEM\CurrentControlSet\Services \Eventlog</p>
<p><strong>Authenticated Users:</strong> 読み取り</p>  
<p><strong>継承メソッド:</strong> 伝達</p>  
<p><strong>注意:</strong> Eveyone を Authenticated Users で置き換えます。継承された ACL はすべて残ります。 .</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \SYSTEM\CurrentControlSet\Services \Tcpip</p>  
<p><strong>Authenticated Users:</strong> 読み取り</p>  
<p><strong>継承メソッド:</strong> 伝達</p>
<p><strong>注意:</strong> Eveyone を Authenticated Users で置き換えます。継承された ACL はすべて残ります。</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p>HKEY_CLASSES_ROOT</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> \HKEY_CLASSES_ROOT</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>Authenticated Users:</strong> 読み取り</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)</p>  
<p><strong>Power Users:</strong> 特殊 (読み取り、書き込み、削除)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り</p>
<p><strong>継承メソッド:</strong> 伝達</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>ファイル システムへのアクセス許可</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> C:\autoexec.bat</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> C:\boot.ini</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> C:\config.sys</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> C:\ntbootdd.sys</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><strong>注意:</strong> SCSI が利用可能なときに使用します。</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> C:\ntdetect.com</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> C:\ntldr</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %ProgramFiles%</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p>(サブフォルダおよびファイル)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p>(サブフォルダおよびファイル)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\appmgmt</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>
<p><strong>継承メソッド:</strong> 伝達</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\config</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\dllcache</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\DTCLog</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p>(サブフォルダおよびファイル)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>  
<p><strong>継承メソッド:</strong> 伝達</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\GroupPolicy</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>Authenticated Users:</strong> 読み取り、実行</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>
<p><strong>継承メソッド:</strong> 伝達</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\ias</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\Ntbackup.exe</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\NTMSData</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>継承メソッド:</strong> 伝達</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\rcp.exe</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\Regedt32.exe</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\repl</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>
<p><strong>継承メソッド:</strong> 伝達</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\repl\export</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p>Replicator: 読み取り、実行</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>  
<p><strong>継承メソッド:</strong> 伝達</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\repl\import</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p>Replicator: 修正</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>
<p><strong>継承メソッド:</strong> 伝達</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\rexec.exe</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\rsh.exe</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\secedit.exe</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\Setup</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>
<p><strong>継承メソッド:</strong> 伝達</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDirectory%\spool\Printers</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p>(サブフォルダおよびファイル)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> フォルダのスキャン、属性の読み取り、拡張属性の読み取り、ファイルの作成、フォルダの作成</p>  
<p>(フォルダおよびサブフォルダ)</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDrive%</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p>(サブフォルダおよびファイル)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>  
<p><strong>継承メソッド:</strong> 伝達</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDrive%\Documents and Settings</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>
<p><strong>継承メソッド:</strong> 伝達</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDrive%\Documents and Settings\Administrator</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDrive%\Documents and Settings\All Users</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>
<p><strong>継承メソッド:</strong> 伝達</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDrive%\Documents and Settings\All Users\Documents\DrWatson</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p>(サブフォルダおよびファイル)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> フォルダのスキャン、ファイルの作成、フォルダの作成</p>  
<p>(フォルダおよびサブフォルダ)</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDrive%\Documents and Settings\All Users\Documents\DrWatson\ drwtsn32.log</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 修正</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDrive%\io.sys</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDrive%\msdos.sys</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemDrive%\Temp</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p>(サブフォルダおよびファイル)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> フォルダのスキャン、ファイルの作成、フォルダの作成</p>  
<p>(フォルダおよびサブフォルダ)</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemRoot%</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p>(サブフォルダおよびファイル)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemRoot%\ $NtServicePackUninstall$</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemRoot%\debug</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p>(サブフォルダおよびファイル)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り、実行</p>  
<p><strong>継承メソッド:</strong> 伝達</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemRoot%\debug\UserMode</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> (フォルダのみ) - フォルダのスキャン、フォルダの一覧、ファイルの作成。 (ファイルのみ) – ファイルの作成、フォルダの作成。</p>
<p><strong>継承メソッド:</strong> 伝達</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemRoot%\regedit.exe</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>継承メソッド:</strong> 置換</p>  
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemRoot%\Registration</p>  
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> 読み取り</p>
<p><strong>継承メソッド:</strong> 伝達</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemRoot%\repair</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /> %SystemRoot%\ Temp</p>
<p><strong>Administrators:</strong> フル コントロール</p>  
<p><strong>CREATOR OWNER:</strong> フル コントロール</p>  
<p>(サブフォルダおよびファイル)</p>  
<p><strong>SYSTEM:</strong> フル コントロール</p>  
<p><strong>Users:</strong> フォルダのスキャン、ファイルの作成、フォルダの作成</p>  
<p>(フォルダおよびサブフォルダ)</p>
<p><strong>継承メソッド:</strong> 置換</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>その他のレジストリの設定</strong></p>
<p>(値は 10 進数で示します。そうでない場合は、注記します。)</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>DirectDraw を無効にする</em></strong></p>
<p><img src="images/Dd277462.scg06(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>不要なデバイスを無効にする</em></strong></p>
<p><img src="images/Dd277462.scg07(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>OS/2 および POSIX サブシステムを削除する</em></strong></p>
<p><img src="images/Dd277462.scg08(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>カーネル オブジェクトの属性を保護する</em></strong></p>
<p><img src="images/Dd277462.scg09(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>ヌル セッション アクセスを制限する</em></strong></p>
<p><img src="images/Dd277462.scg10(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>名前付きパイプ上で ヌル セッション アクセスを制限する</em></strong></p>
<p><img src="images/Dd277462.scg11(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>アプリケーションで生成された入力からのセッション ロックの干渉を防止する</em></strong></p>
<p><img src="images/Dd277462.scg12(ja-jp,TechNet.10).gif" /></p>  
<p><strong>注意:</strong> この機能の効力を発揮させるためには、このキーと共に、スクリーン セーバーを適切に設定することが重要です。スクリーン セーバーについて、以下の設定を行う必要があります。</p>  
<ul>  
<li><p>スクリーン セーバーの選択</p></li>  
<li><p>パスワードによる保護</p></li>  
<li><p>スクリーン セーバーのタイムアウト期間</p></li>  
</ul>
<p>スクリーンセーバーが適切に構成されていないと、この機能はコンピュータ全体のセキュリティに関して、基本的に効果を発揮しません。</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>監査ログがいっぱいのしきい値のパーセントに達したら監査イベントを生成する</em></strong></p>
<p><img src="images/Dd277462.scg13(ja-jp,TechNet.10).gif" /></p>
<p>(ローカルの要件に応じて、値を編集することができます。)</p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>サービス拒否攻撃に対して TCP/IP スタックを強化する</em></strong></p>
<p><img src="images/Dd277462.scg14(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>パスワードによるスクリーンセーバーの保護を直ちに発効させる</em></strong></p>
<p><img src="images/Dd277462.scg15(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>LMHash の作成を無効にする</em></strong></p>
<p><img src="images/Dd277462.scg16(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>自動実行を無効にする</em></strong></p>
<p><img src="images/Dd277462.scg17(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>監査ログがいっぱいになったときに、管理上の警告を発する</em></strong></p>
<p><img src="images/Dd277462.scg18(ja-jp,TechNet.10).gif" /></p>
<p><strong>注意:</strong> 管理上の警告は Alerter サービスとメッセンジャ サービスの両方に依存しています。送信元のコンピュータ上で Alerter サービスが、受信側のコンピュータ上でメッセンジャ サービスが、それぞれ実行されていることを確認してください。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>LDAP BIND コマンド要求の LDAP サーバーでの処理</em></strong></p>
<p><img src="images/Dd277462.scg19(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p><strong>その他の推奨事項</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>管理者の暗号化証明書のバックアップ</em></strong></p>
<p>可能な場合には、管理者の暗号化証明書のバックアップを取り、安全な場所に保管しておきます。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>自動画面ロック保護の有効化</em></strong></p>
<p>スクリーン セーバーをパスワードで保護するように設定します。推奨するタイムアウト期間は 15 分です。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"> 
<p><img src="images/Dd277462.box(ja-jp,TechNet.10).gif" /></p></td>
<td style="border:1px solid black;"><p><strong><em>システム修復ディスクの更新</em></strong></p>
<p>実行した変更を反映するために、システム修復ディスクを更新します。</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;">  <img src="images/Dd277462.check(ja-jp,TechNet.10).gif" /></td>
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
-   [付録 C ‐ ユーザー権利と特権](https://technet.microsoft.com/ja-jp/library/9d7407aa-87b7-4564-9659-3e99abe3ac6c(v=TechNet.10))  
-   [付録 D ‐ ユーザー アカウントとグループ アカウント](https://technet.microsoft.com/ja-jp/library/50b1a83f-d25a-4ffe-b601-3adc677fa632(v=TechNet.10))  
-   付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト  
-   [付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/8842dd66-853c-4c8f-bb69-ae750f139356(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
