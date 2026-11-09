# SAGUD 薩谷德｜16族語歡迎網站

靜態網站，可直接部署 GitHub Pages。

## 部署
1. 建立公開 GitHub Repository，名稱例如 `sagud-welcome`。
2. 將本資料夾的 **內容** 上傳至 Repository 根目錄（index.html 必須位於根目錄）。
3. Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save。
4. 網址為 `https://USERNAME.github.io/sagud-welcome/`。
5. 16 組 QR Code 對應 `https://USERNAME.github.io/sagud-welcome/#amis` 等網址；正式網址確認後才製作 QR Code。

## 注意
- `tribes.json` 的 romanization 目前直接沿用音檔檔名，底線及特殊字元仍需族語專業校對。
- 音檔來源資料夾註記「族語語音合成系統 - 族語AI成果網站」，請先確認公開播放與商業包裝 QR Code 使用授權。
- 本網站不會自動播放音檔，須由使用者點擊播放。
- 需透過 HTTP 網站伺服器測試（例如 GitHub Pages）；直接以 file:// 開啟 index.html 時，瀏覽器可能阻擋讀取 JSON。
- `assets/background.jpg` 已縮圖壓縮以改善手機載入速度。
