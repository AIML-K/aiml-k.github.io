---
title: "The Weight Gram Matrix Captures Sequential Feature Linearization in Deep Networks"
authors:
- "taehuncha"
- "Daniel Beaglehole"
- "Adityanarayanan Radhakrishnan"
- "admin"
# Date is the first verified arXiv submission, NOT a conference publication date.
date: "2026-05-07"

# Schedule page publish date (NOT publication's date).
# publishDate is intentionally unset until human release review.
draft: true

# Publication type, following existing ICML conference pages.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "NeurIPS 2026"
publication_short: "NeurIPS 2026"

# Faithful Korean translation of the original abstract.
abstract: |
  심층 신경망이 표현을 어떻게 학습하는지 이해하는 것은 여전히 기계학습 이론의 핵심 과제입니다. 본 연구에서는 가중치 갱신과 특징의 변화를 연결하여 신경망 학습을 분석하는 특징 중심의 프레임워크를 제안합니다. 특징의 변화 양상을 포착하는 핵심 대상이 가중치 그람 행렬임을 밝혀 주는 간단한 항등식인 Feature Learning Equation을 도입합니다. 이를 통해 경사 하강법을 특징의 가상적인 변화를 암묵적으로 유도하는 과정으로 해석할 수 있으며, 이 특징들의 공분산 구조를 Virtual Covariance라고 부릅니다. Virtual Covariance는 학습 중 표현이 어떻게 변화하는지를 특징짓습니다. 이러한 관점을 바탕으로 특징과 목표 사이의 선형 정렬 정도를 정량화하는 척도인 Target Linearity를 도입합니다. 학습 과정과 층별 변화 양상을 분석하여, 심층 신경망이 표현을 목표와 선형적으로 정렬된 구조로 순차적으로 변환하도록 학습한다는 것을 보입니다. 이러한 선형화 관점은 Neural Collapse와 생성 모델에서의 선형 보간을 비롯한 여러 경험적 현상에 대한 통합적인 해석을 제공합니다.

# Summary. An optional shortened abstract.
summary: |
  가중치 그람 행렬로 학습과 깊이에 따른 특징 표현의 목표 정렬을 분석합니다.

tags:
- "Feature Learning"
- "Weight Gram Matrix"
- "Neural Collapse"

links:
- name: PDF
  url: https://arxiv.org/pdf/2605.06258
- name: arXiv
  url: https://arxiv.org/abs/2605.06258
- name: HTML
  url: https://arxiv.org/html/2605.06258v2

- name: NeurIPS 2026
  url: https://nips.cc/virtual/2026/poster/152900
- name: "코드"
  url: https://github.com/cth127/GramLin

# No new or unverified image assets are introduced.
image:
  caption: ""
  focal_point: ""
  preview_only: false
---
