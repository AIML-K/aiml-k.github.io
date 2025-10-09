---
title: "IPPRO: Importance-based Pruning with PRojective Offset for Magnitude-indifferent Structural Pruning"
authors:
- jaeheunjung
- jaehyuklee
- yeajinlee
- admin
date: "2025-10-19T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*[ICCV 2025 Workshop - 2nd Workshop and Challenge on Unlearning and Model Editing (U&ME)](https://sites.google.com/view/u-and-me-workshop/)*"
publication_short: "In *ICCV 2025 U&ME workshop*"

abstract: "With the growth of demand on neural network compression methods, the structured pruning methods including importance-based approach are actively studied. The magnitude importance and many correlated modern importance criteria often limit the capacity of pruning decision, since the filters with larger magnitudes are not likely to be pruned if the smaller one didn't, even if it is redundant. In this paper, we propose a novel pruning strategy to challenge this dominating effect of magnitude and provide fair chance to each filter to be pruned, by placing it on projective space. After that, we observe the gradient descent movement whether the filters moves toward the origin or not, to measure how the filter is likely to be pruned. This measurement is used to construct PROscore, a novel importance score for IPPRO, a novel importance-based structured pruning with magnitude-indifference. Our evaluation results shows that the proposed importance criteria using the projective space achieves near-lossless pruning by reducing the performance drop in pruning, with promising performance after the finetuning. Our work debunks the ``size-matters'' myth in pruning and expands the frontier of importance-based pruning both theoretically and empirically."

# Summary. An optional shortened abstract.
summary: 'IPPRO is projective geometry-infused filter importace criteria for the structured pruning, ensuring the removal of the effect of magnitudes by embedding them into the projective space with temporal model extension. The PROscore, the proposed novel importance score, observes the gradient descent movement whether the filters moves toward the origin or not, to measure how the filter is likely to be pruned.'

tags:
- Structured pruning

links:

- name: PDF
  url: https://arxiv.org/pdf/2507.14171
# - name: Github
#   url: TODO
- name: arXiv
  url: https://arxiv.org/abs/2507.14171

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
  caption: "2nd Workshop and Challenge on Unlearning and Model Editing (U&ME) **[Website](https://sites.google.com/view/u-and-me-workshop/)**"
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
