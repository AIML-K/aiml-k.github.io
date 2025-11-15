---
title: "Curse of Smoothness in Functional Neural Networks"
authors:
- taehuncha
- admin
date: "2025-11-10T00:00:00Z"
doi: "10.1109/LSP.2025.3624683"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-11-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Signal Processing Letters*"
publication_short: "In *IEEE SPL*"

abstract: |
Functional neural networks (FNNs) have emerged as powerful tools for modeling complex relationships in functional data, leveraging the flexibility of deep learning to capture non-linear patterns.
However, most components of FNNs are directly borrowed from standard deep neural networks, such as element-wise non-linear activation functions and gradient-based optimization strategies.
In this study, we investigate how the functional nature of FNNs affects gradient-based optimization.
Analogous to the well-known vanishing gradient problem, we theoretically show that the smoothness of the hidden state function bounds the weight gradient norm, a phenomenon we call the \textit{curse of smoothness}.
Empirically, we demonstrate that FNN optimization becomes significantly more difficult as model depth increases, compared to conventional deep neural networks.
In particular, we verify that gradients in FNNs vanish in deeper layers as the hidden state functions become smoother.
These findings suggest that applying standard deep learning techniques to functional data without accounting for the unique properties of functional data can lead to misleading or suboptimal results.Functional neural networks (FNNs) have emerged as powerful tools for modeling complex relationships in functional data, leveraging the flexibility of deep learning to capture non-linear patterns.
However, most components of FNNs are directly borrowed from standard deep neural networks, such as element-wise non-linear activation functions and gradient-based optimization strategies.
In this study, we investigate how the functional nature of FNNs affects gradient-based optimization.
Analogous to the well-known vanishing gradient problem, we theoretically show that the smoothness of the hidden state function bounds the weight gradient norm, a phenomenon we call the \textit{curse of smoothness}.
Empirically, we demonstrate that FNN optimization becomes significantly more difficult as model depth increases, compared to conventional deep neural networks.
In particular, we verify that gradients in FNNs vanish in deeper layers as the hidden state functions become smoother.
These findings suggest that applying standard deep learning techniques to functional data without accounting for the unique properties of functional data can lead to misleading or suboptimal results.

# Summary. An optional shortened abstract.
summary: |
This study reveals that functional neural networks (FNNs) suffer from a “curse of smoothness,” where the smoothness of hidden state functions causes gradient vanishing and hampers optimization in deep architectures, highlighting the limitations of directly applying standard deep learning methods to functional data.

tags:
- Functional Neural Network
- Vanishing Gradient

links:
- name: PDF
  url: https://github.com/cth127/cth127.github.io/blob/main/assets/pdf/2025/IEEE2025_Paper.pdf
- name: Github
  url: https://github.com/AIML-K/curse_of_smoothness
# - name: arXiv
#   url: https://arxiv.org/abs/2506.01994
- name: URL
  url: https://ieeexplore.ieee.org/document/11215882/

# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: "NeurIPS 2025 Workshop - OPT: Optimization for Machine Learning: **[Website](https://opt-ml.org/)**"
#   focal_point: ""
#   preview_only: false

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
