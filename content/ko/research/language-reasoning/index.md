---
title: '언어, 추론, 지식'
summary: '언어 모델의 이해와 개선'
date: 2026-06-17
---

## 개요

언어 모델(LM)은 범용 추론 엔진으로 자리 잡았지만, 추론 능력이 고르지 않고 때로는 거짓을 확신에 차서 말합니다. 
이 연구 주제는 언어 모델의 내부 표현과 그것이 지식 검색, 추론, 자기 평가 등 언어 모델 기반 시스템의 동작에 미치는 영향을 연구합니다.

대표적인 예가 환각입니다. 우리는 사전 학습된 언어 모델이 근거에 충실하지 않은 환각 텍스트에 대해 구별 가능한 확률 분포를 출력한다는 것을 보였으며, 질의응답에서 발생하는 환각의 유형과 이를 탐지하는 지표의 한계를 정리했습니다. 
또한 모델이 학습 분포를 넘어, 예를 들어 화학 영역까지 어느 정도 외삽할 수 있는지 탐구하며, 문장 수준 토픽 모델부터 측면 기반 밀집 문단 검색에 이르는 더 나은 표현과 검색 방법을 개발합니다. 
나아가 오늘날 에이전트 실행 체계가 작동하는 방식과 유사하게 강화학습을 도입하여 언어 모델의 동작을 제어하고, 중앙은행 커뮤니케이션의 파급 효과 추출과 같이 결과가 중요한 실제 텍스트 문제에 적용합니다.

## 핵심 질문

- 환각은 왜 발생하며, 신뢰할 수 있고 설명 가능한 언어 모델을 향해 이를 어떻게 탐지하고 측정하며 줄일 수 있을까요?
- 언어 모델은 학습 분포를 넘어 얼마나 잘 외삽할 수 있으며, 실제로는 어느 정도까지 가능할까요?
- 텍스트에 대한 추론의 신뢰성을 높이려면 언어 모델 내부의 지식을 어떻게 표현하고 검색해야 할까요?

## 대표 연구

- [Pre-trained Language Models Return Distinguishable Probability Distributions to Unfaithfully Hallucinated Texts](https://aiml-k.github.io/publication/2024emnlp-cha-lee/) — *EMNLP 2024 Findings*
- [SentenceLDA: Discriminative and Robust Document Representation with Sentence Level Topic Model](https://aiml-k.github.io/publication/cha-lee-2024-sentencelda/) — *EACL 2024*
- [Evaluating Extrapolation Ability of Large Language Model in Chemical Domain](https://aiml-k.github.io/publication/2024acl-cha-lee/) — *ACL 2024 Workshop*
- [Consequence-Guided Information Extraction for Predicting Central Bank Communication's Effect](https://aiml-k.github.io/publication/2026ce-cha-lee/) — *Computational Economics, 2026*

전체 연구 성과는 [논문](/publication/) 페이지에서 확인할 수 있습니다.

## 관련 자료

- [LanguageModel](/tag/languagemodel/) 태그가 붙은 연구 기록
- 대규모 언어 모델과 추론에 관한 [행사](/event/)와 토론

## 연구진

- [Donghun Lee](/author/donghun-lee/) — 연구책임자
- [Taehun Cha](/author/taehun-cha/) — 환각, 외삽, 표현
- [Suhyun Bae](/author/suhyun-bae/) — 질의응답에서의 환각
- [Hanyoung Kim](/author/hanyoung-kim/) — 밀집 문단 검색

전체 연구실 구성원은 [구성원](/people/) 페이지에서 확인할 수 있습니다.
