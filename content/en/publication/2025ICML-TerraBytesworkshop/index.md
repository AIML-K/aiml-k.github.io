---
title: "Enhancing Generative Seismic Modeling via Proposed Paired Dataset Construction Method"
authors:
- jaehyuklee
- jaeheunjung
- hanyoungkim
- changhaejung
- admin
date: "2025-07-18T03:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*[ICML 2025 Workshop - TerraBytes: Towards global datasets and models for Earth Observation](https://icml.cc/virtual/2025/workshop/39951)*"
publication_short: "In *ICML 2025 TerraBytes Workshop*"

abstract: "Observation in Earth sciences encompasses not only what can be visually perceived but also what can be inferred through instrumental recordings. As such, seismic data, though not directly visible, fall within the domain of Earth Observation (EO). Earthquakes are inherently sparse events, and the limited availability of ground motion records and associated metadata poses significant challenges for predicting and responding to earthquake-induced hazards. Although numerous data augmentation techniques based on deep learning have been proposed, their effectiveness is often hindered by the scarcity of high-quality training data. We introduce a scalable framework for constructing training datasets from limited seismic observations, aimed at improving the performance of generative models. By training models on the paired dataset constructed using our proposed methodology, we demonstrate both quantitatively and qualitatively that the generated waveforms closely resemble real seismic signals, thereby validating the effectiveness of our approach."

# Summary. An optional shortened abstract.
summary: 'This work presents a scalable framework to generate high-quality training datasets from sparse seismic observations and an accompanying dataset from publicly available seismographic data source, enabling deep generative models to produce realistic earthquake waveforms despite limited data.'

tags:
- Seismology
- Dataset
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
  caption: "Jaeheun after the poster session -- **[Workshop Website](https://icml.cc/virtual/2025/workshop/39951)**"
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
