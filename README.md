# 醬動 JN DONG（PWA 版）

可以加入手機主畫面、離線使用的健身 app。免費放在 GitHub Pages 上就能分享給朋友。

## 檔案
- `index.html`：app 本體
- `manifest.webmanifest`：app 名稱、圖示、顏色
- `sw.js`：離線快取
- `icon-*.png`、`apple-touch-icon.png`：主畫面圖示

## 用 GitHub Pages 免費上線
1. 到 github.com 註冊或登入。
2. 右上角「+」→「New repository」，名稱例如 `jndong`，選 **Public**，按 Create。
3. 在新的 repository 頁面點「uploading an existing file」，把這個資料夾裡的**所有檔案**拖進去（不是整個資料夾），按「Commit changes」。
4. 到「Settings」→ 左邊「Pages」→ Branch 選 `main`、資料夾選 `/ (root)` → Save。
5. 等 1–2 分鐘，網址會出現在同一頁，格式是 `https://你的帳號.github.io/jndong/`。

## 加入手機主畫面
- **iPhone**：用 Safari 打開網址 → 分享按鈕 → 「加入主畫面」。
- **Android**：用 Chrome 打開網址 → 右上角選單 → 「安裝應用程式」或「加到主畫面」。

## 更新 app
上傳新的檔案覆蓋舊的即可。若改了 `index.html`，把 `sw.js` 第 2 行的 `v1` 改成 `v2`（之後依序遞增），朋友的手機下次開啟就會拿到新版。

## 注意
- 每個人的紀錄只存在自己手機的瀏覽器裡。換手機或清除瀏覽器資料前，請到「進度」頁最下面「匯出紀錄」備份。
- 這個版本沒有 AI 功能（AI 菜單、AI 教練、週回顧），這些只在 Claude 版本提供。
- 本 app 的建議僅供一般參考；有傷病、懷孕或慢性病，請先諮詢醫師或物理治療師。
