---
layout: page
permalink: /publications/
title: publications
description: Asterisks (*) denote equal contributions.
nav: true
nav_order: 1
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

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

<div class="pub-section">
<h2>International Journal</h2>
{% bibliography --query @*[pubtype=intl_journal]* %}
</div>

<div class="pub-section">
<h2>International Conference</h2>
{% bibliography --query @*[pubtype=intl_conf]* %}
</div>

<div class="pub-section">
<h2>Domestic Journal</h2>
{% bibliography --query @*[pubtype=domestic_journal]* %}
</div>

<div class="pub-section">
<h2>Domestic Conference</h2>
{% bibliography --query @*[pubtype=domestic_conf]* %}
</div>

