# 倉儲管理系統

此頁面已支援：
- 手機與電腦共用同一份資料（雲端同步）
- 手機版與電腦版自適應排版

## 啟用手機/電腦同步

1. 建立 Firebase 專案並啟用 **Realtime Database**。
2. 開啟 `index.html`（以及同內容檔案 `倉儲管理系統_V5_前期存貨版.html`）中的 `firebaseConfig`。
3. 將以下欄位填入你的 Firebase 設定值：
   - `apiKey`
   - `authDomain`
   - `databaseURL`
   - `projectId`
   - `storageBucket`
   - `messagingSenderId`
   - `appId`
4. 重新載入網頁後，手機與電腦會即時同步更新庫存與紀錄。

> 若 `firebaseConfig` 未填，系統會自動改為本機模式（僅單一裝置儲存）。