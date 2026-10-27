# 織間 Yarn Studio
免費、無相依套件的繁體中文織圖編輯器。直接用瀏覽器開啟 index.html 即可操作。

## 功能
- 方格配色、畫筆、橡皮擦、填色、取色
- 5–100 格尺寸、縮放、格線、復原重做
- 自由放置、拖曳與旋轉簡易針法符號（字元式圖例，非專業針法排版引擎）
- 圖片轉固定色盤方格（等比例置中取樣）
- PNG 圖片下載、JSON 專案下載與重新開啟
- 瀏覽器 localStorage 自動儲存

## GitHub Pages 免費部署
1. 在 GitHub 建立 Public repository。
2. 把 index.html、README.md 和 .nojekyll 放在儲存庫根目錄。
3. 開啟 Settings → Pages。
4. Source 選 Deploy from a branch，分支 main，資料夾 / (root)，按 Save。
5. 等待 GitHub 顯示網站網址。

使用 GitHub 提供的 github.io 網址，不需要購買網域。請遵守 GitHub Pages 使用限制。

## 資料與費用
本專案不需要後端、資料庫、API key、訂閱或付費套件。圖片轉換與下載都在本機瀏覽器進行。公開原始碼不會自動公開使用者織圖；織圖不會傳上 GitHub。
自動儲存不會跨裝置同步，清除瀏覽器資料可能遺失。請下載 JSON 備份。瀏覽器私密模式、檔案模式或儲存空間限制可能影響自動儲存。

## 限制
這是第一版編輯工具，尚無帳號、雲端同步、多專案管理、專業曲線針法排版、照片反推針數或 PDF 排版。自由符號須自行檢查織法。

## 本機 Git
在本資料夾執行 git init，接著 git add . 和 git commit，連接自己的 GitHub remote 後推送即可。
