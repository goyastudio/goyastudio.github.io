---
layout: page
title: 3D Asset–Object Modeling Image Pair Dataset (AI Hub)
description: Public dataset of 10,000 3D object assets and 960,000 multi-view RGB, mask, depth, and normal renders for 3D generation and reconstruction
img: assets/img/aihub_3d_asset_thumb.png
importance: 4
category: work
related_publications: false
start_date: 2022-04-01
end_date: 2022-12-31
organization: Smart Design Lab, KAIST
---

## Project Overview

This project built **3D 에셋-사물 모델링 이미지 쌍 데이터** (3D Asset–Object Modeling Image Pair Data), a public dataset released on [AI Hub](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=71412), the Korean national AI training-data platform. Smart Design Lab at KAIST led the work, and DreamTrueal refined, processed, and inspected the data.

## Dataset

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/aihub_3d_asset_views.png" title="Multi-view renders of a 3D asset" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Each asset is rendered from 24 camera viewpoints (source: AI Hub)
</div>

- **10,000 3D object assets** across **402 classes**, split into portable (66%) and non-portable (34%) objects
- **960,000 labeled 2D images**: each asset is rendered from 24 viewpoints in Unity, giving 240,000 each of RGB, mask, depth, and normal images
- **Formats**: 3D assets in FBX, OBJ, MTL, and PNG; renders in PNG; annotations and camera metadata in JSON
- **Size**: about 566 GB in total

## Applications

The paired 3D assets and multi-view renders can be used for:

- **Robotics**: object recognition and manipulation
- **3D reconstruction** and **novel view synthesis**
- **Image-to-3D generation**
- **Depth and normal estimation**
- **Digital twin and simulation** environments

---

**Released**: Beta v1.0 in June 2023, final v1.1 in December 2023
**Organization**: Smart Design Lab, KAIST (lead), with DreamTrueal

**Dataset**: [AI Hub — 3D 에셋-사물 모델링 이미지 쌍 데이터](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=71412)
