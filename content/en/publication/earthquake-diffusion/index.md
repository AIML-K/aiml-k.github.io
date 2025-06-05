---
title: "Broadband Ground Motion Synthesis by Diffusion Model with Minimal Condition"
authors:
- jaeheunjung
- jaehyuklee
- changhaejung
- hanyoungkim
- bosungjung
- admin
date: 2024-08-15
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 'Earthquakes are rare. Hence there is a fundamental call for reliable methods to generate realistic ground motion data for data-driven approaches in seismology. Recent GAN-based methods fall short of the call, as the methods either require special information such as geological traits or generate subpar waveforms that fail to satisfy seismological constraints such as phase arrival times. We propose a specialized Latent Diffusion Model (LDM) that reliably generates realistic waveforms after learning from real earthquake data with minimal conditions: location and magnitude. We also design a domain-specific training method that exploits the traits of earthquake dataset: multiple observed waveforms time-aligned and paired to each earthquake source that are tagged with seismological metadata comprised of earthquake magnitude, depth of focus, and the locations of epicenter and seismometers. We construct the time-aligned earthquake dataset using Southern California Earthquake Data Center (SCEDC) API, and train our model with the dataset and our proposed training method for performance evaluation. Our model surpasses all comparable data-driven methods in various test criteria not only from waveform generation domain but also from seismology such as phase arrival time, GMPE analysis, and spectrum analysis. Our result opens new future research directions for deep learning applications in seismology.'

# Summary. An optional shortened abstract.
summary: 'We present a novel seismic waveform generation method that shows professional-level realism from seismological criteria'

tags:
- Diffusion
- Generative model
# featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2412.17333
url_pdf: http://arxiv.org/pdf/2412.17333
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
  caption: 'Earthquakes are rare but correlated.'
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
