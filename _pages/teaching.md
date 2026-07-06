---
layout: page
permalink: /talk/
title: talk
description:
nav: true
nav_order: 6
_styles: >
  .talk-list {
    list-style: none;
    padding: 0;
  }
  .talk-item {
    border-left: 3px solid var(--global-theme-color);
    padding: 1rem 1.2rem;
    margin-bottom: 2rem;
    background: var(--global-card-bg-color);
    border-radius: 0 8px 8px 0;
  }
  .talk-item h3 {
    margin: 0 0 0.5rem 0;
    font-size: 1.1rem;
  }
  .talk-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 0.3rem 1.5rem;
    font-size: 0.9rem;
    color: var(--global-text-color-light);
  }
  .talk-meta span i {
    margin-right: 0.3rem;
  }
  .talk-img {
    width: 100%;
    max-height: 350px;
    object-fit: cover;
    border-radius: 6px;
    margin-top: 0.8rem;
  }
  .talk-video {
    position: relative;
    padding-top: 56.25%;
    margin-top: 0.8rem;
    border-radius: 6px;
    overflow: hidden;
  }
  .talk-video iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
  }
---

<ul class="talk-list">

  <li class="talk-item">
    <h3>Uncertainty-Guided Data Augmentation for Engineers | Deep Dive - Yongmin Kwon</h3>
    <div class="talk-meta">
      <span><i class="fa-brands fa-youtube"></i> <a href="https://youtu.be/5llG0WbguFU" target="_blank" rel="noopener">YouTube</a></span>
      <span><i class="fa-solid fa-users"></i> Deep Dive w/ Jousef Murad</span>
    </div>
    <div class="talk-video">
      <iframe src="https://www.youtube.com/embed/5llG0WbguFU" title="Uncertainty-Guided Data Augmentation for Engineers - Yongmin Kwon" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
  </li>

  <li class="talk-item">
    <h3>인공지능을 활용한 최적 설계 : 이론 및 실습</h3>
    <div class="talk-meta">
      <span><i class="fa-solid fa-calendar"></i> 2024. 8. 22 - 23</span>
      <span><i class="fa-solid fa-location-dot"></i> KAIST 기계공학동</span>
      <span><i class="fa-solid fa-users"></i> 한국최적설계학회</span>
    </div>
    {% include figure.liquid path="assets/img/talk_ksod_2024.jpg" class="talk-img" alt="인공지능을 활용한 최적 설계 : 이론 및 실습" %}
  </li>

  <li class="talk-item">
    <h3>대한기계학회 CAE 및 응용역학부문 신기술 강습회</h3>
    <div class="talk-meta">
      <span><i class="fa-solid fa-calendar"></i> 2024. 8. 13</span>
      <span><i class="fa-solid fa-location-dot"></i> 서울대학교 신공학관 (301동) 105호</span>
      <span><i class="fa-solid fa-users"></i> CAE 및 응용역학부문 신기술위원회</span>
    </div>
    {% include figure.liquid path="assets/img/talk_ksme_2024.jpg" class="talk-img" alt="대한기계학회 CAE 및 응용역학부문 신기술 강습회" %}
  </li>

</ul>
