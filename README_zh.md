# 周冠廷 (Kuan-Ting Chou) | Senior Software Engineer

**9+ 年開發經驗 | 專精於金流系統架構、高效能遊戲引擎、Web3 基礎設施與量化交易實作**

### **技術總覽 (Technical Skills)**

* **後端與架構**：Node.js, TypeScript, C#, Move (Sui), RESTful API, Microservices.
* **資料庫**：MySQL, PostgreSQL, Schema 設計, 索引優化.
* **雲端與運維**：AWS (ECS, SQS, RDS), **Terraform (IaC)**, Docker, GitHub Actions.
* **數據與金融**：量化策略回測, Bybit/Finlab API 整合, 風險控管演算法.
* **專項技術**：自動化測試 (Coverage 90%), 軟硬體整合 (RS232, PID Control, DMX), LLM Agentic Workflow.

---

### **工作經歷 (Professional Experience)**

#### **AIFIAN | Senior Backend Engineer**

*2024.01 – 2026.02*

* **高可靠金流架構設計**：以 Adapter 模式整合 Stripe、Wise 等支付閘道。設計以 **AWS SQS** 與 **Cron-job 異步補件 (Async Repair)** 組成的**雙層對帳機制**，確保最終一致性與 100% 冪等處理。
* **資料庫 Schema 設計**：根據資料存取模式設計主鍵、外鍵與索引，建構兼顧查詢效能與資料一致性的 **MySQL/PostgreSQL** Schema。
* **基礎設施即代碼 (IaC)**：利用 **Terraform** 模組化管理 ECS、RDS 與 SQS，確保測試與生產環境配置對齊，並維護 **99% SLA**。
* **深度效能優化**：分析 Heap Snapshot 修復記憶體洩漏，使佔用率從 **40% 降至 3%**；維持核心系統 **90% 測試覆蓋率**。

#### **河流遊戲 (River Games) | Senior Software Engineer / Lead**

*2020.03 – 2024.01*

* **高效能 ECS 引擎開發**：導入 **Unity ECS** 並自主實作 2D 渲染與物理系統，利用 **C# Job System** 將同屏實體處理量從 100 提升至 2,000+。
* **框架與規範制定**：導入 DI 框架 (Zenject) 與 MVC 規範解耦 Singleton 相依問題；設計基於 Google Sheets 的數據驅動工作流。
* **跨端邏輯共享**：實作 C# 共享 Codebase 封裝核心戰鬥與數值邏輯，供 Unity 前端與 .NET 後端同步調用。

#### **自由接案 (Freelance Software Engineer)**

*2018.11 – 2020.03*

* **精密軟硬體整合**：於台中歌劇院專案開發自定義 **Keyframe Editor** 控制工業機器人；於北美館專案導入 **PID 控制演算法**，透過即時回饋穩定動力裝置輸出。
* **低延遲多媒體管線**：利用 **Texture Sharing** 與 **Shader-to-DMX** 實作即時投影與燈光同步控制；以 Python 撰寫音訊路由邏輯。

#### **日本遊戲產業經歷 (Early Career)**

* **Asobimo, Inc. (Japan)**：重構角色招式編輯器至 Timeline 架構，開發行為樹 (BT) AI 模組。
* **SEGA (Japan)**：隸屬《人中之龍》部門 TA Team，開發角色臉部動畫控制工具。

---

### **個人專案 (Side Projects)**

* **台股量化交易系統**：實現 **年化 +59.0%**、**MDD -21.3%**、**Sharpe Ratio 2.2** 之多因子量化策略。
* **Sui 區塊鏈平台**：實作自定義 **Indexer** 優化讀取效能，並以 **Terraform** 自動化管理雲端基礎設施。
* **AI 算命師 (紫微斗數)**：實作排盤演算法，結合 **LLM Agentic Workflow** 進行結構化命理分析。

---

### **學歷 (Education)**

* **國立台灣大學** | 資訊與多媒體研究所 碩士 (2014 – 2017)
* **國立台灣大學** | 資訊工程學系 學士 (2010 – 2014)
