---
layout: page
title: Generative AI for Optimal Duct Design in Seat HVAC Systems
description: Generative AI combined with a physics-based surrogate model for pressure-drop-optimal duct design in seat ventilation
img: assets/img/narnia_case_63.jpg
importance: 2
category: work
related_publications: false
start_date: 2024-03-01
end_date: 2026-03-01
organization: Narnia Labs
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/narnia_case_63.jpg" title="Generative AI for Optimal Duct Design in Seat HVAC Systems" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Generative AI for Optimal Duct Design in Seat HVAC Systems — Narnia Labs case study (originally: 모빌리티 시트 공조 시스템 덕트(Duct) 최적 설계를 위한 생성형 AI)
</div>

## Project Overview

Developed an end-to-end AI platform for designing seat ventilation ducts in mobility applications. Given target boundary conditions, a generative model proposes candidate duct geometries and a predictive surrogate estimates the pressure drop of each candidate in real time. A latent-space optimization loop then converges to a pressure-drop-optimal shape without running conventional CFD.

## My Role

**Project Manager, Narnia Labs**
- Led problem definition and scoping in collaboration with the client team
- Owned client-facing communication and delivery milestones throughout the engagement
- Drove hands-on technical work on the generative + predictive AI platform for pressure-drop-optimal duct design

## The Challenge

Traditional seat-vent duct design leans heavily on individual engineer experience, which limits both novelty and rigor:

- **Experience-dependent, limited creativity**: Designs are dominated by the engineer's own repertoire, making it hard to reach truly novel duct topologies.
- **Limited search methodology**: Conventional performance analysis provides little help in systematically exploring hole patterns or flow-channel shapes for optimality.
- **Slow evaluation loop**: There is no fast way to evaluate many candidate shapes against diverse operating conditions.

## Technical Approach

Integrated three components into a single design platform:

- **Conditional generative model**: Takes design region and operating constraints as input and produces candidate 3D duct geometries.
- **Physics-informed surrogate**: Predicts the pressure drop of a given 3D duct directly, replacing expensive CFD. The loss embeds airflow physics so predictions remain physically consistent.
- **Latent-space optimization**: Searches the generator's latent space to converge on a duct shape that minimizes pressure loss under given constraints.
- **Designer-facing GUI**: Packaged the whole workflow so that non-specialists can use it without CAE expertise.

## Impact

- **Radical cut in simulation cost**: Real-time pressure-drop prediction replaces expensive CFD runs, collapsing turnaround from days to seconds.
- **Broader design exploration**: The workflow evaluates a large candidate space quickly, letting designers reach shapes they would not have proposed by hand.
- **Design know-how as digital asset**: Continuous data updates turn individual engineering intuition into a reusable, company-owned digital asset.

---

**Client**: Automotive OEM and Tier-1 supplier (undisclosed)
**Organization**: Narnia Labs
**Category**: Automobile

**Source**: [Narnia Labs Case Study #63](https://narnia.ai/kor/html/resource/caseStudiesDetail.html?id=63)
