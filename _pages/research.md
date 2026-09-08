---
layout: page
permalink: /research/
title: research
description: Foundation models as oracles for engineering design.
nav: true
nav_order: 1
---

<div class="row justify-content-center mt-2 mb-2">
  <div class="col-12">
    {% include figure.liquid loading="eager" path="assets/img/research_oracle.png" class="img-fluid rounded z-depth-1" alt="A researcher, carrying domain constraints (physics, geometry, manufacturing), approaching a Foundation Model that generates candidate forms" %}
  </div>
</div>
<div class="caption text-center">
  <em>My research in one picture:</em> bringing physics, geometry, and manufacturing constraints to foundation models — so that what they generate is engineering-valid, not just visually plausible.
</div>

## Research focus

**Making foundation models useful for engineering design** — by treating them as *oracles to be queried under geometric and physical constraints*, so what they generate stays inside the design domain, carries load, and remains manufacturable.

Generative foundation models now propose plausible forms in almost any modality, but engineering design still cannot use them directly. An output must be *physically valid*: it must stay inside the design domain, keep the fixture and loading interfaces intact, carry load, and remain manufacturable. Retraining on more engineering data does not solve this — the training objective reproduces a distribution, not constraints, so conditional generation *biases* an output rather than *binds* it. The gap is therefore one of formulation, not of training.

My research treats foundation models not as objects of retraining but as **oracles to be queried**. An oracle returns a plausible form for almost any query but cannot tell which form carries load. That judgment must come from outside the model — supplied here by geometric and physical constraints that recover engineering features the model never learned.

The same idea plays out across modalities, with different instantiations. When the oracle is an image model, a frozen text-to-image diffusion, queried through score distillation, can be paired with finite-element sensitivity so density-based topology optimization is guided by both physics and an explicit representation of design intent. When it is a geometry model, geometric and physical losses can be back-propagated into the latents of a pretrained flow-matching sampler so shape and mechanics are co-designed *as the geometry forms*. When it is a language model, a multi-agent system can decompose the problem and call analysis tools whose returned results stand in for differentiable losses — for example, to co-design airframe geometry and flight control of a multicopter. These are illustrative instantiations, not a fixed recipe: what to ask, where to filter the response, and how to express a specification as constraints depend on the problem and the modality. Nothing here updates model weights, so a new domain, load, or objective is handled by changing the prompt, the specification, and the constraints.

As the formulation fits more closely, responsibility for setting the criterion shifts from the engineer toward the oracle. This is not a claim of autonomous design. It is a way to elicit the unlearned engineering knowledge that foundation models will not surface on their own — and a measurable path toward it.
