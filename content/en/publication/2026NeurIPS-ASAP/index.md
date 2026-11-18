---
title: "ASAP: Attention Sink Anchored Pruning"
authors:
- "jaehyuklee"
- "hanyoungkim"
- "yanggeekim"
- "admin"
# Date is the first verified arXiv submission, NOT a conference publication date.
date: "2026-05-21"

# Publication type, following existing ICML conference pages.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "NeurIPS 2026"
publication_short: "NeurIPS 2026"

# Source-grounded abstract paraphrase; not a verbatim reproduction.
abstract: |
  Vision Transformers (ViTs) face severe computational bottlenecks due to the quadratic complexity of self-attention at high resolutions. Existing token reduction methods rely on local metrics, such as single-layer attention scores, that are inherently vulnerable to the attention sink phenomenon, where uninformative tokens are paradoxically preserved over salient foreground objects. We propose ASAP (Attention Sink Anchored Pruning), a training-free framework that recasts this sink as a feature. Modeling ViT information flow as a Lazy Random Walk, ASAP identifies the sink as a dominant accumulator of probability mass. By computing the diffusion distance to the sink within the cumulative transition matrix, ASAP partitions tokens via Radial Diffusion Clustering and compresses background redundancy through Transition Weight Pooling in a single shot. Extensive experiments across image, video, and vision-language tasks demonstrate ASAP outperforms state-of-the-art methods, accelerating throughput by up to 48% while maintaining or even exceeding baseline accuracy.

# Summary. An optional shortened abstract.
summary: |
  Training-free visual-token compression guided by information-flow distance from an attention sink.

tags:
- "Token Pruning"
- "Attention Sink"

links:
- name: PDF
  url: https://arxiv.org/pdf/2605.22372
- name: arXiv
  url: https://arxiv.org/abs/2605.22372
- name: HTML
  url: https://arxiv.org/html/2605.22372v2

- name: NeurIPS 2026
  url: https://nips.cc/virtual/2026/poster/151159
- name: "Project (code forthcoming)"
  url: https://github.com/2jaehyuk/Attention-Sink-Anchored-Pruning

# No new or unverified image assets are introduced.
image:
  caption: ""
  focal_point: ""
  preview_only: false
---

The project repository currently contains a README announcing code release in December 2026; an implementation is not yet available there.
