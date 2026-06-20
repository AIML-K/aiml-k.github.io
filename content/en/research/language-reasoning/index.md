---
title: 'Language, Reasoning, and Knowledge'
summary: 'Understanding and improving language models'
date: 2026-06-17
---

## Overview

Language models (LMs) have become general-purpose reasoning engines, yet they reason unevenly and sometimes state confident falsehoods. 
This theme studies the internal representations of LMs and how they affect the behavior of LM-based system, e.g. knowledge retrieval, reasoning, and self-assessment, to name a few.

Hallucination is a famous example: we have shown that pre-trained language models return distinguishable probability distributions on unfaithfully hallucinated text, and we have mapped the types of hallucination that arise in question answering along with the limits of the metrics used to detect them. 
We also probe how far models can extrapolate beyond their training distribution — for instance, into chemical domains — and we develop better representations and retrieval, from sentence-level topic models to aspect-based dense passage retrieval. 
Bringing in reinforcement learning to control the behavior of LMs (akin to how harnessing agents work nowadays) to high-stakes real-world text, such as extracting the consequences of central bank communications.

## Core Questions

- What causes hallucination, and how can it be detected, measured, and reduced towards trustable and explainable language models?
- How well can/do language models extrapolate beyond their training distribution?
- How should internal knowledge in LMs be represented and retrieved so that reasoning over text becomes more reliable?

## Representative Work

- [Pre-trained Language Models Return Distinguishable Probability Distributions to Unfaithfully Hallucinated Texts](https://aiml-k.github.io/publication/2024emnlp-cha-lee/) — *EMNLP 2024 Findings*
- [SentenceLDA: Discriminative and Robust Document Representation with Sentence Level Topic Model](https://aiml-k.github.io/publication/cha-lee-2024-sentencelda/) — *EACL 2024*
- [Evaluating Extrapolation Ability of Large Language Model in Chemical Domain](https://aiml-k.github.io/publication/2024acl-cha-lee/) — *ACL 2024 Workshop*
- [Consequence-Guided Information Extraction for Predicting Central Bank Communication's Effect](https://aiml-k.github.io/publication/2026ce-cha-lee/) — *Computational Economics, 2026*

See all work on the [Publications](/publication/) page.

## Related

- Logs tagged [LanguageModel](/tag/languagemodel/)
- [Events](/event/) and discussions on LLMs and reasoning

## People

- [Donghun Lee](/author/donghun-lee/) — Principal Investigator
- [Taehun Cha](/author/taehun-cha/) — hallucination, extrapolation, representation
- [Suhyun Bae](/author/suhyun-bae/) — hallucination in question answering
- [Hanyoung Kim](/author/hanyoung-kim/) — dense passage retrieval

See [People](/people/) for the full lab.
