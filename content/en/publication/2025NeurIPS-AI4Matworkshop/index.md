---
title: "Bridging data-rich and data-poor domains on Lithium-Ion Battery via Scanning Electron Microscopic data through Convolutional Neural Network Transfer Learning"
authors:
- Haein Jeon
- Bo-Yeong Kang
- admin
- Jimin Oh
date: "2025-09-20T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*[NeurIPS 2025 Workshop - AI4Mat: AI for Accelerated Materials Design](https://sites.google.com/view/ai4mat/home)*"
publication_short: "In *NeurIPS 2025 AI4Mat Workshop*"

abstract: |
  Scanning Electron Microscopy (SEM) imaging offers a powerful yet underutilized tool for diagnosing the state of lithium-ion battery cathodes. However, deep learning models for SEM-based state prediction often suffer from limited training data and domain shifts, particularly when functional electrolyte additives are introduced. In this work, we propose a two-stage transfer learning framework using an EfficientNet-B0 backbone to robustly classify cathode SEM images across nine classes defined by material composition (NCM333, NCM622, NCM811) and aging state (pristine, formation-aged, 100 cycles). Our method first pretrains the model on a data-rich source domain of additive-free samples, then fine-tunes it on a smaller target domain containing additive-induced variations. To address class imbalance, we compare targeted oversampling and weighted loss strategies. Experimental results show that our framework consistently outperforms pretraining-only and fine-tuning-only baselines, achieving over 0.98 accuracy and F1 scores for domain-shifted classes. Qualitative analysis using Grad-CAM further confirms that the model captures physically meaningful features, such as particle cracking and boundary degradation. These findings demonstrate the effectiveness of transfer learning in reducing data scarcity and domain shift in SEM-based battery diagnostics, providing a practical solution for automated analysis in next-generation battery development.

# Summary. An optional shortened abstract.
summary: |
  We propose a transfer learning framework using EfficientNet-B0 to robustly classify SEM images of lithium-ion battery cathodes across compositions and aging states, effectively handling data scarcity and domain shift from electrolyte additives.

tags:
- Material Discovery
- Transfer Learning
- Chemical Engineering

links:
- name: PDF
  url: https://pir.sh/Bme1VZQ1Xy
# - name: Github
#   url: TODO
# - name: arXiv
#   url: https://arxiv.org/abs/2506.01994
- name: openreview
  url: https://openreview.net/forum?id=j3aOU8Ahue&noteId=NLXTlvNSX0

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
  caption: "AI Can See Through These SEM Images -- **[NeurIPS 2025 AI4Mat Workshop](https://sites.google.com/view/ai4mat/home)**"
  # caption: "NeurIPS 2025 Workshop - AI4Mat: AI for Accelerated Materials Design: **[Website](https://sites.google.com/view/ai4mat/home)**"
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
