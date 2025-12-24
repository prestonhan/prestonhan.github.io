---
layout: page
title: Experience
permalink: /experience/
description:
nav: true
nav_order: 4
_styles: |
  .exp-card {
    border: none;
    border-radius: 1rem;
    box-shadow: 0 8px 18px rgba(0,0,0,0.06);
    transition: transform 0.15s ease, box-shadow 0.15s ease;
  }
  .exp-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 12px 24px rgba(0,0,0,0.09);
  }
  .exp-img {
    border-top-left-radius: 1rem;
    border-top-right-radius: 1rem;
    object-fit: cover;
    height: 230px;
    width: 100%;
  }
  .exp-title {
    font-size: 1.15rem;
    font-weight: 600;
    margin-bottom: 0.2rem;
  }
  .exp-meta {
    font-size: 0.9rem;
    color: var(--global-muted-color);
    margin-bottom: 0.4rem;
  }
  .exp-tags span {
    display: inline-block;
    font-size: 0.8rem;
    color: var(--global-muted-color);
    margin-right: 0.35rem;
  }
  .exp-btn {
    font-size: 0.85rem;
    padding: 0.3rem 0.8rem;
    border-radius: 999px;
  }
  .text-center p {
  font-size: 1.1rem;
  font-weight: 400;
  }
---

<div class="text-center mb-4">
  <p>We are shaped by our experiences.</p>
</div>

<div class="row row-cols-1 row-cols-md-3 g-4">

  <!-- ICIS 2025 presentation -->
<!-- ICIS 2025 presentation -->
 <div class="col">
  <div class="card exp-card h-100">
    <img
    src="{{ '/assets/img/experience/ICIS_2025_presentation.png' | relative_url }}"
    alt="ICIS 2025 presentation"
    class="exp-img"
    >
    <div class="card-body">
     <div class="exp-title">ICIS 2025 Presentation</div>
     <div class="exp-meta">Nashville, TN · 2025 · Presenter</div>
     <div class="exp-tags">
        <span>#AI_adoption</span>
        <span>#police_technology</span>
        <span>#algorithmic_bias</span>
        <span>#ICIS_2025</span>
     </div>
    </div>
    <div class="card-footer bg-white border-0">
      <a
        href="{{ '/research/icis2025/' | relative_url }}"
        class="btn btn-outline-dark exp-btn"
      >
        View Abstract
      </a>
    </div>
  </div>
 </div>

  <!-- CIST 2024 presentation -->
  <div class="col">
    <div class="card exp-card h-100">
      <img
        src="{{ '/assets/img/experience/CIST_2024_presentation.png' | relative_url }}"
        alt="CIST 2024 presentation"
        class="exp-img"
      >
      <div class="card-body">
        <div class="exp-title">CIST 2024 Presentation</div>
        <div class="exp-meta">Seattle, WA · 2024 · Presenter</div>
        <div class="exp-tags">
          <span>#Multimodal_analysis</span>
          <span>#e_commerce_reviews</span>
          <span>#CIST_2024</span>
        </div>
      </div>
      <div class="card-footer bg-white border-0">
        <a
          href="{{ '/research/cist2024/' | relative_url }}"
          class="btn btn-outline-dark exp-btn"
        >
          View Abstract
        </a>
      </div>
    </div>
  </div>

  <!-- Intel ISEF 2015 -->
  <div class="col">
    <div class="card exp-card h-100">
      <img
        src="{{ '/assets/img/experience/ISEF_2015.png' | relative_url }}"
        alt="Intel ISEF 2015 presentation"
        class="exp-img"
      >
      <div class="card-body">
        <div class="exp-title">Intel ISEF 2015 Presentation</div>
        <div class="exp-meta">Pittsburgh, PA · 2015 · Finalist</div>
        <div class="exp-tags">
          <span>#mountain_safety</span>
          <span>#heart_rate_algorithm</span>
          <span>#early_research_experience</span>
          <span>#Intel_ISEF</span>
        </div>
      </div>
    </div>
  </div>

  <!-- Providence Spring Elementary School -->
  <div class="col">
    <div class="card exp-card h-100">
      <img
        src="{{ '/assets/img/experience/PSE.png' | relative_url }}"
        alt="Last day in Providence Spring Elementary School"
        class="exp-img"
      >
      <div class="card-body">
        <div class="exp-title">Last Day in PSE</div>
        <div class="exp-meta">
          Providence Spring Elementary School · Charlotte, NC · <span class="exp-year">2010</span>
        </div>
        <div class="exp-tags">
          <span>#elementary_school_memory</span>
          <span>#signing_in_Korean</span>
          <span>#friends</span>
        </div>
      </div>
    </div>
  </div>

</div>
