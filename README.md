# 推薦的好用開源Android APP中文列表

Awesome FOSS Android Apps list (Traditional Chinese) 

本列表收錄的好用Android APP，全部都是自由開源軟體(Free and Open Source)，包含F-Droid與Github的開源專案。

如果不想依賴Google Play或中國的應用程式商店，並且想尋找「開源、無廣告、免費」的APP，那麼以下列表值得您參考。點選藍色字可直接前往下載頁面。

請善用右邊的目錄快速跳轉。Github可以點選README右上角的三個點顯示目錄。

文中提及的APP多半可以在[F-Droid](https://ivonblog.com/posts/what-is-f-droid/)這個開源應用程式商店取得，有些要額外加入軟體庫。

如果APP沒上架F-Droid，您也可以透過[Obtainium](https://ivonblog.com/posts/use-obtainium-to-download-foss-apps/)來下載Github、Gitlab等網站發表的APK，真的不行再使用Google Play吧。


## 第三方應用程式商店

第三方應用程式商店包含F-Droid的第三方前端，UI相較於官方版F-Droid的比較流暢，有的還支援使用者評分。

|名稱|簡介|
|---|---|
|[Neo Store](https://f-droid.org/zh_Hant/packages/com.machiav3lli.fdroid/)|內建許多第三方軟體庫的F-Droid客戶端，Droidfy的後繼者。|
|[G-Droid](https://f-droid.org/en/packages/org.gdroid.gdroid/)|含有使用者評分功能的第三方F-Droid客戶端。|
|[Aurora Store](https://f-droid.org/zh_Hant/packages/com.aurora.store/)|免登入即可下載Google Play的免費APP，不需要依賴GMS服務。也可以用個人Google帳號登入Aurora Store，下載已經購買的APP。|
|[Obtainium](https://github.com/ImranR98/Obtainium)|從各大軟體的網站下載APP。例如使用者填入Github儲存庫，Obtainium就會自動檢查新版本。支援Github、Gitlab、F-Droid、IzzyOnDroid等網站。|


## 瀏覽器

Android手機的瀏覽器陣營大致可以分為Chromium系(WebKit)與Firefox系(Gecko)。

為何同為自由軟體的Mozilla Firefox沒有上架F-Droid呢？請看[此討論串](https://forum.f-droid.org/t/why-is-the-normal-firefox-not-available-in-f-droid/11645)，Firefox僅在Github與Google Play上架，F-Droid只有Firefox的fork。

|名稱|簡介|
|---|---|
|[Mozilla Firefox](https://hg-edge.mozilla.org/mozilla-central)| Firefox官方手機版，支援安裝擴充功能擋廣告、同步電腦帳號。|
|[Fennec F-Droid](https://f-droid.org/en/packages/org.mozilla.fennec_fdroid/)|基於Mozilla Firefox (Fenix) 開發，強調隱私保護。支援登入Mozilla帳號同步。|
|[Iceraven](https://github.com/fork-maintainers/iceraven-browser)|Firefox的fork，保留舊版Firefox的功能，支援安裝更多電腦版的Firefox擴充功能，而非Firefox原版限定的擴充功能，還可以存取about:config調整細部設定。|
|[Tor Browser for Android](https://support.torproject.org/tormobile/tormobile-7/)|支援Tor連線的瀏覽器，基於Firefox開發。需要啟用Guardian Project軟體庫。|
|[Cromite](https://github.com/uazo/cromite)|基於Chromium開發，Bromite繼承者，支援Adblocker清單、載入Greasemonkey指令稿、自訂User Agent，可以檢視網頁原始碼。JavaScript JIT、WebGL、WebRTC預設是停用的，強化安全性與隱私保護，需要到設定裡面手動開啟。開發者另提供vanilla版本的Chromium。|
|[Vanadium](https://github.com/GrapheneOS/Vanadium)|GrapheneOS開發的Chromium瀏覽器，強調隱私保護。|
|[Brave Browser](https://github.com/brave/brave-browser)|基於Chromium開發的跨平台瀏覽器，有自家的同步帳號機制、搜尋引擎、加密貨幣、VPN功能。支援擋廣告和追蹤器。|
|[Midori Browser](https://github.com/goastian/midori-android)|獨立開發的跨平台輕量瀏覽器，並非基於Chromium或Firefox。支援擋廣告。|
|[EinkBro](https://f-droid.org/zh_Hant/packages/info.plateaukao.einkbro/)|專為電子紙閱讀器設計的瀏覽器。|
|[TVBro](https://github.com/truefedex/tv-bro)|專為Android TV設計的擋廣告瀏覽器。|


## 網路連線

(防火牆、VPN、DNS)

|名稱|簡介|
|---|---|
|[Adaway](https://f-droid.org/zh_Hant/packages/org.adaway/)|擋廣告APP，無Root也可以使用(本機VPN)，有Root效果更好。|
|[Blockada](https://f-droid.org/packages/org.blokada.fem.fdroid/)|用DNS(本機VPN)擋廣告的軟體。|
|[NetGuard](https://f-droid.org/zh_Hant/packages/eu.faircode.netguard/)|限制APP連網權限。|
|[OpenVPN](https://github.com/schwabe/ics-openvpn)|跨平台VPN軟體OpenVPN官方Android版客戶端。|
|[迷霧通 Geph](https://github.com/geph-official/geph-android)|愛沙尼亞Gephyra OÜ公司販售的VPN服務，使用自有的協定繞過網路審查，主要針對中國翻牆用戶設計，提供低速免費方案。|
|[Proton VPN](https://f-droid.org/zh_Hant/packages/ch.protonvpn.android/)|Proton公司販售的隱私VPN服務，支援KillSwitch和Port Forwarding。|
|[Mullvad VPN](https://f-droid.org/zh_Hant/packages/net.mullvad.mullvadvpn/)|Mullvad公司販售的隱私VPN服務，不論訂閱多久時間，一個週期都是公道價5美元，支援加密貨幣付款。註冊帳號不需要電子郵件，而是一串代碼組成。|
|[TorServices (alpha)](https://f-droid.org/packages/org.torproject.torservices/)|Guardian Project提供的Tor網路服務，|
|[Orbot: Tor for Android](https://support.torproject.org/tormobile/tormobile-7/)|讓手機使用全域Tor網路連線。|


## 通訊軟體

(撥號、通訊錄、通訊軟體客戶端)

|名稱|簡介|
|---|---|
|[Koler](https://f-droid.org/zh_Hant/packages/com.chooloo.www.koler/)|撥號APP，可設定延遲回覆。|
|[Fossify Phone](https://f-droid.org/zh_Hant/packages/org.fossify.phone/)|簡易撥號APP。|
|[Call Recorder](https://f-droid.org/packages/com.github.axet.callrecorder/)|通話錄音APP。|
|[OpenContacts](https://f-droid.org/zh_Hant/packages/opencontacts.open.com.opencontacts/)|開源聯絡人APP。資料庫跟系統內建的分開，因此不會被其他APP讀取到聯絡人資訊。|
|[Fossify Contacts](https://f-droid.org/zh_Hant/packages/org.fossify.contacts/)|簡易聯絡人管理APP。|
|[Fossify Messages](https://f-droid.org/zh_Hant/packages/org.fossify.messages/)|簡易簡訊APP。|
|[K-9 Mail](https://f-droid.org/zh_Hant/packages/com.fsck.k9/)|支援多個帳號的電郵APP，未來將與Mozilla Thunderbird合併。|
|[Protonmail](https://github.com/ProtonMail/android-mail)|加密電子郵件Protonmail的官方客戶端。|
|[Telegram FOSS](https://f-droid.org/zh_Hant/packages/org.telegram.messenger/)|開源分支版的Telegram客戶端，跟官方的界面幾無差異。|
|[Elements](https://f-droid.org/packages/im.vector.app/)|存取群組聊天Elements.io的官方客戶端，支援Matrix通訊協定。|


## 主題裝飾

(桌布、啟動器)

|名稱|簡介|
|---|---|
|[Muzei](https://f-droid.org/packages/net.nurik.roman.muzei/)|自動抓取藝術畫當桌布的APP，還有各種擴充插件可選取不同圖片來源，例如NASA、國家地理、Pixiv、Danbooru。|
|[Materials Live Wallpaper](https://f-droid.org/zh_Hant/packages/com.reminimalism.materialslivewallpaper/)|渲染各種材質的物件當桌布，會跟著手機角度變化。|
|[Neo Launcher](https://github.com/NeoApplications/Neo-Launcher)|支援自訂APP分類、自訂APP名稱、隱藏APP、手勢、快捷抽屜、桌面搜尋引擎等多樣功能的桌面啟動器。|
|[Lawnchair](https://github.com/LawnchairLauncher/lawnchair)|類似Nova Launcher的桌面啟動器。F-Droid版已不再更新，需到Github下載APK。|
|[Fossify Launcher](https://f-droid.org/zh_Hant/packages/org.fossify.home/)|簡潔，近似原生Android的啟動器。|
|[Kvaesitso](https://github.com/MM2-0/Kvaesitso)|以搜尋為導向的啟動器。|
|[KISS Launcher](https://f-droid.org/packages/fr.neamar.kiss/)|極簡風格桌面。|
|[FLauncher](https://gitlab.com/flauncher/flauncher)|Android TV專用的第三方桌面。|
|[GIF Live Wallpaper](https://f-droid.rg/en/packages/net.redwarp.gifwallpaper/)|用GIF圖片當桌面背景。|


## 檔案管理器

|名稱|簡介|
|---|---|
|[質感檔案 Material Files](https://f-droid.org/zh_Hant/packages/me.zhanghai.android.files/)|質感設計風格的檔案管理員，支援解壓縮、文字編輯、查看圖片、連接FTP伺服，有免Root存取Android/data目錄的能力。|
|[Fossify File Manager](https://f-droid.org/zh_Hant/packages/org.fossify.filemanager/)|簡易檔案管理員，提供資料夾上鎖功能。|
|[Ghost Commander](https://f-droid.org/zh_Hant/packages/com.ghostsq.commander/)|有二個面板的檔案管理器，方便對照檔案。類似Total Commander。|
|[Amaze File Manager](https://github.com/TeamAmaze/AmazeFileManager)|有二個面板的檔案管理器，支援解壓縮、檢視PDF、文字編輯。附加空間清理、尋找重複圖片、連接雲端硬碟的功能。|
|[PlainApp](https://github.com/ismartcoding/plain-app)|界面極簡的檔案管理器，快速找出圖片與影片，還能寫Markdown筆記和閱讀RSS動態。該APP特色是能跑一個網頁伺服器，再從電腦網頁存取檔案。|


## 生產力

(程式碼編輯器、文件編輯器、筆記軟體)

|名稱|簡介|
|---|---|
|[LibreOffice Viewer](https://f-droid.org/zh_Hant/packages/org.documentfoundation.libreoffice/)|文件基金會官方推出的ODF檢視器，可檢視和編輯.odt、.ods、.odp文件。|
|[Collabora Office](https://www.collaboraonline.com/collabora-office-android-ios/)|Collabora公司基於LibreOffice開發的手機文件編輯器，支援常見Office檔案格式和PDF檔，可檢視和編輯.odt、.ods、.odp文件。|
|[OpenDocument Reader](https://f-droid.org/zh_Hant/packages/at.tomtasche.reader/)|Stefl und Taschauer OG.公司維護的APP，可檢視和編輯.odt、.ods、.odp文件。|
|[Librera Reader](https://f-droid.org/packages/com.foobnix.pro.pdf.reader/)|功能豐富的閱讀器，可開啟大多數格式的電子書，存取雲端硬碟的書籍。|
|[KOReader](https://f-droid.org/en/packages/org.koreader.launcher.fdroid/)|適合電子紙使用的電子書閱讀器。支援PDF、DjVu、EPUB、FB2、CBZ格式。|
|[MJ PDF](https://github.com/mudlej/mj_pdf)|簡單又省資源的PDF閱讀器。|
|[OCR](https://f-droid.org/zh_Hant/packages/io.github.subhamtyagi.ocr/)|從圖片中識別文字，使用Google Tesseract引擎。|
|[Markor](https://f-droid.org/zh_Hant/packages/net.gsantner.markor/)|編輯後可即時預覽成果的Markdown編輯器。|
|[Fossify Notes](https://f-droid.org/zh_Hant/packages/org.fossify.notes/)|簡易筆記軟體，支援撰寫代辦事項，並在桌面釘選小工具。|
|[Joplin](https://github.com/laurent22/joplin)|跨平台筆記軟體，使用Markdown與手寫筆儲存筆記，提供多種雲端同步方案，支援點對點加密筆記。|
|[Saber Notes](https://github.com/saber-notes/saber)|跨平台筆記軟體，以手寫筆記為主，支援嵌入PDF。|
|[思源筆記 SiYuan](https://f-droid.org/zh_Hant/packages/org.b3log.siyuan/)|跨平台個人知識管理系統，提供Markdown和區塊式編輯，還有許多心智圖模板，伺服器能夠自架。|


## 多媒體

(相機、相簿、影片播放器、影像處理)

|名稱|簡介|
|---|---|
|[VLC](https://f-droid.org/zh_Hant/packages/org.videolan.vlc/)|影片兼音樂播放器，支援字幕，可在背景播放影片，或當成音樂播放器使用。|
|[mpv-android](https://f-droid.org/en/packages/is.xyz.mpv/)|MPV影片/音樂播放器Android版，支援使用電腦版的設定檔。|
|[Metro](https://f-droid.org/en/packages/io.github.muntashirakon.Music/)|基於RetroPlayer開發的音樂播放器，支援讀取資料夾。|
|[Fossify Music Player](https://f-droid.org/zh_Hant/packages/org.fossify.musicplayer/)|簡易音樂播放器，支援依照資料夾模式播放音樂。|
|[CaPods](https://f-droid.org/zh_Hant/packages/eu.darken.capod/)|查看AirPods的電量。|
|[Open Camera](https://f-droid.org/zh_Hant/packages/net.sourceforge.opencamera/)|相機APP，可設定拍照錄影的成像品質、GPS、HDR等細部設定。支援使用Camera2 API拍攝RAW照片。|
|[Fossify Camera](https://f-droid.org/zh_Hant/packages/org.fossify.camera/)|簡易相機APP，能夠選擇要不要儲存EXIF。|
|[RemoteVideoCam](https://f-droid.org/packages/org.avmedia.remotevideocam/)|讓二支手機連線，讓彼此看到對方的鏡頭畫面。|
|[Fossify Gallery](https://f-droid.org/zh_Hant/packages/org.fossify.gallery/)|相簿APP，可簡單編輯相片、批次刪除EXIF、資料夾模式檢視照片，取代已經封閉原始碼的「簡易相簿」|
|[Les Pas](https://f-droid.org/zh_Hant/packages/site.leos.apps.lespas/)|相簿APP，可同步相片至NextCloud。|
|[Aves Libre](https://f-droid.org/packages/deckers.thibault.aves.libre/)|相簿APP，支援檢視圖片、影片、地圖資訊。|
|[Open Video Editor](https://github.com/devhyper/open-video-editor)|輕量影片剪輯、轉檔工具，可以在影片上加文字。|
|[Litrato](https://github.com/DrMint/Litrato)|照片調整軟體，提供多款濾鏡。|
|[Image Toolbox](https://github.com/T8RIN/ImageToolbox)|功能豐富的圖片編輯APP，功能包括調整色調曲線、加上濾鏡、自動去背、裁切圖片、批次轉換圖片格式、縮小圖片、消除EXIF、合併為PDF、多張圖片拼成一張。|
|[Pocket Paint](https://f-droid.org/zh_Hant/packages/org.catrobat.paintroid/)|圖片編輯APP，支援簡易圖層、繪圖。|
|[Com-Phone Story Maker](https://f-droid.org/en/packages/ac.robinson.mediaphone/)|製作有聲書影片。|
|[Krita](https://f-droid.org/zh_Hant/packages/org.krita/)|專業的跨平台繪圖程式，僅適合平板使用。|
|[PixaPencil](https://f-droid.org/en/packages/com.therealbluepandabear.pixapencil/)|像素畫繪圖程式。|
|[Tux Paint](https://f-droid.org/en/packages/org.tuxpaint/)|兒童繪圖程式。|
|[Fossify Paint](https://f-droid.org/zh_Hant/packages/org.fossify.paint/)|簡易塗鴉程式。|
|[Fossify Recorder](https://f-droid.org/zh_Hant/packages/org.fossify.voicerecorder/)|簡易錄音機。|


## 社群媒體與影音串流

(包含各種網站的客戶端)

社群媒體有些是使用開源前端，但後端閉源的服務。例如「Tusky」是前後端都開源，而「NewPipe」後端的Youtube是閉源的網路服務。

|名稱|簡介|
|---|---|
|[AntennaPod](https://f-droid.org/zh_Hant/packages/de.danoeh.antennapod/)|Podcast聆聽客戶端，自由匯入匯出收藏紀錄。|
|[LBRY F-Droid](https://f-droid.org/zh_Hant/packages/io.lbry.browser/)|區塊鏈影音平台LBRY的官方客戶端。|
|[Youtube ReVanced/ReVanced Manager](https://github.com/ReVanced/revanced-manager)|破解版的官方Youtube，去廣告、隱藏任意版面。|
|[NewPipe](https://f-droid.org/zh_Hant/packages/org.schabi.newpipe/)|免登入觀看Youtube/PeerTube影片，無廣告、可下載影片、支援背景播放。|
|[PipePipe](https://f-droid.org/zh_Hant/packages/InfinityLoop1309.NewPipeEnhanced/)|NewPipe的分支版，免登入觀看Bilibili/Niconico/Youtube影片。|
|[Seal](https://github.com/JunkFood02/Seal)|採用yt-dlp技術的YouTube影片下載器。|
|[InnerTune](https://f-droid.org/packages/com.zionhuang.music/)|無廣告聆聽Youtube Music，支援播放歌詞、Android Auto。|
|[Vitune](https://github.com/25huizengek1/ViTune)|無廣告聆聽Youtube Music，界面十分精簡，支援Android Auto。取代已經停止開發的ViMusic。|
|[Thorium a PeerTube client](https://f-droid.org/zh_Hant/packages/net.schueller.peertube/)|觀看PeerTube的客戶端，需要手動加入站點。|
|[LibreTube](https://f-droid.org/zh_Hant/packages/com.github.libretube/)|觀看Youtube影片，無廣告、可下載影片、支援背景播放。透過實例儲存播放清單和訂閱列表。|
|[Mastodon](https://f-droid.org/zh_Hant/packages/org.joinmastodon.android/)|Mastodon官方客戶端。|
|[Tusky](https://f-droid.org/zh_Hant/packages/com.keylesspalace.tusky/)|支援多個實例帳號的Mastodon客戶端。|
|[OctoDroid](https://f-droid.org/zh_Hant/packages/com.gh4a/)|第三方Github客戶端，支援線上管理issues等操作。|
|[LabCoat](https://f-droid.org/zh_Hant/packages/com.commit451.gitlab/)|Gitlab官方客戶端，查看commits和issues。|
|[GitNex for Gitea](https://f-droid.org/zh_Hant/packages/org.mian.gitnex/)|Gitea客戶端，支援多樣操作。|
|[PixEz Flutter](https://github.com/Notsfsssf/pixez-flutter)|跨平台Pixiv客戶端，支援查看動圖。|
|[Pixiv-Shaft](https://github.com/CeuiLiSA/Pixiv-Shaft)|第三方Pixiv客戶端。|
|[木之子漫畫閱讀器](https://f-droid.org/zh_Hant/packages/com.ero.kinoko/)|支援多個線上漫畫平台，可閱覽或下載漫畫。|
|[Mihon](https://github.com/mihonapp/mihon)|Tachiyomi繼承者，免費漫畫閱讀器，可以線上瀏覽與下載漫畫，支援多個線上平台。有非常多的分支版本，|
|[EhViewer overhauled](https://github.com/FooIbar/EhViewer)|採用Material Design設計的E-hentai閱讀器。|
|[JHentai](https://github.com/jiangtian616/JHenTai)|使用Flutter寫成的跨平台E-hentai閱讀器，提供雙頁閱讀界面。|
|[AnimeTV](https://github.com/amarullz/AnimeTV)|Android TV專用的看動漫APP。|
|[Streamflix](https://github.com/stantanasi/streamflix)|Android TV專用APP，觀看戲劇專用。|
|[CloudStream](https://github.com/recloudstream/cloudstream)|免費觀看直播的Android TV APP。|
|[LoliSnatcher](https://github.com/NO-ob/LoliSnatcher_Droid)|支援多個動漫booru貼圖站的閱讀器，可搭配Hydrus Network使用。|
|[Hacki for Hacker News](https://f-droid.org/zh_Hant/packages/com.jiaqifeng.hacki/)|Hacker News閱讀器。|
|[Fluent Reader Lite](https://github.com/yang991178/fluent-reader-lite)|跨平台RSS閱讀器。|



## 導航

|名稱|簡介|
|---|---|
|[Breezy Weather](https://f-droid.org/packages/org.breezyweather/)|採用Material Design的天氣APP，能夠從世界各國取得天氣資料，包括OpenWeatherMap、Open-Meteo、台灣中央氣象署等等。 |
|[OSMAnd~](https://f-droid.org/zh_Hant/packages/net.osmand.plus/)|以OpenStreetMap當作圖資的導航APP，支援離線地圖，可以讀取軌跡.gpx檔並繪製在地圖上。|
|[Organic Maps](https://f-droid.org/en/packages/app.organicmaps/)|以OpenStreetMap當作圖資的導航APP，規劃登山、腳踏車路線，支援離線地圖。|
|[Street­Complete](https://f-droid.org/packages/de.westnordost.streetcomplete/)|回答簡單問題，改善OpenStreeMap圖資。|
|[Vespucci](https://f-droid.org/packages/de.blau.android/)|隨時隨地編輯OpenStreetMap圖資。|
|[OpenTracks](https://f-droid.org/en/packages/de.dennisguse.opentracks/)|離線執行的運動軌跡記錄器，使用OpenStreetMap當作圖資，可搭配智慧手錶記錄心率。使用.gpx格式分享資料，配合OSM Dashboard地圖資料將軌跡顯示在地圖上。|
|[OSMTracker](https://f-droid.org/packages/net.osmtracker/)|運動軌跡記錄器，使用OpenStreetMap當作圖資。使用.gpx格式分享資料，並能在路線圖嵌入照片與筆記。|
|[GPSLogger](https://f-droid.org/zh_Hant/packages/com.mendhak.gpslogger/)|自動在背景紀錄GPS軌跡。|
|[Trackbook - Movement Recorder](https://f-droid.org/en/packages/org.y20k.trackbook/)|紀錄健行、出遊的移動軌跡，使用OpenStreetMap當圖資。|
|[GMaps WV](https://f-droid.org/zh_Hant/packages/us.spotco.maps/)|簡易網頁版Google地圖，OpenStreetMap不夠用時的補充用途。|
|[osm2gmaps](https://f-droid.org/zh_Hant/packages/net.retiolus.osm2gmaps/)|依照網址，轉換為不同導航軟體的座標。|


## 健康

|名稱|簡介|
|---|---|
|[Noice: Natural Calming Noise](https://f-droid.org/packages/com.github.ashutoshgngwr.noice/)|白噪音生成器兼鬧鐘，支援Chromecast。|
|[Gadgetbridge](https://f-droid.org/zh_Hant/packages/nodomain.freeyourgadget.gadgetbridge/)|連線到智慧手錶與智慧手環，更有隱私的紀錄健康資訊與GPS軌跡，資料可以任意匯出，不被原廠的專有軟體APP綁住。|
|[Fridgey](https://f-droid.org/zh_Hant/packages/lying.fengfeng.foodrecords/)|紀錄食材照片。|
|[Flexify](https://github.com/brandonp2412/Flexify)|追蹤健身進度。|
|[Minimalist Pomodoro Timer](https://github.com/adrcotfas/Goodtime?tab=readme-ov-file)|蕃茄鐘小工具。|
|[Fossify Clock](https://f-droid.org/zh_Hant/packages/org.fossify.clock/)|簡易鬧鐘與計時器。|


## 理財

|名稱|簡介|
|---|---|
|[Currencies: Exchange Rate Calculator](https://f-droid.org/en/packages/de.salomax.currencies/)|貨幣匯率轉換器，使用Frankfurter API。|
|[卡提碼 Catima](https://f-droid.org/zh_Hant/packages/me.hackerchick.catima/)|載具條碼、票卷、卡片管理器。|
|[開支助手 My Expenses](https://f-droid.org/en/packages/org.totschnig.myexpenses/)|記帳APP，可匯出為QIF、CSV。|


## 輸入法

|名稱|簡介|
|---|---|
|[Hacker's Keyboard](https://f-droid.org/packages/org.pocketworkstation.pckeyboard/)|內建許多電腦快捷鍵的英文輸入法，適合用於遠端桌面。|
|[AnySoftkeyboard](https://f-droid.org/packages/com.menny.android.anysoftkeyboard/)|支援多語言的英文鍵盤。|
|[Fossify Keyboard](https://f-droid.org/zh_Hant/packages/org.fossify.keyboard/)|提供Emoji輸入與剪接簿紀錄的英文鍵盤。|
|[中州韻 TRIME](https://f-droid.org/zh_Hant/packages/com.osfans.trime/)|支援強大自定義配置的中文輸入法框架，使用RIME引擎。注音使用者請使用「洋蔥注音輸入方案」。|
|[樸實注音鍵盤](https://f-droid.org/zh_Hans/packages/org.ghostsinthelab.apps.guilelessbopomofo/)|基於新酷音輸入法開發的極簡注音輸入法，提供簡繁轉換。|
|[小企鵝 Fcitx5 for Android](https://github.com/fcitx5-android/fcitx5-android)|移植自Linux系統的輸入法，支援拼音、倉頡、嘸蝦米等輸入方案。|


## 遊戲

有開源手遊這種東西？當然有，有的完成度很高，並非小品遊戲等級。這些遊戲不只開源，還具備好玩、免費、無廣告、無課金機制的要素。這裡收錄的是具備獨特玩法的遊戲，不收：西洋棋、數獨、麻將、踩地雷、俄羅斯方塊、2048之類爛大街的小遊戲。

|名稱|簡介|
|---|---|
|[Habitica](https://github.com/HabitRPG/habitica-android)|將日常待辦事項變成破關RPG，增添生活樂趣。|
|[Luanti](https://f-droid.org/zh_Hant/packages/net.minetest.minetest/)|舊名Minetest，自由開源的沙盒遊戲，有大量模組可安裝，能把遊戲搞得像Minecraft一樣。如果F-Droid的APK無法啟動，請改到官網下載APK。|
|[SuperTux](https://github.com/SuperTux/supertux/wiki/Download-Portable)|玩法類似超級瑪莉的企鵝遊戲，非官方移植版。難度高。|
|[SuperTuxKart](https://f-droid.org/zh_Hant/packages/org.supertuxkart.stk/)|自由軟體吉祥物駕駛卡丁車的賽車遊戲，畫面品質優秀。|
|[Tux Rider](https://f-droid.org/zh_Hant/packages/com.drodin.tuxrider/)|企鵝滑雪遊戲。|
|[Exterme Tux Racer](https://drodin.com/extremetuxracer/)|Tux Rider升級版，細節更多。Android版由droidin移植。|
|[Endless Sky](https://f-droid.org/zh_Hant/packages/com.github.thewierdnut.endless_mobile/)|以太空為主題的冒險與貿易遊戲。|
|[韋諾之戰 The Battle for Wesnoth](https://f-droid.org/zh_Hant/packages/it.alessandropira.wesnoth114/)|具有豐富背景故事的回合制戰略遊戲。|
|[寒霜之旅 Xeonjia: Ice Adventures](https://f-droid.org/en/packages/xyz.deepdaikon.xeonjia/)|2D冒險遊戲。|
|[大災變：黑暗之日 Cataclysm: Dark Days Ahead](https://github.com/CleverRaven/Cataclysm-DDA)|2D末日題材戰鬥遊戲。|
|[像素地牢 Pixel Dungeon](https://f-droid.org/zh_Hant/packages/com.watabou.pixeldungeon/)|像素風的Roguelike遊戲，在地下城打怪。|
|[破碎像素地牢 Shattered Pixel Dungeon](https://f-droid.org/zh_Hant/packages/com.shatteredpixel.shatteredpixeldungeon/)|Pixel Dungeon的衍生版本。|
|[像素工廠 Mindustry](https://f-droid.org/packages/io.anuke.mindustry/)|跨平台的塔防+資源蒐集遊戲。|
|[沙漠風暴 StormPlane](https://github.com/HurTeng/StormPlane)|模仿「雷電」的直向射擊遊戲。|
|[The Powder Toy](https://play.google.com/store/apps/details?id=uk.co.powdertoy.tpt&hl=zh_TW&gl=US)|真實物理模擬遊戲。|
|[OpenTTD](https://f-droid.org/zh_Hant/packages/org.openttd.fdroid/)|基於運輸大亨開發的模擬經營遊戲。|
|[UnCiv](https://f-droid.org/en/packages/com.unciv.app/)| 類似文明帝國V的遊戲，支援安裝模組。|
|[Freeciv](https://play.google.com/store/apps/details?id=pl.org.zielinscy.freeciv&hl=en_US)| 仿造文明帝國II的遊戲。|
|[OpenMW](https://f-droid.org/packages/com.libopenmw.openmw/)|開源版上古捲軸3。|
|[OpenArena](https://play.google.com/store/apps/details?id=ws.openarena.sdl&hl=zh_TW&gl=US)| 開源版雷神之鎚III。|
|[FreeDoom](https://f-droid.org/packages/net.nullsum.freedoom/)| 開源版毀滅戰士。|
|[Sonic Robo Blast 2](https://www.srb2.org/download/)| 音速小子同人遊戲，玩法類似早年的3D遊戲。|
|[H-Craft Championship](https://play.google.com/store/apps/details?id=com.irrgheist.hcraft_championship&hl=en_US)| 科幻賽車競速遊戲。|
|[AAAAXY](https://f-droid.org/zh_Hant/packages/io.github.divverent.aaaaxy/)|燒腦的2D解謎遊戲。
|[Lato](https://f-droid.org/zh_Hant/packages/ardash.lato/)|美麗的2D滑雪遊戲。|
|[Pixel Wheels](https://f-droid.org/en/packages/com.agateau.tinywheels.android/)|2D賽車遊戲。|
|[Vector Pinball](https://f-droid.org/packages/com.dozingcatsoftware.bouncy/)|重新設計的Windows彈珠台遊戲。|
|[GCompris](https://f-droid.org/zh_Hant/packages/net.gcompris.full/)|開源的兒童教育軟體，內建多個學科的小遊戲。|
|[Apple Flinger](https://f-droid.org/zh_Hant/packages/com.gitlab.ardash.appleflinger.android/)|雙人版憤怒鳥。|
|[Frozen Bubble](https://f-droid.org/packages/org.jfedor.frozenbubble/)|類似泡泡龍的射擊遊戲。|
|[MOROway](https://f-droid.org/zh_Hant/packages/de.moroway.oc/)|鐵路管理遊戲。|
|[Freebloks 3D](https://f-droid.org/packages/de.saschahlusiak.freebloks/)|電子版Blokus桌遊。|
|[Chaldea](https://f-droid.org/zh_Hant/packages/cc.narumi.chaldea.fdroid/)| 手機遊戲Fate/Grand Order的戰鬥模擬器、素材計算器。|
|[J2ME Loader](https://f-droid.org/zh_Hant/packages/ru.playsoftware.j2meloader/)| 讓您在Android玩古早功能型手機上的Java小遊戲。 |
|[ScummVM](https://docs.scummvm.org/en/latest/other_platforms/android.html)| 老遊戲開源引擎的模擬器。 |
|[RetroArch](https://f-droid.org/zh_Hant/packages/com.retroarch/)| 經典老遊戲模擬器。 |
|[PPSSPP](https://f-droid.org/packages/org.ppsspp.ppsspp/)| 著名的PSP掌機模擬器，需要自備ROM。 |
|[Dolphin Emulator](https://f-droid.org/en/packages/org.dolphinemu.dolphinemu/)| Nitendo Wii模擬器。 |
|[Lemuroid](https://f-droid.org/zh_Hant/packages/com.swordfish.lemuroid/)|基於Libretro開發，Atari、Game Boy、SEGA、PSP、Nitendo 3DS等遊戲主機的模擬器。|
|[Winlator](https://github.com/brunodev85/winlator)|利用Proot Linux + Box64 + Wine技術，轉譯遊玩Windows exe遊戲。|
|[Moonlight Game Streaming](https://f-droid.org/en/packages/com.limelight/)|遠端串流遊玩電腦上的遊戲，需要搭配Sunshine伺服器使用。|


## 工具程式

 (以及不知道該如何分類的APP)

|名稱|簡介|
|---|---|
|[microG](https://microg.org/fdroid.html)|取代部份GMS服務的開源程式，德國製造。|
|[Plexus](https://github.com/techlore/plexus)|查詢有哪些APP不需要GMS服務也能跑，可到Github貢獻資料庫。|
|[Exodus](https://github.com/Exodus-Privacy/exodus)|顯示APP含有哪些追蹤器，保護使用者隱私。|
|[Package Mnager](https://github.com/SmartPack/PackageManager)|檢視APP詳細資訊，可以安裝APP Bundle，包括.apk、.apks、 .apkm、.xapk等格式。|
|[Neo Backup](https://f-droid.org/en/packages/com.machiav3lli.backup/)|備份單獨或全部的APP資料，需要Root權限。|
|[Screen Orientation Control](https://github.com/ohmae/orientation-faker)|螢幕強制旋轉軟體。|
|[UnitsTool](https://f-droid.org/zh_Hant/packages/com.unitstool/)|轉換溫度、物理量、貨幣等單位。|
|[EverTranslator](https://github.com/firemaples/EverTranslator)|螢幕懸浮翻譯，即時辨識螢幕上的文字|
|[Rtranslator](https://github.com/niedev/RTranslator)|採用Whisper技術的即時語音翻譯軟體。|
|[LibreTranslator](https://www.f-droid.org/zh_Hant/packages/de.beowulf.libretranslater/)|使用Libre Translate API的翻譯軟體。|
|[Snapdrop & PairDrop for Android](https://f-droid.org/zh_Hant/packages/com.fmsys.snapdrop/)|在多個裝置間透過Wifi傳送檔案，雙方使用瀏覽器就能接收。|
|[KDE Connect](https://f-droid.org/packages/org.kde.kdeconnect_tp/)|讓手機跟電腦傳輸檔案、同步通知、控制簡報、當作遠端滑鼠。|
|[LocalSend](https://github.com/localsend/localsend)|跨平台無線傳檔軟體。|
|[Aria2App](https://github.com/devgianlu/Aria2App)|基於Aria2開發的下載管理器，支援BT種子和斷點續傳。|
|[LibreTorrent](https://f-droid.org/zh_Hant/packages/org.proninyaroslav.libretorrent/)|BT種子與磁力連結下載器。|
|[Limbo x86 PC Emulator](https://f-droid.org/zh_Hant/packages/com.limbo.emu.main/)|使用QEMU模擬x86電腦虛擬機，特定手機支援pKVM可以全速執行虛擬機。|
|[Fossify Calendar](https://f-droid.org/zh_Hant/packages/org.fossify.calendar/)|簡易離線月曆APP，可用日月年檢視行程。|
|[Fossify Caculator](https://f-droid.org/zh_Hant/packages/org.fossify.math/)|簡易計算機，可以在桌面放小工具。|
|[Tasks.org](https://f-droid.org/zh_Hant/packages/org.tasks/)|開源的線上待辦事項APP。|
|[Bitwarden](https://mobileapp.bitwarden.com/fdroid/repo/)|跨平台密碼管理器，跨裝置同步密碼與自動填入密碼。|
|[AnkiDroid](https://f-droid.org/packages/com.ichi2.anki/)|用單字卡學語言單字，可配合Anki電腦版使用。|
|[Termux](https://f-droid.org/zh_Hant/packages/com.termux/)|有自己一套套件管理器的終端機模擬器，可執行桌面Linux程式。|
|[Terminal Emulator](https://f-droid.org/zh_Hant/packages/com.termoneplus/)|終端機模擬器，配合Android Shell使用。|
|[Acode](https://f-droid.org/zh_Hant/packages/com.foxdebug.acode/)|程式碼編輯器，整合Git操作，支援語法自動偵錯。|
|[Squircle](https://f-droid.org/zh_Hant/packages/com.blacksquircle.ui/)|程式碼編輯器，支援語法自動偵錯。|
|[RustDesk](https://f-droid.org/zh_Hant/packages/com.carriez.flutter_hbb/)|簡單易用的跨平台遠端桌面軟體，伺服器可以自架。|
|[AVNC](https://f-droid.org/zh_Hant/packages/com.gaurav.avnc/)|VNC遠端桌面檢視器，支援虛擬滑鼠鍵盤。|
|[bVNC](https://github.com/iiordanov/remote-desktop-clients)|VNC、RDP、SPICE、Proxmox遠端桌面檢視器，支援虛擬滑鼠鍵盤。|
|[aFreeRDP](https://f-droid.org/zh_Hant/packages/com.freerdp.afreerdp/)|RDP遠端桌面檢視器。|
|[ScreenStream](https://f-droid.org/zh_Hant/packages/info.dvkr.screenstream/)|透過Wifi串流手機畫面，並用瀏覽器檢視。|
|[Bluetooth Remote](https://f-droid.org/packages/com.atharok.btremote/)|讓手機變成Android TV的藍芽遙控器。|
|[IRRemote](https://gitlab.com/divested-mobile/irremote)|使用手機的紅外線遠端控制Android TV。|
|[Shelter](https://f-droid.org/en/packages/net.typeblog.shelter/)|利用Android的工作設定檔功能，以沙盒形式隔離APP，雙開APP，可另外設定檔案互通。|
|[Insular](https://f-droid.org/packages/com.oasisfeng.island.fdroid/)|類似Google Play上的"Island APP"，移除不必要的Google組件。利用Android的工作設定檔功能，以沙盒形式隔離APP，選擇性給某些APP啟用VPN連線。|
|[Cross Platform Disk Test](https://github.com/maxim-saplin/CrossPlatformDiskTest)|測試硬碟讀寫速度的跑分軟體。|
|[xOPS: Cross-Platform CPU Benchmark](https://github.com/maxim-saplin/xOPS-App)|測試CPU運算速度的跑分軟體，支援壓力測試。|
