---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 强制动画优先级，确保不被主题覆盖 */
  .fade-up {
    animation: fadeInUp 0.8s ease-out forwards !important;
    opacity: 0 !important;
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
</style>

<div class="fade-up">
  <h2>About me</h2>
  <p>🔬 I'm currently a PhD student at <strong>Northwest University</strong>, majoring in Pure Mathematics. My advisor is Prof. Zhisu Li.</p>
</div>

<div class="fade-up">
  <h2>Research Interests</h2>
  <p>My research focuses on elliptic partial differential equations, geometric analysis.</p>
</div>

<div>
  <h2>Preprints and Publications</h2>
  <ul class="papers-list">
    <li><strong>[2025]</strong> Title of Paper One. <em>arXiv:xxxx.xxxxx</em>. [<a href="#">PDF</a>]</li>
    <li><strong>[2024]</strong> Title of Paper Two. <em>Journal Name</em>. [<a href="#">DOI</a>]</li>
    <li><strong>[2023]</strong> Title of Paper Three. <em>Conference Proceedings</em>.</li>
  </ul>
</div>
