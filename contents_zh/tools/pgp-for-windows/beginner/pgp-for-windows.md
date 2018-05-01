[Title]: # ()
[Order]: # (0)

# PGP WINDOWS 電腦工具指南

## PGP WINDOWS 電腦工具指南 
Windows　的郵件加密工具

**學習內容:   
- [電子郵件](umbrella://lesson/email)**  
**下載點：**   
- GPG4Win  
- Mozilla Thunderbird  
- Enigmail  
**電腦需求：** 有網路連線,運行 WINDOWS 的電腦和一個電郵帳號
**本指南所使用的版本：**   
- Windows: Windows 7 旗艦版  
- Mozilla Thunderbird 24.6.0  
- Enigmail 1.7  
- GPG4Win 2.2.1  
**許可授權：** 自由軟體；混合式自由軟體授權  
**程度** 進階
**所需時間：** 30-60 分鐘

**PGP 可以：**  
- 保護電郵通訊防止被原收件者以外的人讀取。
- 確認電郵來自某特定對像，而不是為其它送件人偽造的訊息。(否則電子郵件很容易被造假)。這二者都是很重要的防禦措施，尤其如果自己是監控或假消息的對像。

### 1.0 開始之前 

要使用 Pretty Good Privacy (PGP), 需要安裝一些額外軟體來和珼用的雷郵客戶端程式一起工作，也需要建立一個個人私鑰，好讓自己保持私密。私鑰是用來解密收到的電子郵件並可提供數位簽名以證明此郵件的確來自原送件人。最後，你將會學到如何散佈自己的公鑰資訊，好該讓其它人可以寄給你加密電郵訊息，並驗證所收到的電郵的確來自原發信人。

**注意，收發兩端的電子郵件通訊都必須使用 PGP-相容軟體來能有效運作。**

通常只會在自己個人的設備上使用，而非共同的設備。幸好, PGP 可以運行在大多數桌面或手機設備，可以利用這些指南來協助設定其版本。這份指南則是給 WINDOWS 用戶參考。

### 1.1 綜覽

使用 PGP 來交換安全電郵，用戶須運用到以下三個軟體：GPG4Win (GNU Privacy Guard Windows 版，即 GnuPG), Mozilla Thunderbird and Enigmail。 

- GnuPG 是實際上用來加密和解密電郵內容的軟體。
- Mozilla Thunderbird 電郵客戶端軟體，不透過瀏覽器來讀寫電子郵件。 
- Enigmail 是　Mozilla Thunderbird 上的外掛工具，好讓上述軟體可以綁在一起使用。

注意！ 這個指南會教導如何使用在電郵客戶端軟體 Mozilla Thunderbird(其與微軟 Outlook　信件軟體功能類似) 使用 PGP。用戶可能有自己習慣使用的電郵軟體工具(或使用網頁電郵服務如 Google Mail 或 Outlook.com)。這個指南不會提及如何在這類軟體上使用 PGP。用戶可以選擇要新安裝 Thunderbird 工具來實驗 PGP 或者研究如何自用的軟體上是否有使用 PGP 的方式。我們目前還未其它電郵軟體上找到滿意的解決方式。

**使用 PGP 不會完全加密你的電子郵件：收件者和送件者的資訊仍未加密，主旨也不會加密！**

在現有的電郵系統中，加密送件人和收件人的資訊是不可能的。利用 Enigmail 外掛工具來使用　Mozilla Thunderbird　可以方便地讓用戶加密電郵內容。若有人在監看你的電郵，仍然可以看出你所通訊的對像和發信時間。

首先必須下載該軟體，安裝後進行設定與使用。 

### 2 下載軟體

### 2.1 取得 GPG4Win
可在　GPG4Win 下載頁， 下載　Windows 相似小型的安裝軟體　GnuPG (also known as GPG)。
![image](tool_pgpwin1.png)

點擊只帶有 GnuPG 要件的輕量(香草或軟量)GnuPG　安裝版本。 

**注意： 此 GPG 版本網站上只提共"http" 下載，而無安全"https" 下戴。如擔心自己受到某單位的監控會防礙你的網路連線，則可能要研究更深入的解決方式，例如下載安裝 Tails，它是一個安全的作業系統可替代 Windows.**

許多瀏覽器會詢問確認是否要下載此檔案。Internet Explorer 11 下方會顯示橙色邊框的瀏覽視窗。

大多數瀏覽器在繼續一下步之前最好先儲存檔案，故請點擊"Save" button_. 大多數瀏覽器會默認儲存在「下載」資料夾。 

### 2.2 使用 Mozilla Thunderbird

請到 Mozilla Thunderbird 官網
![image](tool_pgpwin2.png)

點擊標示"Thunderbird Free Download"的綠色按鍵。

Mozilla Thunderbird 官網會偵察到用戶使用的語言，如果使用 Thunderbird 其它的語言，請從點擊"Other Systems & Languages" 連結來作調整。

大多數瀏覽器會先詢問是否要下載此檔案， Internet Explorer 11 下方會顯示橙色邊框的瀏覽視窗。
![image](tool_pgpwin3.png)

大多數瀏覽器在繼續一下步之前最好先儲存檔案，故請點擊"Save" button_. 大多數瀏覽器會默認儲存在「下載」資料夾。 

### 2.3 下載 Enigmail

可從 Enigmail website　取得該軟體。
![image](tool_pgpwin4.png)

大多數瀏覽器會先詢問是否要下載此檔案， Internet Explorer 11 下方會顯示橙色邊框的瀏覽視窗。
![image](tool_pgpwin5.png)
大多數瀏覽器在繼續一下步之前最好先儲存檔案，故請點擊"Save" button_. 大多數瀏覽器會默認儲存在「下載」資料夾。 

下載 Enigmail, GPG4Win　和 Mozilla Thunderbird　之後， Downloads 資料夾內該有這三個檔案：
![image](tool_pgpwin6.png)

### 3 軟體安裝

### 3.1 安裝 GPG4Win

Windows Explorer 視窗一直維持開啟狀態，然後雙擊 gpg4win-xxx-x.x.x.exe。它會詢問是否要安裝此程式。請點擊"Yes" 按鍵。
![image](tool_pgpwin7.png)

此時會彈出一個視窗, 可讓用戶來檢視將會安裝什麼，接下來請按"Next" 鍵。
![image](tool_pgpwin8.png)

此時會出現授權許可畫面，請直接點擊"Next" 按鈕。
![image](tool_pgpwin9.png)

GPG4Win 香草包沒有元件可挑選，所以直接點選"Next "按鍵即可。至於 GPG4Win-Light 包，請取消選取所有可選的東西，只要安裝 GnuPG 即可。
![image](tool_pgpwin10.png)

接下來， 你可以選擇要把 GPG 安裝在哪裏。請不要變更原先默認的設定，請按"Next" 鍵。
![image](tool_pgpwin11.png)

下二個畫面會有一些安裝選項。請按"Next" 鍵並選擇"Install" 鍵：
![image](tool_pgpwin12.png)![image](tool_pgpwin13.png)

接下來可以看到一個帶有進度條的視窗當完成後會出現 "Installation Complete."。再次點擊 "Next"按鍵。
![image](tool_pgpwin14.png)

最後一個安裝步驟，請取消"Show the README file"旁的勾選，然後點擊"Finish"按鈕。
![image](tool_pgpwin15.png)

這樣就完成了，現在讓我們繼續換到 Mozilla Thunderbird　安裝流程。

### 3.2 安裝 Mozilla Thunderbird

類似於 GPG4Win, 雙擊檔案　Thunderbird Setup 24.6.0.exe 以安裝 Mozilla Thunderbird。像安裝其它軟體一樣，會詢問你是否要執行此軟體，請點擊  "Run" 鍵。
![image](tool_pgpwin16.png)

Mozilla Thunderbird 安裝時會詢問是否同意讓你的電腦來安裝此軟體，請按"Yes" 按鍵。
![image](tool_pgpwin17.png)

接下來應會看到　Mozilla Thunderbird 設定視窗，請點"Next" 按鍵。
![image](tool_pgpwin18.png)

接著用戶可選要使用標準設定或是自定設定。維持標準設定選項，然後按"Next" 按鍵。
![image](tool_pgpwin18.png)

Mozilla Thunderbird　會回報其檔案安裝的總結資訊，請點 "Install" 按鍵。
![image](tool_pgpwin19.png)

安裝過程結束後，可看到最後視窗可讓用戶啟動 Mozilla Thunderbird,　請點擊 "Finish" 按鍵。
![image](tool_pgpwin20.png)

### 3.3. Enigmail 安裝

**Step 1. 準備** 

Mozilla Thunderbird 首次安裝時，會出現一個小小的確認視窗詢問一些默認設定問題。建議挑選 "Set as Default" 選項即可。
![image](tool_pgpwin21.png)

這裏會詢問是否要有一個全新的電郵地址，在此請按 "Skip this and use my existing email"。現在須要設定 Mozilla Thunderbird 以便收發電郵。如果只習於使用 gmail.com, outlook.com, or yahoo.com, Mozilla Thunderbird 對你來說可能是一個全新體驗，會其實也大同小異。
![image](tool_pgpwin22.png)

**Step 2. Mozilla Thunderbird　新增郵件帳號**

出現一個新視窗
![image](tool_pgpwin23.png)

請輸入全名，電郵地址，以及電郵密碼。Mozilla 不會接取用戶的密碼或是電郵帳。接下來請點擊"Continue" 按鍵。
![image](tool_pgpwin24.png)

許多情況下 Mozilla Thunderbird 會自動地偵察必要的設定資訊。但有些情況 Mozilla Thunderbird 不知道完整的資訊，故用戶須自行手動輸入。以下例子是以 Gmail 為示範的情況:

Incoming Mail (IMAP) Server - Requires SSL  
- imap.gmail.com  
- Port: 993  
- Requires SSL:Yes

Outgoing Mail (SMTP) Server - Requires TLS  
- smtp.gmail.com  
- Port: 465 or 587  
- Requires SSL: Yes  
- Requires authentication: Yes  
- Use same settings as incoming mail server

**Full Name or Display Name:** [your name or pseudonym]

**Account Name or User Name:** 完整的　Gmail 地址(username@gmail.com). Google Apps 用戶請輸入包含域名的資訊 username@your_domain.com

**Email address:** 完整的電郵地址 (username@gmail.com) 如為 Google Apps 用戶請輸入 username@your_domain.com

**Password:** 你的 Gmail 密碼

**如果使用 Google 二階段認證(依個人的威脅模型，最好啟動此功能！)，則無法使用標準的 Gmail 密碼來登入 Thunderbird。通常會需要為 Thunderbird 建位一個特別密碼以便讀取 Gmail 帳戶。請見[Google's own guide](https://support.google.com/mail/answer/1173270?hl=en)了解如何操作。**

如果輸入的資訊正確，請點擊 "Done" 按鈕。
![image](tool_pgpwin25.png)

Mozilla Thunderbird 開始把郵件下戴到你的電腦上，試著寄一封測測信看看。

**步驟 3. 安裝 Enigmail**

Mozilla Thunderbird 與 GPG4Win　底下 Enigmail 的安裝有點不同，之前提過，Enigmail 是 Mozilla Thunderbird　的一件外掛工具。請在 "Menu button," 或稱Hamburger 按鍵下，選擇"Add Ons."
![image](tool_pgpwin26.png)

用戶會自動被帶到 Add-ons Manager 外掛管理分頁。
![image](tool_pgpwin27.png)

點擊小齒輸叫出小選單，並挑選"Install add-on from file" ，以開啟檔案選擇視窗。
![image](tool_pgpwin28.png)

檔案選擇視窗很可能會開啟下載資料夾，如果沒有的話，請直接到下載資料夾( Enigmail 被暫存的位置)點擊檔案 enigmail-1.7-tb+sm.xpi 然後按 "Open"。
![image](tool_pgpwin29.png)

現在會出現一個小視窗詢問用戶是否確認要安裝 Enigmail。請點"Install Now"按鈕。
![image](tool_pgpwin30.png)

Enigmail 外掛安裝完畢後，Mozilla Thunderbird 會重新啟動其程式來激活 Enigmail。點擊 "Restart Now" 按鈕好讓 Mozilla Thunderbird 重新啟動。
![image](tool_pgpwin31.png)

Mozilla Thunderbird 重新啟動，會另彈出一視窗以開始設置 Enigmail 外掛手續。維持"Yes, I would like the wizard to get me started" 選項並點擊"Next" 按鍵。
![image](tool_pgpwin32.png)

Enigmail 提供三種郵件處理選項。如果有別人的公鑰，則默設的選項是加密送出的郵件，若無對方的公鑰則不予加密。也可以利用　PGP keys　隨時對電郵予以加密，故用戶必須找出對方的公鑰，或是第三種選項：關閉自動加密功能，只當需要時才使用　PGP。
![image](tool_pgpwin33.png)

不知道你偏好哪一種方式，但"Convenient auto encryption" 似乎是個不錯的選擇。如果有疑問，則請選"Don't encrypt my messages by default." ，然後點擊"Next"按鈕。

現在可以對所有發出的電郵進行數位簽名。利用 PGP 簽名可讓收件者檢查用戶所寄出的訊息以及訊息內容並未遭到竄改。選取　"Sign my messages by default" 按鈕.但是這樣作也有缺點，就是會標誌出郵件有透過 PGP　來寄送。[有些國家](www.cryptolaw.org/) (諸如中國、伊朗、白俄羅斯和一些中東國家)使用未經許可的加密，即便只是私人用途，仍被視為違法，因此有人有足夠理由不想讓其它人知道自己在使用 PGP。

點擊"Next"按鈕。
![image](tool_pgpwin34.png)

現在可看到一個選項，可讓 Enigmail做些變動來設定 Mozilla Thunderbird.
![image](tool_pgpwin35.png)

若點擊點擊"詳情"按鈕，則可以檢視相關的變動
![image](tool_pgpwin36.png)

若默認使用PGP/Mime(稍後介紹其設定)，為了無縫轉移，下方的選項可以取消 (或重啟)：

- 關閉不佳的文字。  
- 以明文格式來查看訊息內容。
- 不要以 HTML 格式編寫內容。
最後的選項可以防止電子郵件在加密或解密上的潛在問題。請小心所選的功能可以移除粗體、畫底線或有色的文字，檢視過這些變動後，可點"OK button"


小視窗會自動關閉，請點擊 "Next" 按鈕。

現在要來進行建立私鑰與公鑰的手續。

### 4 建立私鑰與公鑰

安裝設定 Enigmail 外掛完成後，用戶將可以來建立建立自己的私鑰與公鑰配對，這是先假設用戶之前未曾建立私鑰與公鑰。

請點擊 "Next" 按鈕
![image](tool_pgpwin37.png)

除非已設定一組以上旳電郵帳號，Enigmail 會選擇已設定完成的電郵。第一件事是為私鑰取一組強度高的密語。請參見**[密碼課程](umbrella://lesson/passwords)** 了解其進一步的操作資訊。

確認有好好地記下記住了這串密語，或是把它記在紙上，並存放在一個方便查察的安全地方（如錢包或是皮包裏)。不要把記有密語的紙本隨處亂放。

請點擊 "Next" 按鈕

Enigmail　會顯示私鑰的資訊以及其設定選項。通常建議建立 4096-bit 長度的金鑰， 請點擊 "Next" 按鈕。
![image](tool_pgpwin38.png)

**密鑰會在一段時間後失效，若發生此狀況，其它人會停止用舊密鑰傳送郵件給你，雖然一般用戶不會收到警告或通知。因此最好能記下失效期限，留意在到期日之前要處理此問題。**

可以透過新鑰、延後到期日來延展已有密鑰的生命期，或是重新開始弄另一把新鑰來取代。這些方法都得要聯絡郵件通信人確認對方有最新的公鑰，而目前的軟體工具在自動更新密鑰的功能仍為不足。所以只好自己提醒自己。如果擔心自己無法處理好，也可以考慮設定一個永不過期的密鑰，這種情況下也可能對方透過這把密鑰寄了加密郵件給　你，但自己卻不再保有私鑰或不再使用 PGP。

Enigmail 會產生密鑰，有一個小視窗會彈出來詢問是否要生成一個撒銷證明。這個撤銷證明的重要之處在於可讓用戶將公鑰與私鑰變得無效。要注意的是，只是刪除私鑰並不會讓公鑰失效，反而可能收到許多加密郵件但卻沒法予以解密。

請點擊"Generate Certificate"按鈕。
![image](tool_pgpwin39.png)

出現的視窗會提供一個位置來儲存撤銷證明，可以將它存在電腦上，但我們建議最好把這個檔案存到 USB 隨身碟並放到一個安全的地點，也最好將帶有密鑰的電腦上移除此撤銷證明，以避及免發生不小心的撤銷情況。

更好的作法是，把這個檔案儲存在另一個加密的磁碟上，請選擇欲存放檔案的位置，並點擊"Save"按鈕。
![image](tool_pgpwin40.png)

現在　Enigmail 會再次給出關於儲存撤銷證明檔案的進一步指示，請點擊"OK"按鈕
![image](tool_pgpwin41.png)

最後順利完成製作公鑰和私鑰了。請點擊"Finish"按鈕。
![image](tool_pgpwin42.png)

### 5 可選的步驟　

### 5.1 顯示長 密鑰-IDs

下一個步驟完全可省略但它們在使用 OpenPGP 與 Enigmail　上很有幫助。簡言之，密鑰 ID 是指紋的一小部份。當要驗查某特定者的公鑰時，指紋是最好的方式。變動默認的設定以更方便來讀取證明的指紋。點擊證明按鈕， Enigmail 選項和密鑰管理。
![image](tool_pgpwin43.png)

出現一個視窗中有二欄：名字和密鑰 ID.
![image](tool_pgpwin43.png)

在最右邊有一個小的按鈕，點擊它來設定欄位，取消勾選密鑰 ID 選項並點選指紋選項。
![image](tool_pgpwin44.png)

現在欄位變成像這樣：
![image](tool_pgpwin45.png)

現在已設好一個傳送加密或一般郵件的電子信箱了，接下來可以繼續執行實際找人來交換加密郵件的手續了。

### 5.2 使用 PGP/MIME

這是最後一個可選擇的設定步驟，就是啟動 PGP/MIME 可讓加密或簽署附件更為容易。

透過選單按鈕可以來進行設定，滑鼠游標移到選項上再點擊帳號設定，即會開啟帳號設定視窗。
![image](tool_pgpwin46.png)

出現帳號設定視窗後，請點選 OpenPGP 安全分頁，再勾選 Use PGP/MIME by default. 接下來選 OK 按鈕. 現在 Enigmail 將會默認使用 PGP/MIME。
![image](tool_pgpwin47.png)

**使用 PGP 不會加密整個電郵，因此送件者和收件人收到的資訊會被加密，但加密送件者和收件人則會破壞電郵。使用 Thunderbird 與 Enigmail 外掛可讓用戶輕鬆地加密和解密信件內容。**

### 6.1 讓別人知道你使用 PGP

現在可開始用 PGP了，也許要讓別人知道以便於利用 PGP 傳送給你加密的訊息。

且看三種不同的方式讓他人可以知道你有使用 PGP。

**a) 透過電子郵件**

只須將自己的公鑰以附件方式寄給其它人即可。

在Mozilla Thunderbird　下撰寫郵件
![image](tool_pgpwin48.png)

填入收件人電郵與主旨欄，像是"my public key," 點擊 Enigmail 選單並選取 "Attach My Public Key" 選項。
![image](tool_pgpwin49.png)

現在可以送出電郵，而收件者可以下載並使用你所送出的公鑰。

如果使用這個方式，最好讓收件人可以透過其它通訊方式來驗證你的公鑰指紋，尤其如果電郵通訊已遭到攔截或被竄改的情況。

**b) 透過自己的網站**

除利用電子郵件外，可以把公鑰資訊放在自己的網站上。最簡單的作法是上傳公鑰檔案並作一個連結可下載，本指南不進一步介紹相關的手續，但使用它最好能知道如何把誦證明滙出成檔案格式以便在未來可使用。

點擊設定按鈕，選擇 Enigmail 底下的金鑰管理。

以粗體來突顯證明，然後用滑鼠右鍵來啟動選單，選擇滙出金鑰到檔案。
![image](tool_pgpwin50.png)

此時會出現一個帶有三個按鈕的小視窗，請選擇其中的"Export Public Keys Only"按鈕。
![image](tooL_pgpwin51.png)

確認沒有誤選到 "Export Secret Keys" 按鈕，因為這會滙出私鑰，讓別人可以假冒你的身份，如果他們成功地猜出你使用的密碼。

再在視窗會閧啟，以便於儲存檔案，為了更方便在以後找到，請把這個檔案存到文件資料夾之下。
![image](tool_pgpwin52.png)

現在可任意使用這個檔案了。

**c) 上傳到公鑰伺服器**

公鑰伺服器讓找尋與下載公鑰更為容易，大部份現代的公鑰伺服器都可同步，所以公鑰只須上傳到一個伺服器，最後會流傳到其它的伺服器上。

雖然將公鑰上傳到伺服器是一種便於讓其它人知道你持有公開的 PGP 證明，但也應知道由於伺服器的運作天性，一旦上傳了公鑰就沒辦法將其刪除，只能將其標註為撤銷記號。

**將公鑰上傳到伺服器之前，最好先考慮清楚是否想讓全世界知道你有一個公鑰但之後就無法將這筆資訊移除的後果。**

如果仍選擇要上傳公鑰到伺服器上，則重回到 Enigmail 密鑰管理視窗。

選擇 Keyserver 選項以及上傳公鑰選項。
![image](tool_pgpwin53.png)

### 6.2 找到其它也使用 PGP　的朋友

**a) 透過 email　取得他人公鑰**

可透過電郵附件收到別人的公鑰
![image](tool_pgpwin54.png)

雙擊新訊息，即會出現一個新分頁。注意視窗底下的附件，用滑鼠右鍵來點該附件，並選取"Import OpenPGP Key."。出現一個小視窗會返回滙出的結果，請按 OK 按鈕。
![image](tool_pgpwin55.png)

如果再次打開 Enigmail 金鑰管理視窗，可以直接檢驗結果。你的 PGP 金鑰會是粗體，因為它同時含有公鑰和私鑰。而剛才滙入的公鑰不會是粗體因為它不帶有私鑰。
![image](tool_pgpwin56.png)

**b) 以檔案方式得到公鑰**

可以從網頁或某的通訊聊天軟體來下載公鑰。如果是這種情況，通常下載的檔案會存到下載資料夾。

開啟 Enigmail 金鑰管理並選"File"選單，選取"Import Keys from File."
![image](tool_pgpwin57.png)

公鑰可能有不同的副檔名，例如.asc, .pgp, or .gpg。請選擇檔案並按"Open"按鈕。
![image](tool_pgpwin58.png)

一個小視窗會彈出，提供了滙出的結果，請按"OK"按鈕。
![image](tool_pgpwin59.png)

**c) 由公鑰伺服器取得對方公鑰**

伺服器是取得公鑰的有效方式，試試透過它找尋公鑰。請打開金鑰管理選單，然後點擊"Keyserver"選項選取"Search for Keys."
![image](tool_pgpwin60.png)

彈出一個帶有搜尋欄位的小視窗。可輸入完整的電郵地址, 部份電郵地址或名字。本示範中，以搜尋含有"eff.org."作為示範。
![image](tool_pgpwin61.png)

彈出一個大視窗，其中含有多種選項。如果向下捲動，會留意到有些證書為斜體和灰淡色。這類證明通常是已經過期或是被撤銷。
![image](tool_pgpwin62.png)

以 Danny O'Brien 的公鑰為例，其有一個逾期、撤銷的證書，一個有效的證書。請點擊左邊的地方選擇有效的證書，再按 OK 按鈕。
![image](tool_pgpwin63.png)

有些情況，某人可能有一個以上的證書，其皆顯示為有效。這可能是任何人自行上傳的公鑰證書，而公鑰並不真的為該電子郵件使用者所擁有。這種情況下，驗證指紋就顯得極為重要了。

彈出一個小視窗通知用戶是否成功：
![image](tool_pgpwin64.png)

Enigmail 金鑰管理員現在顯示新增的證明：
![image](tool_pgpwin65.png)

### 7.1 傳送 PGP 加密電郵

現在可以寄出第一封加密電子郵件了。在 Mozilla Thunderbird 主視窗下點擊 "Write" 按鈕，以開啟撰寫郵件的小視窗。
![image](tool_pgpwin66.png)

撰寫郵件訊息內容，並輸入收件人。為此測試目的，請選一名已有其公鑰的收件者。Enigmail 會偵測而自動地加密該郵件。
![image](tool_pgpwin67.png)

注意主旨行不會被加密，所以選一些無關看不出來重點的用語，例如 like "hello."_

當點擊"Send"時，會出現一個小視窗要求輸入你的 PGP 金鑰密碼。記得這個密碼和電子郵件密碼不是同一個！

輸入正確密碼並按 "OK"，你的電郵會被加密後送出。
![image](tool_pgpwin68.png)

電郵內容本身會被加密與變形，例如本例中的文字：
![image](tool_pgpwin69.png)

將會轉換成為：
![image](tool_pgpwin70.png)

### 7.2 收到 PGP 加密電郵

接下來看看收到加密電郵的情況。 Mozilla Thunderbird 會通知有新郵件，請直接按此訊息。
![image](too.png;_pgpwin71)

出現一個小視窗會詢問 PGP 金鑰的密鑰，記住：不會輸入成 email 密碼，然後按 "OK"。 
![image](tool_pgpwin72.png)

現在訊息會被解密顯示。
![image](tool_pgpwin73.png)

### 8 撤銷 PGP 金鑰

**a) 透過 Enigmail 介面撤銷 PGP 金鑰**

由 Enigmail 所產生的 PGP 金鑰會自動在五年會失效。如果遺失了所有檔案，只好希望一旦金鑰逾期別人會詢問別的金鑰資訊。

有些情況可能須在 PGP 密鑰到期之前取消它，例如希望另外產生一個全新更強的 PGP 密鑰。最簡單的方式是透過 Enigmail 的密鑰管理來撤銷自己的 PGP 密鑰。
![image](tool_pgpwin74.png)

在自己的 PGP 密鑰(粗體字顯示)上按滑鼠右鍵，然後選擇"Revoke Key"。
![image](tool_pgpwin75.png)

彈出小視窗，告知目前的狀況並取得當事人的確認。按"Revoke Key" 按鈕。
![image](tool_pgpwin76.png)

密碼視窗打開後，請輸入 PGP 密鑰密碼然後點選　"OK"。
![image](tool_pgpwin77.png)

會出現一個新視窗讓你知道此程序已成功，點擊"OK"。
![image](tool_pgpwin78.png)

當再次回到 Enigmail 密鑰管理視窗，留意 PGP 金鑰的地方已有不同，現在它會顯示為斜體或淡灰色。
![image](tool_pgpwin79.png)

**b) 利用撤銷證書來撤銷 PGP 金鑰**

之前提過, Enigmail 產生的 PGP 金鑰會在五年後自動失效，所以如果遺失所有檔案，可以確信其它人在逾期後會知道要詢問另一個公鑰資訊。

我們也提過，有些人會因為一些原因在金鑰失效前希望取消 PGP 金鑰。

同樣地，有人有原因要撤銷現有的金鑰。

有時可能會收到朋友的通知，告之其撤銷了自己的金鑰。

在前面部份，也許有人注意到當利用 Enigmail　金鑰管理員來撤銷金鑰時，其內部會產生與滙入撤銷證書。因此如果之前的金鑰已有撤銷證書，就會用到它來進行撤銷程序。 

啟動 Enigmail 金鑰管理員，點擊"File" 選單並選擇 "Import Keys from File."
![image](tool_pgpwin80.png)

將彈出一個視窗，讓用戶可選擇撤銷證明，請點擊該檔案然後按"Open"。
![image](tool_pgpwin81.png)

收到通知表示證書已成功地滙入，而金鑰已遭撤銷。請按"OK" 。
![image](tool_pgpwin82.png)

一旦按了"OK"，即會被帶回到 Enigmail 金鑰管理員，此時可看到撤銷的證書呈現灰暗與斜體字狀態。
![image](tool_pgpwin83.png)

如果撤銷的金鑰為自己所有，且之前曾上傳公鑰到伺服器，或許你需要重新上傳現在已被撤銷的金鑰到伺服器，好讓其它人知道不要再使用它。

現在有了適當的工具，請試試傳送自己的 PGP-加密郵件吧。