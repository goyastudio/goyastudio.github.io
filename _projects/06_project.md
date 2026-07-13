---
layout: page
title: Generative AI for Lightweighting and Cost Reduction of Washing Machine Parts
description: Generative AI that explores lightweight, high-stiffness designs for washing machine structural components under strict performance targets
img: assets/img/narnia_case_48.png
importance: 6
category: work
related_publications: false
start_date: 2023-07-01
end_date: 2023-12-01
organization: Narnia Labs
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/narnia_case_48.png" title="Generative AI for Lightweighting and Cost Reduction of Washing Machine Parts" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Generative AI for Lightweighting and Cost Reduction of Washing Machine Parts — Narnia Labs case study (originally: 세탁기 부품의 경량화 및 원가 절감을 위한 생성형 AI)
</div>

## Project Overview

Developed a generative AI workflow to lightweight and cost-reduce structural components in large washing machines while preserving their performance targets. From a small set of core geometric criteria, the system produces a large variety of candidate designs and automatically evaluates their structural response, enabling exploration of the safety-vs-cost trade-off far beyond what a human engineer can realistically try.

## My Role

**AI Researcher, Narnia Labs**
- Individual contributor on the implementation code for the parametric-design and structural-verification pipeline
- Built and tuned the generation–evaluation loop that surfaces the mass-vs-stiffness trade-off

## The Challenge

Reducing part cost while preserving structural performance is constrained by both data and process limits:

- **Data-limited design exploration**: Innovative structural changes are desirable for cost reduction, but limited reference data restricts how broadly the initial design space can be explored.
- **Cost vs. durability trade-off**: Large-drum washing machines subject parts to high rotational and dynamic loads. Reducing part weight and cost while retaining safety margins is a challenging multi-objective problem.

## Technical Approach

Delivered an intelligent design–verify pipeline for structural components:

- **Auto-generation from a minimal seed**: Given core geometric criteria for a part, the system combinatorially generates a large number of candidate designs, breaking free from the initial data limitation.
- **Automated structural verification**: Instead of engineers running individual analyses, the system evaluates each candidate's structural response — vibration, load-bearing — automatically.
- **Intelligent optimization (roadmap)**: A next step is to close the loop with an AI that inverts the evaluation results into a proposed "minimum weight, maximum stiffness" design.

## Impact

- **Unbounded structural-design exploration**: Frees the search from the limits of legacy data and human intuition, systematically covering a much broader design space.
- **Cost-quality trade-off surfaced explicitly**: Automatically analyzed candidates reveal the optimal frontier that reduces mass (cost) while retaining strength (quality).
- **R&D efficiency through pipeline automation**: Replaces manual test cycles with an automated pipeline, accelerating early-stage decisions and demonstrating tangible cost-reduction potential.

---

**Client**: Electronics manufacturer (undisclosed)
**Organization**: Narnia Labs
**Category**: Electronics

**Source**: [Narnia Labs Case Study #48](https://narnia.ai/kor/html/resource/caseStudiesDetail.html?id=48)
