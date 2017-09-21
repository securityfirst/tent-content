[Title]: # ()
[Difficulty]: # (初學者)
[Order]: # (0)

# Orbot & Orweb 工具指南　

## Orbot & Orweb 工具指南　
Android手機上的反審查與線上匿名軟體

**學習內容：[網際網路](umbrella://lesson/the-internet)**
**下載處：**
- Orbot：[https://guardianproject.info/apps/](https://guardianproject.info/apps/)或是在手機上的[Google Play商店](https://play.google.com/store/apps/details?id=org.torproject.android)。
- Orweb：[https://guardianproject.info/apps/](https://guardianproject.info/apps/)或是手機上的[Google Play商店](https://market.android.com/details?id=info.guardianproject.browser)
**系統需求：**Android 2.3 以上版本(Orweb 則為 Android 1.6以上版本)
**本指南所用版本:**Orbot：14.0.4.3； Orweb：0.6.1
**版權宣告：**Orbot: 免費自由， BSD；Orweb：自由開源軟體(GPL v3)
**程度：**進階者
**所需時間：**30-40 分鐘

**Orbot & Orweb 一起使用可讓你：**
- 對所造訪的網站隱藏數位身份
- 向網路服務供應商(ISPs)/網路監控機制隱藏你曾造訪哪些網站
- 繞過網路審查以及網路過濾規則.

**ORBOT**
![image](tool_orbot1.png)

### 1.1 開始之前要知道的事情

Orbot 讓 Android 設備可以連上 Tor 網路。更多資訊請見[網際網路課程](umbrella://lesson/the-internet)介紹

### 2.0 安裝 Orbot

**第 1 步：**在 Android 手機上，先到 [Google Play 商店](https://play.google.com/stor/apps/details?id=org.torproject.android)下載與安裝該應用軟體。
![image](tool_orbot2.png)

**第 2 步：**在安裝程序開始之前，會彈出畫面讓你檢示這個應用軟體可以取得哪些在手機上的權限。請仔細檢查，如果你同意這些授權，就按「接受」以完成安裝；如果你不同意讓軟體取得這些權限，就按退回鍵以取消安裝。

### 2.1 設定 Orbot

第一次使用 Orbot

**第 1 步：**輕觸應用程式圖示就可打開 Orbot
![image](tool_orbot3.png)

**第 2 步：**選擇你要使用的語言然後再按下一步“Next”.

**第 3 步：**簡易設定畫面將會出現，閱讀它的說明後再按下一步。

**第 4 步：**出現警告訊息，請仔細閱讀以了解其要求，再按下一步。
![image](tool_orbot4.png)

**第 5 步：**要求你同意授權讓 Orbot 可取得超級使用者權限。你的手機事前要已經取 rooted 即已取得最高權限才能安裝使用得 Orbot 的透明代理特性。這部份我們暫不在此指南做太多介紹。(有關 root 手機介紹，請參見**[行動電話課程：專家篇」(umbrella://lesson/mobile-phones)**）。如果你的智慧型手機尚未 root，只要改點_“I understand and would like to continue without Superuser”_。下一步畫面會解釋 Tor 的好處，你需要使用可和 Orbot 共用的應用軟體，或者是支援 HTTP 或 SOCKS　代理的軟體。
![image](tool_orbot5.png)

**第 6 步：**出現可和 Orbot 共同的軟體清單，記下它們然後繼續下一步。
![image](tool_orbot6.png)

**第 7 步：**已完成 Orbot 設定。最後一個畫面將介紹典型的 Tor 與 Orbot 使用，讀完這些介紹後，輕點「結束」“Finish”。
![image](tool_orbot7.png)

**第 8 步：**按下結束鍵後，你將可看到未啟動的 Orbot 螢幕
![image](tool_orbot8.png)

### 3.0 基礎使用

### 3.0.1 啟動與停止Orbot

**第 1 步：**觸擊與握住螢幕中央 Orbot 灰色圖示，直到其轉成黃色並顯示：_“Orbot is starting”_
![image](tool_orbot9.png)

**第 2 步：**初次啟動 Orbot 將出現一個通知以確認你成功地連上了 Tor 網路。你只會在安裝完成後第一次使用 Orbot 看到這個通知。輕觸“OK”以看到 Orbot 變成綠色顯示其正在運行中。
![image](tool_orbot10.png)

**第 3 步：**要讓 Orbot 斷線，只要輕觸綠色的 Orbot 直到它轉成灰色，或是要退出 Orbot，輕觸選單圖示(螢幕右上方的三個垂直點)選擇「退出」“Exit"
![image](tool_orbot11.png)

### 3.0.2 匿名地瀏覧網路

要匿名地在瀏覧網路或是線上聊天，你得安裝其它應用程式好讓你透過 Orbot　連結的代理伺服器.這就是 Orbweb，以下將介紹它的用法。

### 3.1 進階使用

### 3.1.1 新身份

你如果想要在網路上顯示新的連線來源, 在 Orbot 綠色的圖示滑動_左右_以取得_新身份_。它的圖像會旋轉然後顯示_"You've switched to a new Tor Identity"_
![image](tool_orbot12.png)

### 3.1.2 使用橋接

如果在你的國家使用 Tor 受到限制或是違法，或是你想要掩飾你正在使用 Tor, 你可以設定 Orbot 使用橋接。

**第 1 步：**輕觸螢幕上方三個交錯的小點圖示以進入設定畫面。

**第 2 步：**滑動到下面的橋接部份勾選"Use Bridges"使用橋接的選項方塊
![image](tool_orbot13.png)

**第 3 步：**輕觸橋接部份底下_"Use Bridges"_其將會出現一個要求輸入你所使用的_Enter Bridge Address_畫面。正確輸入後，輕觸“OK”，然後再重啟Orbot 以便開始利用_橋接_。

### 3.1.3 自動啟動Orbot

為確保你不會忘記使用 Orbot，可以將它設定為開機後自動啟用狀態。

**第 1 步：**輕觸螢幕上方三個交錯的小點圖示以進入設定畫面。

**第 2 步：**點選設定畫面上方啟動選項中的_"Start Orbot”_
![image](tool_orbot15.png)

**ORWEB**
![image](tool_orbot16.png)

### 1.1 開始前要知道的二三事
Orweb 是一個免費自由的 Android 平台行動手機應用軟體，其由 Guardian Project 開發，和 Orbot 搭配以便匿名瀏覧網路。

**注意:**目前 Orweb 的版本(0.6.1 and older)發現了程式臭蟲其可能會洩露你的資訊，如IP 位置給用HTML5作影片觀看的網站所有者。Orweb 仍可讓你來對付網路審查和防止網路連線服務商 (ISP)對你的監控，但我們不推薦用它來檢視那一些認為是具敵意的網站。這方面的資訊，請參考開發者的回應。Orweb 需在 Orbot 正確安裝與設定後才能正常運作。

記住：如果你未使用 Orweb 之前所創建的部落格或是寫的電子郵件，該網站仍會知道你真實的位置即使你現在已安裝使用了 Orweb。如果你想要有更高的匿名保護，以是使用 Orweb 要一併考慮採取的步驟:不要透過它來進入你使用真名的網路帳號、從不要給出你的個人資料、不要重做當你匿名時所做的同樣事情、運行 iOS 的 iPhones手機，可使用 [OnionBrowser](https://mike.tig.as/onionbrowser)。

### 2.0 安裝 Orweb

**第 1 步：**在你的　Android 手機開啟 [Google Play 商店](https://play.google.com/store/apps/details?id=info.guardianproject.browser)下載安裝。
![image](tool_orbot17.png)

**第 2 步：**在進行安裝前，會彈出畫面讓你檢示這個應用軟體可以取得哪些在手機上的權限。請仔細檢查如果你同意這些授權，就按「接受」以完成安裝。如果你不同意讓軟體取得這些權限，就按退回鍵以取消安裝。

**第 3 步：**完成下載安裝 Orweb 後，可以從開啟來啟動該應用程式。

###3.0 基本使用

**初次使用Orweb**

**第 １ 步：**輕點 Orweb 應用圖示
![image](tool_orbot１18.png)

**第 2 步：**Orweb 將會啟動且自動連到 _https://check.torproject.org_, 以確認其已連接上運行中的 Tor 網路。如果可以連上，你會看到一則訊息表示_瀏覧器正在設定使用 Tor_。如果 Orweb 無法連線到該網址，你會在瀏覧器中看到「出錯」的訊息若發生這種情況。建議你先檢查手機上的 Orbot 是否正確地安裝與有效運行。
![image](tool_orbot19.png)

**第 3 步：**要瀏覧網站,輕觸 Orweb 圖示畫面上方並輸入要造訪的網址後，再點擊螢幕上的"Go"觸控鍵
![image](tool_orbot20.png)

### 3.1 進階使用

### 3.1.1 Change User Agent 改變行動裝置

如果你希望能向造訪的網頁隱去使用上網的手機型號資訊，Orweb 能夠透過設定來裝成不一樣的設備型號。

**第 1 步：**輕觸螢幕上方的選單圖示(三個垂直點) 選擇設定“Settings”
![image](tool_orbot21.png)

**第 2 步：**在_設定settings_下，滑動到下方的隱私部份並輕點「行動裝置」 “User Agent”
![image](tool_orbot22.png)

**第 3 步：**出現一份_「行動裝置」User Agents_清單，點選你的選擇(例如輕觸 _iPhone_ 選項來用它作為設定的假裝設備，這樣你透過 Orweb 到其它網站時，都會把你認作是使用 _iPhone_ 上網)
![image](tool_orbot23.png)

### 3.1.2 清除瀏覧記錄

### 3.1.2.1 手動方式

手動清除你的網頁瀏覧記錄和緩存,和隱瞞手機上曾訪造的網站,請輕觸選單圖示 (有三個垂直點) 然後選擇“Clear History/Cache”.

### 3.1.2.2 自動方式

要自動清除的網頁瀏覧記錄和緩存:

**第 1 步：**請輕觸選單圖示 (有三個垂直點) 上的設定“Settings”.

**第 2 步：**在設定下,滑動到下方點選_“Clear Back History”_
![image](tool_orbot24.png)

**注意：＊＊當你作此設定後,你將無法再使用返回鍵功能來檢視你曾經訪問過的網頁。

### 3.1.3 清除 Cookies

**注意：**刪除cookies 會使你登出過去曾經已登入的網站

**第 1 步：**輕觸選單圖示 (有三個垂直點) 以找到設定鍵“Settings”.

**第 2 步：**滑動到下方 Cookies 部份選擇“Clear cookie data“.

**第 3 步：**輕點“OK”確認刪除 cookies
![image](tool_orbot25.png)