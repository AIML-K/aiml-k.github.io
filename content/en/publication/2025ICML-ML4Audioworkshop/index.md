---
title: "Broadband Ground Motion Synthesis by Diffusion Model with Minimal Condition"
authors:
- jaehyuklee
- jaeheunjung
- yeajinlee
- changhaejung
- admin
date: "2025-07-18T04:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*[AI Heard That! ICML 2025 Workshop on Machine Learning for Audio](https://icml.cc/virtual/2025/workshop/39973)*"
publication_short: "In *ICML 2025 ML4Audio Workshop*"

abstract: "Seismic waves produced by earthquakes are among the most powerful natural sounds on Earth. Generating realistic earthquake induced ground motion waveforms can contribute significantly to both scientific understanding and practical mitigation of seismic hazards. However, existing generative models tend to generate subpar waveforms. We present High-fidelity Earthquake Groundmotion Generation System (HEGGS) and demonstrate its superior performance using earthquakes from North American regions. HEGGS leverages the intrinsic structure of seismic data through an end-to-end differentiable pipeline consisting of a conditional latent diffusion model and a high-fidelity waveform reconstruction module. HEGGS is evaluated with a variety of metrics drawn from both the audio generation and seismology communities, including P/S phase arrival accuracy, envelope correlation, signal-to-noise ratio, and section plot visualization. By modeling seismic signals as structured environmental sound, HEGGS contributes to the broader field of machine learning for audio and offers a framework for modeling rare geophysical phenomena with generative methods."

# Summary. An optional shortened abstract.
summary: 'HEGGS is a high-fidelity generative system that produces realistic earthquake ground motion waveforms by modeling seismic signals as structured environmental sounds using a conditional latent diffusion model and waveform reconstruction pipeline.'

tags:
- Diffusion Model
- Audio
- Time Series

links:
# - name: PDF
#   url: https://arxiv.org/pdf/2506.01994
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
  caption: "Jaehyuk was explaining it -- **[Workshop Website](https://mlforaudioworkshop.github.io/)**"
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
