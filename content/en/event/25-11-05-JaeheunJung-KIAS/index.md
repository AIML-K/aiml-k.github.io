---
title: 'Bypass and Beyond: Extension–Contraction Strategies for Escaping Training Stagnation and Achieving Lossless Pruning'

event: AI and Natural Sciences Seminar @ KIAS
event_url: https://www.kias.re.kr/kias/activities/seminars/view.do?seqno=PGN1720250819-0004&menuNo=404003&schoolsCd=CP&centrspgmsCd=&sdate=2025-10-07&edate=&mjrcdnm=&searchCnd=1&searchWord=&pageIndex=1 
tags: ['seminar']

location: Room 7323, Korea Institute of Advanced Study
address:
  street: 85 Hoegi-ro
  city: Dongdaemun-gu, Seoul
  # region: CA
  postcode: '02455'
  country: South Korea

summary: 'How well can algebraically grounded methods tackle optimization and model compression challenges in deep learning?'
abstract: |
  What can be done when gradient-based training slows down near saddle points or suboptimal local minima? In this talk, I introduce Bypass, a principled method that actively guides optimization away from stationary regions by temporarily extending the model space, exploring new descent directions, and contracting back to the original architecture while preserving the learned function. This extension–contraction framework is algebraically grounded, easy to implement, and remarkably effective in improving both convergence and generalization. Building on the same algebraic foundation, I present Catalyst, a novel regularization technique for structured pruning. Catalyst identifies the geometry of pruning-invariant sets and extends the parameter space with a geometry-aware regularizer that enables lossless pruning with clear bifurcation dynamics. It offers a theoretically sound and empirically robust alternative to conventional magnitude-based pruning methods. Together, Bypass and Catalyst demonstrate how algebraic insights can lead to practical improvements in both training and compression. This talk will be of interest to researchers and practitioners working on optimization, model efficiency, and the geometry of deep learning.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-11-05T14:00:00+09:00'
date_end: '2025-11-05T15:00:00+09:00'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-10-11T00:00:00Z'

authors: 
  - jaeheunjung

# Is this a featured talk? (true/false)
featured: false

image:
  caption: '[**KIAS website link**](https://www.kias.re.kr/kias/activities/seminars/view.do?seqno=PGN1720250819-0004&menuNo=404003&schoolsCd=CP&centrspgmsCd=&sdate=2025-10-07&edate=&mjrcdnm=&searchCnd=1&searchWord=&pageIndex=1)'
#   focal_point: Right

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

links:
- name: Bypass
  url: https://aiml-k.github.io/publication/2024tnnls-jung-lee/
- name: Catalyst
  url: https://aiml-k.github.io/publication/2025icml-hildworkshop-catalyst/
- name: KIAS
  url: https://www.kias.re.kr/kias/activities/seminars/view.do?seqno=PGN1720250819-0004&menuNo=404003&schoolsCd=CP&centrspgmsCd=&sdate=2025-10-07&edate=&mjrcdnm=&searchCnd=1&searchWord=&pageIndex=1

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---

We are excited to see this talk! It is first event for AIML@K students to give a talk at KIAS.

<!-- 
Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://docs.hugoblox.com/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/writing-markdown-latex/).

Further event details, including page elements such as image galleries, can be added to the body of this page. -->
