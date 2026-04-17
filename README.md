# ShadowSpeak

English shadowing practice PWA — works fully offline after first load.

## 部署到 GitHub Pages

1. 把 `shadowspeak/` 資料夾裡的所有檔案上傳到你的 GitHub repo 根目錄
2. 到 repo Settings → Pages → Source 選擇 `main` branch → `/root`
3. 儲存後等約 1 分鐘，GitHub 會給你一個 `https://yourusername.github.io/reponame` 的網址
4. 用 Android Chrome 打開網址，點右上角「⋮」→「加到主畫面」即可安裝為 PWA

## 功能說明

| 步驟 | 內容 | 網路需求 |
|---|---|---|
| Step 1 | 上傳音檔、完整播放、斷句、選句 | ❌ 離線 |
| Step 2 | 播放原句→錄音跟讀→回聽對比→下載 | ❌ 離線 |
| Step 3 | Paraphrase + 情境改寫 + 30s 輸出 | ✅ API 待接入 |

## 注意事項

- 麥克風錄音需要 HTTPS（GitHub Pages 預設支援）
- 錄音檔為 `.webm` 格式（Android Chrome 標準格式）
- 斷句目前為模擬示範，正式版本需接入 Web Audio API 靜音偵測

## 圖示

`icons/` 資料夾放 `icon-192.png` 和 `icon-512.png`（可用任何圖示工具生成）
