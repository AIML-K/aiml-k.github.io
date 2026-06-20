---
title: "Consequence-Guided Information Extraction for Predicting Central Bank Communication’s Effect"
authors:
- taehuncha
- admin
date: "2026-03-13T00:00:00Z"
doi: "10.1007/s10614-025-11284-6"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-06-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computational Economics*"
publication_short: "In *Comp. Econ.*"

abstract: |
  Predicting how financial markets respond to central bank communications is a key challenge in economics and finance. However, central bank communications are relatively rare events, making it challenging to apply standard data science methods. To address this issue, we focus on the characteristics of central bank communications, especially those from the FOMC, which typically consist of a short statement and a full-length minute. We introduce a consequence-guided information extraction system that utilizes state-of-the-art natural language processing and reinforcement learning techniques. Utilizing the pre-trained BERT prediction as a reward signal, we train a model to highlight the most influential text span in FOMC minutes. Then, we apply the Open Information Extraction system to obtain the structured information tuples from the highlighted span. By using it as a feature extractor, we achieve 77-86% accuracy in predicting the future direction of the various economic variables, compared to 43–66% accuracy from standard natural language processing methods such as bag-of-words, topic modeling, and fine-tuned BERT. Our study shows how a model with limited capacity can be improved when combined with a proper structure, especially in a data-scarce situation.

# Summary. An optional shortened abstract.
summary: |
  We introduce a novel consequence-guided information extraction framework, which extracts information from FOMC Communications relevant to the consequential Treasury yield curve shifts.
  
tags:
- FOMC Communication
- Yield Curve Shift
- Natural Language Processing

links:
# - name: PDF
#   url: https://github.com/cth127/cth127.github.io/blob/main/assets/pdf/2025/IEEE2025_Paper.pdf
# - name: Github
#   url: https://github.com/AIML-K/curse_of_smoothness
# - name: arXiv
#   url: https://arxiv.org/abs/2506.01994
- name: URL
  url: https://link.springer.com/article/10.1007/s10614-025-11284-6

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
  caption: "We harness RL towards domain-professional-level document understanding"
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
