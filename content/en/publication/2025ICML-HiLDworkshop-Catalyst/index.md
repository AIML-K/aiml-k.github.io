---
title: "Catalyst: Structured Pruning with Robust Bifurcation Dynamics"
authors:
- jaeheunjung
- admin
date: "2025-07-18T01:00:00Z"
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

abstract: 'Structured pruning reduces the computational cost of neural networks by removing filters, but conventional regularizers such as L1 or Group Lasso exhibit strong magnitude bias and unstable decision boundaries, suggesting suboptimal pruning dynamics. In this work, we revisit pruning through the lens of optimization, geometry and learning dynamics. We first characterize the precise algebraic conditions under which pruning preserves model outputs, then use this insight to design Catalyst, a novel regularizer defined in an extended parameter space with auxiliary variables. Catalyst reshapes the loss landscape to promote emergent bifurcation dynamics between filters to be pruned or preserved, ensuring magnitude-invariant, fair, and robust pruning decisions. Our formulation highlights how high-dimensional learning dynamics can be achieved via a well-founded regularizer for pruning. Empirically, the Catalyst pruning algorithm consistently outperforms standard approaches, demonstrating both its theoretical soundness and practical effectiveness.'

# Summary. An optional shortened abstract.
summary: 'Catalyst is a novel pruning regularizer that leverages auxiliary variables and optimization geometry to induce emergent bifurcation dynamics, enabling fair, magnitude-invariant, and robust filter pruning that consistently outperforms conventional methods both theoretically and empirically.'

tags:
- Pruning
- Bifurcation Dynamics

links:

- name: PDF
  url: https://openreview.net/pdf?id=v0l6QS3Umt
- name: openreview
  url: https://openreview.net/forum?id=v0l6QS3Umt
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
  caption: "Catalyst pruning induces robust bifurcation - to-prune or not-to-prune"
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
