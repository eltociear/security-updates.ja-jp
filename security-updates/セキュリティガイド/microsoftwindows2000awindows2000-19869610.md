---
TOCTitle: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定'
Title: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定'
ms:assetid: '1adc2300-c9de-4ee0-bab7-9f8a797b03bc'
ms:contentKeyID: 19869610
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277458(v=TechNet.10)'
---

Microsoft Windows 2000 セキュリティ構成ガイド
=============================================

### 付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定

最終更新日: 2003年2月18日

**Windows 20000 既定のセキュリティ ポリシーの設定**

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
<th><p>セキュリティの設定</p></th>
<th><p>ローカル セキュリティ ポリシー (Professional および Server/Adv. Server)</p></th>
<th><p>ドメイン コントローラ セキュリティ ポリシー</p></th>
<th><p>ドメイン セキュリティ ポリシー</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>アカウント ポリシー</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><strong>パスワード ポリシー</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>パスワードの履歴を記録する</em></p></td>
<td style="border:1px solid black;"><p>パスワードを記憶しない</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>パスワードを 1 つ記憶する</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>パスワードの有効期間</em></p></td>
<td style="border:1px solid black;"><p>42 日</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>42 日</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>パスワードの変更禁止期間</em></p></td>
<td style="border:1px solid black;"><p>0 日</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>0 日</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>パスワードの長さ</em></p></td>
<td style="border:1px solid black;"><p>0 文字</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>0 文字</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>パスワードは要求する複雑さを満たす</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>無効</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>暗号化を元に戻せる状態でドメインのすべてのユーザーのパスワードを保存する</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>無効</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>アカウント ロックアウト ポリシー</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ロックアウト期間</em></p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>アカウントのロックアウトのしきい値</em></p></td>
<td style="border:1px solid black;"><p>無効なログインの試みなし</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>無効なログインの試みなし</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ロックアウト カウントのリセット</em></p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>Kerberos ポリシー</strong></p></td>
<td style="border:1px solid black;"><p><strong>(ポリシー利用不可)</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ユーザー ログオンの制限を強制する</em></p></td>
<td style="border:1px solid black;"><p>(利用不可)</p>
<p>(ローカル既定値は有効)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>有効</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>サービス チケットの最長有効期間</em></p></td>
<td style="border:1px solid black;"><p>(利用不可)</p>
<p>(ローカル既定値は 60 分)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>600 分</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>チケットの最長有効期間</em></p></td>
<td style="border:1px solid black;"><p>(利用不可)</p>
<p>(ローカル既定値は 7 時間)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>10 時間</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ユーザー チケットを更新できる最長有効期間</em></p></td>
<td style="border:1px solid black;"><p>(利用不可)</p>
<p>(ローカル既定値は 10 日)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>7 日</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>コンピュータの時計の同期の最長トレランス</em></p></td>
<td style="border:1px solid black;"><p>(利用不可)</p>
<p>(ローカル既定値は 60 分)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>5 分</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p>ローカル ポリシー</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><strong>監査ポリシー</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>アカウント ログオン イベントの監査</em></p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>アカウント管理の監査</em></p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ディレクトリ サービスのアクセスの監査</em></p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ログオン イベントの監査</em></p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>オブジェクト アクセスの監査</em></p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ポリシーの変更の監査</em></p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>特権使用の監査</em></p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>プロセス追跡の監査</em></p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>システム イベントの監査</em></p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>監査しない</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><strong>ユーザー権利の割り当て</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ネットワーク経由でコンピュータへアクセス</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Backup Operators</p>  
<p>Power Users</p>  
<p>Users</p>
<p>Everyone</p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Authenticated Users</p>  
<p>Everyone</p>  
<p>IUSR_W2K-<em>コンピュータ名</em></p>
<p>IWAM_W2K-<em>コンピュータ名</em></p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ペレーティング システムの一部として機能</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ドメインにワークステーションを追加</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>Authenticated Users</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ファイルとディレクトリのバックアップ</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Backup Operators</p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Backup Operators</p>
<p>Server Operators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>走査チェックのバイパス</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Backup Operators</p>  
<p>Power Users</p>  
<p>Users</p>
<p>Everyone</p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Authenticated Users</p>
<p>Everyone</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>システム時刻の変更</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Power Users</p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Server Operators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ページ ファイルの作成</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>トークン オブジェクトの作成</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>永続的共有オブジェクトの作成</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>プログラムのデバッグ</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ネットワーク経由でコンピュータへアクセスを拒否する</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>バッチ ジョブとしてログオンを拒否する</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>サービスとしてログオンを拒否する</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ローカルでログオンを拒否する</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>コンピュータとユーザー アカウントに委任時の信頼を付与</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>リモートコンピュータからの強制シャットダウン</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Server Operators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>セキュリティ監査の生成</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>クォータの増加</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>スケジューリング優先順位の繰り上げ</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>デバイス ドライバのロードとアンロード</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>メモリ内のページのロック</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>バッチ ジョブとしてログオン</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>IUSR_W2K-<em>コンピュータ名</em></p>
<p>IWAM_W2K-<em>コンピュータ名</em></p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>サービスとしてログオン</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ローカル ログオン</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Backup Operators</p>  
<p>Power Users</p>  
<p>Users</p>  
<p><em>コンピュータ名</em>/Guest</p>
<p><em>コンピュータ名</em>/TsInternetUser (Server/Adv. Server のみ)</p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Authenticated Users</p>  
<p>Backup Operators</p>  
<p>IUSR_W2K-<em>コンピュータ名</em></p>  
<p>Print Operators</p>  
<p>Server Operators</p>
<p>TsInternetUser</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>監査とセキュリティ ログの管理</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ファームウェア環境値の修正</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>単一プロセスのプロファイル</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Backup Operators</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>システム パフォーマンスのプロファイル</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ドッキング ステーションからコンピュータを削除</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Backup Operators</p>
<p>Users</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>プロセス レベル トークンの置き換え</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ファイルとディレクトリの復元</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Backup Operators</p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Backup Operators</p>
<p>Server Operators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>システムのシャットダウン</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p>
<p>Backup Operators</p>  
<p>Power Users</p>
<p>Users (Professional のみ)</p></td>
<td style="border:1px solid black;"><p>Account Operators</p>
<p>Administrators</p>  
<p>Backup Operators</p>  
<p>Print Operators</p>
<p>Server Operators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ディレクトリ サービス データの同期化</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ファイルとその他のオブジェクトの所有権の取得</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p>セキュリティ オプション</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>匿名接続の追加を制限する</em></p></td>
<td style="border:1px solid black;"><p>なし。既定のアクセス許可に依存。</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>サーバー オペレータがタスクのスケジュールを割り当てるのを許可する (ドメイン コントローラのみ)</em></p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>システムをシャットダウンするのにログオンを必要としない</em></p></td>
<td style="border:1px solid black;"><p>有効 (Professional のみ)</p>
<p>無効 (Server/Adv. Server のみ)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>リムーバブル NTFS メディアを取り出すのを許可する</em></p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>セッションを切断する前に、ある一定のアイドル時間を必要とする</em></p></td>
<td style="border:1px solid black;"><p>15 分</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>グローバル システム オブジェクトへのアクセスを監査する</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>バックアップと復元の特権の使用を監査する</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ログオン時間を経過した場合は自動的にユーザーをログオフする</em></p></td>
<td style="border:1px solid black;"><p>(スタンドアロンの Professional、Server、または Advanced Server ではこのオプションは利用不可)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>無効</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ログオン時間が時間切れになった場合、自動的にユーザーをログオフする (ローカル)</em></p></td>
<td style="border:1px solid black;"><p>有効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>システムのシャットダウン時に仮想メモリのページ ファイルをクリアする</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>常にクライアント側の通信にデジタル署名を行う</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>可能な場合、クライアントの通信にデジタル署名を行う</em></p></td>
<td style="border:1px solid black;"><p>有効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>常にサーバーの通信にデジタル署名を行う</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>可能な場合、サーバーの通信にデジタル署名を行う</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>有効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ログオンに Ctrl+Alt+Del を必要としない</em></p></td>
<td style="border:1px solid black;"><p>未定義 (Professional のみ)</p>
<p>無効 (Server/Adv. Server のみ)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ログオン画面に最後のユーザー名を表示しない</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>LAN Manager 認証レベル</em></p></td>
<td style="border:1px solid black;"><p>LM &amp; NTLM 応答の送信</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ログオン時のユーザーへのメッセージのテキスト</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>ログオン時のユーザーへのメッセージのタイトル</em></p></td>
<td style="border:1px solid black;"><p>(空)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ドメイン コントローラが利用できない場合に使用する、前回ログオンのキャッシュ数</em></p></td>
<td style="border:1px solid black;"><p>10 ログオン</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>コンピュータ アカウント パスワードのシステム保守をしない</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>ユーザーがプリンタ ドライバをインストールできないようにする</em></p></td>
<td style="border:1px solid black;"><p>無効 (Professional のみ)</p>
<p>有効 (Server/Adv. Server のみ)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>パスワードが無効になる前にユーザーに変更を促す</em></p></td>
<td style="border:1px solid black;"><p>14 日</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>回復コンソール: 自動管理ログオンを許可する</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>回復コンソール: すべてのドライブとフォルダに、フロッピーのコピーとアクセスを許可する</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>Administrator アカウント名の変更</em></p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>Guest アカウント名の変更</em></p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>CD-ROM へのアクセスを、ローカル ログオン ユーザーだけに制限する</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>フロッピーへのアクセスを、ローカル ログオン ユーザーだけに制限する</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>セキュリティで保護されたチャネル: 常にセキュリティ チャネルのデータをデジタル的に暗号化または署名する</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>セキュリティで保護されたチャネル: 可能な場合、セキュリティ チャネルのデータをデジタル的に暗号化または署名する</em></p></td>
<td style="border:1px solid black;"><p>有効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>セキュリティで保護されたチャネル: 可能な場合、セキュリティ チャネルのデータをデジタル的に署名する</em></p></td>
<td style="border:1px solid black;"><p>有効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>セキュリティで保護されたチャネル: 強力な (Windows 2000 かそれ以降のバージョン) セッション キーを必要とする</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>システム パーティションの保護 (RISC プラットフォームのみ)</em></p></td>
<td style="border:1px solid black;"><p>(スタンドアロンの Professional、Server、または Advanced Server ではこのオプションは利用不可)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>サード パーティ製の SMB サーバーへ接続するためのパスワードを、暗号化しないで送信する</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>セキュリティ監査のログを記録できない場合は直ちにシステムをシャットダウンする</em></p></td>
<td style="border:1px solid black;"><p>無効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>スマート カード取り出し時の動作</em></p></td>
<td style="border:1px solid black;"><p>無動作</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>グローバル システム オブジェクトの既定のアクセス許可を強化する (例: シンボリック リンク)</em></p></td>
<td style="border:1px solid black;"><p>有効</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>署名されていないドライバのインストール時の動作</em></p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>署名されていないドライバ以外のインストール時の動作</em></p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>イベント ログ</p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>イベント ログの設定</strong></p></td>
<td style="border:1px solid black;"><p><strong>イベント ビューアにおけるログ プロパティの設定</strong></p></td>
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>アプリケーション ログの最大サイズ</em></p></td>
<td style="border:1px solid black;"><p>512 Kb</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>セキュリティ ログの最大サイズ</em></p></td>
<td style="border:1px solid black;"><p>512 Kb</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>システム ログの最大サイズ</em></p></td>
<td style="border:1px solid black;"><p>512 Kb</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>アプリケーション ログのゲスト アクセスの制限</em></p></td>
<td style="border:1px solid black;"><p>(利用不可)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>セキュリティ ログのゲスト アクセスの制限</em></p></td>
<td style="border:1px solid black;"><p>(利用不可)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>システム ログのゲスト アクセスの制限</em></p></td>
<td style="border:1px solid black;"><p>(利用不可)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>アプリケーション ログの保存日数</em></p></td>
<td style="border:1px solid black;"><p>7 日を超えたイベントを上書きする</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>セキュリティ ログの保存日数</em></p></td>
<td style="border:1px solid black;"><p>7 日を超えたイベントを上書きする</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>システム ログの保存日数</em></p></td>
<td style="border:1px solid black;"><p>7 日を超えたイベントを上書きする</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>アプリケーション ログの保存方法</em></p></td>
<td style="border:1px solid black;"><p>7 日を超えたイベントを上書きする</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>セキュリティ ログの保存方法</em></p></td>
<td style="border:1px solid black;"><p>7 日を超えたイベントを上書きする</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><em>システム ログの保存方法</em></p></td>
<td style="border:1px solid black;"><p>7 日を超えたイベントを上書きする</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><em>セキュリティの監査ログがいっぱいになったら、コンピュータをシャットダウンする</em></p></td>
<td style="border:1px solid black;"><p>(利用不可)</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
<td style="border:1px solid black;"><p>未定義</p></td>
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
-   付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定  
-   [付録 B ‐ 監査カテゴリとイベント](https://technet.microsoft.com/ja-jp/library/0fc077e8-8bf5-4b4d-a555-a8c26c9792f0(v=TechNet.10))  
-   [付録 C ‐ ユーザー権利と特権](https://technet.microsoft.com/ja-jp/library/9d7407aa-87b7-4564-9659-3e99abe3ac6c(v=TechNet.10))  
-   [付録 D ‐ ユーザー アカウントとグループ アカウント](https://technet.microsoft.com/ja-jp/library/50b1a83f-d25a-4ffe-b601-3adc677fa632(v=TechNet.10))  
-   [付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト](https://technet.microsoft.com/ja-jp/library/b1327283-7a58-409a-9554-59e4bbc01374(v=TechNet.10))  
-   [付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/8842dd66-853c-4c8f-bb69-ae750f139356(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
