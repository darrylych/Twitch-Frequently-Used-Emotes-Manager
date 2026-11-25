# 隱私權政策 / Privacy Policy

**Twitch Frequently Used Emotes Manager**（以下簡稱「本擴充功能」）

生效日期 / Effective date: 2026-11-25

[繁體中文](#繁體中文) · [English](#english)

---

## 繁體中文

### 摘要

本擴充功能的所有處理都在您的瀏覽器內完成。**本擴充功能不會收集、上傳、販售或分享任何資料**，沒有任何分析或追蹤程式，也沒有自己的伺服器。

### 本擴充功能存取的資料

- **Twitch 表情歷史紀錄**：Twitch 官方存放在您瀏覽器 `localStorage` 中的 `twilight.emote_picker_history`，內容是表情 ID、名稱與使用次數。本擴充功能只在您開啟彈出視窗並進行操作時，於 twitch.tv 分頁中讀取或寫回這份資料，用來顯示、編輯、釘選、排序、匯入、匯出與清除表情紀錄。
- 本擴充功能**不會**讀取您的 Twitch 帳號資訊、聊天內容、觀看紀錄或任何其他網站的資料。

### 儲存在您瀏覽器中的資料

以下資料使用 Chrome 擴充功能儲存空間（`chrome.storage`），只存在您的裝置上：

- 偏好設定（語言、主題、是否隱藏預設表情、預設匯入模式、排序方式）。
- 釘選清單與釘選前的真實使用次數。
- 儲存槽：您手動儲存的表情清單與槽位名稱。
- 自動備份：刪除、匯入、載入等操作前的清單副本（最多 10 份）。
- 趨勢紀錄：每天一份的各表情使用次數快照（最多 60 天），用來計算「本週」與「久未使用」。

偏好設定與釘選清單存在 `chrome.storage.sync`。如果您在 Chrome 開啟了同步功能，Google 會依您的 Chrome 同步設定在您的裝置之間同步這些資料；本擴充功能本身不會傳送它們。其餘資料存在 `chrome.storage.local`，不會同步。

您可以隨時在設定頁重設趨勢紀錄、在備份分頁刪除儲存槽，或移除本擴充功能以刪除上述所有資料。

### 網路請求

本擴充功能會從 Twitch 的圖片伺服器（`static-cdn.jtvnw.net`）載入表情圖片，與您在 Twitch 網站上看到表情時相同。除此之外，本擴充功能不會連線到任何伺服器。

您匯出的 JSON 或 CSV 檔案只會存到您選擇的位置，或複製到您的剪貼簿。

### 權限說明

- **`activeTab`**：在您點擊擴充功能圖示時，與目前的 Twitch 分頁溝通。
- **`scripting`**：當 Twitch 分頁是在安裝或更新本擴充功能之前開啟的，用來連上該分頁。
- **`storage`**：儲存上述偏好設定、釘選、儲存槽、自動備份與趨勢紀錄。
- **在 `twitch.tv` 執行的內容指令碼**：在 Twitch 分頁中讀寫表情歷史紀錄。

### 聯絡方式

如果您對本隱私權政策有任何疑問，請到 [GitHub Issues](https://github.com/darrylych/Twitch-Frequently-Used-Emotes-Manager/issues) 與我聯繫。

### 政策更新

本政策更新時會修改本頁面與上方的生效日期。

---

## English

### Summary

Everything the extension does happens inside your browser. **The extension does not collect, upload, sell or share any data.** It contains no analytics or tracking and has no server of its own.

### Data the extension accesses

- **Twitch emote history** — the `twilight.emote_picker_history` entry that Twitch itself stores in your browser's `localStorage`, containing emote IDs, names and use counts. The extension reads or writes it in the twitch.tv tab only when you open the popup and use it, in order to display, edit, pin, sort, import, export and clear your emote history.
- The extension does **not** read your Twitch account details, chat messages, viewing history or data from any other website.

### Data stored in your browser

The following is kept in Chrome's extension storage (`chrome.storage`) on your device:

- Preferences (language, theme, hide default emotes, default import mode, sort order).
- Your pins and each pinned emote's real use count.
- Saved slots: emote lists you saved yourself, and the slot names.
- Automatic backups: copies of your list taken before deletes, imports, loads and similar actions (up to 10).
- Trend history: one snapshot of each emote's use count per day (up to 60 days), used for "this week" and "gathering dust".

Preferences and pins are stored in `chrome.storage.sync`. If you have Chrome sync turned on, Google syncs them between your devices according to your Chrome sync settings; the extension itself does not transmit them. Everything else is stored in `chrome.storage.local` and is not synced.

You can reset trend history in Settings, delete saved slots in the Backup tab, or remove the extension to delete all of the above.

### Network requests

The extension loads emote images from Twitch's image server (`static-cdn.jtvnw.net`), just as the Twitch website does. It makes no other network requests.

JSON or CSV files you export are only saved where you choose, or copied to your clipboard.

### Permissions

- **`activeTab`** — talk to the Twitch tab you are on when you click the extension icon.
- **`scripting`** — connect to Twitch tabs that were already open before the extension was installed or updated.
- **`storage`** — store the preferences, pins, saved slots, automatic backups and trend history described above.
- **Content script on `twitch.tv`** — read and write the emote history inside the Twitch tab.

### Contact

If you have questions about this policy, please open an issue on [GitHub Issues](https://github.com/darrylych/Twitch-Frequently-Used-Emotes-Manager/issues).

### Changes

When this policy changes, this page and the effective date above will be updated.
