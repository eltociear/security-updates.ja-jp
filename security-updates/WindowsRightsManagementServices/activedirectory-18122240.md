---
TOCTitle: Active Directory キャッシュ設定の変更
Title: Active Directory キャッシュ設定の変更
ms:assetid: '8789a7a5-2065-4fae-9104-e0a70f1f2fb6'
ms:contentKeyID: 18122240
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc747586(v=WS.10)'
---

Active Directory キャッシュ設定の変更
=====================================

レジストリ内の設定で、Active Directory キャッシュに格納されるエントリの数が指定されています。クライアント要求に対する応答時間を向上するために、この設定を変更できます。詳細については、この項目の「ディレクトリ サービス パフォーマンスの最適化」を参照してください。また、キャッシュに格納される情報の有効期間を指定することもできます。

32 ビット バージョンの Windows Server 2003 が動作しているコンピュータの場合、次のレジストリ キーは、キャッシュ エントリの完全なサブキー パスです。

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0\\DirectoryServices**

64 ビット バージョンの Windows Server 2003 が動作しているコンピュータの場合、次のレジストリ キーは、キャッシュ エントリの完全なサブキー パスです。

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0\\DirectoryServices**

メモリ内キャッシュの動作を制御するエントリの一覧を次の表に示します。

###  

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
<th>名前</th>
<th>型</th>
<th>既定値</th>
<th>説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>PrincipalCacheMax</p></td>
<td style="border:1px solid black;"><p>DWORD</p></td>
<td style="border:1px solid black;"><p>1,000</p></td>
<td style="border:1px solid black;"><p>キャッシュに格納できるプリンシパルとその電子メール アドレスおよび SID の最大数</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>PrincipalCacheExpireMinutes</p></td>
<td style="border:1px solid black;"><p>DWORD</p></td>
<td style="border:1px solid black;"><p>12</p></td>
<td style="border:1px solid black;"><p>プリンシパルについてキャッシュに格納される情報の有効期間</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p>GroupIDCacheMax</p></td>
<td style="border:1px solid black;"><p>DWORD</p></td>
<td style="border:1px solid black;"><p>1,000</p></td>
<td style="border:1px solid black;"><p>キャッシュに格納できるグループとその電子メール アドレスおよび SID の最大数</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>GroupIDCacheExpireMinutes</p></td>
<td style="border:1px solid black;"><p>DWORD</p></td>
<td style="border:1px solid black;"><p>12</p></td>
<td style="border:1px solid black;"><p>グループ メンバシップ用にキャッシュされた情報の有効期間</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p>GroupMembershipCacheMax</p></td>
<td style="border:1px solid black;"><p>DWORD</p></td>
<td style="border:1px solid black;"><p>1,000</p></td>
<td style="border:1px solid black;"><p>キャッシュに格納できるグループ メンバの連絡先の最大数</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>GroupMembershipCacheExpireMinutes</p></td>
<td style="border:1px solid black;"><p>DWORD</p></td>
<td style="border:1px solid black;"><p>12</p></td>
<td style="border:1px solid black;"><p>グループ メンバの連絡先用にキャッシュされた情報の有効期間</p></td>
</tr>  
</tbody>  
</table>
  
| ![](images/Cc747586.Caution(WS.10).gif)注意                                                                                               |  
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| レジストリに不適切な編集を行うと、システムに大きな損害を与える可能性があります。レジストリに変更を加える前に、コンピュータ上の重要なデータをバックアップしてください。 |
  
| ![](images/Cc747586.note(WS.10).gif)注                                                                                                                                                                                                                                                     |  
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| **PrincipalCacheExpireMinutes**、**GroupIDCacheExpireMinutes**、**GroupMembershipCacheExpireMinutes**、および**ContactMembersofGroupCacheExpireMinutes** レジストリ エントリは、データベース サーバーのディレクトリ サービス データベースに格納されているローカルの Active Directory キャッシュの有効期限も制御します。 |
