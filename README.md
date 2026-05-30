# Chong Ming Chen 陳崇銘 — 個人履歷網站

一個單檔、純靜態的多語履歷網站，可直接部署到 GitHub Pages。

🔗 **線上瀏覽**：https://jokerjkeeper.github.io/resume/

## 特色

- **三語切換**：English / 繁體中文 / 简体中文，右上角一鍵切換
- **自動偵測語言**：首次造訪依瀏覽器系統語言自動選擇，之後記住偏好（localStorage）
- **簡約風格**：中性灰階配色、低調排版，專注於內容
- **響應式**：桌機 / 手機自動調整版面
- **可列印 / 存 PDF**：右上「列印 / PDF」按鈕，已最佳化列印樣式
- **零相依**：單一 `index.html`，無外部框架或建置流程

## 內容區塊

個人優勢 ・ 技術技能 ・ 工作經歷 ・ 代表專案 ・ 學歷

## 本機開啟

直接用瀏覽器開啟 `index.html` 即可，無需任何伺服器或安裝步驟。

## 部署到 GitHub Pages

1. 將本 repo 推送到 GitHub
2. 進入 **Settings → Pages**
3. **Source** 選 `Deploy from a branch`，Branch 選 `main` / `/ (root)`，按 **Save**
4. 約一分鐘後即可透過上方網址瀏覽

## 修改內容

所有履歷文字以資料物件（`INTRO` / `SKILLS` / `EXPERIENCE` / `PROJECTS` / `EDUCATION`）
集中存放於 `index.html` 底部的 `<script>` 中，每筆皆為 `{ en, tw, cn }` 三語格式，
修改對應欄位即可，無需改動版面樣式。

## 授權

個人履歷內容，著作權所有；版面與程式碼可自由參考。
