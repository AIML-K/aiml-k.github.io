---
title: "ASAP: Attention Sink Anchored Pruning"
authors:
- "jaehyuklee"
- "hanyoungkim"
- "yanggeekim"
- "admin"
# Date is the first verified arXiv submission, NOT a conference publication date.
date: "2026-05-21"

# Schedule page publish date (NOT publication's date).
# publishDate is intentionally unset until human release review.
draft: true

# Citation uses the verified arXiv preprint; conference proceedings remain unverified.
publication_types: ["article"]

publication: "arXiv preprint; listed by NeurIPS 2026"
publication_short: "NeurIPS 2026 listing / arXiv"

# Source-grounded abstract paraphrase; not a verbatim reproduction.
abstract: |
  ASAP is a training-free method for reducing visual tokens. It models information flow through transformer layers as a lazy random walk and uses distance from an attention sink to group tokens, compressing redundant background information. The paper evaluates the method on image, video and vision-language tasks, reporting trade-offs between computational cost and task accuracy.

# Summary. An optional shortened abstract.
summary: |
  Training-free visual-token compression guided by information-flow distance from an attention sink.

tags:
- "Token Pruning"
- "Attention Sink"

links:
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

## Publication status

The exact paper title appears in the [official NeurIPS 2026 downloads list](https://nips.cc/Downloads/2026), which links to the conference page above. The conference track and proceedings citation still require author review. The citation here is the arXiv export, and the displayed date is the first arXiv submission date.

The project repository currently contains a README announcing code release in December 2026; an implementation is not yet available there.
