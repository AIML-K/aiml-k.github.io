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

# Publication type, following existing ICML conference pages.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "NeurIPS 2026"
publication_short: "NeurIPS 2026"

# Source-grounded abstract paraphrase; not a verbatim reproduction.
abstract: |
  Vision Transformer(ViT)는 고해상도에서 자기 주의(self-attention)의 이차 복잡도로 인해 심각한 계산 병목에 직면합니다. 기존 토큰 축소 방법은 단일 층의 어텐션 점수와 같은 국소적 지표에 의존하며, 이러한 지표는 정보가 부족한 토큰이 두드러진 전경 객체보다 우선적으로 보존되는 역설적인 attention sink 현상에 본질적으로 취약합니다. 우리는 이러한 sink를 유용한 특성으로 재해석하는 학습이 필요 없는 프레임워크인 ASAP(Attention Sink Anchored Pruning)를 제안합니다. ASAP는 ViT의 정보 흐름을 Lazy Random Walk로 모델링하여 sink를 확률 질량이 집중적으로 누적되는 지점으로 식별합니다. 누적 전이 행렬 내에서 sink까지의 확산 거리를 계산함으로써, ASAP는 Radial Diffusion Clustering을 통해 토큰을 분할하고 Transition Weight Pooling을 통해 배경의 중복 정보를 한 번에 압축합니다. 이미지, 비디오, 비전언어 과제 전반에 걸친 광범위한 실험은 ASAP가 기준 모델의 정확도를 유지하거나 오히려 능가하면서 처리량을 최대 48% 높여 최신 최고 성능의 방법들을 능가함을 보여줍니다.

# Summary. An optional shortened abstract.
summary: |
  추가 학습 없이 attention sink와의 정보 흐름 거리를 활용해 시각 토큰을 압축합니다.

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
- name: "프로젝트 (코드 공개 예정)"
  url: https://github.com/2jaehyuk/Attention-Sink-Anchored-Pruning

# No new or unverified image assets are introduced.
image:
  caption: ""
  focal_point: ""
  preview_only: false
---

현재 프로젝트 저장소에는 2026년 12월 코드 공개를 예고하는 README가 있으며, 구현 코드는 아직 올라와 있지 않습니다.
