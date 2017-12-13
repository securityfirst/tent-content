[Title]: # ()
[Order]: # (0)

# Pidgin 工具指南:

## Pidgin 工具指南
Windows系統上的加密即時訊息軟體

**學習內容：
- [傳送訊息](umbrella://lesson/sending-a-message)**
**下載點：**
- [https://pidgin.im/download/](https://pidgin.im/download/)
- [https://otr.cypherpunks.ca/](https://otr.cypherpunks.ca)
**系統需求：**網路連線, 可運行 Windows XP 或更新版本的電腦，XMPP (Jabber)帳號。
_(Pidgin 能運作於多款網路聊天協議諸如：AIM、Facebook、Google Talk、MSN、MXit 與 Yahoo 等等。我們在此則介紹 XMPP，其前身為Jabber)_
**本指南所用版本:
- Windows 7 Ultimate; 
- Pidgin 2.10.9; pidgin-otr 4.0.0-1
**版權宣告：**自由軟體 ; 混合式自由軟體
**程度：**初學者
**其它參考資料：**[https://pidgin.im/cgi-bin/mailman/listinfo/support](https://pidgin.im/cgi-bin/mailman/listinfo/support)
**所費時間：**20 分鐘

**使用OTR 加密 Pidgin可讓你:**
- 透過單一軟體即可組織與管理大多數流行的網路即時通訊服務
- 能夠對即時聊天訊息進行加密,且不讓伺服器記錄這些聊天活動
- 能夠確保通訊對像是你要找的人

### 1.0 開始之前

Pidgin 是 Windows 系統中一個簡單好用的即時聊天軟體，它使用一種稱之為 OTR (Off-the-record)的網路協議，其可讓用戶能進行私密的談話。

- 注意:這裏的OTR不要和 Google 的 “Off the record”搞混了，後者是取消了聊天活動記錄功能但其並無加密或認證功能。
－　Pidgin 支援以下即時通訊服務: AIM、Bonjour、Gadu-Gadu、Google Talk、Groupwise、ICQ、IRC、MSN、MXit、MySpaceIM、SILC、SIMPLE、 Sametime、Yahoo!、Zephyr 以及使用 XMPP 訊息協議的即時通軟體。
- Pidgin 無法讓不同即時聊天服務協議進行通訊，例如如果你是用 Pidgin 來登入你的 Google Talk帳號，你就無法和使用 ICQ 的朋友進行網路聊天。但不管如何，Pidgin 還是可以設定其支援的各種通訊協議服務的多重帳號管理，這樣你就可以同時開啟 Gmail 與 ICQ 帳號來和使用其特定服務協議的朋友聊天（當然前提是Pidgin 也支援該服務協議)。
- Pidgin 系統預設會記錄下聊天活動，所以你必須知道要如何關閉變動此功能。但即便你這方取消了記錄聊天記錄的功能，但仍然無法控制談話的對方可能有留下記錄的資料。

**為何我應用 Pidgin + OTR？**
當你在　Google　或 Facebook　上使用 Google Hangout / Facebook 網路聊天時，聊天內容是用 HTTPS 加密，以免在傳輸時受到駭客或其它第三方攻擊。但 Google 或是 Facebook 握有你們聊天內容的讀取密鑰，並不保證他們會好好保護把這些資料，不交給政府當局。

安裝好 Pidgin 之後,你可以同時登入多個帳號,像是 Google Hangouts、Facebook 與 XMPP。Pidgin 可讓你不用 OTR 進行聊天。OTR 只有在雙方都使用的情況下才會有用，但你們仍然可以用 Pidgin 來聊天。Pidgin 也可以讓你進行 out-of-band 頻外認證以確保聊天的對象真是的是你要找的那個人.每一回的對話，都有一個選項能顯示密鑰指紋碼給你和聊天的對象."密鑰指紋碼"是一串像 "342e 2309 bd20 0912 ff10 6c63 2192 1928"的字符組合，用於認證長串的公鑰
.利用其它管道，如電子郵件或 Twitter 直接訊息來交換比對雙方的指紋碼,以確保沒有人干擾介入你們的線上聊天。

**限制：何時不宜使用 Pidgin + OTR？**

Pidgin是一套複雜的軟體，一開始開發時並未把安全當作優先考量。它存在著一些程式臭蟲，政府或一些大公司可能利用這些弱點來破壞安裝使用 Pidgin 的電腦。使用Pidgin 來加密你的通訊內容可以好好地防護非針對式網路聊天大規模監控，但如果你認為自己很可能成為資源充沛攻擊者（如國家機器）所針對攻擊的對象，你就該考慮強度更高的預防手段，像是 PGP 加密電子郵件。

### 2 下載與安裝

### 2.1 取得 Pidgin

你可以從Pidgin官網上取得 Windows Pidgin安裝程式。
![image](tool_pidgin1.png)

點擊_purple紫色的_下載分頁。_不要_點擊綠色的下載鍵，因為你要選擇的是不同的安裝檔案。

你會被引導入下載頁面。
![image](tool_pidgin２.png)

_再一次提醒_，**不要**點擊綠色「立即下載」鍵，因為我們要選不同的程式安裝檔案。
Pidgin 預設的安裝程式檔案很小，因為它並未包含全部資訊以及你所需要的完整檔案，也容易遇上失敗的狀況.所以你最好還是使用離線安裝，它包含所有必要的安裝材料。

點擊**offline installer**的連結，你將會被引導到一個標題為“Sourceforge”的新網頁。幾秒鐘之後，會彈出一個小小的視窗詢問你是否要儲存一個檔案。

- 注意：Pidgin 官網的下載頁使用"HTTPS"因此在防止欄截上相對安全。但被指向的另一個的 Windos 安裝檔案下載點 Sourceforge 使用的是未加密的"HTTP"網址故無提供相對的保護。這意謂著所下載的檔案可能之前有被人攔截替換的風險，這主要是來自本地網路架構的近用者可能企圖來執行針對你的個人監控攻擊(例如惡意的無線熱點提供者)或是國家政府計畫性的散佈竄改軟體給使用者。另一套 [HTTPS Everywhere](https://www.eff.org/https-everywhere) 瀏覧器外掛可以改變 Sourceforge 的下載網址到 HTTPS。我們建議你先安裝好 HTTPS Everywhere　再來進行下載。此外依我們過去的經驗，Sourceforge 網頁上常常有許多廣告會愚弄了使用者下載了不必要的程式，你可以安裝其它廣告封鎖軟體來避免這類煩人又困擾的廣告。

許多瀏覧器會先詢問你是否確認要下載這些檔案。Internet Explorer 11 會在下方顯示一道橙色的桿條。
![image](tool_pidgin3.png)

最好先是把檔案存到電腦上，所以點擊儲存鍵。大多數的瀏覧器會把下載的檔案存在「下載資料夾」Downloads folder。

### 2.2 取得 OTR

你可以到 [OTR](https://otr.cypherpunks.ca)下載頁面取得 pidgin-otr。它是 Pidgin 的外掛
![image](tool_pidgin4.png)

點擊下載分頁會被引導到下載點，請選擇 Win32 installer for pidgin 的連結
![image](tool_pidgin5.png)

許多瀏覧器會先詢問你是否確認要下載這些檔案，如 Internet Explorer 11 會在下方顯示一道橙色的桿條。
![image](tool_pidgin6.png)

對瀏覧器而言，最好先是把檔案存到電腦上。所以點擊儲存鍵，大多數的瀏覧器會把下載的檔案存在 「下載資料夾」Downloads folder。完成下載 Pidgin 與 pidgin-otr 的程式檔之後你的下載資料夾中會有這兩個新檔案「下載資料夾」Downloads folder：
![image](tool_pidgin７.png)

### 2.3 安裝 Pidgin

讓　Windows Explorer 視窗保持開啟，雙擊檔案 pidgin-2.10.9-offline.exe 你將會被詢問是否同意進行安裝該程式。點選同意以繼續。
![image](tool_pidgin8.png)

此時會有一個小視窗要求你選擇語言，選擇OK即可。
![image](tool_pidgin9.png)

過程中會有一個小視窗顯示安裝進度，點選下一步。
![image](tool_pidgin10.png)

現在你進入了版權總覧畫面，繼續點選下一步。
![image](tool_pidgin11.png)

你可以看到不同元件已被安裝，先不要改變設定，點選下一步。
![image](tool_pidgin12.png)

Pidgin即將完成安裝於某資料夾。不必更動資訊，點選下一步。
![image](tool_pidgin13.png)

你可看到一有捲動文字的視窗最後會出現「完成安裝」的訊息，點選下一步。
![image](tool_pidgin14.png)

最後出現的是Pidgin安裝畫面 installer，選完成鍵。
![image](tool_pidgin15.png)

### 2.4 安裝 pidgin-otr

再次回到 Windows Explorer 雙擊檔案 pidgin-otr-4.0.0-1.exe 你將會被詢問是否同意安裝此程式。點選同意鍵
![image](tool_pidgin16.png)

現在你進入了安裝過程的總覧畫面，繼續點選下一步。
![image](tool_pidgin17.png)

進入版權宣告部份，點選同意。
![image](tool_pidgin18.png)

pidgin-otr 即將完成安裝於某資料夾，不必更動資訊，點選安裝。
![image](tool_pidgin19.png)

最後出現的是 pidgin-otr 安裝程式畫面，點選完成鍵。
![image](tool_pidgin20.png)

### 3 設定

### 3.1 設定Pidgin

點擊 Windows 圖示到開始選單下選擇開啟 Pidgin。
![image](tool_pidgin21.png)

### 3.2 新增帳號

第一次啟動, 會出現歡迎畫面並讓你可以新增帳號，顯然此時你還未設定任何帳號，所以就點擊「新增」”Add“。
![image](tool_pidgin22.png)

現在你進入了「新增帳號」”Add Account “視窗。 _**Pidgin 能夠運作在不同的聊天服務協議底下,如AIM, Facebook, GoogleTalk, MSN, MXit and Yahoo等等,但我們還是把焦點放在XMPP上面,其前身是Jabber。**_ 

在協議輸入的地方“ Protocol entry”,請選擇“XMPP”

在用戶名稱地方”Username“ ,請輸入你的XMPP帳號名稱 

在網域名稱的地方"Domain entry",請輸入你XMPP 帳號的網域名

接著在密碼的地方,請輸入你的 XMPP登入密碼

如果點選「記住密碼」“Remember password”這個選項，或許可以讓你更易於近用帳號。但記住一旦選擇了「記住密碼」“Remember password”這個功能，你的密碼將會被儲存在你的電腦上,任何可以用你的電腦的人也可以取用到密碼。如果你憺心，就不要啟動這個選項。之後每當你登入 Pidgin 就會被要求輸入 XMPP 的帳號密碼。
![image](tool_pidgin23.png)

### 3.3 新增好友

現在你可能要新增一些人來聊天。在好友選單“Buddies menu”下選擇「新增好友」“Add Buddy”即會出現「新增好友」的視窗
![image](tool_pidgin24.png)

在新增視窗下,你可以輸入對方的用戶名稱。其它的使用者不必要來自同一個伺服器，但必須要使用相同的聊天服務協議，像是 XMPP 等。在「好友名稱」“Buddy's username”處，打入包括網域名的好友名稱，它有點像是電子郵件地址。在(可選的) 被「網名」”Alias“，你可以任意輸入好友的暱稱或名字。這不一定強制，但是有助於讓你記住聊天對象如果他的 XMPP 帳號很難記，點擊「新增」“Add”。
![image](tool_pidgin25.png)

一旦你點擊了新增鍵，對方會接到一則通知詢問是否同意受授權讓你把他加入到聯絡清單上。如果對方同意的話，你也會同意收到類似的加入請求授權。一樣點選「同意授權」“Authorize”
![image](tool_pidgin26.png)

### 3.4 設定 OTR 外掛

現在你必須要設定 OTR 外掛好讓你可以安全地聊天，在工具選單下點選外掛選項。
![image](tool_pidgin27.png)

滑動到“Off-the-Record Messaging”選項並點。它在“Off-the-Record Messaging”的地方點擊「設定外掛」“Configure Plugin”
![image](tool_pidgin28.png)

此刻會出現”Off-the-Record Messaging“的設定畫面。留意到它表示 “No key present”，㸃擊“Generate”鍵。
![image](tool_pidgin29.png)

會再出現一個小視窗並產生一組密鑰，這個動作完成後請按“OK”。
![image](tool_pidgin30.png)

你會看到以下的新訊息：「40個字符的文字字串,分成5組各8個字符」"a 40 character string of text, broken up into 5 groups of eight characters"。這就是你的OTR 指紋碼，點擊關閉鍵，再關上外掛設定的視窗畫面。
![image](tool_pidgin31.png)

### 4.0 安全地聊天

你現在可以和某人網路聊天了。你們雙方可以相互傳送訊息，但目前仍不算安全。即便你們都是透過連接 XMPP 伺服器，但還是有可能你們之間的連線會被不安全地窺看。在聊天視窗下，注意到它下方有顯示紅色的「非私密」“Not private”字眼，請點擊此一按鍵。
![image](tool_pidgin32.png)

選單將會開啟，請選擇「授權好友」“Authenticate buddy”
![image](tool_pidgin33.png)

這時又會跳出一個視窗詢問你：你要如何來授權好友? How would you like to authenticate your buddy?

它提供了三種方法:

**選項1：分享祕密**

事前雙方先約定好一行共享的文字祕密。最好直接交換而不要透過不安全的管道如S kype 或電子郵件與對方交換這則訊息。你和好友必須同時輸入這行文字後，再點擊「授權」“Authenticate”。
![image](tool_pidgin34.png)

如果你和好友未來仍會使用PIDGIN網路聊天，但目前使用中的電腦還未建立OTR指紋碼，分享祕密的認證授權是不錯的方法。

**選項2：手動指紋碼認證**

如果你和好友已經交換了指紋碼而現在要使用Pidgin來聊天，手動的指紋碼認證則能派上用場. 但如果你或對方更換了電腦，這就行不通了得要再建立新的指紋碼.如果你拿到的指紋碼和電腦上的相符合,請選擇「授權」 ”Authenticate“。
![image](tool_pidgin35.png)

<b>選項3：問題和答案**

如果你和好友尚未共享祕密也之前沒有指紋碼，那麼就得靠問問題與回答的方式來認證了.但這個方式要基於你們雙方對某事有共同的認識,例如一起做過的事情或共同記憶。

請輸入你要問的題目，不要太過簡單讓他人可以輕易猜到但也不要弄得太困難。一個好例子是---我們在內湖哪一家餐廳一起吃過飯??而壞例子則像：你在日本可以買到蘋果嗎?**答案必須完全符合，所以記住當挑選問題時你的答案是什麼，大小寫也有關係，所以你最好要考慮把它記下來(哪寫用大寫字母哪些用小寫字母)。**

輸入問題和答案後，點擊「授權」“Authenticate”。
![image](tool_pidgin36.png)

你的好友將會看到一個顯示問題回覆的視窗，他必須填入答案後再點擊「授權」“Authenticate”，然後對方會接到一則訊息以確認該授權是否成功。
![image](tool_pidgin37.png)
![image](tool_pidgin38.png)

當你的好友完成了授權手續, 你這邊也會接到成功授權的通知消息。
![image](tool_pidgin39.png)

你的好友也同樣地完成了對你的授權認證，如此一來你們雙方總算可以進行安全的網路聊天了。這時候在聊天視窗底下右側的「私密」“Private”圖示變成了綠色。
![image](tool_pidgin40.png)

### 5. 與其它軟體工作

不同的網路聊天協議軟體如 Jitsi, Pidgin, Adium,和 Kopete 之間應該也可以進行授權認證。你並不需要使用相同的聊天軟體才能利用 XMPP 與 OTR，但有時候軟體會有錯誤出現。OS X上的聊天軟體 Adium，在問題與答案認證方法上就偶有錯誤出現。當你遇到這種類似狀況時，檢查對方是否是使用 Adium 然後看看能否用其它方法認證。