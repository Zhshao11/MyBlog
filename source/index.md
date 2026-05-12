---
title: Home
date: 2026-05-12 00:00:00
aside: false
top_img: false
comments: false
---

<!-- 首页总容器：集中承载主页的 Hero、功能入口、项目预览、博客预览和路线图模块。 -->
<div class="portfolio-shell">
  <!-- Hero 模块：进入主页后第一眼看到的定位信息和主要行动按钮，模仿 Magic Portfolio 的清晰首屏。 -->
  <section class="pf-hero">
    <div class="pf-hero-main">
      <p class="pf-eyebrow">Portfolio / Blog / Future Lab</p>
      <h1>Backend & Agent Developer</h1>
      <p class="pf-lead">
        这里是主页总览：用一个清晰入口展示学习日常、Agent 与 Java 项目、学校协作项目，以及后续想投入的技术方向。
      </p>
      <div class="pf-actions">
        <a class="pf-button pf-button-primary" href="/projects/">View Projects</a>
        <a class="pf-button" href="/blog/">Read Blog</a>
        <a class="pf-button" href="https://github.com/Zhshao11" target="_blank" rel="noopener">GitHub</a>
      </div>
    </div>
    <!-- 主页右侧信息面板：用编号列表快速解释网站的四类核心内容，避免首页像普通博客列表。 -->
    <div class="pf-hero-panel">
      <span class="pf-status">Now Organizing</span>
      <h2>Site Map</h2>
      <ul class="pf-clean-list">
        <li><span>01</span> Learning notes and blog records</li>
        <li><span>02</span> Agent and Java project cases</li>
        <li><span>03</span> School collaboration projects</li>
        <li><span>04</span> Future technical explorations</li>
      </ul>
    </div>
  </section>

  <!-- 四个内容入口模块：对应 Blog、Agent/Java Project、School Project、Interesting Work 四个核心功能区。 -->
  <section class="pf-section">
    <div class="pf-section-head">
      <p class="pf-eyebrow">Navigation</p>
      <h2>Four Content Areas</h2>
    </div>
    <div class="pf-grid pf-grid-4">
      <a class="pf-card pf-link-card" href="/blog/">
        <span class="pf-card-index">01</span>
        <h3>Learning Notes</h3>
        <p>学习日常、技术博客、环境配置、Debug 复盘和工具链记录。</p>
      </a>
      <a class="pf-card pf-link-card" href="/projects/#agent-and-java">
        <span class="pf-card-index">02</span>
        <h3>Agent / Java</h3>
        <p>Agent workflow、RAG、工具调用，以及 Java 后端工程实践。</p>
      </a>
      <a class="pf-card pf-link-card" href="/projects/#school-collaboration">
        <span class="pf-card-index">03</span>
        <h3>School Projects</h3>
        <p>学校里参与的老师横向项目、团队协作和可公开的工程贡献。</p>
      </a>
      <a class="pf-card pf-link-card" href="/interesting-work/">
        <span class="pf-card-index">04</span>
        <h3>Interesting Work</h3>
        <p>感兴趣的技术、准备推进的项目、阅读路线和阶段性计划。</p>
      </a>
    </div>
  </section>

  <!-- 方向预览模块：给面试官快速扫一眼当前网站重点关注的项目类型和能力方向。 -->
  <section class="pf-section">
    <div class="pf-section-head">
      <p class="pf-eyebrow">Preview</p>
      <h2>Selected Directions</h2>
    </div>
    <div class="pf-grid pf-grid-3">
      <article class="pf-card">
        <div class="pf-card-top">
          <span class="pf-tag">Agent</span>
          <span class="pf-muted">Building</span>
        </div>
        <h3>Agent Project Cases</h3>
        <p>后续放入工具调用、RAG、任务编排、多轮交互或评测相关项目，用 case study 写清楚问题、架构和结果。</p>
      </article>
      <article class="pf-card">
        <div class="pf-card-top">
          <span class="pf-tag">Java</span>
          <span class="pf-muted">Backend</span>
        </div>
        <h3>Java Backend Projects</h3>
        <p>集中展示 Spring Boot、数据库、缓存、接口设计、部署和工程化能力，不把项目写成简单功能清单。</p>
      </article>
      <article class="pf-card">
        <div class="pf-card-top">
          <span class="pf-tag">School</span>
          <span class="pf-muted">Collaboration</span>
        </div>
        <h3>Horizontal Projects</h3>
        <p>对不方便公开的学校协作项目，只展示职责、技术栈、系统模块和可验证贡献，避免泄露敏感信息。</p>
      </article>
    </div>
  </section>

  <!-- 博客与路线图模块：左侧展示近期笔记入口，右侧展示下一步网站内容补齐计划。 -->
  <section class="pf-section pf-split">
    <div>
      <div class="pf-section-head">
        <p class="pf-eyebrow">Recent Notes</p>
        <h2>Blog Snapshot</h2>
      </div>
      <a class="pf-card pf-link-card" href="/2026/05/09/Ubuntu20-04-GLIBC-2-34-%E7%BD%91%E7%BB%9C%E4%BB%A3%E7%90%86%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90/">
        <span class="pf-tag">Linux</span>
        <h3>Ubuntu20.04 网络代理软件推荐</h3>
        <p>一篇环境配置和工程工具链记录，后续 Blog 会继续沉淀后端与 Agent 开发笔记。</p>
      </a>
    </div>
    <div>
      <div class="pf-section-head">
        <p class="pf-eyebrow">Roadmap</p>
        <h2>Next Updates</h2>
      </div>
      <div class="pf-timeline">
        <div><span>01</span><p>补齐 About 页面中的真实简历信息。</p></div>
        <div><span>02</span><p>把 Agent / Java 项目整理成 3-5 个项目卡片。</p></div>
        <div><span>03</span><p>把未来计划整理成可执行的 Interesting Work 路线图。</p></div>
      </div>
    </div>
  </section>
</div>
