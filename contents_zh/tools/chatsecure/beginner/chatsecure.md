[Title]: # ()
[Order]: # (0)

# ChatSecure 工具指南
iPhone 與 Android 手機上的安全簡訊軟體

**課程內容：[傳送簡訊](umbrella://lesson/sending-a-message)**
**下載位置：[https://chatsecure.org](https://chatsecure.org)；也可以從手機上的 [Apple App store](https://itunes.apple.com/us/app/chatsecure/id464200063) 或是 [Google Play store](https://play.google.com/store/apps/details?id=info.guardianproject.otr.app.im) 直接下載。
**系統需求：**iOS 6.0, Android (各異)
**本指南所用版本：**2.2.4 (iPhone), 13.1.2 (Android)
**版權宣告：** Apple, GPLv3; Android, Apache 2.0
**其它參考資料:[https://guardianproject.info/apps/chatsecure/](https://guardianproject.info/apps/chatsecure/)
**程度：** 初學-中級
**所需時間：** 5-10 分鐘
![image](tool_chatsecure.png)

ChatSecure 是一個適用於 iPhone 與 Android 設備上的免費開源的應用程式，它可以讓用戶傳送通訊無記錄的即時簡訊。ChatSecure讓使用者透過手機來傳送聊天訊息或簡訊，以取代傳統的桌機或筆電。它可以相容於 iPhone 和 Android 手機。

ChatSecure 支援 XMPP 上的 OTR 加密。只要你通訊的對象也同樣使用相容 ORT 的即時聊天工具如 ChatSecure、Adium、Pidgin 或 Jitsi，則所有透過 ChatSecure 傳送的簡訊都可以完整保密。這個應用軟體還可以傳送語音簡訊、照片、檔案以及文字等。

當你利用 ChatSecure 傳送簡訊時, 這些簡訊並不會儲存在你手機記憶體。ChatSecure 和隱私外掛工具 Orbot 一同使用的話可以躲過大部份的防火牆、網路限制或黑名單。它也支援多帳號管理，所以你可以同時與臉書友人、Google 聯絡人或是其它有隱私顧慮的用戶選擇使用支援 OTR 加密功能的即時聊天軟體。

### 如何安全與設定ＣhatSecure

1. 下載安裝 ChatSecure

造訪 Apple App Store 或 Google Play 商店然後搜尋由 Guardian Project 所開發的 ChatSecure。選擇安裝與接受其服務條款，這個軟體就會自動下載安裝。

2. 開啟軟體來設定密碼

當你打開軟體時，會被要求要設定一組密碼，你也將被要求要創建一串密語好在手機上加密資料。如果你選擇這個功能，你的資料會在手機上以及傳輸過程中加密。如果你選擇略過此一步驟，你的簡訊在傳送時仍然會加密，但在你自己的手機上卻未有加密保護。相關的資訊可以參考有關「選擇強度密語」的部份，請見[密碼課程](umbrella://lesson/passwords)。

3. 設定帳號
你可以在ChatSecure上新增不同的聊天帳號，例如要加 Google Talk 或 Google Hangouts，選擇"Google"，要新增 XMPP 或 Jabber 網路簡訊服務，選擇"Jabber (XMPP)"。要新增你的 Facebook 帳號，也同時選擇"Jabber (XMPP)"。一旦你完成新增帳號步驟，輸入你的帳號名稱(或是電子郵件)以及密碼進行登入，你的聯絡人也會自動載入更新。
要新增更多聊天帳號，請點擊選單下的「帳號」分頁。在其右上方點擊"+"符號，你可以選擇加入已有的帳號或是新申請一個服務帳號。

### 如何使用 ChatSecure

1. 登入帳號

要登入帳號，請點擊選單下的「帳號」分頁然後開啟你要使用的聊天服務帳號。一但你登入後，其它人就可以透過手機或是電腦上的即時聊天工具來和你通訊。

2. 開啟端對端加密

你開始與某人進行網路聊天後，點擊顯示選單右上方的小鎖圖示然後選擇啟動加密功能"Start Encryption"。如果對方也安裝了相容OTR的即時通訊軟體，你可以決定是否要進一步認證雙方的指紋碼。

ChatSecure 提供三種方式來認證 OTR 指紋碼，但如果與你通訊的某人是透過電腦進行即時聊天而不是手機上的 ChatSecure，那麼最佳確認 OTR 指紋碼的方法則是透過其它溝通管道。你可以利用SMS簡訊(如 TextSecure)來重新傳送指紋碼，或是如果熟悉對方聲音的話可透過語音電話來口傳認證，使用PGP電子郵件，或面對面的直接比對認證。點擊"手動認證"功能 ChatSecure 就會顯示出你和通話者的指紋碼，如果經確認雙方都有相同的資訊，就可以點擊"認證"鍵。

ChatSecure 支援手動認證或是透過掃描用戶的條型碼（QR）認證.如果你們剛好在同一處空間，你可以輕鬆地用手機掃描對方手機上的條型碼或是念出指紋碼的內容來做確認。

3. 了解各種選項功能
- 如同電腦上使用的即時通訊軟體服務，ChatSecure　也可讓你選擇顯示為離線、忙錄、閒置或暫離等狀態。
- 要更改這些設定請點擊聯絡清單上方你顯示名稱的位置。ChatSecure　也可讓你進行多人群組聊天和新增聯絡人，這可透過主選單來做到。(注意群組聊天無法像一對一聊天時的通訊安全，這是由於 OTR 協定本身的限制。)
- 這個應用軟體也支援多媒體簡訊傳送，它可以拍照然後安全地把照片傳送給也安裝了端對端之間通訊加密軟體，也認證過身份正確的朋友。
- ChatSecure 可讓你選擇創建一個全新的 XMPP 或 Jabber 簡訊帳號，其支援 OTR 加密。如果你還未曾用過 XMPP 傳訊服務，這是一個了解通訊類自由軟體的好機會。