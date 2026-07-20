# 門牌批次定位導航助手

## 使用方式

1. 將 ZIP 解壓縮。
2. 將 `index.html` 上傳到 GitHub repository 根目錄。
3. 開啟 GitHub Pages 網址。
4. 輸入 TGOS APP ID 與 API Key，按「連線 TGOS」。
5. 貼上「水號、姓名、地址」資料，按「整理資料」。
6. 按「開始批次定位」。
7. 核對比對地址後，可逐筆開啟 Google Maps，或匯出 CSV／KML。

## 可接受的輸入格式

每行一筆：

- 地址
- 水號 + Tab + 姓名 + Tab + 地址
- 水號,姓名,地址

## 注意事項

- ZIP 不包含你的 TGOS 金鑰。
- GitHub Pages 是公開的前端網頁，瀏覽器使用的金鑰無法真正保密。請在 TGOS 後台限制允許的網域。
- TGOS 支援模糊地址定位，務必核對「輸入地址」與「比對地址」。
- 本工具採逐筆查詢並設有間隔，避免短時間發出過多要求。
- Google Maps 導航使用 WGS84 經緯度。
