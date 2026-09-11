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
  .journal-covers {
    display: flex;
    flex-wrap: wrap;
    gap: 1.2rem;
    justify-content: center;
    align-items: flex-end;
    margin: 0.8rem 0 1.8rem 0;
    padding: 1rem 0.6rem;
    border-top: 1px solid var(--global-divider-color);
    border-bottom: 1px solid var(--global-divider-color);
  }
  .journal-covers a {
    text-align: center;
    text-decoration: none !important;
    color: var(--global-text-color-light);
    font-size: 0.75rem;
    line-height: 1.2;
    transition: transform 0.15s ease;
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 110px;
  }
  .journal-covers a:hover {
    transform: translateY(-3px);
    color: var(--global-theme-color);
  }
  .journal-covers img {
    height: 130px;
    width: auto;
    max-width: 100%;
    object-fit: contain;
    box-shadow: 0 3px 10px rgba(0,0,0,0.15);
    border-radius: 3px;
    margin-bottom: 0.4rem;
  }
  .journal-covers .jc-name {
    font-weight: 600;
    color: var(--global-text-color);
  }
  .journal-covers .jc-count {
    margin-top: 0.2rem;
    font-size: 0.7rem;
    color: var(--global-text-color-light);
  }
  .journal-covers .jc-count strong {
    color: var(--global-theme-color);
    font-weight: 700;
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

<!--
  Journal paper counts. jekyll-scholar's query DSL does not reliably filter
  on values containing spaces, so these are hardcoded. Update when a new
  paper is added to one of these journals in _bibliography/papers.bib.
-->
{% assign jmd_count = 1 %}
{% assign eaai_count = 2 %}
{% assign advei_count = 1 %}

<div class="journal-covers" aria-label="Journals where my papers have appeared">
  <a href="https://asmedigitalcollection.asme.org/mechanicaldesign" target="_blank" rel="noopener" title="Journal of Mechanical Design">
    <img src="{{ '/assets/img/journal_covers/jmd.png' | relative_url }}" alt="Journal of Mechanical Design cover">
    <span class="jc-name">JMD</span>
    <span class="jc-count"><strong>{{ jmd_count }}</strong> paper{% if jmd_count != 1 %}s{% endif %}</span>
  </a>
  <a href="https://www.sciencedirect.com/journal/engineering-applications-of-artificial-intelligence" target="_blank" rel="noopener" title="Engineering Applications of Artificial Intelligence">
    <img src="{{ '/assets/img/journal_covers/eaai.jpg' | relative_url }}" alt="Engineering Applications of Artificial Intelligence cover">
    <span class="jc-name">EAAI</span>
    <span class="jc-count"><strong>{{ eaai_count }}</strong> paper{% if eaai_count != 1 %}s{% endif %}</span>
  </a>
  <a href="https://www.sciencedirect.com/journal/advanced-engineering-informatics" target="_blank" rel="noopener" title="Advanced Engineering Informatics">
    <img src="{{ '/assets/img/journal_covers/advei.jpg' | relative_url }}" alt="Advanced Engineering Informatics cover">
    <span class="jc-name">AdvEI</span>
    <span class="jc-count"><strong>{{ advei_count }}</strong> paper{% if advei_count != 1 %}s{% endif %}</span>
  </a>
</div>

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

