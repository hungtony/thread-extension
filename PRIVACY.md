# 隱私權政策 (Privacy Policy)

**最後更新日期 / Last Updated:** 2026-11-24

## 繁體中文

感謝您使用「**留言過濾封鎖小幫手 for Threads**」（以下簡稱「本擴充功能」）。我們高度重視您的隱私，特此說明本擴充功能的資料處理方式：

### 1. 資料收集與傳輸
- **本擴充功能不收集、不上傳、不分享、不販售任何個人資料。**
- 本擴充功能**沒有任何外部伺服器**，所有掃描、關鍵字比對與介面操作皆完全在您的瀏覽器本機端執行。

### 2. 本機儲存的資料
本擴充功能使用 Chrome 內建的 `chrome.storage.local` API，僅在您的裝置本機儲存以下設定與暫存資料：
- 您自訂的關鍵字清單與白名單帳號
- 您的個人設定（動作模式、操作延遲時間、批次上限、排除之個人帳號名稱）
- 上次掃描的結果暫存（方便重新開啟視窗時檢視，可隨時按「清除結果」刪除）
- 本機操作歷史紀錄（可隨時於設定頁清除或匯出 CSV）

上述資料僅存於您的瀏覽器本機中，移除本擴充功能後即會一併刪除。

### 3. 權限使用說明
- `activeTab` / `scripting`：僅在您主動點擊掃描或執行時，讀取目前 Threads 貼文頁面的留言文字，或在開啟的工作視窗中協助完成您所勾選的檢舉／封鎖操作。
- `storage`：用於在本機保存您的關鍵字、白名單、設定與掃描暫存結果。
- `notifications`：於批次處理完成或中斷時，向您顯示本機桌面通知。
- `host_permissions` (`threads.com` / `threads.net`)：僅限於 Threads 網域執行上述功能，不會存取其他任何網站。

### 4. 免責與非官方聲明
本擴充功能為獨立開發之第三方輔助工具，與 Meta Platforms, Inc. 或 Threads 無任何隸屬、合作或官方背書關係。

### 5. 聯絡方式
如對本隱私權政策有任何疑問，請透過本專案的 GitHub Issues 或商店支援頁面與開發者聯繫。

---

## English

Thank you for using **Comment Filter & Block Assistant for Threads** ("the Extension"). We respect your privacy and handle all data locally:

### 1. Data Collection & Transmission
- **We do NOT collect, transmit, share, or sell any user data.**
- The Extension has **no remote backend servers**. All comment scanning, keyword matching, and user-initiated actions run strictly locally inside your browser.

### 2. Local Storage
The Extension uses Chrome's `chrome.storage.local` API solely to store your preferences on your own device:
- Custom keywords and whitelisted usernames
- Extension preferences (action mode, delay settings, batch limit, self-account exclusion)
- Temporary scan results (so closing the popup does not lose your current list; clearable at any time)
- Local action history log (clearable or exportable to CSV from the Options page)

All stored data remains on your device and is deleted when you uninstall the Extension.

### 3. Permissions
- `activeTab` / `scripting`: Used only when you initiate a scan or batch action on Threads pages.
- `storage`: Saves your keywords, whitelist, settings, and scan state locally.
- `notifications`: Displays a local desktop notification when a batch job finishes.
- `host_permissions` (`threads.com` / `threads.net`): Strictly scoped to Threads domains; no other websites are accessed.

### 4. Disclaimer
This Extension is an independent, unofficial third-party tool and is not affiliated with, endorsed by, or sponsored by Meta Platforms, Inc. or Threads.
