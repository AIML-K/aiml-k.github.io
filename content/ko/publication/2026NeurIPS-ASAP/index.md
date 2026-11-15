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

publication: "arXiv 프리프린트; NeurIPS 2026 공식 목록 수록"
publication_short: "NeurIPS 2026 목록 / arXiv"

# Source-grounded abstract paraphrase; not a verbatim reproduction.
abstract: |
  ASAP는 추가 학습 없이 시각 토큰을 줄이는 방법입니다. 트랜스포머 층 사이의 정보 흐름을 lazy random walk로 모델링하고, attention sink로부터의 거리를 이용해 토큰을 묶어 중복된 배경 정보를 압축합니다. 이미지·비디오·비전언어 과제에서 계산 비용과 과제 정확도의 관계를 평가합니다.

# Summary. An optional shortened abstract.
summary: |
  추가 학습 없이 attention sink와의 정보 흐름 거리를 활용해 시각 토큰을 압축합니다.

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
- name: "프로젝트 (코드 공개 예정)"
  url: https://github.com/2jaehyuk/Attention-Sink-Anchored-Pruning

# No new or unverified image assets are introduced.
image:
  caption: ""
  focal_point: ""
  preview_only: false
---

## 공개 상태

[NeurIPS 2026 공식 다운로드 목록](https://nips.cc/Downloads/2026)에 이 논문의 정확한 제목과 위 학회 페이지 링크가 실려 있습니다. 학회 트랙과 논문집 서지정보는 저자의 확인이 필요합니다. 이 페이지의 인용 정보는 arXiv 내보내기이며, 표시된 날짜는 arXiv 최초 제출일입니다.

현재 프로젝트 저장소에는 2026년 12월 코드 공개를 예고하는 README가 있으며, 구현 코드는 아직 올라와 있지 않습니다.
