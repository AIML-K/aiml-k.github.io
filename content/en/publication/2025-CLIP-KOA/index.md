---
title: "CLIP-KOA: Enhancing Knee Osteoarthritis Diagnosis with Multi-Modal Learning and Symmetry-Aware Loss Functions"
authors:
- yejinjeong
- admin
date: "2025-04-30T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*[Learning with Longitudinal Medical Images and Data](https://ldtm-miccai.github.io/lmid2025/#call-for-papers)*"
publication_short: "In *MICCAI 2025 LMID workshop*"

abstract: 'Knee osteoarthritis (KOA) is a universal chronic musculoskeletal disorders worldwide, making early diagnosis crucial. Currently, the Kellgren and Lawrence (KL) grading system is widely used to assess KOA severity. However, its high inter-observer variability and subjectivity hinder diagnostic consistency. To address these limitations, automated diagnostic techniques using deep learning have been actively explored in recent years. In this study, we propose a CLIP-based framework (CLIP-KOA) to enhance the consistency and reliability of KOA grade prediction. To achieve this, we introduce a learning approach that integrates image and text information and incorporate Symmetry Loss and Consistency Loss to ensure prediction consistency between the original and flipped images. CLIP-KOA achieves state-of-the-art accuracy of 71.86\% on KOA severity prediction task, and ablation studies show that CLIP-KOA has 2.36\% improvement in accuracy over the standard CLIP model due to our contribution. This study shows a novel direction for data-driven medical prediction not only to improve reliability of fine-grained diagnosis and but also to explore multimodal methods for medical image analysis.'


# Summary. An optional shortened abstract.
summary: 'We propose CLIP-KOA, a CLIP-based framework to enhance the consistency and reliability of knee osteoarthritis (KOA) grade prediction.'

tags:
- Medical
- Multimodal AI

links:

- name: PDF
  url: https://arxiv.org/pdf/2504.19443
# - name: Github
#   url: TODO
- name: arXiv
  url: https://arxiv.org/abs/2504.19443

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
  caption: 'CLIP-KOA proposes flip-invariant multimodal loss function for knee osteoarthritis (KOA)'
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
