# 推薦的好用開源Android APP中文列表

Awesome FOSS Android Apps list (Traditional Chinese) 

本列表收錄的好用Android APP，全部都是自由開源軟體(Free and Open Source)，包含F-Droid與Github上的開源專案，不依賴Google Play下載。

文中提及的APP多半可以在[F-Droid](https://ivonblog.com/posts/what-is-f-droid/)這個開源應用程式商店取得，有些要額外加入軟體庫。

如果APP沒上架F-Droid，您也可以透過[Obtainium](https://ivonblog.com/posts/use-obtainium-to-download-foss-apps/)來下載Github、Gilab等網站發表的APK，真的不行再使用Google Play吧。

## 第三方應用程式商店

第三方應用程式商店包含F-Droid的第三方前端，UI相較於官方版F-Droid的比較流暢，有的還支援使用者評分。

|名稱|簡介|
|---|---|
|[Neo Store](https://f-droid.org/zh_Hant/packages/com.machiav3lli.fdroid/)|內建許多第三方軟體庫的F-Droid客戶端，Droidfy的後繼者。|
|[G-Droid](https://f-droid.org/en/packages/org.gdroid.gdroid/)|含有使用者評分功能的第三方F-Droid客戶端。|
|[Aurora Store](https://f-droid.org/zh_Hant/packages/com.aurora.store/)|免登入下載Google Play上的免費APP。|
|[Obtainium](https://github.com/ImranR98/Obtainium)|直接從軟體開發者的儲存庫下載APP，繞過F-Droid的版本。例如使用者自行填入Github儲存庫，Obtainium就會自動檢查新版本。|


## 瀏覽器

Android手機的瀏覽器陣營大致可以分為Chromium系(WebKit)與Firefox系(Gecko)。

為何同為自由軟體的Mozilla Firefox沒有上架F-Droid呢？請看[此討論串](https://forum.f-droid.org/t/why-is-the-normal-firefox-not-available-in-f-droid/11645)，Firefox僅在Github與Google Play上架，F-Droid只有Firefox的fork。

|名稱|簡介|
|---|---|
|[Mozilla Firefox](https://github.com/mozilla-mobile/firefox-android)| Firefox官方手機版，支援安裝擴充功能擋廣告、同步電腦帳號。|
|[Fennec F-Droid](https://f-droid.org/en/packages/org.mozilla.fennec_fdroid/)|基於Mozilla Firefox (Fenix)開發，強調隱私保護。支援登入Mozilla帳號同步。|
|[Mull](https://f-droid.org/en/packages/us.spotco.fennec_dos/)|基於Mozilla Firefox (Fenix)開發，強調隱私保護。支援登入Mozilla帳號同步。|
|[Iceraven](https://github.com/fork-maintainers/iceraven-browser)|Firefox的fork，保留舊版Firefox的功能，支援安裝更多電腦版的Firefox擴充功能，而非Firefox原版限定的擴充功能，還可以存取about:config調整細部設定。|
|[FFUpdater](https://f-droid.org/packages/de.marmaro.krt.ffupdater/)|自動下載新版Mozilla Firefox APK，免透過Google Play。|
|[FOSS Browser](https://f-droid.org/zh_Hant/packages/de.baumann.browser/)|以原生Android風格開發的瀏覽器。|
|[Duckduckgo Browser](https://f-droid.org/packages/com.duckduckgo.mobile.android/)|基於Mozilla Firefox開發，Duckduckgo公司推出的隱私搜尋瀏覽器。|
|[Tor Browser for Android](https://support.torproject.org/tormobile/tormobile-7/)|支援Tor協定的瀏覽器。需要啟用Guardian Project軟體庫。|
|[Thor Browser](https://f-droid.org/en/packages/threads.thor/)| 內建支援IPNS和IPFS的瀏覽器。|
|[Privacy Browser](https://f-droid.org/packages/com.stoutner.privacybrowser.standard/)|基於Android Webview打造的隱私瀏覽器，支援Tor協定。|
|[Bromite](https://www.bromite.org/fdroid)|基於Chromium開發，強調隱私保護，可設定預設開啟電腦版網站、支援Adblocker、GreaseMonkey腳本。|
|[Cromite](https://github.com/uazo/cromite)|Bromite強化版，強調隱私保護，支援更多Adblocker清單。|
|[Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium-android)| 去掉Google服務的Chromium瀏覽器，支援擴充元件。|
|[Brave Browser](https://github.com/brave/brave-browser)|基於Chromium開發的跨平台瀏覽器，有自家的同步帳號機制、搜尋引擎、加密貨幣功能。支援擋廣告、擋追蹤器。|
|[Kiwi Browser](https://github.com/kiwibrowser/src.next)|基於Chromium開發的瀏覽器，可以裝電腦版擴充功能擋廣告。沒有同步帳號功能。|
|[Midori Browser](https://github.com/kiwibrowser/src.next)|獨立開發的跨平台輕量瀏覽器，並非基於Chromium或Firefox。支援擋廣告。|
|[EinkBro](https://f-droid.org/zh_Hant/packages/info.plateaukao.einkbro/)|專為電子紙閱讀器設計的瀏覽器。|


## 網路連線 (防火牆、VPN、DNS)

|名稱|簡介|
|---|---|
|[Adaway](https://f-droid.org/zh_Hant/packages/org.adaway/)|擋廣告APP，無Root也可以使用(本機VPN)，有Root效果更好。|
|[Blockada](https://f-droid.org/packages/org.blokada.fem.fdroid/)|用DNS(本機VPN)擋廣告的軟體。|
|[NetGuard](https://f-droid.org/zh_Hant/packages/eu.faircode.netguard/)|限制APP連網權限。|
|[OpenVPN](https://github.com/schwabe/ics-openvpn)|跨平台VPN軟體OpenVPN官方Android版客戶端。|
|[迷霧通 Geph](https://github.com/geph-official/geph-android)|愛沙尼亞公司推出的翻牆VPN服務。|
|[TorServices (alpha)](https://f-droid.org/packages/org.torproject.torservices/)|Guardian Project提供的Tor網路服務，|
|[Orbot: Tor for Android](https://support.torproject.org/tormobile/tormobile-7/)|讓手機使用Tor網路連線。|
|[Proton VPN](https://f-droid.org/zh_Hant/packages/ch.protonvpn.android/)|Proton公司提供的隱私VPN服務。|


## 通訊軟體 (撥號、通訊錄、通訊軟體客戶端)

|名稱|簡介|
|---|---|
|[Koler](https://f-droid.org/zh_Hant/packages/com.chooloo.www.koler/)|撥號APP，可設定延遲回覆。|
|[Call Recorder](https://f-droid.org/packages/com.github.axet.callrecorder/)|通話錄音APP。|
|[QKSMS](https://f-droid.org/zh_Hant/packages/com.moez.QKSMS/)|簡訊APP。|
|[OpenContacts](https://f-droid.org/zh_Hant/packages/opencontacts.open.com.opencontacts/)|開源聯絡人APP。資料庫跟系統內建的分開，因此不會被其他APP讀取到聯絡人資訊。|
|[K-9 Mail](https://f-droid.org/zh_Hant/packages/com.fsck.k9/)|支援多個帳號的電郵APP，未來將與Mozilla Thunderbird合併。|
|[Protonmail](https://github.com/ProtonMail/proton-mail-android)|加密電子郵件Protonmail的官方客戶端。|
|[Telegram FOSS](https://f-droid.org/zh_Hant/packages/org.telegram.messenger/)|開源分支版的Telegram客戶端，跟官方的界面幾無差異。|
|[Elements](https://f-droid.org/packages/im.vector.app/)|存取群組聊天Elements.io的官方客戶端，支援Matrix通訊協定。|


## 主題裝飾 (桌布、啟動器)

|名稱|簡介|
|---|---|
|[Muzei](https://f-droid.org/packages/net.nurik.roman.muzei/)|自動抓取藝術畫當桌布的APP，還有各種擴充插件可選取不同圖片來源，例如NASA、國家地理、Pixiv、Danbooru。|
|[Materials Live Wallpaper](https://f-droid.org/zh_Hant/packages/com.reminimalism.materialslivewallpaper/)|渲染各種材質的物件當桌布，會跟著手機角度變化。|
|[Kvaesitso](https://github.com/MM2-0/Kvaesitso)|以搜尋為導向的啟動器。|
|[Neo Launcher](https://github.com/NeoApplications/Neo-Launcher)|支援自訂APP分類、自訂APP名稱、隱藏APP、手勢、快捷抽屜、桌面搜尋引擎等多樣功能的桌面啟動器。|
|[Lawnchair](https://github.com/LawnchairLauncher/lawnchair)|類似Nova Launcher的桌面啟動器。F-Droid版已不再更新，需到Github下載APK。|
|[KISS Launcher](https://f-droid.org/packages/fr.neamar.kiss/)|極簡風格桌面。|
|[Bliss Launcher](https://f-droid.org/zh_Hant/packages/foundation.e.blisslauncher/)|/e/ OS的初版桌面。|
|[Rootless Pixel Launcher](https://f-droid.org/zh_Hant/packages/amirz.rootless.nexuslauncher/)|Pixel手機風格的桌面。|
|[Last-Launcher](https://f-droid.org/zh_Hant/packages/io.github.subhamtyagi.lastlauncher/)|只有文字的極簡桌面。|
|[GIF Live Wallpaper](https://f-droid.rg/en/packages/net.redwarp.gifwallpaper/)|用GIF圖片當背景。|


## 檔案管理器

|名稱|簡介|
|---|---|
|[質感檔案 Material Files](https://f-droid.org/zh_Hant/packages/me.zhanghai.android.files/)|質感設計風格的檔案管理員，支援解壓縮、文字編輯、查看圖片、連接FTP伺服，有免Root存取Android/data目錄的能力。|
|[Fossify File Manager](https://f-droid.org/zh_Hant/packages/org.fossify.filemanager/)|簡易檔案管理員。|
|[Ghost Commander](https://f-droid.org/zh_Hant/packages/com.ghostsq.commander/)|有二個面板的檔案管理器，方便對照檔案。類似Total Commander。|
|[Amaze File Manager](https://github.com/TeamAmaze/AmazeFileManager)|有二個面板的檔案管理器，支援解壓縮、檢視PDF、文字編輯。附加空間清理、尋找重複圖片、連接雲端硬碟的功能。|
|[PlainApp](https://github.com/ismartcoding/plain-app)|界面極簡的檔案管理器，快速找出圖片與影片，還能寫markdown筆記、看RSS。該APP特色是能跑一個網頁伺服器，再從電腦網頁存取檔案。|


## 文字編輯器 (程式碼編輯器、文件編輯器、筆記)

|名稱|簡介|
|---|---|
|[Collabora Office](https://www.collaboraoffice.com/tag/f-droid/)|基於LibreOffice開發的手機文件編輯器，支援常見Office檔案格式和PDF檔。|
|[LibreOffice & OpenOffice document reader ODF](https://f-droid.org/zh_Hant/packages/at.tomtasche.reader/)|可檢視和編輯.odt、.ods、.odp文件。|
|[Librera Reader](https://f-droid.org/packages/com.foobnix.pro.pdf.reader/)|功能豐富的閱讀器，可開啟大多數格式的電子書，可存取雲端上的書籍。|
|[KOReader](https://f-droid.org/en/packages/org.koreader.launcher.fdroid/)|適合電子紙使用的電子書閱讀器。支援PDF, DjVu, EPUB, FB2, CBZ格式。|
|[Acode](https://f-droid.org/zh_Hant/packages/com.foxdebug.acode/)|程式碼編輯器，整合Git操作，支援語法自動偵錯。|
|[Squircle](https://f-droid.org/zh_Hant/packages/com.blacksquircle.ui/)|程式碼編輯器，支援語法自動偵錯。|
|[Markor](https://f-droid.org/zh_Hant/packages/net.gsantner.markor/)|編輯後可即時預覽成果的Markdown編輯器。|


## 多媒體 (相機、相簿、影片播放器、影像處理)

|名稱|簡介|
|---|---|
|[VLC](https://f-droid.org/zh_Hant/packages/org.videolan.vlc/)|影片兼音樂播放器，支援字幕，可在背景播放影片，或當成音樂播放器使用。|
|[mpv-android](https://f-droid.org/en/packages/is.xyz.mpv/)|MPV影片/音樂播放器Android版，支援使用電腦版的設定檔。|
|[Metro](hhttps://f-droid.org/en/packages/io.github.muntashirakon.Music/)|基於RetroPlayer開發的音樂播放器，支援讀取資料夾。|
|[Pods Companion For AirPods](https://f-droid.org/zh_Hant/packages/io.github.domi04151309.podscompanion/)|查看AirPods的電量。|
|[Open Camera](https://f-droid.org/zh_Hant/packages/net.sourceforge.opencamera/)|相機APP，可設定拍照錄影的成像品質、GPS、HDR等細部設定。|
|[Wifi Camera](https://f-droid.org/zh_Hant/packages/teaonly.droideye/)|用Wifi分享手機鏡頭，電腦瀏覽器可看到手機鏡頭畫面。|
|[Spydroid](https://f-droid.org/zh_Hant/packages/net.majorkernelpanic.spydroid/)|整人用的IP攝影機。|
|[RemoteVideoCam](https://f-droid.org/packages/org.avmedia.remotevideocam/)|讓二支手機連線，讓彼此看到對方的鏡頭畫面。|
|[Fossify Gallery](https://f-droid.org/zh_Hant/packages/org.fossify.gallery/)|相簿APP，可簡單編輯相片、批次刪除EXIF，類似快圖瀏覽。|
|[Les Pas](https://f-droid.org/zh_Hant/packages/site.leos.apps.lespas/)|相簿APP，可同步相片至NextCloud。|
|[Aves Libre](https://f-droid.org/packages/deckers.thibault.aves.libre/)|相簿APP，支援檢視圖片、影片、地圖資訊。|
|[Video Transcoder](https://f-droid.org/zh_Hant/packages/protect.videoeditor/)|輕量影片剪輯、轉檔工具。|
|[Litrato](https://github.com/DrMint/Litrato)|照片調整軟體，提供多款濾鏡。|
|[Pocket Paint](https://f-droid.org/zh_Hant/packages/org.catrobat.paintroid/)|圖片編輯軟體，支援簡易圖層、繪圖。|
|[miniPaint](https://viliusle.github.io/miniPaint/)|網頁修圖程式，支援手機版界面。Pixlr、Photopea替代品。|
|[Com-Phone Story Maker](https://f-droid.org/en/packages/ac.robinson.mediaphone/)|製作有聲書影片。|
|[Krita](https://f-droid.org/zh_Hant/packages/org.krita/)|專業的跨平台繪圖程式，僅適合平板使用。|
|[PixaPencil](https://f-droid.org/en/packages/com.therealbluepandabear.pixapencil/)|像素畫繪圖程式。|
|[Tux Paint](https://f-droid.org/en/packages/org.tuxpaint/)|兒童繪圖程式。|


## 社群媒體與影音串流 (客戶端)

社群媒體有些是使用開源前端，但後端閉源的服務。例如「Tusky」是前後端都開源，而「NewPipe」後端的Youtube是閉源的網路服務。

|名稱|簡介|
|---|---|
|[Frost for Facebook](https://f-droid.org/zh_Hant/packages/com.pitchedapps.frost/)|以行動版Facebook界面製作的APP，無敏感權限，並可使用手機網頁版Messenger。|
|[Barinsta](https://f-droid.org/packages/me.austinhuang.instagrabber/)|第三方Instagram客戶端，務求簡潔。|
|[Infinity for Reddit](https://f-droid.org/zh_Hant/packages/ml.docilealligator.infinityforreddit/)|第三方Reddit瀏覽APP，自動去廣告。註：由於Reddit API政策改變的關係，Infinity已變成付費軟體，個人使用的話建議自行[編譯Infinity](https://ivonblog.com/posts/compile-infinity-for-reddit/)。|
|[Fritter](https://f-droid.org/zh_Hant/packages/com.jonjomckay.fritter/)|免登入查看Twitter上的熱門話題。|
|[LBRY F-Droid](https://f-droid.org/zh_Hant/packages/io.lbry.browser/)|區塊鏈影音平台LBRY的官方客戶端。|
|[Youtube ReVanced / ReVance Manager](https://ivonblog.com/posts/youtube-revanced/)|破解版的官方Youtube。|
|[NewPipe](https://f-droid.org/zh_Hant/packages/org.schabi.newpipe/)|免登入觀看Youtube/PeerTube影片，無廣告、可下載影片、支援背景播放。|
|[PipePipe](https://f-droid.org/zh_Hant/packages/InfinityLoop1309.NewPipeEnhanced/)|類似NewPipe，免登入觀看Bilibili/Niconico/Youtube影片。|
|[Seal](https://github.com/JunkFood02/Seal)|採用yt-dlp技術的影片下載器。|
|[InnteTube](https://f-droid.org/packages/com.zionhuang.music/)|無廣告聆聽Youtube Music，支援播放歌詞、Android Auto。|
|[ViMusic](https://f-droid.org/zh_Hant/packages/it.vfsfitvnm.vimusic/)|無廣告聆聽Youtube Music，界面十分精簡，支援Android Auto。|
|[SpotTube](https://github.com/KRTirtho/spotube)|無廣告聆聽Youtube Music，配合Spotify補充歌詞。|
|[Blackhole](https://github.com/Sangwan5688/BlackHole)|免費音樂串流服務，背後服務使用的是JioSaavn和Youtube Music，因此會跑出許多印度歌。|
|[Thorium a PeerTube client](https://f-droid.org/zh_Hant/packages/net.schueller.peertube/)|觀看PeerTube的客戶端，需要手動加入站點。|
|[LibreTube](https://f-droid.org/zh_Hant/packages/com.github.libretube/)|觀看Youtube影片，無廣告、可下載影片、支援背景播放。透過實例儲存播放清單和訂閱列表。|
|[Tusky](https://f-droid.org/zh_Hant/packages/com.keylesspalace.tusky/)|支援多個實例帳號的Mastodon客戶端。|
|[GitHub](https://f-droid.org/zh_Hant/packages/com.github.mobile/)|Github官方客戶端，支援線上管理issues等操作。|
|[LabCoat](https://f-droid.org/zh_Hant/packages/com.commit451.gitlab/)|Gitlab官方客戶端，查看commits和issues。|
|[GitNex for Gitea](https://f-droid.org/zh_Hant/packages/org.mian.gitnex/)|Gitea客戶端，支援多樣操作。|
|[Pixiv Func](https://f-droid.org/zh_Hant/packages/site.xiaocao.pixiv/index.html)|第三方Pixiv客戶端。|
|[木之子漫畫閱讀器](https://f-droid.org/zh_Hant/packages/com.ero.kinoko/)|支援多個線上漫畫平台，可閱覽或下載漫畫。|
|[Tachiyomi](https://staging.f-droid.org/en/packages/eu.kanade.tachiyomi/)|免費漫畫閱讀器，支援多個線上平台。|
|[Mangayomi](https://github.com/kodjodevf/mangayomi)|跨平台版的Tachiyomi，支援許多線上漫畫與動畫平台。|
|[Hendroid](https://f-droid.org/zh_Hant/packages/org.nonononoki.hendroid/)|閱讀多個H漫網站的客戶端。|
|[EhViewer overhauled](https://github.com/Ehviewer-Overhauled/Ehviewer)|採用Material Design設計的E-hentai閱讀器。|
|[Boorusphere](https://github.com/nullxception/boorusphere)|界面簡潔的動漫booru貼圖站閱讀器。|
|[LoliSnatcher](https://github.com/NO-ob/LoliSnatcher_Droid)|支援多個動漫booru貼圖站的閱讀器，可搭配Hydrus Network使用。|
|[Hacki for Hacker News](https://f-droid.org/zh_Hant/packages/com.jiaqifeng.hacki/)|Hacker News閱讀器。|
|[KurobaEx](https://f-droid.org/zh_Hant/packages/com.github.k1rakishou.chan.fdroid/)|4chan匿名板閱讀器。|
|[Fluent Reader Lite](https://github.com/yang991178/fluent-reader-lite)|跨平台RSS閱讀器。|


## 遊戲

有開源手遊這種東西？當然有，有的完成度很高，並非小品遊戲等級。

因數量過多，請看[Android開源手機遊戲列表](https://ivonblog.com/posts/foss-android-games)


## 導航

|名稱|簡介|
|---|---|
|[OSMAnd~](https://f-droid.org/zh_Hant/packages/net.osmand.plus/)|以OpenStreetMap當作圖資的導航APP，支援離線地圖。|
|[Organic Maps](https://f-droid.org/en/packages/app.organicmaps/)|以OpenStreetMap當作圖資的導航APP，規劃登山、腳踏車路線，支援離線地圖。|
|[Street­Complete](https://f-droid.org/packages/de.westnordost.streetcomplete/)|回答簡單問題，改善OpenStreeMap圖資。|
|[Vespucci](https://f-droid.org/packages/de.blau.android/)|隨時隨地編輯OpenStreetMap圖資。|
|[GPSLogger](https://f-droid.org/zh_Hant/packages/com.mendhak.gpslogger/)|自動在背景紀錄GPS軌跡。|
|[OpenTracks](https://f-droid.org/en/packages/de.dennisguse.opentracks/)|紀錄體能運動紀錄。|
|[Trackbook - Movement Recorder](https://f-droid.org/en/packages/org.y20k.trackbook/)|紀錄健行、出遊的移動軌跡，使用OpenStreetMap當圖資。|


## 輸入法

|名稱|簡介|
|---|---|
|[Hacker's Keyboard](https://f-droid.org/packages/org.pocketworkstation.pckeyboard/)|內建許多電腦快捷鍵的英文輸入法，適合用於遠端桌面。|
|[AnySoftkeyboard](https://f-droid.org/packages/com.menny.android.anysoftkeyboard/)|支援多語言的英文鍵盤。|
|[OpenBoard](https://f-droid.org/packages/org.dslul.openboard.inputmethod.latin/)| 基於Gboard開發的英文鍵盤。|
|[中州韻TRIME](https://f-droid.org/zh_Hant/packages/com.osfans.trime/)|支援強大自定義配置的中文輸入法框架，使用RIME引擎。注音使用者請使用「洋蔥注音輸入方案」。|
|[樸實注音鍵盤](https://f-droid.org/zh_Hans/packages/org.ghostsinthelab.apps.guilelessbopomofo/)|基於新酷音輸入法開發的極簡注音輸入法。|


## 理財

|名稱|簡介|
|---|---|
|[Currencies: Exchange Rate Calculator](https://f-droid.org/en/packages/de.salomax.currencies/)|貨幣匯率轉換器，使用Frankfurter API。|
|[Catima](https://f-droid.org/zh_Hant/packages/me.hackerchick.catima/)|儲存實體卡片條碼。|
|[My Expenses](https://f-droid.org/en/packages/org.totschnig.myexpenses/)|記帳APP，可匯出為QIF、CSV。|


## 工具程式 (以及不知道該如何分類的APP)

|名稱|簡介|
|---|---|
|[microG](https://microg.org/fdroid.html)|取代部份GMS服務的開源程式，德國製造。|
|[Plexus](https://github.com/techlore/plexus)|查詢有哪些APP不需要GMS服務也能跑，可到Github貢獻資料庫。|
|[Snapdrop for Android](https://f-droid.org/zh_Hant/packages/com.fmsys.snapdrop/)|在多個裝置間透過Wifi傳送檔案。|
|[OCR](https://f-droid.org/zh_Hant/packages/io.github.subhamtyagi.ocr/)|從圖片中識別文字，使用Google Tesseract引擎。|
|[Neo Backup](https://f-droid.org/en/packages/com.machiav3lli.backup/)|備份APP和資料，需要Root。|
|[UnitsTool](https://f-droid.org/zh_Hant/packages/com.unitstool/)|轉換溫度、物理量、貨幣等單位。|
|[Lingshot](https://github.com/CharlesMoreira1/lingshot)|圖片翻譯軟體。|
|[LibreTranslator](https://www.f-droid.org/zh_Hant/packages/de.beowulf.libretranslater/)|使用Libre Translate API的翻譯軟體。|
|[KDE Connect](https://f-droid.org/packages/org.kde.kdeconnect_tp/)|讓手機跟電腦傳輸檔案、同步通知。|
|[Limbo x86 PC Emulator](https://f-droid.org/zh_Hant/packages/com.limbo.emu.main/)|使用QEMU虛擬機模擬x86電腦系統。|
|[Moonlight Game Streaming](https://f-droid.org/en/packages/com.limelight/)|串流遊玩電腦上的遊戲。|
|[Fossify Calendar](https://f-droid.org/zh_Hant/packages/org.fossify.calendar/)|簡易離線月曆APP，可用日月年檢視行程。|
|[Tasks.org](https://f-droid.org/zh_Hant/packages/org.tasks/)|開源的線上待辦事項APP。|
|[Bitwarden](https://mobileapp.bitwarden.com/fdroid/)|跨平台儲存密碼、自動填入密碼。|
|[AnkiDroid](https://f-droid.org/packages/com.ichi2.anki/)|用單字卡學語言單字，可配合Anki電腦版使用。|
|[Termux](https://f-droid.org/zh_Hant/packages/com.termux/)|有自己一套套件管理器的終端機模擬器，可執行桌面Linux程式。|
|[Terminal Emulator](https://f-droid.org/zh_Hant/packages/com.termoneplus/)|終端機模擬器，配合Android Shell使用。|
|[AVNC](https://f-droid.org/zh_Hant/packages/com.gaurav.avnc/)|VNC遠端桌面檢視器，支援虛擬滑鼠鍵盤。|
|[aFreeRDP](https://f-droid.org/zh_Hant/packages/com.freerdp.afreerdp/)|RDP遠端桌面檢視器。|
|[ScreenStream](https://f-droid.org/zh_Hant/packages/info.dvkr.screenstream/)|透過Wifi串流手機畫面，並用瀏覽器檢視。|
|[Shelter](https://f-droid.org/en/packages/net.typeblog.shelter/)|利用Android的Work Profile功能，以沙盒形式隔離APP，可另外設定檔案互通。|
|[Insular](https://f-droid.org/packages/com.oasisfeng.island.fdroid/)|類似Google Play上的"Island APP"，移除不必要的Google組件。利用Android的Work Profile功能，以沙盒形式隔離APP，選擇性給某些APP啟用VPN連線。|
|[Screen Orientation Control](https://github.com/ohmae/orientation-faker)|螢幕強制旋轉軟體。|
|[Cross Platform Disk Test](https://github.com/maxim-saplin/CrossPlatformDiskTest)|測試硬碟讀寫速度的跑分軟體。|
|[xOPS: Cross-Platform CPU Benchmark](https://github.com/maxim-saplin/xOPS-App)|測試CPU運算速度的跑分軟體，支援壓力測試。|
