---
layout: page
permalink: /datasets/
title: datasets
description: Public datasets I have built for 3D deep learning and engineering design.
nav: true
nav_order: 4
_styles: >
  .dataset-card {
    border-bottom: 1px solid var(--global-divider-color);
    padding-bottom: 1.5rem;
    margin-bottom: 1.5rem;
  }
  .dataset-card:last-child {
    border-bottom: none;
  }
  .dataset-card h2 {
    font-size: 1.2rem;
    font-weight: 600;
    margin-bottom: 0.3rem;
  }
  .dataset-meta {
    color: var(--global-text-color-light);
    font-size: 0.9rem;
    margin-bottom: 0.8rem;
  }
  .dataset-card ul {
    margin-bottom: 0.8rem;
  }
  .dataset-apps {
    margin-bottom: 0.8rem;
  }
  .dataset-apps .app-label {
    font-weight: 600;
    font-size: 0.9rem;
    margin-right: 0.3rem;
  }
  .dataset-apps .app-tag {
    display: inline-block;
    margin: 0 0.3rem 0.4rem 0;
    padding: 0.1rem 0.55rem;
    border-radius: 999px;
    background-color: var(--global-bg-color);
    border: 1px solid var(--global-divider-color);
    color: var(--global-text-color);
    font-size: 0.8rem;
  }
  .dataset-links a {
    display: inline-block;
    margin-right: 0.5rem;
    margin-bottom: 0.4rem;
    padding: 0.15rem 0.6rem;
    border: 1px solid var(--global-theme-color);
    border-radius: 4px;
    font-size: 0.85rem;
  }
---

<!-- _pages/datasets.md -->

<div class="dataset-card">
  <h2>3D Asset–Object Modeling Image Pair Dataset</h2>
  <div class="dataset-meta">
    3D 에셋-사물 모델링 이미지 쌍 데이터 · AI Hub · Smart Design Lab, KAIST (lead) · 2022
  </div>
  <div class="row mb-3">
    <div class="col-12">
      {% include figure.liquid path="assets/img/aihub_3d_asset_thumb.png" class="img-fluid rounded z-depth-1" alt="RGB, normal, mask, and depth renders of a 3D asset" %}
    </div>
  </div>
  <ul>
    <li><strong>10,000 3D object assets</strong> across 402 classes (66% portable, 34% non-portable)</li>
    <li><strong>960,000 labeled images</strong>: each asset rendered from 24 viewpoints in Unity as RGB, mask, depth, and normal images</li>
    <li>FBX / OBJ / MTL / PNG assets with JSON annotations and camera metadata, about 566 GB in total</li>
  </ul>
  <div class="dataset-apps">
    <span class="app-label">Applications</span>
    <span class="app-tag">Robotics (object recognition &amp; manipulation)</span>
    <span class="app-tag">3D reconstruction</span>
    <span class="app-tag">Novel view synthesis</span>
    <span class="app-tag">Image-to-3D generation</span>
    <span class="app-tag">Depth &amp; normal estimation</span>
    <span class="app-tag">Digital twin &amp; simulation</span>
  </div>
  <div class="dataset-links">
    <a href="https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=71412" target="_blank" rel="noopener">AI Hub</a>
    <a href="{{ '/projects/13_project/' | relative_url }}">project</a>
  </div>
</div>

<div class="dataset-card">
  <h2>DeepJEB: 3D Deep Learning-based Synthetic Jet Engine Bracket Dataset</h2>
  <div class="dataset-meta">
    Journal of Mechanical Design · 2024
  </div>
  <div class="row mb-3">
    <div class="col-12">
      {% include figure.liquid path="assets/img/publication_preview/DeepJEB_abstract.png" class="img-fluid rounded z-depth-1" alt="DeepJEB dataset overview" %}
    </div>
  </div>
  <ul>
    <li>Synthetic 3D jet engine bracket geometries generated with deep generative models and automated simulation pipelines</li>
    <li>Paired structural analysis results for training surrogate models such as GNNs and CNNs</li>
    <li>Models trained on DeepJEB achieved up to a 23% increase in R² and over a 70% reduction in MAPE compared with traditional datasets</li>
  </ul>
  <div class="dataset-apps">
    <span class="app-label">Applications</span>
    <span class="app-tag">Scientific machine learning (SciML)</span>
    <span class="app-tag">Surrogate modeling of structural performance</span>
    <span class="app-tag">Generative design</span>
    <span class="app-tag">Design optimization</span>
    <span class="app-tag">3D geometric deep learning (GNN, CNN)</span>
  </div>
  <div class="dataset-links">
    <a href="https://www.narnia.ai/dataset" target="_blank" rel="noopener">dataset</a>
    <a href="https://arxiv.org/abs/2406.09047" target="_blank" rel="noopener">arXiv</a>
  </div>
</div>
