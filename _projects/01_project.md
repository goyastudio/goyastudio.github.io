---
layout: page
title: AI-Based Real-Time Aerodynamic Prediction for 2-Channel Electric Air Vents
description: Physics-constrained predictive AI that replaces CFD simulation for real-time airflow evaluation of automotive air vents
img: assets/img/narnia_case_65.jpg
importance: 1
category: work
related_publications: false
start_date: 2025-05-01
end_date: 2026-01-01
organization: Narnia Labs
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/narnia_case_65.jpg" title="AI-Based Real-Time Aerodynamic Prediction for 2-Channel Electric Air Vents" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    AI-Based Real-Time Aerodynamic Prediction for 2-Channel Electric Air Vents — Narnia Labs case study (originally: AI 예측을 활용한 2채널 전동 에어벤트 최적 설계)
</div>

## Project Overview

Developed a predictive AI framework that replaces computational fluid dynamics (CFD) simulation for evaluating 2-channel electric air vents used in vehicle cabin air-conditioning. The system returns airflow speed and direction distributions in real time from a candidate geometry, enabling designers to evaluate and iterate concepts without going through a full CFD analysis cycle.

## My Role

**Project Manager, Narnia Labs**
- Led problem definition and scoping in collaboration with the client team
- Owned client-facing communication and delivery milestones throughout the engagement
- Drove hands-on technical work on the physics-constrained predictive AI framework for real-time airflow and direction estimation

## The Challenge

Verifying the performance of a new air-vent geometry traditionally requires running heavy CFD simulations for every candidate design:

- **Expert-dependent long turnaround**: CFD requires significant expert time and compute, inflating design cycle time and cost.
- **Bottleneck for design exploration**: Because each variant must go through a full simulation, designers cannot rapidly compare a large number of alternatives.

## Technical Approach

Built a physics-aware predictive AI that supplies airflow and direction estimates in place of CFD:

- **Physics-constrained learning**: Beyond fitting reference data, the training loss enforces physical constraints such as the incompressible continuity equation, so the model is aware of the governing physics — not just the numbers.
- **Aerodynamic reasoning**: The model learns aerodynamic principles from data, producing high-fidelity, physically consistent predictions rather than purely data-fit outputs.

## Impact

- **Real-time airflow prediction**: Airflow speed and direction distributions are estimated instantly for any vent geometry, without invoking CFD.
- **Designer self-evaluation**: Engineers can judge whether their concept meets requirements on their own, without submitting an analysis request to a CFD expert.
- **Rapid data-driven exploration**: The most performant designs can be filtered from a large candidate pool in a fraction of the time previously required.

---

**Client**: Automotive parts manufacturer (undisclosed)
**Organization**: Narnia Labs
**Category**: Automobile

**Source**: [Narnia Labs Case Study #65](https://narnia.ai/kor/html/resource/caseStudiesDetail.html?id=65)
