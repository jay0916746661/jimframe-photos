# JimFrame 活動照片庫

> 📘 中文說明書（2026-11-28 整理）｜狀態：🟢 使用中（不要封存）
> 全部 29 個 repo 的總表與封存建議：[repo 地圖](https://github.com/jay0916746661/jimframe-site/blob/main/docs/repo地圖與封存建議.md)

## 這是什麼
JimFrame 攝影網站的照片倉庫：每場活動一個資料夾（例如 `tsc1121/`、`tsc1122/`），放網站版大圖（1400px）和縮圖（480px）。jimframe-site 的活動頁直接從這裡讀照片。分出來的原因：主站 repo 太大，GitHub Pages 有 1GB 上限。

## 怎麼用／怎麼改
新活動：照 event-photo-pipeline 流程（初篩→調色→縮圖）產生網站版照片，新增一個活動資料夾，再到 jimframe-site 的活動頁接上路徑。照片公開前要先在網站後台 `?admin` 挑過。

## 要注意
照片在網站上破圖：先確認檔名大小寫和路徑完全一樣（GitHub 分大小寫）。repo 已經 8,000 多張，單一 repo 建議不要超過約 5GB；滿了就開 `jimframe-photos-2`。

### 怎麼修（不用 Claude 也做得到）
1. 小改字：在 GitHub 網頁打開檔案 → 右上角鉛筆 ✏️ → 改完按 Commit changes。
2. 大改：用 Antigravity（Gemini）開這個 repo，第一句貼：「先讀 README.md，照裡面的說明改，改完給我分支名＋PR 連結，不要直接改 main。」
3. 改壞了：GitHub 網頁 → Commits → 找到改壞前那一版 → 點 `<>` 看舊檔，複製回來。**不要刪 repo、不要 force push。**

## 封存建議（只是建議，沒有動任何東西）
不建議。

---

## 原本的 README（保留原文）

# jimframe-photos

JimFrame 活動照片的網站版（大圖 1400px＋縮圖 480px），給 jimframe-site 的活動頁讀取。主站因 GitHub Pages 容量上限，新活動照片放這裡。

- `tsc1122/`：TSC 2026 Day3（11/22）
