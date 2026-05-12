---
title: Project
date: 2026-05-12 00:00:00
aside: false
top_img: false
comments: false
---

<!-- Project 页面总容器：集中展示 Agent、Java 后端和学校协作项目。 -->
<div class="portfolio-shell">
  <!-- 项目页 Hero 模块：说明项目页的组织原则，强调用 case study 方式展示项目。 -->
  <section class="pf-hero pf-hero-compact">
    <div class="pf-hero-main">
      <p class="pf-eyebrow">Project / Case Study</p>
      <h1>Projects</h1>
      <p class="pf-lead">
        项目页按岗位相关度组织：Agent 项目、Java 后端项目、学校横向项目。每个项目后续用问题、方案、职责、结果来写，不堆功能列表。
      </p>
    </div>
  </section>

  <!-- 项目页锚点导航：点击后快速跳转到不同项目分类，提供轻量交互。 -->
  <nav class="pf-filter-bar">
    <a href="#agent-and-java">Agent / Java</a>
    <a href="#school-collaboration">School Projects</a>
    <a href="#case-template">Case Template</a>
  </nav>

  <!-- Agent 与 Java 项目模块：后续放最适合求职展示的个人项目或工程项目。 -->
  <section class="pf-section" id="agent-and-java">
    <div class="pf-section-head">
      <p class="pf-eyebrow">Work 01</p>
      <h2>Agent & Java Projects</h2>
    </div>
    <div class="pf-grid pf-grid-2">
      <article class="pf-card pf-project-card">
        <div class="pf-card-top">
          <span class="pf-tag">Agent</span>
          <span class="pf-muted">To Fill</span>
        </div>
        <h3>Agent Workflow Project</h3>
        <p>放入一个 Agent 项目：例如工具调用、RAG、任务分解、多轮对话或评测系统。重点写清楚架构、工具链、边界条件和结果。</p>
        <div class="pf-stack">
          <span>LLM</span><span>Tool Use</span><span>Workflow</span><span>Eval</span>
        </div>
      </article>
      <article class="pf-card pf-project-card">
        <div class="pf-card-top">
          <span class="pf-tag">Java</span>
          <span class="pf-muted">To Fill</span>
        </div>
        <h3>Java Backend Project</h3>
        <p>放入一个 Java 后端项目：例如接口服务、权限系统、业务模块、异步任务、数据库设计或部署实践。</p>
        <div class="pf-stack">
          <span>Java</span><span>Spring Boot</span><span>MySQL</span><span>Redis</span>
        </div>
      </article>
    </div>
  </section>

  <!-- 学校协作项目模块：用于展示老师横向项目或团队项目中可公开的职责和工程贡献。 -->
  <section class="pf-section" id="school-collaboration">
    <div class="pf-section-head">
      <p class="pf-eyebrow">Work 02</p>
      <h2>School Collaboration Projects</h2>
    </div>
    <div class="pf-grid pf-grid-2">
      <article class="pf-card pf-project-card">
        <div class="pf-card-top">
          <span class="pf-tag">Collaboration</span>
          <span class="pf-muted">Protected</span>
        </div>
        <h3>Horizontal Project Slot</h3>
        <p>学校老师横向项目如果涉及不公开信息，只写角色、模块、技术栈和工程贡献，不写客户、金额、敏感数据。</p>
        <div class="pf-stack">
          <span>Backend</span><span>Data</span><span>Deployment</span><span>Teamwork</span>
        </div>
      </article>
      <article class="pf-card pf-project-card">
        <div class="pf-card-top">
          <span class="pf-tag">Engineering</span>
          <span class="pf-muted">To Fill</span>
        </div>
        <h3>System Module Slot</h3>
        <p>这里可以写你负责过的系统模块：接口、数据处理、模型服务接入、日志监控、部署脚本或性能优化。</p>
        <div class="pf-stack">
          <span>API</span><span>Linux</span><span>Service</span><span>Ops</span>
        </div>
      </article>
    </div>
  </section>

  <!-- 项目写作模板模块：给后续填充项目内容时使用，保证每个项目都讲清楚问题、方案、职责和结果。 -->
  <section class="pf-section" id="case-template">
    <div class="pf-section-head">
      <p class="pf-eyebrow">Writing Standard</p>
      <h2>Project Case Template</h2>
    </div>
    <details class="pf-details" open>
      <summary>每个项目建议按这个结构补内容</summary>
      <div class="pf-details-body">
        <p><strong>Problem:</strong> 项目要解决什么问题，为什么需要做。</p>
        <p><strong>Solution:</strong> 你的系统设计、模块划分、关键技术选择。</p>
        <p><strong>My Role:</strong> 你负责的接口、模块、Agent workflow、数据处理或部署工作。</p>
        <p><strong>Result:</strong> 可以验证的结果，例如功能上线、响应时间、稳定性、准确率、用户反馈或代码链接。</p>
      </div>
    </details>
  </section>
</div>
