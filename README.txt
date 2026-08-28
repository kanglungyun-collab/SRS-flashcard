SRS 單字學習卡 PWA

檔案：
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

部署方式：
1. 將整個資料夾上傳到 GitHub Pages、Cloudflare Pages 或其他 HTTPS 靜態網站主機。
2. 用 iPhone Safari 開啟該網址。
3. 按「分享」→「加入主畫面」。
4. 之後即可像 App 一樣開啟。

注意：
- PWA 必須透過 HTTPS 網址執行，直接點本機 HTML 不會完整啟用 Service Worker。
- 第一次開啟需要連網；完成快取後可離線啟動。
- CSV 內容與學習進度保存在瀏覽器 localStorage。
