# QA 自動化測試平台

這是依照目前需求文件製作的 MVP Prototype。

## 功能
- 測試案例管理
- Mock Test Runner
- Pass / Fail 模擬結果
- 執行紀錄
- Pass Rate 統計
- JSON 匯入 / 匯出
- 瀏覽器 localStorage 儲存
- 不需要後端，可直接部署到 GitHub Pages / Vercel / Netlify

## 本機測試
直接雙擊 `index.html` 即可開啟。

## 部署
最簡單方式：GitHub Pages。
1. 在 GitHub 建立公開 repository，例如 `qa-automation-platform`
2. 上傳 `index.html` 與 `README.md`
3. Repository → Settings → Pages
4. Source 選 `Deploy from a branch`
5. Branch 選 `main` / root
6. Save
7. 等待 GitHub Pages 建立網址

注意：資料存在「每個使用者自己的瀏覽器 localStorage」，所以分享網址後，每個人看到的是自己的測試資料，不會互相同步。
