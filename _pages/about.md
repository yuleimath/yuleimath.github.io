---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 淡入上浮动画 */
  .fade-up {
    animation: fadeInUp 0.8s ease-out forwards;
    opacity: 0;
  }
  @keyframes fadeInUp {
    from {
      opacity: 0;
      transform: translateY(20px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  /* 可选：为列表项添加交错淡入效果 */
  .papers-list li {
    opacity: 0;
    animation: fadeInUp 0.5s ease forwards;
    animation-delay: calc(0.1s * var(--order));
    list-style-type: none;
    margin: 8px 0;
  }
  .papers-list li:nth-child(1) { --order: 1; }
  .papers-list li:nth-child(2) { --order: 2; }
  .papers-list li:nth-child(3) { --order: 3; }
  /* 根据实际论文数量添加更多 */
</style>

<div class="fade-up">
  ## About me
  🔬 I'm currently a PhD student at **Northwest University**, majoring in Pure Mathematics. My advisor is Prof. Zhisu Li.
</div>

<div class="fade-up">
  ## Research Interests
  My research focuses on elliptic partial differential equations, geometric analysis.
</div>

<div>
  ## Preprints and Publications
  <ul class="papers-list">
    <li><strong>[2025]</strong> Title of Paper One. <em>arXiv:xxxx.xxxxx</em>. [<a href="#">PDF</a>]</li>
    <li><strong>[2024]</strong> Title of Paper Two. <em>Journal Name</em>. [<a href="#">DOI</a>]</li>
    <li><strong>[2023]</strong> Title of Paper Three. <em>Conference Proceedings</em>.</li>
  </ul>
</div>
