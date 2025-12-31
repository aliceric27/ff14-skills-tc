# FFXIV 繁中版 技能狀態資料庫

一個用於搜尋 Final Fantasy XIV 技能 (Action) 與狀態 (Status) 的網頁工具。

## 功能

- 自動從 GitHub 載入最新繁中資料
- 搜尋技能與狀態名稱、ID
- 依類型篩選（技能/狀態）
- 依模式篩選（PVP/PVE）
- 依職業篩選
- 顯示技能圖示

## 使用方式

直接開啟 `index.html` 即可，頁面會自動從 GitHub 載入最新的 CSV 資料。

如果自動載入失敗，也可手動上傳 CSV 檔案。

## 資料來源

CSV 資料自動從 [ffxiv-datamining-tc](https://github.com/miaki3457/ffxiv-datamining-tc) 載入，感謝 [@miaki3457](https://github.com/miaki3457) 提供繁體中文遊戲資料。

使用 [jsDelivr CDN](https://www.jsdelivr.com/) 來取得最新資料並繞過 CORS 限制。

## 授權

本工具僅供個人學習使用，遊戲資料版權歸 SQUARE ENIX 所有。
