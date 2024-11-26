# 扭蛋機率計算器 (Gacha Probability Calculator)

一個簡單但功能完整的扭蛋/轉蛋機率計算器，支援機率分析、模擬抽卡、花費統計等功能。

## 🌟 主要功能

### 1. 機率分析
- 自動計算總機率和分布
- 支援 SABC 等級分類
- 即時機率驗證和警告
- 自動檢查機率總和是否為 100%

### 2. 抽卡模擬
- 自訂抽卡次數
- 自訂單抽價格
- 完整的抽卡結果統計
- 各等級物品統計

### 3. 期望道具追蹤
- 可設定期望道具
- 高亮顯示抽中的期望道具
- 期望道具抽取統計
- 累積獲得記錄

### 4. 花費統計
- 累積花費追蹤
- 詳細的抽卡歷史記錄
- 每次抽卡的期望道具記錄
- 可刪除個別記錄

## 💻 使用方法

1. **基本操作**
   ```
   - 將機率表複製貼上到文本框
   - 設定單抽價格和抽卡次數
   - 點擊「計算」按鈕查看結果
   ```

2. **期望道具設定**
   ```
   - 在期望道具輸入框輸入道具名稱
   - 點擊「新增」或按 Enter 添加
   - 可隨時點擊 × 移除期望道具
   ```

3. **查看統計**
   ```
   - 機率總覽：顯示在頁面頂部
   - 抽卡結果：包含詳細統計和分布
   - 花費記錄：顯示歷史記錄和總花費
   ```

## 📋 支援的機率表格式

1. SABC 等級格式：
```
S等級物品名稱 1.5%
A等級物品名稱 3.0%
B等級物品名稱 5.0%
C等級物品名稱 10.0%
```

2. 一般格式：
```
物品名稱 1.5%
物品名稱 3.0%
```

## 💾 數據存儲

- 使用 localStorage 自動保存：
  - 期望道具列表
  - 抽卡歷史記錄
  - 累積花費統計

## 🔧 技術特點

- 純前端實現，無需後端
- 響應式設計，適配各種螢幕
- 即時計算和驗證
- 數據本地持久化

## 🚀 快速開始

1. 下載 HTML 檔案
2. 使用瀏覽器開啟
3. 直接開始使用

## ⌨️ 快捷鍵

- `Enter`：在期望道具輸入框中按 Enter 可快速添加
- `Paste`：貼上機率表後自動分析並計算

## 🛠 自訂配置

可以自訂的參數：
- 單抽價格
- 抽卡次數
- 期望道具數量無限制

## 📊 輸出格式

1. **抽卡結果**
   - 總花費
   - 抽卡次數
   - 各物品獲得統計
   - 各等級統計

2. **花費記錄**
   - 時間戳記
   - 抽卡次數
   - 花費金額
   - 期望道具獲得情況

## ⚠️ 注意事項

1. **機率表格式**
   - 確保機率表格式正確
   - 總機率應接近 100%
   - 支援小數點後多位數

2. **瀏覽器支援**
   - 需要支援 localStorage
   - 建議使用現代瀏覽器
   - 需要啟用 JavaScript

## 🔄 更新日志

### v1.0.0
- 基本功能實現
- 機率分析
- 抽卡模擬
- 花費統計

## 📝 授權協議

MIT License

## 🤝 貢獻指南

歡迎提交 Issue 和 Pull Request 來改進這個項目。

## 👥 作者

台服愛麗沙玩家 - Sorina

## 📞 支援與反饋

如有問題請提交 Issue 進行反饋。
