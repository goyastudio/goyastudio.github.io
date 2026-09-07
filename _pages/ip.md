---
layout: page
permalink: /ip/
title: ip
description: Patents and other intellectual property.
nav: true
nav_order: 2
_styles: >
  .pub-section {
    margin-bottom: 2.5rem;
  }
  .pub-section h2 {
    font-size: 1.3rem;
    font-weight: 600;
    color: var(--global-theme-color);
    border-bottom: 2px solid var(--global-theme-color);
    padding-bottom: 0.4rem;
    margin-bottom: 1rem;
  }
  .pub-section ol.bibliography {
    counter-reset: none !important;
    list-style: none !important;
    padding-left: 0 !important;
  }
  .pub-section ol.bibliography li {
    padding-left: 0 !important;
    list-style: none !important;
    border-bottom: 1px solid var(--global-divider-color);
    padding-bottom: 1rem;
    margin-bottom: 1rem;
  }
  .pub-section ol.bibliography li:last-child {
    border-bottom: none;
  }
  .pub-section ol.bibliography li::before,
  .pub-section ol.bibliography li::marker {
    display: none !important;
    content: none !important;
  }
  .pub-empty {
    color: var(--global-text-color-light);
    font-style: italic;
    font-size: 0.9rem;
  }
---

<!-- _pages/ip.md -->

{% include bib_search.liquid %}

<div class="pub-section">
<h2>Patents</h2>
{% bibliography --query @*[pubtype=patent]* %}
</div>
