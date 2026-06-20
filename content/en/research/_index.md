---
title: 'Research'
date: 2026-06-10
type: landing

sections:
  # ---------- Intro ----------
  - block: markdown
    content:
      title: 'Research at AIML@K'
      text: |
        AIML@K is the AI + Math Lab in the Department of Mathematics at Korea 
        University, and the spearhead of the department's research in artificial
        intelligence. Our premise is simple and ambitious: the deepest progress
        in AI is mathematical. We expand the frontier of AI *with* mathematics,
        and we use AI in turn to extend mathematics and frontiers in science.

        That two-way exchange runs through everything we do — such as the theory of
        why deep networks learn, learnable operators that solve scientific equations,
        analysis of deep generative models and more. 

        The themes below are entry points, not walls — most projects sit
        across several of them. Each links to a fuller description and to the
        publications, logs, and events behind it.
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
      title: Research Themes
      filters:
        folders: [research]
    design:
      view: card
      columns: '2'
      spacing:
        padding: ['10px', '0', '20px', '0']

  - block: markdown
    content:
      title: 'Research Themes'
      text: |
        #### [AI for Mathematics](./ai-for-math/)
        Using AI to explore, conjecture, formalize, and assist mathematical
        reasoning — from autoformalization to computational discovery.

        #### [Mathematical Foundations of AI](./math-for-ai/)
        The theory behind learning: optimization, generalization, neural
        dynamics, and the phenomena (feature learning, neural collapse,
        grokking) that explain how models behave.

        #### [AI for Science and Engineering](./ai-for-science/)
        Operator learning and scientific machine learning for PDEs, seismic and
        ground-motion modeling, materials, batteries, and biomedical imaging.

        #### [Language, Reasoning, and Knowledge](./language-reasoning/)
        Language models and their limits: reasoning, retrieval, representation,
        hallucination, and extrapolation.

        #### [Applied AI Systems](./applied-ai/)
        Turning research into practice — education tools, recommendation,
        chatbots, and dependable ML systems.
    design:
      columns: '1'
      spacing:
        padding: ['10px', '0', '20px', '0']

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
