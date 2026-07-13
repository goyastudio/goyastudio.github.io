---
layout: page
title: Generative AI for Automated Vehicle Exterior Structural Design
description: Generative AI that turns a styling surface into a manufacturable interior structure, cutting exterior structural design lead time from weeks to minutes
img: assets/img/narnia_case_46.png
importance: 7
category: work
related_publications: false
start_date: 2024-06-01
end_date: 2024-09-01
organization: Narnia Labs
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/narnia_case_46.png" title="Generative AI for Automated Vehicle Exterior Structural Design" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Generative AI for Automated Vehicle Exterior Structural Design — Narnia Labs case study (originally: 생성형 AI 기반 차량 외장 구조 설계 자동화 및 최적화)
</div>

## Project Overview

Developed a generative AI pipeline that automates the design of internal structural parts behind a vehicle's exterior styling surface. Given a stylist-defined outer surface, the system produces engineering-constraint-compliant 3D internal structures that are ready to hand off to downstream CAE analysis — collapsing a workflow that previously took weeks into minutes.

## My Role

**AI Researcher, Narnia Labs**
- Individual contributor on the surface (sheet) generation model that turns the stylist's outer surface into a valid internal structure
- Contributed to encoding engineering constraints as learned priors so generated candidates are verification-ready

## The Challenge

Traditional vehicle exterior structural design is manual, iterative, and constraint-heavy:

- **Slow manual CAD modeling**: The existing workflow depends heavily on engineer-driven CAD modeling, which takes substantial time from initial concept to verification.
- **Costly rework on analysis failure**: When CAE results miss a target, the engineer restarts from modeling — an expensive re-loop that stretches the overall lead time.
- **Limited alternatives explored**: The cost and time of iterating design + analysis restrict how many alternative concepts the team can realistically evaluate.

## Technical Approach

Automated the styling-to-structure pipeline with a constraint-aware generative model:

- **Styling-surface conditioned generation**: The model takes the designer's styling surface as input and outputs an optimal 3D internal structure that complies with the required engineering constraints.
- **Engineering constraints as learned priors**: Core manufacturability and performance constraints for series production are baked into the model, so generated candidates are verification-ready at inference time.
- **Design-analysis-friendly output**: Generated structures are produced in a form that flows naturally into downstream CAE and edit tools, minimizing rework.

## Impact

- **Weeks → minutes**: The lead time for exterior structural design drops from weeks of manual work to minutes of AI-assisted generation.
- **Shift to decision-focused workflow**: Engineers move from "modeling operator" to "selecting the best AI-proposed alternative", concentrating on higher-value design decisions.
- **More alternatives, higher quality**: Many design candidates can be compared side-by-side within a short window, raising both design completeness and product competitiveness.

---

**Client**: Global automotive OEM (undisclosed)
**Organization**: Narnia Labs
**Category**: Automobile

**Source**: [Narnia Labs Case Study #46](https://narnia.ai/kor/html/resource/caseStudiesDetail.html?id=46)
