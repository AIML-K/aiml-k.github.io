---
title: "Best of Both Worlds: Bridging Laplace and Fourier for Generalizable and Efficient Operator Learning"
authors:
- jeongunha
- admin
date: "2025-09-23T16:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-23T16:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*[NeurIPS 2025 Workshop - ML4PS: Machine Learning and the Physical Sciences](https://ml4physicalsciences.github.io/2025/)*"
publication_short: "In *NeurIPS 2025 ML4PS Workshop*"

abstract: |
  We introduce Laplace–Fourier Neural Operator (LFNO), a novel operator learning model that bridges the strengths of Laplace Neural Operators (LNO) and Fourier Neural Operators (FNO). Building on LNO’s ability to capture transient and steady-state responses, we augment LNO's steady-state component with a Fourier integral operator and a learnable nonlinearity, the key essence of FNO's resolution invariance and efficiency. This integration enables LFNO to efficiently represent both the transient and steady-state responses, thereby enhancing LFNO's ability to model complex dynamics across ODEs and PDEs. We demonstrate LFNO's effectiveness on solving ODE (Duffing equation) and PDE (Euler-Bernoulli beam) benchmarks, in comparison to LNO. These results suggest LFNO as a versatile and generalizable neural operator framework for modeling dynamical systems in both linear and nonlinear regimes, offering a principled step toward ML-powered scalable methods for physical sciences.

# Summary. An optional shortened abstract.
summary: |
  We propose a unified framework combining LNO and FNO.

tags:
- Operator Learning
- Neural Operator
- Fourier Integral Operator

links:
# - name: PDF
#   url: https://arxiv.org/pdf/2506.01994
# - name: Github
#   url: TODO
# - name: arXiv
#   url: https://arxiv.org/abs/2506.01994
- name: openreview
  url: https://openreview.net/forum?id=zxzBsHDioz&noteId=2jddcHYjXJ

# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "NeurIPS 2025 Workshop - ML4PS: Machine Learning and the Physical Sciences: **[Website](https://ml4physicalsciences.github.io/2025/)**"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
