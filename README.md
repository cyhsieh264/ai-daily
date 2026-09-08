# AI 週報

一頁看完這週的 AI 圈。

線上閱讀：**https://cyhsieh264.github.io/ai-daily/**

## 這是什麼

每週一期、每期一頁的 AI 新聞摘要，採報紙編輯風排版：報頭、頭條與本週發布時間線、三欄專題、簡訊、附來源的頁尾。桌面與手機皆可閱讀，直接列印即為 A4 一頁。

最新一期：第 001 期，涵蓋 2026 年 9 月 1 日至 9 月 7 日
https://cyhsieh264.github.io/ai-daily/2026-09-08/

## 專案結構

```
index.html        期數列表（首頁）
style.css         共用樣式
2026-09-08/       第 001 期，資料夾以發刊日命名
  index.html
```

純靜態、無建置流程。字型由 Google Fonts 載入（Noto Serif TC、Noto Sans TC）。所有外部連結皆以新分頁開啟。

## 出新一期

1. 複製最新一期的資料夾，改成新的發刊日，例如 `2026-09-15/`。
2. 修改該資料夾的 `index.html`：期數、日期區間、各篇內容與來源連結。
3. 在根目錄 `index.html` 的期數列表最上方加一列，指向新資料夾。
4. Push 到 `main`，GitHub Pages 約一至兩分鐘後更新。

## 部署

GitHub Pages，來源為 `main` 分支根目錄。
