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

# Original abstract supplied by the author.
abstract: |
  Understanding how deep neural networks learn representations remains a central challenge in machine learning theory. In this work, we propose a feature-centric framework for analyzing neural network training by relating weight updates to feature evolution. We introduce a simple identity, the Feature Learning Equation, which identifies the weight Gram matrix as the key object capturing feature dynamics. This enables us to interpret gradient descent as implicitly inducing a hypothetical evolution of features, whose covariance structure, termed the Virtual Covariance, characterizes how representations evolve during training. Building on this perspective, we introduce Target Linearity, a measure quantifying the linear alignment between features and targets. By analyzing the training and layer-wise dynamics, we show that deep networks learn to sequentially transform representations toward target-linear structure. This linearization perspective provides a unified interpretation of several empirical phenomena, including Neural Collapse and linear interpolation in generative models.

# Summary. An optional shortened abstract.
summary: |
  Weight Gram matrices connect neural-network updates to target-aligned feature evolution across training and depth.

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
- name: "Code"
  url: https://github.com/cth127/GramLin

# No new or unverified image assets are introduced.
image:
  caption: ""
  focal_point: ""
  preview_only: false
---
