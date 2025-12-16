# final_progject


#  智慧冰箱管理系統（Smart Fridge Management System）

# 專題簡介
本專題旨在解決日常生活中「冰箱食材管理混亂、食物容易過期與浪費」的問題。  
透過結合 **React 前端技術**、**自行設計的後端 API** 與 **第三方 AI 服務**，打造一個可實際操作的智慧冰箱管理系統，協助使用者有效管理食材並獲得料理建議。

# 目標使用者
- 大學生（外食與自煮交替）
- 忙碌上班族
- 有飲食控制或減少食物浪費需求的使用者

#問題意識
許多使用者常遇到以下情境：
- 忘記冰箱裡有哪些食材
- 食物過期才發現，造成浪費
- 不知道現有食材可以煮什麼
- 重複購買已經存在的食材

本系統透過視覺化管理與 AI 輔助建議，改善上述問題。


# 解決方案與主要功能

# 1️⃣ 冰箱庫存管理
- 新增食材（名稱、價格、重量、到期日）
- 即時顯示目前庫存清單
- 顯示剩餘比例與到期資訊

#2️⃣ 空間與價值視覺化
- 冰箱空間使用率進度條
- 食材總價值即時計算

#3️⃣ AI 智慧廚房助手
- 使用者可輸入想煮的料理或目標（如：清爽料理、減脂）
- AI 根據現有食材提供料理與保存建議
- 降低食材浪費，提高使用效率

---

# 使用技術與架構

#前端（Frontend）
- React
- JavaScript / CSS
- 部署平台：**Vercel**

# 後端（Backend）
- Node.js
- Express
- 部署平台：**Render**

# API 使用說明

1. **自行設計的後端 API**
   - 管理食材資料（新增 / 讀取）
   - 作為前端與資料、AI 之間的中介層

2. **第三方 AI API（Google Generative AI）**
   - 提供智慧料理與保存建議
   - 作為決策輔助角色，提升系統實用性

3. **Google Spreadsheet API（資料儲存）**
   - 作為雲端資料儲存方案
   - 讓後端能即時讀寫資料，避免複雜資料庫設定


---

##專案連結

- 🔗 前端網站（已部署）：  
  https://smart-fridge-frontend.vercel.app

- 🔗 GitHub Repository：  
  - Frontend：https://github.com/yu072333/smart-fridge-frontend 
  - Backend：https://github.com/yu072333/smart-fridge-backend

- 🎥 Demo 影片（YouTube）：  https://studio.youtube.com/video/9unYtQrG1XE/edit


# 未來展望
若有更多時間，未來可加入：
- 使用者登入與個人化冰箱
- 營養素與熱量分析
- 購物清單與超市 API 串接
- 手機版 UI 優化


