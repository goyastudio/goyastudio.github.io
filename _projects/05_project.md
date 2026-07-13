---
layout: page
title: AI-Driven Design Automation and Vibration Prediction for Test JIGs
description: Deep-learning framework that generates JIG assemblies and predicts vibration performance for product testing setups
img: assets/img/narnia_case_50.png
importance: 5
category: work
related_publications: false
start_date: 2024-06-01
end_date: 2024-12-01
organization: Narnia Labs
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/narnia_case_50.png" title="AI-Driven Design Automation and Vibration Prediction for Test JIGs" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    AI-Driven Design Automation and Vibration Prediction for Test JIGs — Narnia Labs case study (originally: 지그(JIG) 진동 성능 예측 및 최적 형상 제안을 통한 설계 자동화)
</div>

## Project Overview

Developed a deep-learning framework that automates the design of vibration-test JIGs (fixtures used for product vibration testing). A generative model proposes JIG geometries under mounting and space constraints, and a predictive model evaluates their vibration performance directly — replacing the expert-driven, largely manual design loop.

## My Role

**AI Researcher, Narnia Labs**
- Individual contributor on the hands-on implementation of the assembly-generation and vibration-prediction models
- Contributed to integrating the models into the design-engineer-facing software platform

## The Challenge

Traditional JIG design leans heavily on specialist experience and manual iteration:

- **Slow arrival at an optimal shape**: Deriving a JIG geometry that satisfies the required vibration behavior for a given product takes significant time.
- **Poor reuse of prior analyses**: Existing CAE results are hard to reuse effectively, so similar design work is repeatedly redone.
- **Excessive manual design effort**: Reliance on the engineer's intuition and hand-modeling wastes overall engineering resources.

## Technical Approach

Delivered a unified generative + predictive AI pipeline for JIG design:

- **Condition-driven shape generation**: A generative AI trained on prior CAE data proposes per-component JIG geometries that respect mounting conditions and space constraints.
- **Vibration-performance predictor**: A predictive model estimates the vibration response of a newly generated JIG assembly on the fly, without a full CAE run.
- **Dedicated design platform**: The models are integrated into a single software platform so that design engineers can use them directly, without stepping through separate tools.

## Impact

- **Sharp reduction in design man-hours**: AI-assisted shape proposal replaces most of the manual iteration, saving engineering time and effort.
- **Faster vibration-testing setup**: Reliable performance prediction cuts the preparation time required before running the actual vibration test.
- **Validated assembly-generation capability**: Successfully demonstrated a rarely commercialized capability — multi-part assembly generation via AI — reinforcing the foundation of AI-driven engineering design automation.

---

**Client**: Electronics manufacturer (undisclosed)
**Organization**: Narnia Labs
**Category**: Others

**Source**: [Narnia Labs Case Study #50](https://narnia.ai/kor/html/resource/caseStudiesDetail.html?id=50)
