---
title: "Emergent Linear Separability of Unseen Data Points in High-dimensional Last-Layer Feature Space"
authors:
- taehuncha
- admin
date: "2025-07-18T02:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*[ICML 2025 Workshop - 3rd Workshop on High-dimensional Learning Dynamics (HiLD)](https://icml.cc/virtual/2025/workshop/39953)*"
publication_short: "In *ICML 2025 HiLD Workshop*"

abstract: "In this work, we investigate the emergence of linear separability for unseen data points in the high-dimensional last-layer feature space of deep neural networks. Through empirical analysis, we observe that, after training, in-distribution and out-of-distribution samples become linearly separable in the last-layer feature space when the hidden dimension is sufficiently high—even in regimes where the input data itself is not. We leverage these observations for the task of uncertainty quantification. By connecting our findings to classical support vector machine margin theory, we theoretically show that the separating hyperplane exhibits a higher weight norm when facing in-distribution data points. This work highlights linear separability as a fundamental and analyzable property of trained deep neural networks' representations, offering a geometric perspective on the practical uncertainty quantification task in neural networks."

# Summary. An optional shortened abstract.
summary: 'We propose a simple geometric uncertainty measure based on linear separability in the last-layer feature space of deep networks, offering a theoretically grounded and non-probabilistic approach to uncertainty quantification.'

tags:
- Linear Separability
- Uncertainty Quantification

links:
- name: PDF
  url: papers/ICML2025_HiLD_Cha_Lee.pdf
# - name: Github
#   url: TODO
# - name: arXiv
#   url: https://arxiv.org/abs/2506.01994

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
  caption: "Out-of-dist data: linearly separable in last layer embedding?" 
  # caption: "3rd Workshop on High-dimensional Learning Dynamics (HiLD): **[Website](https://sites.google.com/view/hidimlearning/home)**"
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
