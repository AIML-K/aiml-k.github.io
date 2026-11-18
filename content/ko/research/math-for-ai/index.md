---
title: 'AI의 수학적 기초'
summary: 'AI, 특히 딥러닝이 작동하는 이유에 대한 엄밀한 설명 — 학습 동역학, 가지치기, 특징 학습, 표현의 기하학.'
date: 2026-06-20
---

## 개요

현대 AI 시스템은 놀라울 만큼 잘 작동하지만, 알고리즘과 과학의 관점에서 *왜* 잘 작동하는지는 여전히 많은 부분이 충분히 이해되지 않고 있습니다.
이 연구 주제는 최적화 지형, 학습 동역학, 일반화를 단순히 관찰하는 현상이 아니라 분석할 수 있는 대상으로 다루며 학습 시스템의 수학적 기초를 구축합니다.

우리의 연구 성과는 여러 방향에 걸쳐 있습니다. 
최적화 측면에서는 학습이 정지점을 우회하는 방식을 연구했으며, 분수 차수 경사법도 탐구했습니다. 
딥러닝 모델 구조 측면에서는 분기 동역학과 사영기하학을 활용하여 신경망의 함수 출력을 유지하면서 제거할 수 있는 연결을 판단하는, 원리에 기반한 구조적 가지치기 방법을 개발합니다. 
표현 학습의 관점에서는 특징 학습을 공분산 학습의 한 형태로 분석했으며, 신경망의 마지막 층에서 특징의 선형 분리 가능성이 나타나는 현상을 연구합니다. 
이러한 연구를 관통하는 목표는 경험적으로 관찰된 현상을 딥러닝 모델의 동작을 예측하고 더 나은 모델 설계를 이끌며 현대 AI가 작동하는 이유를 더 깊이 이해하게 하는 이론으로 발전시키는 것입니다.

## 핵심 질문

- 최적화 동역학을 지배하는 것은 무엇이며, 학습은 언제 바람직하지 않은 임계점에서 벗어나거나 이를 우회할 수 있을까요?
- 신경망에서 실제로 필요한 부분은 얼마나 되며, 경험적 규칙이 아니라 증명 가능한 구조에 근거하여 어떻게 가지치기할 수 있을까요?
- 학습 중 표현에서 유용한 특징과 명료한 기하학적 구조는 어떻게 나타날까요?

## 대표 연구

- [Bypassing Stationary Points in Training Deep Learning Models](https://aiml-k.github.io/publication/2024tnnls-jung-lee/) — *IEEE TNNLS, 2024*
- [Curse of Smoothness in Functional Neural Networks](https://aiml-k.github.io/publication/2025spl-cha-lee/) — *IEEE Signal Processing Letters, 2025*
- [Catalyst: Structured Pruning with Robust Bifurcation Dynamics](https://aiml-k.github.io/publication/2025icml-hildworkshop-catalyst/) — *ICML 2025 HiLD Workshop*
- [Feature Learning as a Virtual Covariance Learning](https://aiml-k.github.io/publication/2025neurips-optworkshop/) — *NeurIPS 2025 OPT Workshop*
- [Emergent Linear Separability of Unseen Data Points in High-dimensional Last-Layer Feature Space](https://aiml-k.github.io/publication/2025icml-hildworkshop-linsep/) — *ICML 2025 HiLD Workshop*

전체 연구 성과는 [논문](/publication/) 페이지에서 확인할 수 있습니다.

## 관련 자료

- [Math4AI](/tag/math4ai/) 태그가 붙은 연구 기록
- 학습 이론 관련 [행사](/event/)와 독서 모임

## 연구진

- [Donghun Lee](/author/donghun-lee/) — 연구책임자
- [Taehun Cha](/author/taehun-cha/) — 특징 학습, 마지막 층의 기하학
- [Jaeheun Jung](/author/jaeheun-jung/) — 구조적 가지치기, 학습 동역학
- [Bosung Jung](/author/bosung-jung/) — 최적화, 언러닝

전체 연구실 구성원은 [구성원](/people/) 페이지에서 확인할 수 있습니다.
