---
title: 'ABC3: Active Bayesian Causal Inference with Cohn Criteria in Randomized Experiments'
authors:
- taehuncha
- admin

date: '2025-02-25'
publishDate: '2024-12-10T00:00:00.000001Z'
publication_types:
- paper-conference
publication: '*In The 39th Annual AAAI Conference on Artificial Intelligence*'
publication_short: 'In *AAAI 2025*'

abstract: In causal inference, a randomized experiment is a de facto method to overcome various theoretical issues in observational study. However, the experimental design requires expensive costs, so an efficient experimental design is necessary. We propose ABC3, a Bayesian active learning policy for causal inference. We show a policy minimizing an estimation error on conditional average treatment effect is equivalent to minimizing an integrated posterior variance, similar to Cohn criteria. We theoretically prove ABC3 also minimizes an imbalance between the treatment and control groups and the type 1 error probability. Imbalance-minimizing characteristic is especially notable as several works have emphasized the importance of achieving balance. Through extensive experiments on real-world data sets, ABC3 achieves the highest efficiency, while empirically showing the theoretical results hold.

summary: |
  We present ABC3, a Bayesian active learning algorithm for learning conditional average treatment effect in causal inference setting. Theoretical analysis links ABC3 and maximum mean discrepancy (MMD), showing the importance of balanced sampling in accurate estimation.

links:
- name: AAAI
  url: 'https://ojs.aaai.org/index.php/AAAI/article/view/34880'
- name: poster
  url: 'posters/AAAI2025_ABC3_poster.pdf'
- name: arXiv
  url: 'https://arxiv.org/abs/2412.11104'


doi: '10.1609/aaai.v39i25.34880'

url_pdf: 'uploads/files/2025/AAAI2025-cha-lee.pdf'

image:
  caption: 'Active learning can be even more efficient with ABC3'
  focal_point: ""
  preview_only: false

tags: ['Causal Inference','Active Learning','Gaussian Process']

featured: true
---
