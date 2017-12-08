---
TOCTitle: '[HOWTO] Windows XP SP2 におけるメモリ保護の構成方法'
Title: '[HOWTO] Windows XP SP2 におけるメモリ保護の構成方法'
ms:assetid: '3ad3cd19-e9e3-431b-9d34-e6b294ece35d'
ms:contentKeyID: 19869272
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc700810(v=TechNet.10)'
---

\[HOWTO\] Windows XP SP2 におけるメモリ保護の構成方法
=====================================================

公開日: 2005年3月28日

##### トピック

[](#efaa)[はじめに](#efaa)
[](#eeaa)[開始する前に](#eeaa)
[](#edaa)[コンピュータ上のすべてのプログラムに対して DEP を有効にする](#edaa)
[](#ecaa)[DEP 例外リストを有効にする](#ecaa)
[](#ebaa)[システム全体を対象にした DEP オプションを構成する](#ebaa)
[](#eaaa)[関連情報](#eaaa)

### はじめに

Microsoft Windows XP Service Pack 2 (SP2) では、データ実行防止 (Data Execution Prevention: DEP) と呼ばれる一連のハードウェアおよびソフトウェア強制テクノロジを実装することにより、実行不能なコード用に確保されているコンピュータ メモリ領域に悪意のあるコードが挿入されることを防止することができます。 ハードウェア DEP は、特定のプロセッサに組み込まれた機能であり、データ ストレージとして指定されたメモリ領域でコードが実行されることを防止します。 この機能は、No-Execute 機能または Execution Protection 機能とも呼ばれています。 Windows XP SP2 にはソフトウェア DEP も組み込まれています。ソフトウェア DEP は、Windows の例外処理メカニズムのセキュリティ上の弱点を減らすことを目的としています。

ハードウェアおよびソフトウェア DEP テクノロジは、ウイルス対策プログラムと違って、有害なプログラムがコンピュータにインストールされることを防止するためのものではありません。 インストールされたプログラムを監視して、システム メモリが安全に使用されていることを確認するものです。 プログラムを監視するため、ハードウェア DEP は、「実行不能」と宣言されたメモリ ロケーションを追跡します。 「実行不能」と宣言されたメモリでコードが実行された場合、悪意のあるコードの実行を防止するため、 コードが悪意のあるものかどうかに関係なく Windows はそのプログラムを閉じます。

**注意** **:** ソフトウェア DEP は Windows XP SP2 に組み込まれているため、プロセッサのハードウェア DEP 機能に関係なく、既定で有効になっています。 ソフトウェア DEP は既定で、コアとなるオペレーティング システムのコンポーネントおよびサービスに適用されます。

DEP は既定で、アプリケーションの互換性に与える影響を最小限に抑えながらコンピュータを保護することを目的に構成されています。 ただし、DEP の構成によっては、一部のプログラムが正しく実行されない可能性があります。 この文書で説明する次のタスクを使用して、お使いのコンピュータで DEP を構成することができます。

-   コンピュータ上のすべてのプログラムに対して DEP を有効にする

-   DEP 例外リストにプログラムを追加する

-   コンピュータ全体に対して DEP を無効にする

    **重要** **:** この文書に記載されている手順は、オペレーティング システムをインストールしたときの既定の設定で表示される \[スタート\] メニューを使用することを前提に作成されています。 したがって、\[スタート\] メニューの設定を変更している場合には、この手順と異なる可能性があります。

セキュリティ関連用語の定義については、次のサイトを参照してください。

-   マイクロソフト Web サイトの「[Microsoft セキュリティ用語集](http://www.microsoft.com/japan/security/glossary.mspx)」http://www.microsoft.com/japan/security/glossary.mspx

DEP の詳細については、次のサイトを参照してください。

-   [マイクロソフト サポート技術情報 875352「Windows XP Service Pack 2 のデータ実行防止 (DEP) 機能の詳細」](http://go.microsoft.com/fwlink/?linkid=35494)http://go.microsoft.com/fwlink/?linkid=35494

[](#mainsection)[ページのトップへ](#mainsection)

### 開始する前に

この文書では、Windows XP SP2 における DEP の構成方法について説明します。

**注意** **:** ハードウェア DEP は、64 ビットバージョンの Microsoft Windows XP を実行している、DEP と互換性のあるプロセッサが組み込まれたコンピュータでは、既定で有効になっています。 64 ビット アプリケーションは、メモリの "実行不能" 領域では実行されません。 ハードウェア DEP を無効にすることはできません。

Windows XP SP2 および 32 ビット アプリケーションが実行されているプロセッサでは、メモリの "実行可能" 領域または "実行不能" 領域のいずれを使用するか、ソフトウェア DEP を構成できます。

[](#mainsection)[ページのトップへ](#mainsection)

### コンピュータ上のすべてのプログラムに対して DEP を有効にする

ハードウェア DEP およびソフトウェア DEP の既定の構成では、コアとなる Windows コンポーネントおよびサービスが保護され、アプリケーションの互換性に与える影響は最小限に抑えられるようになっています。オプションで、コンピュータ上のすべてのアプリケーションおよびプログラムが保護されるように構成することもできます。 この構成にした場合、保護機能が向上するという利点はありますが、アプリケーションの互換性に関する問題の発生が増える可能性があります。 コンピュータ上のすべてのアプリケーションおよびプログラムが保護されるように DEP が構成されている場合、互換性の問題が発生した際には個々の 32 ビット アプリケーションをソフトウェア DEP の対象から外します。 ハードウェア DEP を無効にしたり、DEP 互換プロセッサ搭載の 64 ビット Windows XP システムで実行されている 64 ビット アプリケーションを DEP の対象から外すことはできません。

#### このタスクを実行するための要件

-   資格情報 : ローカル管理者権限が割り当てられたアカウントを使用して、コンピュータにログオンする必要があります。

##### すべてのアプリケーションが保護されるように DEP を構成する

**すべてのアプリケーションに対して** **DEP** **を有効にするには**

1.  **\[スタート\]** ボタンをクリックして、**\[コントロールパネル\]** をクリックします。

2.  **\[作業する分野を選びます\]** の **\[パフォーマンスとメンテナンス\]** をクリックします。

3.  **\[コントロールパネルを選んで実行します\]** の **\[システム\]** をクリックします。

4.  **\[詳細設定\]** タブをクリックします。

    ![](images/Cc700810.DEPcnf01(ja-jp,TechNet.10).gif)

    **図** **1   \[システムのプロパティ\] - \[詳細設定\]** **タブ**

5.  **\[パフォーマンス\]** の **\[設定\]** をクリックします。

    ![](images/Cc700810.DEPcnf02(ja-jp,TechNet.10).gif)

    **図** **2   \[パフォーマンスオプション\]**

6.  **\[データ実行防止\]** タブをクリックします。

    ![](images/Cc700810.DEPcnf03(ja-jp,TechNet.10).gif)

    **図** **3   \[データ実行防止\]** **タブ**

7.  **\[次に選択するのものを除くすべてのプログラムおよびサービスについて** **DEP** **を有効にする\]** を選択します。

8.  **\[適用\]** をクリックし、**\[OK\]** をクリックします。 設定を有効にするにはコンピュータを再起動する必要があることを知らせるダイアログ ボックスが表示されます。 **\[OK\]** をクリックします。

#### すべてのプログラムに対して DEP の設定が適用されたことを確認する

**すべてのプログラムに対して** **DEP** **の設定が適用されたことを確認するには**

1.  **\[スタート\]** ボタンをクリックして、**\[コントロールパネル\]** をクリックします。

2.  **\[作業する分野を選びます\]** の **\[パフォーマンスとメンテナンス\]** をクリックします。

3.  **\[コントロールパネルを選んで実行します\]** の **\[システム\]** をクリックします。

4.  **\[詳細設定\]** タブをクリックします。

5.  **\[パフォーマンス\]** の **\[設定\]** をクリックして、次に **\[データ実行防止\]** をクリックします。

6.  **\[次に選択するのものを除くすべてのプログラムおよびサービスについて** **DEP** **を有効にする\]** が選択されていることを確認し、**\[OK\]** をクリックして、**\[パフォーマンスオプション\]** ダイアログ ボックスを閉じます。

7.  **\[OK\]** をクリックして **\[システムのプロパティ\]** ダイアログ ボックスを閉じ、**\[パフォーマンスとメンテナンス\]** ウィンドウを閉じます。

[](#mainsection)[ページのトップへ](#mainsection)

### DEP 例外リストを有効にする

DEP によりアプリケーションに問題が発生した場合は、そのことを知らせるダイアログ ボックスが表示されます。

![](images/Cc700810.DEPcnf04(ja-jp,TechNet.10).gif)

**図** **4  ** **アプリケーションを実行しようとして** **DEP** **による問題が発生した場合に表示されるダイアログボックス**

DEP が原因でアプリケーション障害が発生した場合は、アプリケーション ベンダに連絡して、DEP と互換性のあるアップデートが提供されていないか確認することをお勧めします。 提供されている場合は、そのアップデートをインストールすると、DEP との互換性に関するアプリケーションの問題を解決できます。

使用しているアプリケーションに関してそのようなアップデートが提供されていない場合は、次の手順に従って例外リストを構成してください。 例外リストは、DEP の対象から除外するアプリケーションのリストです。

**注意** **:** DEP 例外リスト機能は、すべてのプログラムとサービスが保護されるように DEP が構成されている場合にのみ使用できます。 重要な Windows コンポーネントおよびサービスのみが保護されるように構成されている場合は、例外リストは使用できません。

#### このタスクの実行要件

-   資格情報 : ローカル管理者権限が割り当てられたアカウントを使用して、コンピュータにログオンする必要があります。

##### DEP 例外リストを有効にする

**DEP** **例外リストを有効にするには**

1.  **\[スタート\]** ボタンをクリックして、**\[コントロールパネル\]** をクリックします。

2.  **\[作業する分野を選びます\]** の **\[パフォーマンスとメンテナンス\]** をクリックします。

3.  **\[コントロールパネルを選んで実行します\]** の **\[システム\]** をクリックします。

4.  **\[詳細設定\]** タブをクリックします。

    ![](images/Cc700810.DEPcnf05(ja-jp,TechNet.10).gif)

    **図** **5   \[システムのプロパティ\] - \[詳細設定\]** **タブ**

5.  **\[パフォーマンス\]** の **\[設定\]** をクリックします。

    ![](images/Cc700810.DEPcnf06(ja-jp,TechNet.10).gif)

    **図** **6   \[パフォーマンスオプション\]**

6.  **\[データ実行防止\]** タブをクリックします。

    ![](images/Cc700810.DEPcnf07(ja-jp,TechNet.10).gif)

    **図** **7   \[データ実行防止\]** **タブ**

7.  **\[追加\]** をクリックします。

8.  障害が発生しているアプリケーションの実行可能ファイルを検索して選択し、**\[開く\]** をクリックします。

9.  警告ボックスで **\[OK\]** をクリックします。 選択したプログラムが、DEP プログラムの領域に表示されます。

10. **\[適用\]** をクリックし、**\[OK\]** をクリックします。 設定を有効にするにはコンピュータを再起動する必要があることを知らせるダイアログ ボックスが表示されます。 **\[OK\]** をクリックします。

#### DEP 例外リストの設定が適用されたことを確認する

**メモリ保護の設定が適用されたことを確認するには**

1.  **\[スタート\]** ボタンをクリックして、**\[コントロールパネル\]** をクリックします。

2.  **\[作業する分野を選びます\]** の **\[パフォーマンスとメンテナンス\]** をクリックします。

3.  **\[コントロールパネルを選んで実行します\]** の **\[システム\]** をクリックします。

4.  **\[詳細設定\]** タブをクリックします。

5.  **\[パフォーマンス\]** の **\[設定\]** をクリックして、次に **\[データ実行防止\]** をクリックします。

6.  問題のプログラムが例外一覧に含まれていることを確認したら、**\[OK\]** をクリックして **\[パフォーマンスオプション\]** ダイアログ ボックスを閉じます。

7.  **\[OK\]** をクリックして **\[システムのプロパティ\]** ダイアログ ボックスを閉じ、**\[パフォーマンスとメンテナンス\]** ウィンドウを閉じます。

[](#mainsection)[ページのトップへ](#mainsection)

### システム全体を対象にした DEP オプションを構成する

コンピュータのシステム全体で DEP を変更する場合は、現在実行している Windows インストールの boot.ini 構成ファイルのスイッチを変更する必要があります。 boot.ini スイッチの設定は次のとおりです。

-   **/noexecute =*Policy\_level***

表 1 に、Policy\_level のオプションのリストを示します。

**表** **1 DEP boot.ini** **の構成オプション**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >構成</th>
<th style="border:1px solid black;" >説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>OptIn</strong>
(既定の構成)</td>
<td style="border:1px solid black;">Windows システムのコンポーネントおよびサービスにのみ、DEP 保護機能が適用されます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>OptOut</strong></td>
<td style="border:1px solid black;">DEP はすべてのプロセスに対して有効になります。 管理者は、DEP を適用しないアプリケーションのリストを手動で作成できます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>AlwaysOn</strong></td>
<td style="border:1px solid black;">DEP はすべてのプロセスに対して有効になります。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>AlwaysOff</strong></td>
<td style="border:1px solid black;">DEP はどのプロセスにも適用されません。</td>
</tr>
</tbody>
</table>
  
**重要** **:** boot.ini ファイルに変更を加えた場合は、コンピュータを再起動する必要があります。
  
**警告** **:** システム全体でソフトウェア DEP を無効にすることはお勧めしません。 システム全体で無効にすると、コンピュータの安全性が低下します。 ハードウェア DEP は、手動で無効にすることはできません。
  
#### このタスクの実行要件
  
-   資格情報 : ローカル管理者権限が割り当てられたアカウントで、コンピュータにログオンする必要があります。
  
##### boot.ini を使用してシステム全体で DEP を無効にする  
  
**boot.ini** **を使用して** **DEP** **を無効にするには**
  
1.  **\[スタート\]** ボタンをクリックして、**\[コントロールパネル\]** をクリックします。
  
2.  **\[作業する分野を選びます\]** の **\[パフォーマンスとメンテナンス\]** をクリックします。
  
3.  **\[コントロールパネルを選んで実行します\]** の **\[システム\]** をクリックします。
  
4.  **\[詳細設定\]** タブをクリックして、**\[起動と回復\]** の **\[設定\]** をクリックします。   
  
    ![](images/Cc700810.DEPcnf08(ja-jp,TechNet.10).gif)
  
    **図** **8   \[起動と回復\]** **の設定**
  
5.  **\[起動システム\]** の **\[編集\]** をクリックします。
  
    ![](images/Cc700810.DEPcnf09(ja-jp,TechNet.10).gif)
  
    **図** **9  ** **メモ帳で開いた** **Boot.ini** **ファイル**
  
6.  **メモ帳**の **\[編集\]** をクリックして、**\[検索\]** をクリックします。
  
7.  **\[検索する文字列\]** に「**/noexecute**」と入力し、**\[次を検索\]** をクリックします。
  
8.  **\[検索\]** ダイアログ ボックスで **\[キャンセル\]** をクリックします。
  
9.  "**OptOut**" などの policy\_level を "**AlwaysOff**" に置き換えます (引用符は除く)。
  
    **警告** **:** テキストは、間違えないように入力してください。
  
    **注意** **:** boot.ini ファイルの設定は次のようになります。
  
    **/noexecute=AlwaysOff**
  
10. **メモ帳**の **\[ファイル\]** をクリックして、**\[上書き保存\]** をクリックします。
  
11. **\[OK\]** をクリックして **\[起動と回復\]** ダイアログ ボックスを閉じます。
  
12. **\[OK\]** をクリックして **\[システムのプロパティ\]** ダイアログ ボックスを閉じ、コンピュータを再起動します。
  
#### DEP が無効になっていることを確認する
  
**メモリ保護の設定が適用されたことを確認するには**
  
1.  **\[スタート\]** ボタンをクリックして、**\[コントロールパネル\]** をクリックします。
  
2.  **\[作業する分野を選びます\]** の **\[パフォーマンスとメンテナンス\]** をクリックします。
  
3.  **\[コントロールパネルを選んで実行します\]** の **\[システム\]** をクリックします。
  
4.  **\[詳細設定\]** タブをクリックします。
  
5.  **\[パフォーマンス\]** の **\[設定\]** をクリックして、次に **\[データ実行防止\]** をクリックします。
  
6.  DEP の設定を選択できないことを確認したら、**\[OK\]** をクリックして **\[パフォーマンスオプション\]** ダイアログ ボックスを閉じます。
  
7.  **\[OK\]** をクリックして **\[システムのプロパティ\]** ダイアログ ボックスを閉じ、**\[パフォーマンスとメンテナンス\]** ウィンドウを閉じます。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 関連情報
  
Windows XP SP2 のメモリ保護の詳細については、次のサイトを参照してください。
  
-   Microsoft TechNet Web サイトの「[Microsoft Windows XP Service Pack 2 での機能の変更点 第 3 部 : メモリ保護技術](http://technet.microsoft.com/library/bb457155.aspx)」http://technet.microsoft.com/library/bb457155.aspx
  
Windows XP SP2 のセキュリティの詳細については、次のサイトを参照してください。
  
-   Microsoft ダウンロード センター Web サイトの「[Service Pack 2 用にアップデートされた Windows XP セキュリティ ガイド v2 (Windows XP Security Guide v2 updated for Service Pack 2](http://go.microsoft.com/fwlink/?linkid=35309))」http://go.microsoft.com/fwlink/?linkid=35309 (英語)
  
-   Microsoft TechNet Web サイトの「[Windows XP セキュリティ ガイド 付録 A : Windows XP Service Pack 2 に関する追加ガイダンス (Windows XP Security Guide Appendix A: Additional Guidance for Windows XP Service Pack 2](http://www.microsoft.com/japan/technet/security/prodtech/windowsxp/secwinxp/xpsgapa.mspx))」http://www.microsoft.com/japan/technet/security/prodtech/windowsxp/secwinxp/xpsgapa.mspx
  
セキュリティ関連用語の定義については、次のサイトを参照してください。
  
-   マイクロソフト Web サイトの「[Microsoft セキュリティ用語集](http://www.microsoft.com/japan/security/glossary.mspx)」http://www.microsoft.com/japan/security/glossary.mspx
  
[](#mainsection)[ページのトップへ](#mainsection)