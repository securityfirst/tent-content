[Title]: # ()
[Order]: # (0)

# WINDOWS 系統下的 TOR 工具指南

## WINDOWS 系統下的 TOR 工具指南
線上匿名與對抗網路審查利器
 
**學習內容：** [網際網路](umbrella://lesson/the-internet)  
**本指南將簡介如何使用** [Tor瀏覧器軟體包](https://www.torproject.org/projects/torbrowser.html.en)於 Windows 作業系統。  
**電腦系統需求：** 網路連線，運行於 Windows 環境的電腦  
**本指南使用版本：** Windows: Windows 7 Ultimate; Tor Browser Bundle: 3.6.2  
**版權宣告：** 免費自由軟體; 混合式自由軟體  
**程度：** 中級  
**其它參考資料：** [https://tor.stackexchange.com](https://tor.stackexchange.com/)  
**所需時間：** 15-30 分鐘  

**使用Tor可讓你：**
- 瀏覧網路躲避審查；
- 匿名地瀏網

### 1.0 開始之前

Tor 是由志工所維護的一個網路服務，它透過遮蔽來源與身份技術提供了隱私保障與線上匿名功能。它也能透過　Tor 本身網路來保護你。

當使用網址時有些人可能需要視情況進行匿名或保護隱私，Tor 瀏覧器即提供了一個快速而容易的方法來使用其網路。

最簡單使用 TOR 的方法就是利用它的軟體包，其包含了網頁瀏覧器、Tor 軟體以及其它相關的有用工具可讓你更安全地近用網站資訊.

**Tor 瀏覧器一如其它的網頁瀏覧器一樣，除了它會讓你的連線通訊要透過 Tor，這會讓監控者難以知道你在網路中的行為，也讓他人難以知道你的來源以及造訪了哪些網站。但是要記得：只有透過 Tor 瀏覧器進行的網頁活動才會被匿名。在電腦中安裝了 Tor 瀏覧器並不會影響電腦中其它使用的軟體也變得匿名(例如其它的一般網頁瀏覧器)。**

### 2.0 取得Tor 瀏覧器軟體包

開啟原用的網頁瀏覧器，如 Mozilla Firefox 或 Internet Explorer，然後在網址處輸入：[https://www.torproject.org/projects/torbrowser.html.en](https://www.torproject.org/projects/torbrowser.html.en) 。如果是透過搜尋引擊來找 Tor 瀏覧器軟體包，請確認它的網址是正確的。
![image](tool_torwin1.jpeg)

點擊紫色的下載按鍵來下載程式安裝包。
![image](tool_torwin2.jpeg)

網站會自動偵測你的作業系統，因此 WINDOWS 用戶將可以得到所合適的檔案。如果你想要不同的程式安裝版本，你可以滑動到下方的 Tor 瀏覧器下載區來找到你需要的檔案。
![image](tool_torwin3.jpeg)

許多瀏覧器會詢問確認你是否要下載該檔案，例如 Internet Explorer 11 會在視窗下方顯示出一個橙色的警示列。
![image](tool_torwin4.jpeg)

一般最好是先把檔案存在電腦上再進行安裝，所以先點擊儲存鍵。這個示範中顯示了 Tor 3.6.2 版本的安裝包,這是本指南撰寫時所介紹的安裝版本；或許你在讀本手冊時，已有了其它更新的版本。

### 2.1 安裝 Tor 瀏覧器軟體包

下載完成後，你可以到檔案暫存的位置來開啟資料夾。通常暫存的位置是在「下載」目錄裏，滑鼠雙擊程式安裝檔案 _torbrowser-
install-3.6.2_en-US.exe_ 
![image](tool_torwin5.jpeg)

此時會出視一個關於軟體來源的警告視窗，你必須小心注意這些警告以確認是否為你要安裝的軟體、來自可信任的官方網址、透過安全的連線方式而取得等。如果一切都沒問題，那麼就繼續往下走，點擊執行鍵。
![image](tool_torwin6.jpeg)

有一個小視窗會詢問你要使用什麼語言包，它提供了多種選項。選擇你要的語言後點擊“OK”鍵
![image](tool_torwin7.jpeg)

這時候會出現一個新的小視窗告訴你　Tor 瀏覧器將要被安裝的位置。一般預設的位置是你的電腦桌面，當然你可以依習慣來改變你想要安裝的位置，不過現在我們先讓它維持預設的狀態。
![image](tool_torwin8.jpeg)

當安裝完成後，你可以看到一個視窗告之安裝程序已完成。如果你點擊完成鍵，Tor 瀏覧器會自動立即開啟。現在先取消執行 Tor 瀏覧器的選項，我們稍後再回來使用它。如果你不小心點擊了檢查項而Tor 瀏覧器開始啟動了，只要先把它的視窗關上即可。
![image](tool_torwin9.jpeg)

Tor 瀏覧器軟體包並未一併安裝其它程式，也不會出現在你電腦上開始的程式選單中。
![image](tool_torwin10.jpeg)

### 3.0 使用 Tor 瀏覧器軟體包 

**第一次使用 Tor 瀏覧器** ：當你完成程式安裝時，並未選擇立即啟動，這是第一次啟動 Tor 瀏覧器。如果你完全按照預設的安裝設定，你將會在電腦桌面上看到一個名為“Tor Browser”的資料夾。
![image](tool_torwin11.jpeg)

打開這個資料然後雙擊其中一個叫作“Start Tor Browser”的檔案
![image](tool_torwin12.jpeg)

第一次啟動 Tor 瀏覧器，你會看到一個視窗可讓你調整必要的更動。當然也可以之後再回來進行變動，所以先來連上 Tor 網路，請點擊「連線」。
![image](tool_torwin13.jpeg)

點擊連線後，會出現一個綠色列桿的新視窗顯示 Tor 瀏覧器正在啟動中。
![image](tool_torwin14.jpeg)

通常第一次啟動會花較長的時間，請保持耐心。過幾分鐘後，Tor 瀏覧器就完成連線設定而會開啟網頁瀏覧器，恭喜你成功安裝好 Tor 瀏覧器。
![image](tool_torwin14.jpeg)
