[Title]: # ()
[Order]: # (0)

# JITSI 工具指南

## Jitsi 工具指南
安全的語音、視訊與即時通訊軟體

**學習內容：** [撥打電話](umbrella://lesson/making-a-call)

**下載地點：** [https://jitsi.org/Main/Download](https://jitsi.org/Main/Download)

**電腦需求：** Windows、Mac OS X、Ubuntu、Linux 等作業環境

**本指南中所用的軟體版本：** Jitsi 2.4

**版權宣告：** 免費開源軟體

**程度：** 初學者

**所需時間：** 15-20 分鐘

### 1.1 開始啟動　

**使用Jitsi可讓你：**
- 替代 Skype 進行電腦之間安全加密的語音通話、簡訊傳送以及視訊會議。
- 它可以登入且利用你已有的通訊服務帳號，如 Facebook、MSN、Google Talk、Yahoo Messenger等，同步與不同頻道的聯絡人通訊。
- 它可以與我們所介紹的其它軟體共用，如 Pidgin、Adium、ChatSecure　同步進行安全通訊。

### 2.1 如何安裝 Jitsi

要安裝 Jitsi, 請執行以下步驟:

**第 1 步.** 雙擊所下載的檔案（例如 windows 系統使用的 jisi-2.4-latest-x86.exe)，打開檔案時，會自動彈出安全警告視窗。然後點選「下一步」來啟動 Windows 安裝畫面，它接著會出現「歡迎來到 Jitsi 簡單安裝」視窗。

**第 2 步.** 點選「下一步」來激活「末端用戶使用版權絛款」視窗；點選「接受服務協議」選項以進行「下一個」步驟／繼續點選「下一步」以進入檔案安裝的「資料夾目的地」視窗。

**第 3 步.** 選擇「下一步」以啟動「其它任務」然後目前先同意軟體預設的設定。

**注意：** 當電腦重新開機後，打開「自行啟動 Auto-start」 功能可能會讓電腦的速度變慢，尤其當你的電腦上有多個應用程式設為自行啟動狀態。

**第 4 步.** 點擊「下一步」進入「準備好安裝 Jitsi」視窗，然後點選「安裝」即會啟動「Jitsi安裝中」畫面並顯示目前的安裝完成進度。

**第 5 步.** 點擊「完成」以結束安裝手續即會自動開啟 Jitsi。首先會出現「登入」畫面如下
![image](tool_jitsi1.png)

**注意：** 有點時候安裝與第一次啟動 Jitsi 後，電腦會彈出「安全警示」視窗其情況如上圖。

**第 6 步.** 同時選擇「私密 Private」與「公開 Public」網路二個選項，再點擊「同意取用 Allow access」。可以看到「Jitsi 登入視窗」或是主要的用戶使用介面視窗。
![image](tool_jitsi2.png)

### 2.2 如何在Jitsi新增帳號

請注意即使 Jitsi 使用加密，網路通訊服務的提供商如Google、Facebook仍然會監控你的通訊(也包括你所通訊的對象)，也會和第三方分享如政府或私人公司這些資訊。因此儘管 Jitsi 有加密功能，最好還是避免使用這些服務來做敏感議題的通訊。

### 2.2.1 如何新加入 Gmail/Google 帳號

**注意：** 以下以 Google Talk 帳號為例來說明安裝過程，其它的通訊協議安裝也是大同小異。不同的通訊協議服務提供商之間某些通訊或加密的功能或許會失效 (如 Facebook、Gmail、Yahoo 等等)。但基本上同一個服務提供者不同帳號之間的通訊應該還是沒問題。

**第1步.** 選擇啟動　**Start > Jitsi**　或是雙擊桌面上的 Jitsi 圖示來開啟應用軟體。

**第2步.** 在「登入」畫面下，輸入你的 Gmail 帳號的用戶名稱和密碼，依下方的圖像所示：
![image](tool_jitsi3.png)

**注意：** 你可以同時使用不同聊天服務協議並新增多個帳號。

**第3步.** 點「登入」以激活你的即時聊天視窗。
**注意：** 如果你關閉登入視窗，或是你需要新增其它的帳號，可在_File > Add new account..._ 選單中進行。
在新出現的視窗中選擇「網路　Network」為 Google Talk，然後再打入Gmail 帳號的用戶名稱與密碼，一如下圖所示：
![image](tool_jitsi4.png)

要在 Jitsi 上認證你所註冊的 Gmail 帳號, 請依照以下步驟：
**第1步.** 在選單下** Select **Tools > Options** 以激活以下視窗：
![image](tool_jitsi5.png)

**注意** 如果你採用二步驟認證方式以保護 Gmail 帳號的取用，當你試著透過 Jitsi 以一般密碼來登入 Gmail 帳號，可能會收到如下的訊息。要登入Jitsi，你得要產生一組「應用程式專用」密碼。請依 Googl 的[說明指示來進行](https://support.google.com/accounts/answer/185833?hl=en)。

### 2.2.2 註冊新的 Jabber/XMPP、SIP 帳號或是把已有帳號加到 Jitsi

Jabber/XMPP 、SIP 開放標準的文字與聲音通訊. 有許多伺服主機提供免費的帳號申請好讓你使用 Jitsi。下面我們推薦一些適合作敏感通訊使用的服務主機

* **Riseup.net** Jabber/XMPP account

如果你有 Riseup.net 安全電子郵件服務的帳號 (主機位於美國) 你也可以利用在 Jisti 底下加入這個帳號來進行 Jabber/XMPP 網路通訊-請見下面如何新增已有 Jabber/XMPP 帳號的介紹。

* **Jabber.ccc.de** 其它 Jabber/XMPP 帳號

依以下步驟在Jabber.ccc.de 註冊帳號 (其主機位在德國):

**第1步.** Jitsi 選單底下, 選擇 **_File > Add new account..._** ，在新彈出的視窗中，選擇 **_Network:_ XMPP** 并检查 _Create a new XMPP account option_ 。在伺服器位置 *Server，打入　jabber.ccc.de*　再輸入你想取的 XMPP 用戶名稱以及密碼，然後按密碼欄位的確認鍵Confirm，它就會出現以下畫面
![image](tool_jitsi6.png)

**第2步.** 點擊 **Add**，在成功註冊後你將可以看到一個類似以上的畫面。
如果你想要的用戶名稱已被使用, 註冊過程將會失敗而出現以下訊息： _We failed to create your account due to the following error: Could not confirm data_ 。你可以試著用不同的用戶名稱再重新一遍註冊過程。

**注意** 如果你超過12個月未登入jabber.ccc.de，你的帳號將自動遭到移除而你的用戶名稱也可能被其它人選用。

* **ostel.co** SIP 帳號

**SIP** 帳號無法透過 Jitsi 軟體來進行註冊。這個 **ostel.co** 伺服器(主機位於美國)提供[用戶在其網站上註冊](https://ostel.co/users/sign_up)。輸入你要的用戶名稱，密碼以及一組你現有的電子郵件，然後點擊網頁上的 _Sign up_ 按鍵。順利完成註冊後再回到 Jitsi，在選單中選擇在 **_File > Add new account..._** ，選擇 **Network: SIP** ，然後打入之前在網頁上申請的用戶名稱(例如：terence.the.tester@ostel.co) 以及密碼，再點擊 **Add** 。請見下面的參考圖片：
![image](tool_jitsi7.png)

* **新增已有的 Jabber/XMPP、SIP 帳號到 Jitsi**

如果之前已有 Jabber/XMPP 或 SIP 帳號，你可以把它們加到 Jitsi。在選單下選擇 **_File > Add new account..._** ，然後再選擇適合的網路協議服務(依 XMPP 或 SIP 等帳號類型而定)。

### 2.2.3 如何加入 Facebook 帳號

首先你得在 Facebook 上完成二項設定變更才能讓 Jitsi 可以串結你的 Facebook 聊天協議。

**Facebook 用名名稱**

Facebook 要用一個用戶名稱來連結到 Jitsi 以便使用其聊天功能，大多數旳臉書用戶已有其用戶名稱。要查出你的用戶名稱，請登入自己臉書帳號：你的用戶名稱正是當你檢視自己的時間表或頁面時，出現於網址列之中出現於 _https://www.facebook.com/_ 之後的名字。你的用戶名稱也會顯示在你的 Facebook 個人電子郵件地址(ex: username@facebook.com)。你可以看見或是變更這個用戶名稱，其作法是到你的臉書 _Account Settings > General_ 之處或是網址處打入[https://www.facebook.com/username](https://www.facebook.com/username) 。設定用戶名稱 Facebook 可能會要求你的帳號進行認證，其步驟要求傳送認證碼簡訊到你的手機上。

**App Settings 應用程式設定**

Facebook的應用程式平台必須先開啟，這樣 **Jitsi** 才能夠連結到 Facebook 聊天功能。到你的臉書 _Account Settings > Apps_ 底下檢其設定是否開啟。它將打開你帳號下的"應用程式平台"。

**注意** 啟動了臉書的"應用程式平台"，也會把你個人的臉書資料開放給其它第三方的應用程式開發者。這些資料並不只有供你自己同意的臉書應用程式來使用，也會包括許多你朋友所使用的臉書應用程式。因此在打開了臉書的"應用程式平台"之後，記得要檢查 "Apps others use"「其它應用程式使用」底下的設定。這個設定可讓你向臉友使用的應用程式隱藏某一些個人資料，不幸的是，Facebook並未提供全盤的個人資料隱藏方式。某些類別的資訊，(例如朋友清單、性別或是其它你設為公開的資訊)都可以被看到，只要你開啟了Facebook的"應用程式平台 application platform"。所以你可以決定是否要接受這樣的隱私交換。

現在你可以準備在 Jitsi 加入你的臉書帳號了，請依如下的步驟：

**第 1 步.** 由主選單下選擇 **_File > Add New Account..._**

**第 2 步.** 在新增帳號的對話視窗中，在 **Network** 選單中挑 _Facebook_，然後輸入你的用戶名稱和密碼，再點擊 **"Add"**
![image](tool_jitsi8.png)

### 2.3 如何更改 Jitsi 帳號的密碼

知道如何變更帳號的密碼是一個重要的安全要素。許多用於 Jitsi 的帳號在設定下提供了密碼更新的方式，可透由網頁介面來進行。但是有些 Jabber/XMPP 與 SIP 帳號沒有任何網頁介面可以來管理密碼更新。要變更這些運行於 Jitsi 的帳號密碼請依以下步驟：

**第 1 步.** 在選單下選擇 **_Tools > Options_** ，再選擇 **_Accounts_** 分頁

**第 2 步.** 點擊 **_Edit_** 鍵以激活新視窗。

**第 3 步.** 點擊 _改變帳號密碼_ ，以激活 _變更帳號密碼_ 視窗。

**第 4 步.** 重覆輸入二次新密碼後點選確 _認鍵_ OK，然後關閉視窗。

**第 5 步.** 關閉簡易帳號註冊視窗。

### 2.4 如何設定 Jitsi 以提高其安全性

### 2.4.1 取消與移除所有的通話和聊天記錄

Jitsi 原則會預設儲存語音通話、文字聊天的記錄。你可以點擊 Jitsi 主視窗中的圖示來取用語音或視訊通話資料：
![image](tool_jitsi9.png)

若要看文字聊天記錄則可以到聊天視窗中點擊聯絡人底下一個像是計時器的小圖示：
![image](tool_jitsi10.png)

即便使用 OTR 方式加密了所有聊天的內容，但你送出或收到的文字訊息仍然會以開放文字格式存在你的電腦上。

要防止 Jitsi 收集這些資訊(以及移除已累積的資料)，你和你的聯絡人應該要採取以下步驟：

**取消 Jitsi 收集資訊的功能：**

**第 1 步.** 在選單下選擇 **_Tools > Options**_，選擇 **_General_** 分頁然後取消 _Log chat history_ 的選項。

**第 2 步.** 在 _Options_ 視窗下, 首先選擇 _Advanced_ 分頁, 然後 **_再選擇 Logging_** 部份，取消 **uncheck the _Enable packet logging_** 選項，其如下圖所示
![image](tool_jitsi11.png)

要重啟 Jitsi 這些變更才會生效。

**要移除你過去的通話與聊天記錄:**

**第 1 步.** 關上 Jitsi

**第 2 步.** 到 Jitsi 使用者資料夾 _history_ver1.0_ 底下移除全部記錄資料。如果只要消除某一部份的記錄，也可以移除 _history_ver1.0_ 的子目錄。至於_user profile_ 的位置與 _log history_ 依電腦作業系統而異:

* Windows XP 或更早版本上是 _C:\\Documents and Settings\\&lt;Windows login/user name&gt;\\Application Data\\Jitsi\\history_ver1.0_
* Windows Vista, 7, 8, 則是 _C:\Users\&lt;Windows login/user name&gt;\AppData\Roaming\Jitsi\history_ver1.0_
* Mac OS X: 在你的家目錄下 _~/Library/Application Support/Jitsi/history_ver1.0_
* Linux: 在家目錄下 _~/.jitsi/history_ver1.0_

參見[安全刪除課程](umbrealla://lesson/safely-deleting)以了解如何安全地移除資訊。

### 2.4.2 在文字聊天時使用私密傳訊

當你設定好 Jitsi 後，一般也建議盡可能採用私密與利用 OTR 加密的通訊方式。其作法是，在選單下選擇 **_Tools > Options_** ，再選擇 _Security_ 分頁中的 _Chat_ 子分頁並點選啟用螢幕下方的 _Require private messaging_ 功能。

### 2.4.3 利用主密碼來保護你的帳號密碼

最好不要讓Jitsi記住你帳號的密碼，如果讓它記憶帳密，任何取用你電腦的人都可以輕易地開啟 Jitsi 然後登入你的帳號。它也可能在「選項」視窗中看到你的密碼。所以 **強烈建議** 使用好的主密碼來保護你的帳密。一旦你設定好主密碼，Jitsi 在啟動後會詢問你。

**第 1 步.** 在選單中開啟「選項」視窗其方式是先選擇 **_Tools > Options_** ，再選擇 **_Security_** 分頁下的 **_Passwords_** 子分頁。然後點擊 **_Use a master password_** ，以激活 **_master password_** 之視窗。

**第 2 步.** 在新視窗下輸入你的主密碼。如何挑選一組強度高的密碼，請見 **[密碼課程](umbrella://lesson/passwords)**。

**第 3 步.** 點擊 _OK_ 以確認此密碼並激活視窗，彈出 _Master Password successfully set up_ 之訊息。點擊 _OK_ 關閉視窗後再重新回到 _Options_ 視窗其顯示如下圖：
![image](tool_jitsi12.png)


**注意：_Change Master Password_** 按鈕可讓你更新主密碼而 **_Saved Passwords_** 鍵則是讓你可以取用 Jitsi 所記住的密碼，也可以在需要時移除它們。

### Jitsi - 新增聯絡人以及文字與語音通訊

### 3.1 新增聯絡人 (buddies) 到Jitsi

在 Jitsi 下至少有了一組聊天通訊帳號登入後，你就可以開始新增聯絡並與他們通訊了。

**第 0 步.** 在主視窗下選擇 **_Start > Jitsi_** 或是雙擊電腦桌面上的 Jitsi 圖示以啟動。

**第 1 步.** 選擇 **_File > Add contact..._** 後將會啟動如下圖的視窗畫面：
![image](tool_jitsi13.png)

**第 2 步.** 選擇你要在哪一個聊天帳號下新增聯絡人(例如：_terance.the.tester@jit.si_)。

**可選擇的:** 你也可以新增聯絡人到其它聊天帳號的群組中，但是首你必須先創建一個群組。從選單下選擇 **_File > Create group...**_ 

輸入聯絡人的用戶名稱或電郵資訊到 **_「身份」ID 或「電話號碼」 Number_** 欄位中(例如：*sally.the.doer@jit.si*).

你可以選擇對方的名字或匿稱，其可見於 Jitsi 主視窗的聯絡人清單，將它鍵入在 **_ID or Number_** 的欄位裏。

**第 3 步.** 點擊 _Add_ 以關閉 _Add contact_ 視窗，返回 Jitsi 主視窗。在聯絡人清單上將會看到所新增的聯絡人正處於等待授權的狀態"Waiting for authorisation"

**第 4 步.** 一旦當你的聯絡人登入帳號後 (sally.the.doer@jit.si)，對方會收到一個彈出的通知表示你請求把她加入你的聯絡清單:
對方可以選擇： _Ignore_ 這樣你會一直處於等待被授權的狀態； _Deny_ 你將會收到請求遭拒的通知；或是 _Authorise_ 對方已同意你的請求加入所以在你的聯絡清單上可以見到對方。

### 3.2 文字聊天 OTR 加密(即時訊息)

現在你可以新增聯絡人或是同意它人的授權請求，你可以在聯絡清單上點擊對方名字底下相關的圖示來閧啟文字通訊、視訊或視訊電話、桌面分享等功能:
![image](tool_jitsi14.png)

**第 1 步.** 我們將採索 Jitsi 最主要的功能：安全文字聊天、採用 OTR 加密訊息。OTR 的功能類似於我們在本書其它課程中所提到的 GPG/PGP 方式。就如同 PGP，你和通訊者對象可以加密雙方的通訊之前，你們都要先設定好 Jitsi 以產生你們的密鑰。在選單下選擇 **_Tools > Options_** 然後再選擇 _Security_ 分頁下的 _Chat_ 子分頁。你將會看到一個類似底下的畫面：
![image](tool_jitsi15.png)

**第 2 步.** 再來,請點擊 **_Generate_** 鍵,你將會看到生成的指紋：
![image](tool_jitsi16.png)

每一個帳號會有一組指紋，你只需要在新增帳號或是安裝 Jitsi 進行這個動作，不要把現存的指紋移入其它設備上。

現在你可以進行通訊了:

**第 3 步.** 從 Jits 主視窗中選擇一名聯絡人後點擊 _send message_ 圖示 (聯絡人名字底下左邊算來第一個) 以打開文字聊天視窗:
![image](tool_jitsi17.png)

注意 _Encrypt chat with OTR_ 圖示，出現在聊天視窗右上方的位置。這個圖示將提醒你目前的聊天是否處於加密的狀態，例如現在這個小鎖是打開的(在鎖頭與鎖身之間有一個小空隙！)

**第 4 步.** 點擊 **_Encrypt chat with OTR_** 圖示，留意視窗圖示的變化：
![image](tool_jitsi18.png)

觀察到現在鎖已經完全關上了，這表示你和聯絡人之間傳送的任何訊都會被加密。留意這個訊息仍是 _unverified private_ 談話，你應該要 _authenticate_ sally.the.doer@jit.si.

**第 5 步.** 點擊授權連結 **_authenticate sally.the.doer@jit.si_** 以開啟 _Authenticate Buddy_ 之視窗：
![image](tool_jitsi19.png)

注意它會出現訊息建議你們雙方要透過其它管道(非目前所用的文字聊天)來比對指紋碼，這樣你才能更確認所通訊的聯絡人的確是你要找的當事人。比對指紋碼的好方式是當面進行或是透過視訊、聲音等較簡單方式來確認其它人的身份。完成指紋比對後，從拉下的選單中挑選 **_I have verified_** 指紋的選項，然後點擊 **_Authenticate Buddy_** 
![image](tool_jitsi20.png)

關上 _Authenticate Buddy_ 視窗以回到聊天主視窗。
![image](tool_jitsi21.png)

留意到現在小鎖圖示不再顯示橙色三角形與白色驚嘆號的危險標記。這表示已授權了你的聯絡人，**每一位聯絡人須要作一次授權的動作**。如果三角危險標記又再次出現，它表示你正在與一位未經授權者聊天。這種情況會發生在你的聯絡人在其它設備上安裝了 Jitsi 並使用不同的加密鑰匙(重安裝 Jitsi 或其它 OTR 程式等等)。這種情況下你要雙方重新授權以確認彼此通訊對像的身份。Jitsi 可讓你同時與多人文字聊天，但 OTR 加密只能在一對一時有效。

### 3.3 ZRTP 加密的語音與視訊聊天

Jitsi 提供獨立的可加密式語音和視訊聊天，其開放標準稱之為 ZRTP。要啟動這樣的加密聊天，你必須

**第 1 步.** 點擊 Jitsi 聯絡人清單上的某位聯絡人上的語音 (聯絡人名字下方左邊算來第2個) 或視訊圖示(第3個)。這將會彈出一個新視窗顯示 Jitsi 正在建立連線：
![image](tool_jitsi22.png)

你的聯絡人將會看到一個來電通知

**第 2 步.** 如果對方接受了這通來電你也會收到通知:
![image](tool_jitsi23.png)

**注意** 那個紅色的小掛鎖圖示表示目前通話仍未採行 ZRTP 加密。

**第 3 步.** 等候... 你和對方的程式正在建立加密連線，這會花上一點時間。如果成功了你將看到 _zrtp_ 字母顯示對應著橙色背景的關上掛鎖圖示，其如下圖所示。如果你無法成功建立連線，你仍可以通話但其並無加密。可以試著離線重啟 Jitsi 再試一次看看這次程式是否能順利加密連線。有時不同的聊天通訊服務提供者之間(如 Google、Jit.si) ZRT 加密功能無法運作。
![image](tool_jitsi24.png)

**第 4 步.** 觀察 _zrtp_ 字母下面部份掛鎖圖示會出現一串字母與"Compare with partner"的訊息。雙方查證確認是否看到的是相同的字母，如果是的話，它表示你們之間的通訊已經受到加密保護了。其它人無法干擾。你可以點擊 **_Confirm_** ，而原本橙色的 _zrtp_ 背景區也將轉變為綠色：
![image](tool_jitsi25.png)

**第 5 步.**現在你可以點擊黑色部份右上方的白色x標誌以關閉確認畫面：

Jitsi 可讓你進行多方的語音和視訊通話，但注意在這種多方通訊情況下。ZRTP 加密得涉及多方之間啟動連線而不只是雙方彼此通話而已。
