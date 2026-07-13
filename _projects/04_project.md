---
layout: page
title: Generative Design of Brake Calipers with 3D Deep Learning
description: 3D deep-learning generative design for automotive brake calipers with structural performance prediction and optimization
img: assets/img/narnia_case_59.png
importance: 4
category: work
related_publications: false
start_date: 2022-05-01
end_date: 2023-12-01
organization: Narnia Labs
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/narnia_case_59.png" title="Generative Design of Brake Calipers with 3D Deep Learning" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Generative Design of Brake Calipers with 3D Deep Learning — Narnia Labs case study (originally: 3D 딥러닝 기반 제너레이티브 디자인을 이용한 제동 캘리퍼 형상 구현)
</div>

## Project Overview

Developed a 3D deep-learning framework for the design of automotive brake calipers. The system proposes thousands of candidate geometries, predicts their structural performance on the fly, and optimizes for a target trade-off between strength and weight — enabling design exploration well beyond the historical repertoire of human engineers.

## My Role

**Project Manager, Narnia Labs**
- Led problem definition and scoping in collaboration with the client team
- Owned client-facing communication and delivery milestones throughout the engagement
- Drove hands-on technical work on the 3D deep-learning generative-design framework integrating a generator, evaluator, and optimizer

## The Challenge

Existing brake-caliper design relies on repeated manual CAD + physical / CAE test cycles:

- **Repetitive design–test loop**: Reaching a design that goes beyond historical templates typically requires many rounds of test, hurting both cost and lead time.
- **Manual-process resource waste**: Engineers hand-design a candidate, then run structural analyses and physical tests until requirements are met — a highly iterative and expensive workflow.

## Technical Approach

Built an integrated AI framework combining generation, evaluation, and optimization:

- **AI-based design assistant**: A 3D deep-learning model trained on existing designs and the underlying physics can propose tens of thousands of caliper designs and immediately estimate their performance.
- **Generator + Evaluator loop**: Rather than only drawing candidate shapes, the system actively generates new designs and pre-evaluates their structural response, closing the automation loop.
- **Optimizer**: A dedicated optimization stage searches for shapes that simultaneously maximize stiffness and minimize weight — targets that the human designer struggles to balance manually.

## Impact

- **High-stiffness, lightweight caliper designs**: Structural performance is preserved (or improved) while weight is reduced, cutting development cost at the same time.
- **Creative, non-standard geometries**: The AI proposes topologies that a human engineer would rarely intuit, expanding the reachable design space.
- **Faster, cheaper development**: Structurally sound, novel caliper designs are delivered significantly faster and at lower cost than the traditional manual workflow.

---

**Client**: Automotive parts manufacturer (undisclosed)
**Organization**: Narnia Labs
**Category**: Automobile

**Source**: [Narnia Labs Case Study #59](https://narnia.ai/kor/html/resource/caseStudiesDetail.html?id=59)
