---
title: Interesting Work
date: 2026-05-12 00:00:00
aside: false
top_img: false
comments: false
---

<!-- Interesting Work 页面总容器：用于展示未来技术探索、阅读方向和准备做的项目。 -->
<div class="portfolio-shell">
  <!-- 页面 Hero 模块：解释该页面不是愿望清单，而是技术雷达和行动计划。 -->
  <section class="pf-hero pf-hero-compact">
    <div class="pf-hero-main">
      <p class="pf-eyebrow">Future Lab / Technical Radar</p>
      <h1>Interesting Work</h1>
      <p class="pf-lead">
        这里不写空泛愿望，专门放感兴趣、准备实践、正在阅读或计划做成项目的技术方向。它可以弥补成果还在积累阶段时的内容密度。
      </p>
    </div>
  </section>

  <!-- 技术兴趣卡片模块：把感兴趣的方向拆成 Planned、Prototype、Reading 等可执行状态。 -->
  <section class="pf-section">
    <div class="pf-section-head">
      <p class="pf-eyebrow">Radar</p>
      <h2>Technical Interests</h2>
    </div>
    <div class="pf-grid pf-grid-3">
      <article class="pf-card">
        <div class="pf-card-top">
          <span class="pf-tag">Planned</span>
          <span class="pf-muted">Agent</span>
        </div>
        <h3>Tool-Using Agent</h3>
        <p>设计一个能调用搜索、文件、数据库或业务 API 的 Agent demo，重点验证工具选择、失败恢复和执行轨迹。</p>
      </article>
      <article class="pf-card">
        <div class="pf-card-top">
          <span class="pf-tag">Prototype</span>
          <span class="pf-muted">Backend</span>
        </div>
        <h3>LLM Backend Service</h3>
        <p>把 LLM 能力接入 Java 后端服务，关注鉴权、限流、日志、异步任务、成本控制和错误处理。</p>
      </article>
      <article class="pf-card">
        <div class="pf-card-top">
          <span class="pf-tag">Reading</span>
          <span class="pf-muted">Eval</span>
        </div>
        <h3>Agent Evaluation</h3>
        <p>整理 Agent 评测方法：任务成功率、工具调用准确性、上下文污染、长任务稳定性和人工回放。</p>
      </article>
    </div>
  </section>

  <!-- 构建路线图模块：用时间线展示后续如何把兴趣方向转化成可展示项目。 -->
  <section class="pf-section">
    <div class="pf-section-head">
      <p class="pf-eyebrow">Timeline</p>
      <h2>Build Roadmap</h2>
    </div>
    <div class="pf-timeline pf-timeline-wide">
      <div><span>Step 1</span><p>整理已有项目材料，先补齐 Projects 页面中的 3 个真实项目。</p></div>
      <div><span>Step 2</span><p>做一个最小可运行的 Agent demo，支持工具调用和执行日志展示。</p></div>
      <div><span>Step 3</span><p>把 Java 后端能力和 LLM workflow 连接起来，形成一个可讲解的完整 case。</p></div>
      <div><span>Step 4</span><p>将过程写成 Blog，形成面试时可以追问的技术证据链。</p></div>
    </div>
  </section>

  <!-- 可折叠说明模块：说明该页面后续可以补充的内容类型，避免正文过长影响首屏清晰度。 -->
  <section class="pf-section">
    <details class="pf-details">
      <summary>展开：这个页面后续可以放什么</summary>
      <div class="pf-details-body">
        <p>可以放阅读清单、正在做的 demo、暂时没有完全完成但有阶段性结果的项目、感兴趣的开源项目、技术雷达和学习路线。</p>
        <p>不建议放没有行动计划的口号，也不要把技术名词堆成技能墙。</p>
      </div>
    </details>
  </section>
</div>
