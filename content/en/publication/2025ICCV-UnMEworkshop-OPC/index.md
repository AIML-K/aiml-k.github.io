---
title: "OPC: One-Point-Contraction Unlearning Toward Deep Feature Forgetting"
authors:
- jaeheunjung
- bosungjung
- suhyunbae
- admin
date: "2025-07-18T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "*[ICCV 2025 Workshop - 2nd Workshop and Challenge on Unlearning and Model Editing (U&ME)](https://sites.google.com/view/u-and-me-workshop/)*"
publication_short: "In *ICCV 2025 U&ME workshop*"

abstract: 'Machine unlearning seeks to remove the influence of particular data or class from trained models to meet privacy, legal, or ethical requirements. Existing unlearning methods tend to forget shallowly: phenomenon of an unlearned model pretend to forget by adjusting only the model response, while its internal representations retain information sufficiently to restore the forgotten data or behavior. We empirically confirm the widespread shallowness by reverting the forgetting effect of various unlearning methods via training-free performance recovery attack and gradient-inversion-based data reconstruction attack. To address this vulnerability fundamentally, we define a theoretical criterion of "deep forgetting'' based on one-point-contraction of feature representations of data to forget. We also propose an efficient approximation algorithm, and use it to construct a novel general-purpose unlearning algorithm: One-Point-Contraction (OPC). Empirical evaluations on image classification unlearning benchmarks show that OPC achieves not only effective unlearning performance but also superior resilience against both performance recovery attack and gradient-inversion attack. The distinctive unlearning performance of OPC arises from the deep feature forgetting enforced by its theoretical foundation, and recaps the need for improved robustness of machine unlearning methods.'

# Summary. An optional shortened abstract.
summary: 'We identify a major weakness in existing machine unlearning methods—namely, their tendency to forget only at the output level while retaining internal representations that allow for data recovery. To address this, we introduce a new theoretical framework called "deep forgetting" based on one-point contraction and propose a practical algorithm, One-Point-Contraction (OPC), which shows strong resilience against known attacks and outperforms existing methods on unlearning benchmarks.'

tags:
- Machine unlearning

links:

- name: PDF
  url: https://arxiv.org/pdf/2507.07754
# - name: Github
#   url: TODO
- name: arXiv
  url: https://arxiv.org/abs/2507.07754

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
  caption: "Recovery attack recovers almost all unlearned models and OPC shows the resistance"
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
