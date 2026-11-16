---
title: CRA 製造商義務
summary: 將產品安全、漏洞處理、文件與通報義務拆成可追蹤的工作流。
source_type: regulation
status: in-force
version: "EU 2024/2847"
last_verified: 2026-11-16
tags:
  - CRA
  - manufacturer
  - vulnerability-management
---

# CRA 製造商義務

## 適用前提

本頁只整理製造商視角。若組織是進口商、經銷商、授權代表，或因重新貼牌、重大修改而承擔製造商責任，應另外核對各角色條文。

## 四個工作面向

### 產品設計與風險管理

製造商需依產品風險與預期用途處理 CRA Annex I 的基本資安要求。工程上應把要求連到威脅模型、架構控制、驗證結果及未解風險，而不是只建立一份要求清單。

### 漏洞處理與安全更新

漏洞處理包含接收、評估、修補、揭露與安全更新。產品團隊應能說明支援期間、元件與相依套件、漏洞來源、修補決策及對使用者的通知方式。

### 技術文件與符合性程序

技術文件需要支持產品如何滿足適用要求。是否能採自我評估或須由第三方參與，與產品分類、採用的標準及符合性評估模組有關，不能只由產品是否「重要」作直覺判斷。

### 漏洞與事件通報

European Commission 的 CRA 通報說明指出，部分通報義務自 **2026-09-11** 起適用。官方摘要列出遭主動利用漏洞的早期警示、後續通知與最終報告等階段；實際事件必須再依 CRA Article 14 與官方通報平台規則判斷時點及內容。

## 可準備的證據

| 工作面向 | 證據例 |
|---|---|
| 風險評估 | 產品邊界、資產、威脅、控制與殘餘風險紀錄 |
| 安全開發 | 安全需求、設計審查、程式碼與元件檢查、修正紀錄 |
| 測試 | 測試計畫、環境、版本、步驟、原始結果與判定準則 |
| 漏洞處理 | 接收管道、分級準則、修補 SLA、通知與揭露流程 |
| 供應鏈 | SBOM、第三方元件來源、版本、漏洞監控與更新責任 |
| 符合性 | 技術文件、EU declaration of conformity、標示與保存紀錄 |

這些是工程證據類型，不表示只要文件存在就已符合 CRA。證據需能對應實際產品版本、適用要求與執行結果。

## 常見誤解

- **做過滲透測試就足夠：**單次測試不能取代全生命週期的風險管理與漏洞處理。
- **有 SBOM 就完成供應鏈管理：**SBOM 是基礎資料，仍需持續監控、影響分析與修補決策。
- **所有通報都是發現後 24 小時交完整報告：**CRA 採分階段通報；各階段內容與期限應依正式條文及現行官方指引確認。

## 尚待確認事項

特定產品仍需確認產品分類、支援期間、符合性評估路徑、採用標準的現行法律地位，以及通報平台的最新操作規則。

## 參考來源

- [EUR-Lex：Regulation (EU) 2024/2847](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32024R2847)，特別是 Articles 13–14、Annex I 及符合性評估相關條文。
- [European Commission：CRA reporting obligations](https://digital-strategy.ec.europa.eu/en/policies/cra-reporting)
- [European Commission：CRA implementation](https://digital-strategy.ec.europa.eu/en/factpages/cyber-resilience-act-implementation)
