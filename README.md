---

### 校園二手書交易平台：「書在哪」專案概述

本專案「書在哪」旨在建立一個專為校園學生設計的二手書交易平台。有鑑於學生對教科書和參考書的需求、書籍價格壓力、課程結束後的書籍閒置，以及現有二手書流通管道分散且資訊不對等的問題，本平台應運而生，期望能提供一個更有效率、更經濟實惠的交易方案。

**專案核心目標：**

* 促進相同系所學生之間特定課程書籍的流通。
* 以「校內面交」為核心交易模式，簡化流程、減少物流成本與時間。
* 讓學生以更經濟實惠的價格取得所需書籍。
* 提升資源再利用效率，建立互利共贏的校園交易生態系統。
* 主要研究對象為桃園銘傳電資學院的學生。

**欲解決的問題與專案動機：**

現有的二手書交易平台（如 TAAZE、蝦皮）或校內零散管道（社團、學長姐）存在交易效率不彰、資訊不透明、賣家收益低或買家篩選困難等問題。本專案的動機即是為了解決這些痛點，提供一個專屬校園、流程簡化、交易安全的平台。

**主要功能特色：**

平台將包含以下核心功能以提升交易便利性與安全性：

* **會員系統：**
    * 訪客註冊（含電子郵件驗證）
    * 會員登入
    * 忘記密碼與重設
    * 修改個人資料
    * (可能包含帳號綁定功能)
* **書籍商品管理：**
    * 賣家上架、編輯、下架書籍資訊（含圖片、書況、價格）
    * 會員與訪客瀏覽/搜尋書籍
    * 查看書籍詳細資訊
* **交易流程與管理：**
    * 心願清單管理
    * 購物車管理（加入、查看、修改、刪除）
    * 從購物車產生訂單
    * 買賣雙方查看訂單
    * 設定與修改面交時間地點
    * 訂單變更及面交更新即時通知
* **即時通訊：**
    * 提供會員間私聊溝通
    * 保存聊天記錄
* **輔助功能：**
    * 上傳個人課表以利面交時段推薦
    * 支援多種檔案格式上傳（限制格式與大小）
    * 輸入資料格式驗證與錯誤提示
    * 確保交易資料一致性與即時同步
    * 直覺的操作介面設計

**使用技術：**

本專案採用以下技術堆疊：

* **後端框架：** ASP.NET Core MVC (開源、跨平台、高靈活性、模組化，支援 MVC 架構分離關注點)。
* **資料庫：** Microsoft SQL Server (關聯式資料庫管理系統，支援標準 SQL)。
* **前端技術：** HTML, CSS, JavaScript, Bootstrap (開源前端框架，用於快速構建響應式網頁)。
* **功能套件：**
    * MailKit：用於郵件驗證及通知。
    * SignalR：實現 .NET 應用程式的實時 Web 通信 (用於聊天功能)。
    * OpenStreetMap (OSM)：提供開放地圖資料庫 (應用於地圖展示、地點標註)。

**系統設計重點：**

* **架構模式：** 採用 MVC 架構，實現邏輯分層，提升可擴展性與可維護性。
* **可行性分析：** 經過技術、經濟、操作及時間四個維度的評估，專案具備可行性。
* **非功能性需求：** 注重可用性（直觀介面、錯誤提示）、安全性（HTTPS、密碼加密、權限控管、檔案上傳限制）、可維護性（MVC 分層、程式碼規範、註解、代碼審查）。
* **設計圖示：** 包含使用案例圖、初步類別圖及核心功能的系統循序圖。
* **介面預覽：** 預期介面風格簡潔直觀，採用卡片式與模組化設計，並提供首頁、書籍詳情頁及會員中心草圖。

**專案團隊：**

本專案由以下銘傳大學資訊管理學系成員共同研究開發：盧彥霖、顏恩齊、徐啓崴、黃偉翔、吳俊寬、王筠維、巫至捷。指導教授為鄭毅萍教授。

**開始使用：**

(此部分需根據實際開發情況補充環境需求、安裝步驟及使用方法。)

---