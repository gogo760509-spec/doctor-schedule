門診醫師表格製作網站｜圖片＋Excel＋Word＋PDF 匯入版

支援匯入
1. 圖片：PNG / JPG / WEBP
   - 雙階段繁中 OCR
   - 高對比去格線
   - 漏字格逐格放大重試

2. Excel：XLSX / XLS / XLSM
   - 直接讀取儲存格
   - 可選工作表
   - 自動辨識門診時間／診別／星期欄位

3. Word：DOCX / DOCM
   - 直接讀取 Word 表格
   - 支援合併儲存格
   - 若使用舊版 .doc，請先另存為 .docx

4. PDF
   - 文字型 PDF：優先直接讀取文字層
   - 掃描型 PDF：自動改用繁中 OCR
   - 建議使用正面、清晰、完整的門診表 PDF

其他功能
- 三時段合計最多 42 格
- 診別「診」固定鎖定，只能修改數字
- 醫師姓名最多 4 字
- 中文輸入法 IME 重複字修正
- 星期六晚診、星期日固定休診
- 清空醫師名字／清空診別
- PNG 300 dpi，表格外圍透明

網路需求
- Excel：SheetJS
- Word：Mammoth.js
- PDF：PDF.js
- 圖片／掃描型 PDF OCR：Tesseract.js
以上函式庫目前由 CDN 載入，因此首次使用相關匯入功能需要網路。

上架
- 將 index.html 放到網站公開目錄即可。
- 可部署至 GitHub Pages / Netlify / Vercel / Cloudflare Pages。
