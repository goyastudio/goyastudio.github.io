---
layout: page
title: AI-Based Vehicle Crash Kinematics Prediction
description: Machine learning system for predicting small overlap crash response using early-stage design data
img: assets/img/hmc.png
importance: 3
category: work
related_publications: false
start_date: 2021-05-01
end_date: 2022-05-31
---

## Project Overview

This project developed an AI-based prediction system for vehicle kinematic response in small overlap frontal crash tests. The system enables engineers to predict crash behavior during early design stages using only vehicle geometry and specification data, eliminating the need for expensive physical prototypes.

## My Role

**Technical Implementation Lead**
- Implemented machine learning models for crash kinematics prediction
- Developed vehicle trajectory extraction pipeline using object detection algorithms
- Conducted correlation analysis between design parameters and crash response
- Delivered end-to-end prediction system integrated with vehicle development workflow

## Background

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/hmc.png" title="Small Overlap Crash Test Analysis" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    AI-driven analysis of vehicle kinematics in small overlap crash scenarios
</div>

### Small Overlap Frontal Crash Test

In small overlap frontal tests, only a portion of the vehicle's front end collides with a barrier, creating unique crash dynamics that differ significantly from full-width frontal impacts. This test scenario is critical for passenger safety assessment.

### The Challenge

Traditional crash test evaluation faced several limitations:

- **Subjective assessment**: Vehicle kinematic response classification relied on developer's subjective judgment rather than quantitative metrics
- **Lack of predictive capability**: No method existed to predict crash behavior during early design stages
- **Limited understanding**: Correlation between vehicle design parameters and crash kinematics was poorly understood
- **High development cost**: Physical crash tests are expensive, limiting design iteration capability

## Technical Solution

### Machine Learning-Based Prediction Model

Developed a prediction system that forecasts vehicle kinematic response using only early-stage design information:

**Input**: Vehicle geometry and specification data (available in early design phase)

**Output**: Quantitative prediction of vehicle trajectory and kinematic behavior during small overlap crash

### Key Technical Components

1. **Automated Trajectory Extraction**
   - Implemented object detection algorithms to extract vehicle motion from crash test videos
   - Automated conversion of visual data into quantitative trajectory measurements

2. **Design-Response Correlation Analysis**
   - Analyzed relationships between vehicle design variables (geometry, structure, weight distribution) and crash kinematics
   - Identified key design parameters that influence crash response

3. **Predictive Modeling**
   - Trained machine learning models to predict crash kinematics from design parameters
   - Enabled quantitative response prediction without physical testing

## Impact

### Early Design Phase Integration

The system enables crash performance evaluation during early design stages when:
- Physical prototypes don't yet exist
- Design changes can be implemented at minimal cost
- Multiple design alternatives can be quickly evaluated

### Quantitative Decision Making

Replaced subjective judgment with objective, data-driven metrics for:
- Vehicle kinematic response classification
- Design optimization guidance
- Safety performance prediction

### Development Efficiency

- Reduced dependency on expensive physical crash tests
- Accelerated design iteration cycles
- Improved understanding of design-performance relationships

The methodology developed in this project demonstrates how AI can transform traditional automotive safety engineering by enabling predictive analysis during conceptual design phases.

---

**Project Duration**: May 2021 - May 2022 (1 year)
**Client**: Hyundai Motor Company
**Organization**: Narnia Labs
