# 微光｜屬靈讀經筆記

一個可直接部署到 GitHub Pages 的繁體中文單頁互動網站。

## 功能
- 引導式讀經：5 步驟引導觀察、理解、個人回應、禱告與實踐。
- 一鍵生成：將經文摘要整理成可編輯筆記架構。
- 我的筆記：本機儲存、開啟編輯、刪除、匯出／匯入 JSON 備份。
- 今日金句與禱告欄位。
- 響應式版面，支援手機與桌面。

## 部署到 GitHub Pages
1. 建立一個新的 GitHub repository。
2. 將 `index.html` 與 `README.md` 上傳到 repository 根目錄。
3. 開啟 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 **Deploy from a branch**。
5. Branch 選 `main`，資料夾選 `/(root)`，按 **Save**。
6. 等待 GitHub Pages 部署完成，使用頁面提供的網址開啟。

## 重要說明
- 本版本是可操作的前端原型；「一鍵生成」使用內建筆記模板，不會呼叫雲端 AI，也不會自動查經。
- 筆記保存在瀏覽器 `localStorage`，不會自動同步到其他裝置。請定期匯出 JSON 備份。
- 若要加入 Gemini 等模型，請另建安全的後端／Serverless API；不要把 API key 寫進公開的前端 HTML 或 GitHub repository。
- AI 是讀經整理輔助，不應宣稱代表神直接發言；經文解釋需重視上下文、可靠釋經資料與教會群體的辨識。
