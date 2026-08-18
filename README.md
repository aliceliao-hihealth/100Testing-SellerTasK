# 賣家側　任務分配

JustPlay 官網穩定度測試（100 筆訂單，正式環境）測試團隊文件。

## 閱讀方式

**網頁版（建議）**：<https://aliceliao-hihealth.github.io/100Testing-SellerTasK/>

倉儲／營運／財會三類作業的負責事項、前置作業、訂單終態分流與作業要點

本頁分為兩個分頁，可於上方切換：**任務分配**（`#tasks`）與**測項清單**（`#items`）。

## 本次測試的其他文件

| 文件 | 內容 |
|---|---|
| [事前說明](https://aliceliao-hihealth.github.io/100Testing-Readme/) | 全體必讀：目的、工作範圍、各項工作對應的文件、開始前八項確認、回報方式 |
| [買家側　逐筆執行腳本](https://aliceliao-hihealth.github.io/100Testing-Buyer-Scripe/) | 100 列均已載明日期、時段、裝置、商品與數量、取貨方式與應執行動作 |
| [邊角案例手冊](https://aliceliao-hihealth.github.io/justplay_game_edgecase/) | 27 個客服／營運情境的處理方式。測試期間依手冊處理，並同時驗證手冊本身 |
| [說明圖（四張）](https://aliceliao-hihealth.github.io/100Testing-Readme/diagrams.html) | 文件結構、執行流程、訂單分流樹、3 天時間軸 |

三份文件建議的閱讀順序為：**事前說明 → 依承接的工作查閱買家側或賣家側文件**。承接的工作對應該讀哪幾份，列於《事前說明》第三節，也畫在說明圖第①張。

## 本 repo 內容

| 檔案 | 說明 |
|---|---|
| `index.html` | 網頁版，單檔、無外部資源，支援手機瀏覽與列印 |
| `seller_tasks.md` | Markdown 原始檔，供改版時比對差異 |
| `test_items.md` | 測項清單 Markdown 原始檔 |
## 版本

| 項目 | 內容 |
|---|---|
| 最後更新 | 2026-08-18 |
| 維護 | Alice Liao（PM Lead）|
| 來源 | `專案/JustPlay/PRD/qa-evidence/` |

> 內容有誤或與實際情況不符，請於測試群組回報。
