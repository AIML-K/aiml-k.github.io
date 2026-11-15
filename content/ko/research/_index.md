---
title: '연구'
date: 2026-06-10
type: landing

sections:
  # ---------- Intro ----------
  - block: markdown
    content:
      title: 'AIML@K의 연구'
      text: |
        우리의 출발점은 단순하면서도 도전적입니다. AI 발전의 가장 깊은 바탕에는 수학이 있다는 것입니다. 
        우리는 수학*으로* AI의 지평을 넓히고, 다시 AI를 활용하여 수학과 과학의 최전선을 확장합니다.

        심층 신경망이 학습하는 이유에 관한 이론, 과학 방정식을 푸는 학습 가능한 연산자, 심층 생성 모델 분석 등 우리가 수행하는 모든 연구에는 이러한 양방향 교류가 흐르고 있습니다. 
        아래의 연구 주제는 서로를 가르는 경계가 아닙니다. 대부분의 프로젝트는 여러 주제에 걸쳐 있습니다. 
        각 주제에서는 자세한 설명과 관련 논문 등을 확인할 수 있습니다.
    design:
      columns: '1'
      # A light tinted band to separate the intro from the cards.
      # background:
      #   color: '#f7f8fa'
      spacing:
        padding: ['40px', '0', '20px', '0']

  # ---------- Research themes ----------
  # NOTE: This is a hand-written grid of links so the page is guaranteed to
  # build with no dependency on per-page images or tags. Once each subpage has
  # a `featured` image, you can swap this for an auto-generated card grid:
  
  - block: collection
    content:
      title: 연구 주제
      filters:
        folders: [research]
    design:
      view: card
      columns: '2'
      spacing:
        padding: ['10px', '0', '20px', '0']

  # - block: markdown
  #   content:
  #     title: 'Research Themes'
  #     text: |
  #       #### [AI for Mathematics](./ai-for-math/)
  #       Using AI to explore, conjecture, formalize, and assist mathematical
  #       reasoning — from autoformalization to computational discovery.

  #       #### [Mathematical Foundations of AI](./math-for-ai/)
  #       The theory behind learning: optimization, generalization, neural
  #       dynamics, and the phenomena (feature learning, neural collapse,
  #       grokking) that explain how models behave.

  #       #### [AI for Science and Engineering](./ai-for-science/)
  #       Operator learning and scientific machine learning for PDEs, seismic and
  #       ground-motion modeling, materials, batteries, and biomedical imaging.

  #       #### [Language, Reasoning, and Knowledge](./language-reasoning/)
  #       Language models and their limits: reasoning, retrieval, representation,
  #       hallucination, and extrapolation.

  #       #### [Applied AI Systems](./applied-ai/)
  #       Turning research into practice — education tools, recommendation,
  #       chatbots, and dependable ML systems.
  #   design:
  #     columns: '1'
  #     spacing:
  #       padding: ['10px', '0', '20px', '0']

  # # ---------- Featured publications ----------
  # # Mirrors the homepage "Select Publications" block. Shows items with
  # # `featured: true` in their publication front matter.
  # - block: collection
  #   content:
  #     title: Featured Publications
  #     text: ''
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       featured_only: true
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: publication
  #   design:
  #     columns: '1'
  #     view: showcase
  #     flip_alt_rows: true

  # # ---------- Recent research activity ----------
  # # Mirrors the logs page portfolio block. Pulls from the `log` folder and
  # # offers tag filters that already exist in your logs taxonomy.
  # - block: portfolio
  #   id: research-activity
  #   content:
  #     title: Recent Research Activity
  #     subtitle: 'From the AIML@K logs'
  #     filters:
  #       folders:
  #         - log
  #       tags: []
  #       exclude_tags: []
  #     sort_by: 'Date'
  #     sort_ascending: false
  #     default_button_index: 0
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: AI4Math
  #         tag: AI4Math
  #       - name: Math4AI
  #         tag: Math4AI
  #       - name: LM
  #         tag: LanguageModel
  #       - name: AI4Sci
  #         tag: AI4Science
  #       - name: Applied
  #         tag: Application
  #   design:
  #     columns: '1'
  #     view: compact
---
