---
title: 資安法規與標準知識庫
summary: 從法律義務、候選標準到產業測試規格，建立可追溯的產品資安閱讀路徑。
source_type: official-guidance
status: published
version: "1.0"
last_verified: 2026-11-16
tags:
  - product-security
  - compliance
---

<section class="hero">
  <p class="eyebrow">PRODUCT CYBERSECURITY KNOWLEDGE BASE</p>
  <h1>先分清文件的角色，再談產品資安合規</h1>
  <p class="hero-lead">本站以官方來源整理歐盟《Cyber Resilience Act》、產品資安標準與 O-RAN 安全測試規格，協助讀者辨識「法律要求什麼、標準如何支援、測試證據如何準備」。</p>
  <div class="hero-actions">
    <a class="button-primary" href="cra/">從 CRA 開始</a>
    <a class="button-secondary" href="methodology/source-levels/">查看來源分級</a>
  </div>
</section>

<div class="notice-bar" role="note">
  <strong>內容定位：</strong>學習與研究用摘要，不取代正式法規、標準原文、驗證機構意見或法律意見。所有狀態以頁面標示的查證日期為準。
</div>

## 三種文件，三種角色

<div class="card-grid">
  <article class="topic-card">
    <span class="status status-law">已生效法規</span>
    <h3>Cyber Resilience Act</h3>
    <p>從產品範圍、經濟營運者義務與適用時程理解法律層級的要求。</p>
    <a href="cra/">查看 CRA 制度概覽 →</a>
  </article>
  <article class="topic-card">
    <span class="status status-review">核准階段</span>
    <h3>ETSI EN 304 627</h3>
    <p>聚焦路由器、連網數據機與交換器的產品資安要求；目前狀態不可寫成已發布調和標準。</p>
    <a href="standards/en-304-627/">查看標準狀態 →</a>
  </article>
  <article class="topic-card">
    <span class="status status-spec">產業規格</span>
    <h3>O-RAN 安全測試</h3>
    <p>以測試分類與證據思維理解 O-RAN 安全驗證，不把產業規格直接等同於法律義務。</p>
    <a href="oran/">查看規格定位 →</a>
  </article>
</div>

## 目前重要時程

<div class="timeline" aria-label="CRA 重要時程">
  <div class="timeline-item">
    <div class="timeline-date">2024-12-10</div>
    <div><strong>CRA 生效</strong><br>Regulation (EU) 2024/2847 進入生效狀態。</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2026-09-11</div>
    <div><strong>通報義務開始適用</strong><br>與遭主動利用漏洞及嚴重事件相關的部分通報義務先行適用。</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2027-12-11</div>
    <div><strong>CRA 主要條文全面適用</strong><br>產品與經濟營運者須依正式條文確認自身義務及例外。</div>
  </div>
</div>

日期依 [EUR-Lex 的 Regulation (EU) 2024/2847](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32024R2847) Article 71 整理，查證日期為 2026-11-16。

## 建議閱讀路徑

1. 先讀 [CRA 適用範圍](cra/scope.md)，確認產品是否可能屬於 products with digital elements。
2. 再讀 [製造商義務](cra/manufacturer-obligations.md)，區分產品要求、漏洞處理與通報時程。
3. 查看 [EN 304 627](standards/en-304-627/index.md) 或 [O-RAN 安全測試](oran/security-testing-overview.md)，理解標準與測試證據能支援的部分。
4. 最後回到 [來源分級](methodology/source-levels.md)，確認每項結論的證據層級與限制。

## 本站查證方式

本站以 [EUR-Lex](https://eur-lex.europa.eu/)、[European Commission](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)、[ETSI Work Programme](https://portal.etsi.org/webapp/workProgram/Report_WorkItem.asp?wki_id=74416) 與 [O-RAN ALLIANCE](https://www.o-ran.org/technical-groups/wg11) 等第一手來源為主。文件狀態、版本與日期可能改變，使用前請核對原文。
