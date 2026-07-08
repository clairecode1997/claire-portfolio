# 個人作品集網站（靜態）

完整可部署的靜態網站，直接把整個 `portfolio-site/` 資料夾上傳到 GitHub Pages、Netlify 或 Vercel 即可。

## 結構

| 檔案 | 說明 |
|---|---|
| `index.html` | 首頁：Hero、作品任務板、技能樹、冒險日誌（經歷）、聯絡 |
| `marx-pm-case-study.html` | MarX PM case study（已加返回首頁連結） |
| `marx-ux-case-study.html` | MarX UX case study（已加返回首頁連結） |
| `assets/` | 圖片 |

所有頁面右上角皆可切換中／英，選擇會記憶在瀏覽器。

## 發佈前請自行修改（都在 index.html）

1. **中文姓名**：目前只放英文名，若要加中文名，改 `<h1 class="name">`。
2. **時間軸年份**：MarxAI 實習標 2025；北科大與德國交換的年份請搜尋 `Journey` 區塊自行補上。
3. **三張 Coming Soon 卡片**（謀殺衛斯理、Taiwan Island、點子松）：取自你的履歷專案清單，內容待補；不需要的直接刪除該 `<div class="quest locked">` 區塊。
4. **聯絡方式**：目前只有 Email，可在 `contact-row` 加 LinkedIn／GitHub 按鈕（複製現有 `<a class="btn">` 改連結即可）。
5. **Sprint 看板截圖**（PM case study 內）含團隊成員姓名，公開前建議打碼或刪除 `assets/sprint-board.png`。

## 部署（GitHub Pages 範例）

1. 建一個 repo（例如 `claire-portfolio`），把資料夾內容推上去。
2. Settings → Pages → Source 選 `main` branch 根目錄。
3. 完成，網址為 `https://<帳號>.github.io/claire-portfolio/`。
