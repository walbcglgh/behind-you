# behind-you

> 一個基於瀏覽器的互動式資訊安全意識教育工具，展示現代網頁能從訪客裝置中讀取哪些公開資訊。

## 🔗 線上體驗

[點此進入](https://walbcglgh.github.io/behind-you/)（請使用桌面或手機瀏覽器）

⚠️ **進入前請詳閱頁面警告與法律文件。**

\---

## 📋 功能特色

|功能|說明|
|-|-|
|**裝置指紋展示**|解析並展示訪客的瀏覽器、作業系統、螢幕解析度、語言設定|
|**IP 地理位置**|透過公開 API 取得推估的城市與 ISP 資訊|
|**時區感知**|依據裝置時區與本地時間調整互動內容|
|**分頁行為監控**|示範 `visibilitychange` API 的應用|
|**輸入節奏分析**|示範如何透過 `keydown` 事件分析使用者打字節奏|
|**全螢幕體驗**|使用 `Fullscreen API` 提供沉浸式展示|
|**震動回饋**|使用 `Vibration API` 提供觸覺回饋（限支援裝置）|
|**Web Audio 音效**|純前端生成音效，無需外部音檔|
|**持久化狀態**|使用 `localStorage` 記錄互動進度|

\---

## 🛡️ 隱私與安全聲明

本專案**僅展示瀏覽器自願公開的標準資訊**，不會：

* ❌ 存取您的私人檔案、相機、麥克風
* ❌ 安裝任何程式或惡意軟體
* ❌ 將資料傳送至第三方伺服器（除 ipapi.co 的 IP 查詢外）
* ❌ 使用追蹤型 Cookie

所有原始碼完全開源，歡迎檢視。

詳見：

* [服務條款](tos.html)
* [隱私政策](privacy.html)
* [免責聲明](disclaimer.html)

\---

## 🚀 本地部署

```bash
# Git Clone 專案
git clone https://github.com/walbcglgh/behind-you.git
cd behind-you

# 本專案為純前端靜態網頁，無需建置步驟
# 直接用瀏覽器開啟 index.html 即可
# 或使用任意靜態伺服器
python -m http.server 8080
# 然後訪問 http://localhost:8080
```

\---

## 🏗️ 技術棧

* **HTML5** + **CSS3**（動畫、過渡效果、響應式布局）
* **Vanilla JavaScript**（無框架依賴）
* **Web Audio API**（動態音效生成）
* **Fullscreen API** / **Vibration API** / **MediaDevices API**
* **GitHub Pages**（免費託管）

\---

## 📁 專案結構

```
behind-you/
├── index.html          # 入口警告頁（含法律連結）
├── game.html           # 核心互動體驗
├── tos.html            # 服務條款
├── privacy.html        # 隱私政策
├── disclaimer.html     # 免責聲明
└── README.md           # 本文件
```

\---

## ⚠️ 注意事項

* 本作品包含**閃光、畫面抖動、音效與心理壓迫元素**
* 不建議光敏性癲癇患者、心臟病患者、焦慮症患者或 12 歲以下兒童使用
* 若感到不適，請立即關閉瀏覽器分頁
* 所有「系統入侵」效果均為**前端技術演示**，不具備真實攻擊能力

\---

## 📝 授權

本專案原始碼以 MIT License 釋出。

**免責聲明：** 本專案僅供教育與娛樂用途。開發者不對因使用本專案而產生的任何心理不適、設備損壞或第三方誤解負責。

\---

> \\「您現在坐在螢幕前面，對吧？」\\

