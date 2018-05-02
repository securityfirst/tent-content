[Title]: # ()
[Order]: # (0)

# SIGNAL 工具指南

## Signal 工具指南   
iPhones 撥打加密電話

**閱讀課程:**
- [打電話](umbrella://lesson/making-a-call)
**下載處:** 這個應用可自[Apple App Store](https://itunes.apple.com/us/app/signal-private-messenger/id874139669?mt=8)下載  
**電腦需求:** Requires iOS 7.0 或更新版。 相容於 iPhone, iPad, 和 iPod touch.  
**本指南中使用的版本:** Signal - Private Messenger 1.0.5  
**版本授權:** GPLv3  
**程度:** 初學者-中級  
**其它參考資料:**  
- [https://whispersystems.org/blog/signal/](https://whispersystems.org/blog/signal/)  
- [http://support.whispersystems.org/](http://support.whispersystems.org/)  
**時間需求:** 15-20 分鐘

**使用 Signal 可以:** 
- 使用智能手機透過無線網路或電信連線，撥打加密的語音電話。

注意:   
- 雖然它利用電話門號作為聯絡, 但實際上需要透過數據連線來撥打電話; 因此雙方的手機設備都必須都要有網路連線才能夠進行通話。 
- Signal 只能在雙方都是利用 Signal 的情況才能進行加密，或是用戶透過 Signal 和 RedPhone， 後者是一款在 Androids 手機上的應用程式。 (請另見 **[RedPhone 工具指南](umbrella://lesson/redphone)** 有關 Androids 手機的指示)

### 1.0 如何安裝 Signal 

**步驟 1:** 下載和安裝 Signal - Private Messenger在 iOS 設備, 進入 App Store 並搜尋 "Signal" 選取該應用 "Signal - Private Messenger" by Open Whisper Systems.
點擊下載應用並選擇"接受" iTunes Store 服務條款。此應用程式即會自動下載與安裝。點擊"Open"以啟動該應用。

**步驟 2:** 註冊與驗證手機門號 當看到像這樣的畫面時:
![image](tool_signal1.png)

請輸入手機門號並點擊"註冊" 為了驗證手機門號，你將透過簡訊收到一組6位數字的註冊碼；請在以下空格中填入這個代碼。如果一直沒收到 SMS 簡訊，另一個方式是透過接收語音電話來驗證電話號碼。點擊 "驗證"

### 2.0 使用 Signal
為了使用 Signal, 欲通話的對方也必須有安裝 Signal 或 RedPhone。如果使用 Signal 試著打電話給某人但他們的手機並未安裝 Signal 或 RedPhone，這時 Signal 會詢問你是否要透過 SMS 邀請對方安裝 Signal, 它無法讓你繼續在該應用程式下完成電話通訊。
![image](tool_signal2.png)

 2.1 如何開始進行加密的語音通話

要向某位聯絡人開始進行加密的語音通話，必須使用  Signal 應用的撥號號器 (Android 下的 RedPhone 則有所不同, 它可以利用手機系統預設的撥號器。)

一旦通話連線建立了，通話的雙方會看到一對隨機的文字。這個文字配對可讓你來查驗雙方的身份和金鑰，也就是所謂的金鑰驗證手續。
![image](tool_signal3.png)

要查驗通話者最可信的方式是使用原本通話頻道外的管道來驗證來核對文字組合。如果能認得出對方的聲音，也可以大聲念出這些文字來核對。當然有些高明的攻擊者也許有辦法破解這個方法。文字組合必須要一模一樣。
