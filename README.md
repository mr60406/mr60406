# 楊政豪 | mr60406

> 持續學習 Python、資料工程、SQL 與 AI，並透過實際專案把知識轉化為可以執行、驗證與持續改進的系統。

## 關於我 | About Me

你好，我是 **楊政豪（mr60406）**。

我目前持續投入 **Python、SQL Server、資料工程、金融資料分析、機器學習與 AI 應用** 的學習與實作。我的學習方式並不是只停留在語法或教學範例，而是希望透過真正的專案，把資料取得、資料庫設計、資料清洗、特徵工程、模型、回測、視覺化與系統治理逐步串接起來。

目前最主要的實作是 **Automated Stock Trading** 專案。我把它當成一個長期學習工程：從 SEC 等來源取得財務資料，處理 JSON / XBRL 與資料品質問題，再建立技術指標、企業護城河研究、PIT（Point-in-Time）資料約束、AI 選股與回測流程。

我仍在持續學習，也不把自己包裝成已經精通所有技術的人。對我而言，重要的是能夠理解問題、實際動手、發現錯誤、驗證結果，並把每一次修改留下可以追蹤的紀錄。

---

## 技術與學習方向 | Skills & Learning

### Programming & Data
- **Python** — 資料處理、自動化、API 串接、金融資料流程
- **SQL / SQL Server** — Schema 設計、資料查詢、歷史資料保存與資料治理
- **REST API / requests** — 外部資料來源與 API 整合
- **JSON / XBRL** — SEC 財務資料解析與標準化
- **pyodbc** — Python 與 SQL Server 整合

### Financial Data & Quant Research
- 財務報表資料工程
- 技術指標與交易訊號研究
- 基本面與企業護城河分析
- Point-in-Time（PIT）資料設計
- Feature Engineering
- Machine Learning 選股流程
- Backtesting / Forward Return 驗證

### Visualization & Application
- **Streamlit** — 研究與交易工作站 UI
- **Power BI** — 財務與研究資料視覺化（持續學習與整合中）

### Engineering Practices
- Git / GitHub
- Branch / Pull Request 工作流程
- 測試與 Regression Verification
- 資料 lineage / provenance
- 文件化與系統契約
- 以可重現、可驗證為目標的資料流程設計

---

## 主要專案 | Featured Project

### Automated Stock Trading

我的核心學習專案是一套持續開發中的自動化股票研究與交易系統。

它不只是「預測股票漲跌」的模型，而是嘗試建立完整流程：

```text
Financial / Market Data
        ↓
Data Collection & Validation
        ↓
SQL Server / Historical Data
        ↓
Fundamental + Technical Features
        ↓
Moat / Company Screening
        ↓
Point-in-Time Dataset
        ↓
AI / Machine Learning Selection
        ↓
Entry Signal Analysis
        ↓
Backtesting & Validation
        ↓
Research / Trading UI
```

目前專案涵蓋：

- SEC 財務資料取得與解析
- 財報欄位 mapping、資料清洗與品質驗證
- SQL Server 財務與市場資料儲存
- EPS、ROIC、ROE、BVPS、FCF 等財務特徵研究
- MACD、KDJ、成交量等技術面資料與訊號研究
- 企業護城河與基本面篩選
- 歷史資料與 Point-in-Time 防止未來資訊洩漏
- AI / Machine Learning 選股流程
- Forward Return 與回測系統
- Streamlit / Power BI 研究介面規劃
- Regression tests、資料 lineage 與系統文件治理

🔗 [View Automated Stock Trading Repository](https://github.com/mr60406/automated-stock-trading)

---

## 我的學習方式 | How I Learn

我習慣用「**做出來 → 找問題 → 驗證 → 重構 → 再驗證**」的方式學習。

在專案開發過程中，我逐漸發現，真正困難的往往不是寫出一段 Python，而是：

1. 資料來源是否可信？
2. NULL 或異常資料應該怎麼處理？
3. 歷史模型有沒有不小心看到未來資料？
4. 資料被更新後，能不能知道它從哪裡來？
5. 程式修改後，有沒有破壞原本正確的結果？
6. AI 的輸入到底應該是什麼，而不是把所有資料全部丟進模型？

因此，我開始把更多時間投入在 **資料品質、歷史可追溯性、測試、系統契約與架構設計**，而不只是追求快速完成功能。

我也會使用 AI 工具協助研究、程式開發與 Code Review，但我希望 AI 是加速學習與工程流程的工具，而不是取代理解與驗證。

---

## 現在正在學習 | Currently Learning

目前持續加強：

- Python 軟體工程能力
- SQL 與資料庫架構
- Financial Data Engineering
- Machine Learning / Feature Engineering
- 時序資料與 Point-in-Time 設計
- Quantitative Research & Backtesting
- Power BI / Data Visualization
- Streamlit / PySide6 應用程式介面
- AI-assisted Software Development

---

## 我的目標 | Goal

我的目標不是只完成一個作品，而是逐步建立一套屬於自己的能力：

> **能夠從真實世界取得資料，理解資料、治理資料、建立模型、驗證結果，最後把它做成真正可以使用的系統。**

我知道自己還有很多需要學習的地方，因此這個 GitHub 也會持續記錄我的進步、犯過的錯誤，以及每一次把問題做得更完整的過程。

---

## English Summary

I'm **Zheng-Hao Yang (mr60406)**, a hands-on learner focused on **Python, SQL Server, data engineering, financial data analysis, machine learning, and AI-assisted software development**.

My main project is an evolving automated stock research and trading system. Through this project, I am learning how to build reliable pipelines from raw financial and market data to validated datasets, feature engineering, company screening, point-in-time machine-learning workflows, backtesting, and research interfaces.

Rather than presenting myself as an expert in every technology I use, I focus on continuous improvement: **build, test, identify problems, understand them, refactor, and verify again**.

My long-term goal is to develop the ability to turn real-world data and ideas into systems that are **reproducible, explainable, testable, and genuinely useful**.
