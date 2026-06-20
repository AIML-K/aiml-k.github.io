---
title: 'Mathematical Foundations of AI'
summary: 'A rigorous account of why AI (mostly deep learning) works: training dynamics, pruning, feature learning, and the geometry of representations.'
date: 2026-06-20
---

## Overview

Modern AI systems work remarkably well, yet much of *why* they work from algorithmic and scientific perspective remains poorly understood.
This theme builds mathematical foundations for learning systems, treating optimization landscapes, training dynamics, and generalization as objects we can analyze rather than merely observe.

Our results span several fronts. 
From optimization side, we have studied how training can bypass stationary points, and also dabbled on fractional-order gradient methods. 
On deep learning model structure, we develop principled structural pruning — using bifurcation dynamics and projective geometry to decide what edges a network can lose without giving up its functional output. 
From the representation learning viewpoint, we analyzed feature learning as a form of covariance learning and study the emergent linear separability of features in a network's last layer. 
The throughline is turning empirical phenomena into theory that predicts behavior of deep learning models, guides better model design, and deeper understanding of why modern AI works.

## Core Questions

- What governs optimization dynamics, and when can training escape or bypass bad critical points?
- How much of a network is truly necessary, and how do we prune with provable structure rather than heuristics?
- How do useful features and clean geometric structure emerge in representations during training?

## Representative Work

- [Bypassing Stationary Points in Training Deep Learning Models](https://aiml-k.github.io/publication/2024tnnls-jung-lee/) — *IEEE TNNLS, 2024*
- [Curse of Smoothness in Functional Neural Networks](https://aiml-k.github.io/publication/2025spl-cha-lee/) — *IEEE Signal Processing Letters, 2025*
- [Catalyst: Structured Pruning with Robust Bifurcation Dynamics](https://aiml-k.github.io/publication/2025icml-hildworkshop-catalyst/) — *ICML 2025 HiLD Workshop*
- [Feature Learning as a Virtual Covariance Learning](https://aiml-k.github.io/publication/2025neurips-optworkshop/) — *NeurIPS 2025 OPT Workshop*
- [Emergent Linear Separability of Unseen Data Points in High-dimensional Last-Layer Feature Space](https://aiml-k.github.io/publication/2025icml-hildworkshop-linsep/) — *ICML 2025 HiLD Workshop*

See all work on the [Publications](/publication/) page.

## Related

- Logs tagged [Math4AI](/tag/math4ai/)
- [Events](/event/) and reading groups on learning theory

## People

- [Donghun Lee](/author/donghun-lee/) — Principal Investigator
- [Taehun Cha](/author/taehun-cha/) — feature learning, last-layer geometry
- [Jaeheun Jung](/author/jaeheun-jung/) — structured pruning, training dynamics
- [Bosung Jung](/author/bosung-jung/) — optimization, unlearning

See [People](/people/) for the full lab.
