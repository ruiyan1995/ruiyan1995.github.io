---
permalink: /team/
title: "Team"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}



<img src="{{ '/images/logo.svg' | relative_url }}" alt="">



<p style="text-align: justify;font-family: Roboto;">

EMC@IMAG is a group of the <a href="https://imag-njust.net/">Intelligent Media Analysis Group (IMAG)</a> built by the chief leader of Prof. <a href="https://v2.imag-njust.net/people/user/tangjinhui/">Jinhui Tang</a>.  Our team members are as follows.

</p>

<span class='anchor' id='team'></span>

<style>
  table {
    border-collapse: collapse;
  }
  table, th, td {
    border-color: transparent;
  }

  .row > .col {
    margin-bottom: 1rem; /* 或 24px / 2rem 自行调 */
  }

  .card-body {
    padding:0.75rem 1rem;
    margin-bottom: 0rem;
    padding-bottom: 0rem;
  }

  .card-img {
    width: 130px;
    height:180px;
    border-radius: 8px;
    object-fit: cover;
    margin-bottom: -1.2rem;
  }

  .card-title {
      font-size: 1.2rem;
      font-weight: 600;
      margin-bottom: 0.25rem;
  }

  .card-body p {
      font-size: 0.8rem;
  }

  .card-footer {
      background: none;
      border-top: none;
      padding-bottom: 1rem;
      padding-left: 1rem;
      font-size: 1.4rem;  /* 默认大约是 1rem，调大即可 */
      margin-right: 0.5rem;
      padding-top: 0.2rem;
      color: #333;
      transition: transform 0.2s;
  }

  .card-footer i:hover {
      transform: scale(1.2);
      color: var(--lv-orange); 
  }

  .custom-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 0rem;
  }

  /* 左侧头像区域 padding 调整 */
  .custom-card .author-avater {
      margin-right: 20px;
  }

  /* 整体卡片上下 padding 调整 */
  .custom-card {
      padding: 24px 28px;
      flex-wrap: wrap;
      align-items: center; 
  }

  .custom-card .right span {
      font-size: 0.85rem;
      color: #888;
      display: block;
      margin-bottom: 2px;
  }

  .custom-card .right h5 {
      font-size: 1.15rem;
      font-weight: 600;
      color: #d80000; 
      margin-bottom: 6px;
  }

  .custom-card .right p {
      font-size: 0.9rem;
      color: #666;
      margin-bottom: 0;
      line-height: 1.5;
  }

  .custom-card .intro-text {
      font-size: 0.95rem;
      color: #444;
      line-height: 1.7;
      padding-left: 16px;
      border-left: 1px solid #eee;
  }

  /* .justify-text {
      text-align: justify;
      line-height: 1.8;
      font-size: 0.95rem;
      color: #444;
      padding-left: 1rem;
      border-left: 1px solid #eee;
      hyphens: auto;
      word-break: break-word;
      text-indent: 2em;
  }

  .right-wrapper{
      min-width:0;         
  }

  .social-icons {
      display: flex;
      gap: 12px;
      margin-top: 8px;
  }

  .social-icons a {
      color: #777;
      font-size: 18px;
      transition: color 0.2s ease;
  }

  .social-icons a:hover {
      color: #ee7023;  /* 橙色 hover 效果，可改为品牌色 */
  /* } */

  @media (max-width: 768px) {
      .custom-card {
          flex-direction: column !important;
          align-items: flex-start !important;
      }

      .custom-card > div {
          width: 100% !important;
          padding-right: 0 !important;
          margin-bottom: 1rem;
      }

      .custom-card img {
          width: 100% !important;
          height: auto !important;
          max-width: 240px;
          margin-bottom: 1rem;
      }

      .right-wrapper {
          padding-left: 0 !important;
          border-left: none !important;
      } */
  }
</style>

# <font color="#2B6ADD"> Current Member </font>

<div class="row custom-grid">
  <!-- 第一个成员 -->
  <div class="col-md-4">
    <div class="card d-flex flex-column h-100 text-center">
      <div class="card-body">
        <h6 class="card-title mb-0">Hongyu Qu</h6>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidates</p>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Embodied Intelligence</p>
        <p class="mb-neg-2">2024.9 ~ Present</p>
      </div>
    </div> 
  </div>

  <!-- 第二个成员 -->
  <div class="col-md-4">
    <div class="card d-flex flex-column h-100 text-center">
      <div class="card-body">
        <h6 class="card-title mb-0">Xing Ling</h6>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidates</p>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">vision-centric mllm</p>
        <p class="mb-neg-2">2024.9 ~ Present</p>
      </div>
    </div> 
  </div>

  <!-- 第三个成员 -->
  <div class="col-md-4">
    <div class="card d-flex flex-column h-100 text-center">
      <div class="card-body">
        <h6 class="card-title mb-0">Yanzheng Qian</h6>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidates</p>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">VLA</p>
        <p class="mb-neg-2">2025.11 ~ Present</p>
      </div>
    </div> 
  </div>

  <!-- 第四个成员 -->
  <div class="col-md-4">
    <div class="card d-flex flex-column h-100 text-center">
      <div class="card-body">
        <h6 class="card-title mb-0">Weida Wu</h6>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidates</p>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">VLA</p>
        <p class="mb-neg-2">coming soon</p>
      </div>
    </div> 
  </div>

  <!-- 第五个成员 -->
  <div class="col-md-4">
    <div class="card d-flex flex-column h-100 text-center">
      <div class="card-body">
        <h6 class="card-title mb-0">Wenxuan Ge</h6>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidates</p>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">test-time adaptation</p>
        <p class="mb-neg-2">2024.9 ~ Present</p>
      </div>
    </div> 
  </div>

  <!-- 第六个成员 -->
  <div class="col-md-4">
    <div class="card d-flex flex-column h-100 text-center">
      <div class="card-body">
        <h6 class="card-title mb-0">Chufan Yi</h6>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidates</p>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">video temporal grounding</p>
        <p class="mb-neg-2">2024.9 ~ Present</p>
      </div>
    </div> 
  </div>

  <!-- 第七个成员 -->
  <div class="col-md-4">
    <div class="card d-flex flex-column h-100 text-center">
      <div class="card-body">
        <h6 class="card-title mb-0">Weihao Xu</h6>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidates</p>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Video editing</p>
        <p class="mb-neg-2">2024.9 ~ Present</p>
      </div>
    </div> 
  </div>

  <!-- 第八个成员 -->
  <div class="col-md-4">
    <div class="card d-flex flex-column h-100 text-center">
      <div class="card-body">
        <h6 class="card-title mb-0">Li Bo</h6>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidates</p>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Synthetic robot data in VLA </p>
        <p class="mb-neg-2">2025.9 ~ Present</p>
      </div>
    </div> 
  </div>

  <!-- 第九个成员 -->
  <div class="col-md-4">
    <div class="card d-flex flex-column h-100 text-center">
      <div class="card-body">
        <h6 class="card-title mb-0"> Liu Yang</h6>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidates</p>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Inference acceleration</p>
        <p class="mb-neg-2">2025.9 ~ Present</p>
      </div>
    </div> 
  </div>

  <!-- 第十个成员 -->
  <div class="col-md-4">
    <div class="card d-flex flex-column h-100 text-center">
      <div class="card-body">
        <h6 class="card-title mb-0">Wenhao Zhuang</h6>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidates</p>
        <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Event-Based Vision</p>
        <p class="mb-neg-2">2025.9 ~ Present</p>
      </div>
    </div> 
  </div>
</div>
