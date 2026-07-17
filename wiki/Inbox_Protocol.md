---
title: Inbox Protocol
date_created: 2026-07-09
aliases: [Inbox, 收件匣]
tags: [protocol/workflow, knowledgebase, system_rules, process]
status: active
version: 1.0
---

# 📥 統一收件匣機制 (The Universal Inbox Protocol)

**流程目的：** 將所有來源、尚未分類的資訊（無論是外部輸入、臨時想法、主管交辦或網路文章），首先集中存放在一個單一的入口點，從而最大程度地降低心流切換成本和決策疲勞。
**原則核心：** **「接收 (Capture) > 分類 (Process)」**。絕不在訊息進入時就嘗試判定其最終歸屬。

## 🚀 工作流程步驟 (Workflow Steps)

### Step 1: 統一捕獲點 (The Single Intake Point)
*   **動作:** 無論資料的來源是什麼，都必須先將原始資訊（Raw Data）丟入「收件匣」。
*   **預設儲存位置：** `C:\donnydoc\mydocs\mydocs\raw/inbox/` （建議在 `raw/` 下建立一個 `inbox` 子目錄）。
*   **處理方式:** 應以原始、未編輯的格式保存，確保證據鏈完整性。

### Step 2: 每日審核與轉譯 (Daily Review & Transmutation)
*   **執行時間：** 建議在每天工作結束前的固定時段（例如：下午 5 點 - 5:30 PM）進行。
*   **目標:** 將 `raw/inbox/` 中的內容，逐一審閱、分析並完成 **「知識轉譯」** 的過程。
*   **處理流程 (Triage):** 對於 Inbox 中的每一筆資料，必須回答以下兩個問題：
    1.  **它是什麼？(What is it?)**: 核心概念、資訊點或任務定義。
    2.  **它是哪裡屬於的？(Where does it belong?)**: 它應該成為一個 `wiki/` 的知識節點，還是需要一個具體的行動項目 (放入 `Registry/`)。

### Step 3: 分類歸檔與執行 (Categorize & Execute)
*   **如果它是一個「概念」:** $\rightarrow$ **轉化為 `wiki/` 文件並建構連結。**（將知識原子化）
*   **如果它是一個「任務」:** $\rightarrow$ **定義成具體步驟，寫入 `Registry/` 的工作流程表單。**（讓系統監控負責追蹤進度）
*   **如果它是純粹的「參考資料」:** $\rightarrow$ **歸檔到 `outputs/` 供審閱。**

## ⚠️ 實施原則與陷阱 (Adherence Rules & Pitfalls)
1.  **反切換成本：** 切記，流程優化的目標是減少思維跳轉的摩擦力，永遠不要在接收訊息時停止當前的任務進行分類。
2.  **最小化決策:** 剛收到資訊時，只需完成 Step 1 的「丟入」，將判斷延遲到專門的審核時間點（Step 2）。

---
*此協議文件應作為所有團隊成員和 AI Agent 的預設流程參考。每次處理新素材後，都必須自我檢查：我是否遵循了 Inbox Protocol？*