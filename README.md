# 億柒懷舊 Messenger｜Windows XP 網頁模擬 v0.1.2

純前端網站，提供 Windows XP 風格開機／關機、懷舊桌面、虛擬 Messenger、記事本、小畫家、控制台等互動模擬。不需要資料庫或自訂網域。

## v0.1.2 新增：重新開機自動還原

- **重新啟動**：重新載入預設文件、桌布、顯示名稱、控制台設定、模擬聊天紀錄，並清空資源回收筒；當次新增的模擬文件也會消失。
- **關機後再次開機**：同樣恢復全部預設資料。
- **待命與喚醒**：保留當次已修改的內容與程式視窗，不執行還原。
- **登出、再登入**：不執行還原，直到下次重新開機。
- 這是「模擬電腦自動還原」，不是操作真實裝置，也不會刪除其他網站的資料。
- 為了處理 v0.1.0 遺留的持久資料，新版每次模擬開機會清除**本網站舊版四項專用儲存鍵**並恢復預設值。
- 「儲存記事本」表示在當次開機暫存；想永久保留文字時，請自行複製到真實筆記或檔案。

## v0.1.2 新增：YIQI XP 網站與 iPhone 主畫面圖示

- 使用已確認的 YIQI XP（億柒懷舊系統）圖示，提供 `apple-touch-icon.png` 作為 Safari 網站圖示與 iPhone「加入主畫面」圖示。
- 使用同一個相對路徑的 PNG 圖檔，適用 GitHub Pages 專案子路徑，無需自訂網域。
- 除圖示與顯示版本外，延續 v0.1.1 的模擬開機、重新啟動自動恢復等功能，不更動既有站點設定。
- 若 iPhone 主畫面仍顯示舊「億」字圖示，需要移除**舊的主畫面網站捷徑**再從 Safari 重新加入，這不會刪除 GitHub 專案。

## 安裝或更新 GitHub Pages

現有 Repository：`a0900067841-bot/yiqi-retro-messenger`

1. 下載新版 `index.html`，用 Safari 登入 GitHub 並開啟上述 Repository。
2. 在 Repository 根目錄選擇 `Add file` → `Upload files`，上傳**本新版的 `index.html` 與 `apple-touch-icon.png`** 到 Repository 根目錄，`index.html` 取代原本同名檔案。
3. 按 `Commit changes`，等待 GitHub Pages 部署完成，原本的 `github.io` 網址不需要變更。
4. Safari 如果仍看到舊版，可重新整理網頁或開啟新的私人瀏覽分頁驗證。

## 注意事項

- 並非真正的 Windows，也不能執行 `.exe` 或連線到真人 Messenger 好友。
- 原版 Windows 圖示、商標與音效均未直接引用。
- 尚需在真實 iPhone Safari 逐項驗收。
