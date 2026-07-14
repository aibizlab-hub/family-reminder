# family-reminder

HomeMemo — 家庭提醒系統升級版 UI（部署自 `family-reminder-cloud`）。

- 靜態 GitHub Pages SPA，無後端依賴。
- 資料同源讀取 `aibizlab-hub/family-reminder-cloud` repo 嘅 `data.json`（跨 repo 同源，零遷移）。
- 支援 Service Worker（離線 / 自動更新 / Web Push）、日曆、分類、循環提醒、歷史。
- 編輯 / 推送經 `family-reminder-cloud` 嘅 GitHub Actions（cloud-reminder / caregiver-remind workflow）。
