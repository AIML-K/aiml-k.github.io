---
title: "Feature Learning as a Virtual Covariance Learning"
authors:
- taehuncha
- admin
date: "2025-09-23T03:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-23T03:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*[NeurIPS 2025 Workshop - OPT: Optimization for Machine Learning](https://opt-ml.org/)*"
publication_short: "In *NeurIPS 2025 OPT Workshop*"

abstract: "
  Feature learning is central to the success of neural networks but remains poorly understood.
  Recent work proposed the Neural Feature Ansatz, which highlights alignment between learned features and $\nabla_x f$, but does not explicitly explain why and how feature learning dynamics occur.
  To address this, we introduce a novel concept, **virtual update**, a stochastic gradient descent (SGD) step applied to inputs and hidden states rather than parameters, i.e., $x - \\gamma \\nabla\\_x \\mathcal{L}$ and $h - \\gamma \\nabla\\_h \\mathcal{L}$.
  We theoretically show that SGD aligns network weights with the covariance structure of the virtual update.
  This does not result in disagreement with an actual update, as the actually updated input does not deviate far from the virtually updated input.
  Building on this insight, we propose the **virtual covariance learning** algorithm, which directly obtains the weight matrix that achieves the desired covariance structure.
  This algorithm efficiently learns effective weights within one or two epochs--whereas SGD requires $10$–$20$ epochs--with low variance and no overfitting.
  "

# Summary. An optional shortened abstract.
summary: |
  We introduce a novel concept, virtual update, to better understand the feature learning mechanism and propose a virtual covariance learning algorithm that greatly accelerates feature learning.

tags:
- Feature Learning
- Stochastic Gradient Descent

links:
# - name: PDF
#   url: https://arxiv.org/pdf/2506.01994
# - name: Github
#   url: TODO
# - name: arXiv
#   url: https://arxiv.org/abs/2506.01994
- name: openreview
  url: https://openreview.net/forum?id=hvw5FJoaWB

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
  caption: "NeurIPS 2025 Workshop - OPT: Optimization for Machine Learning: **[Website](https://opt-ml.org/)**"
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
