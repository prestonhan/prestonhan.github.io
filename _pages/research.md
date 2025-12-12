---
layout: page
title: Research
permalink: /research/
description: Selected research projects
nav: true
nav_order: 3
_styles: |
  .post-description {
    font-size: 1.2rem;
    font-weight: 400;
    margin-top: 0.3rem;
  }
---

<hr class="research-separator">

<div class="research-list">

  <div class="research-item">
    <h3 class="research-title">
        AI Adoption in U.S. Police Departments: Impacts on Enforcement Outcomes and Arrest Disparities
        <span class="research-date">Dec. 2025</span>
    </h3>
    <p class="research-meta">
        <strong>Seungwoo Han</strong> and Wonseok Oh<br>
        <em>International Conference on Information Systems (ICIS) 2025</em>
    </p>
    <p class="research-links">
        <a href="{{ '/research/icis2025/' | relative_url }}">View abstract</a>
        ·
        <a href="https://aisel.aisnet.org/icis2025/public_is/public_is/4/" target="_blank" rel="noopener">
        ICIS 2025 paper
        </a>
    </p>
    <ul class="research-points">
        <li>Analyzed panel data from U.S. municipal police departments using fixed effects regression methods.</li>
        <li>Distinguished between analytical AI tools and surveillance technologies to measure differential effects on enforcement outcomes and racial disparities.</li>
        <li>Found that analytical AI reduces total arrests while surveillance AI exacerbates racial disparities in specific organizational contexts.</li>
    </ul>
  </div>

  <hr class="research-separator">

  <div class="research-item">
    <h3 class="research-title">
      Multimodal Analysis in E-commerce Reviews: The Impact of Customer Generated and Firm Generated Images on Post Purchase Satisfaction
      <span class="research-date">Oct. 2024</span>
    </h3>
    <p class="research-meta">
      <strong>Seungwoo Han</strong> and Jeongsik Oh<br>
      <em>Conference on Information Systems and Technology (CIST) 2024</em>
    </p>
    <p class="research-links">
        <a href="{{ '/research/cist2024/' | relative_url }}">View abstract</a>
    </p>
    <ul class="research-points">
      <li>Analyzed Amazon review data using deep learning models and natural language processing techniques for multimodal content analysis.</li>
      <li>Implemented the difference in differences methodology to establish the causal effects of image text similarity on consumer satisfaction.</li>
      <li>Revealed a paradoxical finding that high similarity between customer and firm generated content increases ratings and helpful votes while decreasing sentiment scores.</li>
    </ul>
  </div>

</div>

<style>
  .research-links {
    margin-top: 0.3rem;
    font-size: 0.95rem;
  }

  .research-links a {
    text-decoration: none;
  }

  .research-links a:hover {
    text-decoration: underline;
  }

  .research-list {
    margin-top: 1.5rem;
  }

  .research-item {
    margin-bottom: 1.5rem;
  }

  .research-title {
    font-size: 1.15rem;
    font-weight: 600;
    margin-bottom: 0.2rem;
  }

  .research-date {
    font-size: 0.95rem;
    font-weight: 400;
    color: var(--global-muted-color);
    margin-left: 0.4rem;
  }

  .research-meta {
    margin: 0.1rem 0 0.5rem 0;
    font-size: 0.98rem;
    color: var(--global-muted-color);
  }

  .research-points {
    margin-top: 0.3rem;
    margin-bottom: 0;
  }

  .research-points li {
    margin-bottom: 0.15rem;
  }

  .research-separator {
    margin: 1.2rem 0;
  }
</style>
