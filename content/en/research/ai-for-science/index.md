---
title: 'AI for Science and Engineering'
summary: 'How we brought AI to seismology, materials, mechanism design, and biomedical imaging'
date: 2026-06-18
---

## Overview

<!-- Many problems in science and engineering are governed by equations that are expensive to solve and hard to invert. 
This theme develops machine-learning methods — especially operator learning and physics-aware generative models — that approximate these systems efficiently and generalize across conditions. -->

We believe that mathematics-guided AI application can cover a wide range of science and engineering fields.

We built neural operators that use both Laplace and Fourier representations for generalizable, efficient operator learning algorithm suitable for many PDE problems. 
In seismology we showed that AI can create high quality broadband ground motion and ambient seismic noise with diffusion and generative models.  
In material science and engineering we created AI-driven pipelines for estimating and optimizing mechanical properties of epoxy polymers. Also, transfer-learning across data-rich and data-poor battery imaging , and synthesize bar-link mechanism designs directly from specification. 
In biomedical field we developed multimodal models for knee-osteoarthritis diagnosis and automated measurement of
spinal parameters. 
Across all of these, the common thread is to abstractify the governing nature of the underlying problem.

## Core Questions

- How can neural operators learn solution maps for whole families of PDEs (often used in STEM problems), efficiently and with guarantees of generalization?
- How do we build generative models that respect physical structure and stay reliable even when facing out of distribution cases?
- How can effective surrogates be designed to replace or accelerate classical simulation in science and engineering?

## Representative Work

- [Best of Both Worlds: Bridging Laplace and Fourier for Generalizable and Efficient Operator Learning](https://aiml-k.github.io/publication/2025neurips-ml4psworkshop/) — *NeurIPS 2025 ML4PS Workshop*
- [Broadband Ground Motion Synthesis by Diffusion Model with Minimal Condition](https://aiml-k.github.io/publication/2025icml-jung-lee-jung-kim-jung-lee/) — *ICML 2025*
- [CLIP-KOA: Enhancing Knee Osteoarthritis Diagnosis with Multi-Modal Learning](https://aiml-k.github.io/publication/2025-clip-koa/) — *MICCAI 2025 LMID Workshop*
- [Re-experiment Smart: Enhancing Data-driven Prediction of Mechanical Properties of Epoxy Polymers](https://aiml-k.github.io/publication/2025arxiv-smart-reexperimentation/) — *preprint, 2025*
- [PPSD GAN: PPSD-informed Generative Model for Ambient Seismic Noise Synthesizing](https://aiml-k.github.io/publication/2024ieeegrsl-cho-ha-lim-han-kim-lee/) — *IEEE GRSL, 2024*

See all work on the [Publications](/publication/) page.

## Related

- Logs tagged [AI4Science](/tag/ai4science/)
- [Events](/event/) and collaborations with science and engineering partners

## People

- [Donghun Lee](/author/donghun-lee/) — Principal Investigator
- [Jeongun Ha](/author/jeongun-ha/) — operator learning
- [Jaehyuk Lee](/author/jaehyuk-lee/) — seismic and generative modeling
- [Jaeheun Jung](/author/jaeheun-jung/) — ground-motion synthesis, mechanism design
- [Hanyoung Kim](/author/hanyoung-kim/) — generative seismic modeling
- [Minseok Choi](/author/minseok-choi/) — Visiting Scholar (POSTECH), scientific machine learning

See [People](/people/) for the full lab.
