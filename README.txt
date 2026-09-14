門診醫師表格製作網站｜上架版

檔案：
- index.html：網站主檔，可直接部署

上架方式：
1. 將 index.html 上傳到網站主機的公開目錄。
2. 若使用 GitHub Pages / Netlify / Vercel / Cloudflare Pages，可直接上傳此資料夾或 ZIP 解壓後部署。
3. 網站為純前端單頁，不需要資料庫、不需要後端、不需要安裝套件。

功能：
- 自訂早診／午診／晚診診別格數，最多共 40 格
- 診別僅可修改數字，「診」固定鎖定
- 醫師姓名可直接輸入，最多 4 字
- 已處理中文輸入法 IME 重複字問題
- 星期六晚診固定休診、星期日固定休診
- 清空醫師名字、清空診別
- PNG 下載 300 dpi
- 表格外圍透明背景
- 寬度固定 17 cm，高度依格數 9–16 cm

字體：
- 優先使用 Source Han Sans TC / 思源黑體
- 若使用者裝置未安裝，會依序使用 Noto Sans TC / PingFang TC / Microsoft JhengHei

注意：
- 不需要額外圖片、CSS 或 JavaScript 檔案。
- 此版本為單一 index.html，可離線開啟，也可直接部署到靜態網站服務。
