---
TOCTitle: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート'
Title: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート'
ms:assetid: '8842dd66-853c-4c8f-bb69-ae750f139356'
ms:contentKeyID: 19869615
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277463(v=TechNet.10)'
---

Microsoft Windows 2000 セキュリティ構成ガイド
=============================================

### 付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート

最終更新日: 2003年2月18日

##### トピック

[](#ehaa)[G-1. ベースライン Windows 2000 Server セキュリティ構成テンプレート](#ehaa)  
[](#egaa)[G-2. ベースライン Windows 2000 Professional セキュリティのテンプレート](#egaa)  
[](#efaa)[G-3. ベースライン Windows 2000 ドメイン セキュリティ ポリシーのテンプレート](#efaa)  
[](#eeaa)[G-4. ベースライン Windows 2000 ドメイン コントローラ セキュリティ ポリシーのテンプレート](#eeaa)  
[](#edaa)[G-5. 高セキュリティ Windows 2000 Server セキュリティのテンプレート](#edaa)  
[](#ecaa)[G-6. 高セキュリティ Windows 2000 Professional セキュリティのテンプレート](#ecaa)  
[](#ebaa)[G-7. 高セキュリティ Windows 2000 ドメイン セキュリティ ポリシーのテンプレート](#ebaa)  
[](#eaaa)[G-8. 高セキュリティ Windows 2000 ドメイン コントローラ セキュリティ ポリシーのテンプレート](#eaaa)  

### G-1. ベースライン Windows 2000 Server セキュリティ構成テンプレート

<table style="border:1px; solid black;">  
<tr>  
<td>  
; ; (c) Microsoft Corporation 1997-2000  
;  
; セキュリティ構成エディタ用のセキュリティ構成のテンプレート  
;  
; テンプレート名:    CC_Baseline_W2K_Server.inf  
; テンプレート バージョン:   1.0  
;  
;このセキュリティ構成のテンプレートでは、情報テクノロジ セキュリティ評価のための共通基準 (CC)   
;のもとで、Windows 2000 の評価された構成をサポートするための設定を示します。  
;  
; 改訂履歴  
; 0000   -   作成   2002 年 9 月 17 日  
[version]  
signature="$CHICAGO$"  
Revision=1  
[System Access]  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - パスワード ポリシー  
;--------------------------------------------------------------------------------  
MinimumPasswordLength = 8  
RequireLogonToChangePassword = 0  
ClearTextPassword = 0  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - ロックアウト ポリシー  
;--------------------------------------------------------------------------------  
LockoutBadCount = 5  
ResetLockoutCount = 30  
LockoutDuration = -1  
;注意 : アカウントをロックアウトしないとき、下記の構成は行いません。  
;ResetLockoutCount = 30  
;LockoutDuration = -1  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - Kerberos ポリシー  
;--------------------------------------------------------------------------------  
[Kerberos Policy]  
TicketValidateClient = 1  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - 監査ポリシー  
;--------------------------------------------------------------------------------  
;注意 : ベースライン ポリシーには監査ポリシーの設定は指定されていません。  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - ユーザー権利の割り当て  
;--------------------------------------------------------------------------------  
[Privilege Rights]  
SeNetworkLogonRight = *S-1-5-32-545,*S-1-5-32-547,*S-1-5-32-551,*S-1-5-11,*S-1-5-32-544  
SeInteractiveLogonRight = *S-1-5-32-545,*S-1-5-32-547,*S-1-5-32-551,*S-1-5-32-544  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - セキュリティ オプション  
;--------------------------------------------------------------------------------  
;--------------------------------------------------------------------------------  
;レジストリ値  
;--------------------------------------------------------------------------------  
; 完全なパスで表したレジストリ値の名前 = 種類、値  
; REG_SZ                      ( 1 )  
; REG_EXPAND_SZ               ( 2 )  // 拡張する環境変数と共に  
; REG_BINARY                  ( 3 )  
; REG_DWORD                   ( 4 )  
; REG_MULTI_SZ                ( 7 )  
[Registry Values]  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\CachedLogonsCount=1,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateFloppies=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateCDRoms=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Setup\RecoveryConsole\SecurityLevel=4,0  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\DisableCAD=4,0  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Control\Session Manager\ProtectionMode=4,1  
MACHINE\System\CurrentControlSet\Control\Session Manager\Memory Management\ClearPageFileAtShutdown=4,1  
MACHINE\System\CurrentControlSet\Control\Print\Providers\LanMan Print Services\Servers\AddPrinterDrivers=4,1  
MACHINE\System\CurrentControlSet\Control\Lsa\RestrictAnonymous=4,1  
;=========================================================================  
;評価された構成に必須のセキュリティの設定。下に列挙するその他の  
;レジストリ値の設定は Common Criteria (共通基準) に基づく評価された構成に必須です。  
;これらの設定はセキュリティ ポリシーのインターフェイスには表示されません。  
=========================================================================  
;--------------------------------------------------------------------------------  
;DirectDraw を無効にする。ここでは、アプリケーションからグラフィックス  
;ハードウェアに直接アクセスされることを防止するために、DirectDraw を  
;無効にします。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\GraphicsDrivers\DCI\Timeout=4,0  
;--------------------------------------------------------------------------------  
;不要なサービスを無効にする。これらのサービスはサービス インターフェイスに  
;表示されません。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\audstub\Start=4,4  
MACHINE\System\CurrentControlSet\Services\mnmdd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisTapi\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisWan\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NDProxy\Start=4,4  
MACHINE\System\CurrentControlSet\Services\ParVdm\Start=4,4  
MACHINE\System\CurrentControlSet\Services\PptpMiniport\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Ptilink\Start=4,4  
MACHINE\System\CurrentControlSet\Services\RasAcd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Rasl2tp\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Raspti\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Wanarp\Start=4,4  
;--------------------------------------------------------------------------------  
;OS/2 および POSIX サブシステムを削除する。ここでは、OS/2 および POSIX の  
;既定値を削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\SubSystems\Optional=7,""  
;--------------------------------------------------------------------------------  
;カーネル オブジェクト属性を保護する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\EnhancedSecurityLevel=4,1  
;--------------------------------------------------------------------------------  
;ヌル セッション アクセスを制限する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\RestrictNullSessAccess=4,1  
;--------------------------------------------------------------------------------  
;名前つきパイプを通じた ヌル セッション アクセスを制限する。ここでは、既定値を  
;削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionPipes=7,""  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionShares=7,""  
;--------------------------------------------------------------------------------  
;SP3 を編集する。監査ログがいっぱいのしきい値のパーセントに達したときに、  
;監査イベントを生成します。ここでは、セキュリティ イベント ログが 90  
;パーセントにまで達したときに、監査イベントを生成するように設定します。  
;この値がローカルの状況に合わない場合には、管理者はローカルの要件に基づいて、  
;このキーのパーセント値を調整することができます。  
;--------------------------------------------------------------------------------  
MACHINE\SYSTEM\CurrentControlSet\Services\Eventlog\Security\WarningLevel=4,90  
;--------------------------------------------------------------------------------  
;イベント ログ - ログの設定  
;--------------------------------------------------------------------------------  
;監査ログの保存日数  
;0 = 必要に応じてイベントを上書きする  
;1 = 保存日数に指定した日数を過ぎたら上書きする  
;2 = イベントを上書きしない (手作業でログをクリア)  
;注意 : ベースライン ポリシーにはイベント ログの設定は指定されていません。  
;--------------------------------------------------------------------------------  
;システム サービス - Common Criteria (共通基準) に基づく評価された構成に含まれていない  
;サービスを無効にします。  
;--------------------------------------------------------------------------------  
[Service General Setting]  
TrkWks,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
seclogon,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
Schedule,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
ClipSrv,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
NetDDEdsdm,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
AppMgmt,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;OICI;CCLCSWRPLO;;;BU)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
MSDTC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;RP;;;WD)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
LicenseService,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
SMTPSVC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
TrkSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;RPWPDTRC;;;SY)"  
Fax,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
wuauserv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
BITS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;DCRPWPDTRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
cisvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSFTPSVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
IISADMIN,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SharedAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
mnmsrvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
NetDDE,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)"  
SysmonLog,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RSVP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
RasAuto,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RasMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
NtmsSvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RemoteAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SCardSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)"  
SCardDrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMPTRAP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TapiSrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWRPWPDTLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
(A;;CCLCSWRPWPDTLOCRRC;;;BU)"  
TlntSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UPS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TermService,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UtilMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSIServer,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
W3SVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
;--------------------------------------------------------------------------------  
;レジストリ キーへのアクセス許可  
;--------------------------------------------------------------------------------  
[Registry Keys]  
"CLASSES_ROOT",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Microsoft\OS/2 Subsystem for NT",0,"D:PAR(A;CI;KA;;;BA)  
(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\EventLog",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Print\Printers",2,"D:PAR(A;CI;KA;;;BA)  
(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ProductOptions",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ContentIndex",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Computername",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layouts",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\Software\Microsoft\Windows NT\CurrentVersion",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SOFTWARE\Classes\.hlp",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Classes\helpfile",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)  
(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software\Classes",0,"D:AR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software",0,"D:PAR(A;CI;KA;;;BA)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
;--------------------------------------------------------------------------------  
;ファイルおよびフォルダへのアクセス許可  
;--------------------------------------------------------------------------------  
[File Security]  
"%SystemDrive%\config.sys",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\autoexec.bat",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\boot.ini",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson\drwtsn32.log",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemRoot%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
;--------------------------------------------------------------------------------  
;グループの既定のメンバを編集する。  
;--------------------------------------------------------------------------------  
[Group Membership]  
;--------------------------------------------------------------------------------  
;Guests グループからアカウントを削除する。これらの設定はセキュリティ ポリシー  
;インターフェイスに表示されません。  
;--------------------------------------------------------------------------------  
%SceInfGuests%__Members =  
[Strings]  
SceInfAdministrator = Administrator  
SceInfAdmins = Administrators  
SceInfAcountOp = Account Operators  
SceInfAuthUsers = Authenticated Users  
SceInfBackupOp = Backup Operators  
SceInfDomainAdmins = Domain Admins  
SceInfDomainGuests = Domain Guests  
SceInfDomainUsers = Domain Users  
SceInfEveryone = Everyone  
SceInfGuests = Guests  
SceInfGuest = Guest  
SceInfPowerUsers = Power Users  
SceInfPrintOp = Print Operators  
SceInfReplicator = Replicator  
SceInfServerOp = Server Operators  
SceInfUsers = Users  
[Profile Description]  
Description=Evaluated Configuration minimum required security policy settings for Windows 2000 Servers.  
</td>  
</tr>  
</table>   


[](#mainsection)[ページのトップへ](#mainsection)

### G-2. ベースライン Windows 2000 Professional セキュリティのテンプレート

[](#mainsection)[ページのトップへ](#mainsection)

### G-3. ベースライン Windows 2000 ドメイン セキュリティ ポリシーのテンプレート
        ```
[](#mainsection)[ページのトップへ](#mainsection)

### G-4. ベースライン Windows 2000 ドメイン コントローラ セキュリティ ポリシーのテンプレート
        ```
[](#mainsection)[ページのトップへ](#mainsection)

### G-5. 高セキュリティ Windows 2000 Server セキュリティのテンプレート
        ```
[](#mainsection)[ページのトップへ](#mainsection)

### G-6. 高セキュリティ Windows 2000 Professional セキュリティのテンプレート
        ```
[](#mainsection)[ページのトップへ](#mainsection)

### G-7. 高セキュリティ Windows 2000 ドメイン セキュリティ ポリシーのテンプレート
        ```
[](#mainsection)[ページのトップへ](#mainsection)

### G-8. 高セキュリティ Windows 2000 ドメイン コントローラ セキュリティ ポリシーのテンプレート
        ```
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
-   [付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト](https://technet.microsoft.com/ja-jp/library/b1327283-7a58-409a-9554-59e4bbc01374(v=TechNet.10))
-   付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート

[](#mainsection)[ページのトップへ](#mainsection)
