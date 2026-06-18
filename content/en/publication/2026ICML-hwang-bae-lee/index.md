---
title: "Prime Fourier Embeddings: A Principled Basis for Modular Arithmetic"
authors:
- hyunsanghwang
- suhyunbae
- admin
date: "2026-06-17T04:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-06-18T04:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*[ICML 2026 Workshop - 3rd AI for Math Workshop](https://ai4math2026.github.io/)*"
publication_short: "In *ICML 2026 MathAI AI for Math Workshop*"

abstract: |
  Numbers have algebraic structure that standard neural embeddings often fail to expose. We introduce Prime Fourier Embeddings (PFE), which encode integers as prime-indexed (cos, sin) pairs derived from the harmonic analysis of Q, providing a pre-structured representation in which modular arithmetic reduces to selecting the relevant prime channel rather than discovering algebraic structure from scratch. We prove that any linear map equivariant with respect to the product group action on PFE must be block-diagonal with one independent block per prime — a consequence of Schur's lemma applied to the resulting character decomposition. For square-free composite moduli, the Chinese Remainder Theorem predicts which prime channels are task-relevant. Both predictions are confirmed empirically: ablation studies show specialization ratios exceeding 500× between task-relevant and task-irrelevant channels, with perfect in-distribution test accuracy across all square-free composite moduli tested.

# Summary. An optional shortened abstract.
summary: |
  We present Prime Fourier Embeddings (PFE), a deterministic, non-trainable encoding that maps integers to prime-indexed (cos, sin) pairs across digit depths.

tags:
- [AI4Math, Number Representation]

links:
# - name: PDF
#   url: https://arxiv.org/pdf/2506.01994
# - name: Github
#   url: TODO
# - name: arXiv
#   url: https://arxiv.org/abs/2506.01994
- name: openreview
  url: https://openreview.net/forum?id=SmSv0S3bUW


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
  caption: "ICML 2026 Workshop - 3rd AI for Math Workshop: **[Website](https://ai4math2026.github.io/)**"
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
