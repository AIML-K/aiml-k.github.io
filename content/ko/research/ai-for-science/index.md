---
title: '과학과 공학을 위한 AI'
summary: '지진학, 재료, 기구 설계, 생의학 영상에 AI를 적용해 온 연구'
date: 2026-06-18
---

## 개요

<!-- Many problems in science and engineering are governed by equations that are expensive to solve and hard to invert. 
This theme develops machine-learning methods — especially operator learning and physics-aware generative models — that approximate these systems efficiently and generalize across conditions. -->

우리는 수학에 기반한 AI 응용이 폭넓은 과학·공학 분야를 아우를 수 있다고 믿습니다.

우리는 다양한 편미분방정식(PDE) 문제에 적합하도록 라플라스 표현과 푸리에 표현을 함께 활용하는, 일반화 가능하고 효율적인 연산자 학습 알고리즘을 위한 신경 연산자를 구축했습니다. 
지진학에서는 확산 모델과 생성 모델을 활용하여 AI가 고품질 광대역 지반 운동과 상시 지진 잡음을 생성할 수 있음을 보였습니다.  
재료과학·공학에서는 에폭시 고분자의 기계적 물성을 추정하고 최적화하는 AI 기반 파이프라인을 구축했습니다. 또한 데이터가 풍부한 배터리 영상과 데이터가 부족한 배터리 영상 사이의 전이 학습을 수행하고, 설계 명세로부터 막대 링크 기구 설계를 직접 합성합니다. 
생의학 분야에서는 무릎 골관절염 진단을 위한 다중모달 모델과
척추 지표 자동 측정 모델을 개발했습니다. 
이 모든 연구를 관통하는 공통점은 각 문제의 근저를 지배하는 본질을 추상화하는 것입니다.

## 핵심 질문

- 신경 연산자는 과학·기술·공학·수학(STEM) 문제에 자주 쓰이는 편미분방정식 계열 전체의 해 사상을 어떻게 효율적으로, 일반화 보장과 함께 학습할 수 있을까요?
- 물리적 구조를 따르면서 분포 밖의 상황에서도 신뢰성을 유지하는 생성 모델을 어떻게 구축할 수 있을까요?
- 과학과 공학에서 기존 시뮬레이션을 대체하거나 가속할 수 있는 효과적인 대리 모델을 어떻게 설계할 수 있을까요?

## 대표 연구

- [Best of Both Worlds: Bridging Laplace and Fourier for Generalizable and Efficient Operator Learning](https://aiml-k.github.io/publication/2025neurips-ml4psworkshop/) — *NeurIPS 2025 ML4PS Workshop*
- [Broadband Ground Motion Synthesis by Diffusion Model with Minimal Condition](https://aiml-k.github.io/publication/2025icml-jung-lee-jung-kim-jung-lee/) — *ICML 2025*
- [CLIP-KOA: Enhancing Knee Osteoarthritis Diagnosis with Multi-Modal Learning](https://aiml-k.github.io/publication/2025-clip-koa/) — *MICCAI 2025 LMID Workshop*
- [Re-experiment Smart: Enhancing Data-driven Prediction of Mechanical Properties of Epoxy Polymers](https://aiml-k.github.io/publication/2025arxiv-smart-reexperimentation/) — *프리프린트, 2025*
- [PPSD GAN: PPSD-informed Generative Model for Ambient Seismic Noise Synthesizing](https://aiml-k.github.io/publication/2024ieeegrsl-cho-ha-lim-han-kim-lee/) — *IEEE GRSL, 2024*

전체 연구 성과는 [논문](/publication/) 페이지에서 확인할 수 있습니다.

## 관련 자료

- [AI4Science](/tag/ai4science/) 태그가 붙은 연구 기록
- [행사](/event/) 및 과학·공학 분야 파트너와의 협업

## 연구진

- [Donghun Lee](/author/donghun-lee/) — 연구책임자
- [Jeongun Ha](/author/jeongun-ha/) — 연산자 학습
- [Jaehyuk Lee](/author/jaehyuk-lee/) — 지진 및 생성 모델링
- [Jaeheun Jung](/author/jaeheun-jung/) — 지반 운동 합성, 기구 설계
- [Hanyoung Kim](/author/hanyoung-kim/) — 지진 생성 모델링
- [Minseok Choi](/author/minseok-choi/) — 방문연구원(POSTECH), 과학 머신러닝

전체 연구실 구성원은 [구성원](/people/) 페이지에서 확인할 수 있습니다.
