---
# Display name
title: Suhyun Bae
type: landing

# Full Name (for SEO)
first_name: Suhyun
last_name: Bae

# Is this the primary user of the site?
superuser: false

# Role/position
role: M.S. in Mathematics

# Organizations/Affiliations
organizations:
  - name: Korea University
    url: 'http://www.korea.edu'

# Short bio (displayed in user profile at end of posts)
bio: The cake is not a lie!

interests:
- Algebraic Representation Learning
- Hallucination Mitigation & Detection
- Trustworthy & Reliable AI


education:
  courses:
    # - course: Ph.D. in Computer Science
    #   institution: Princeton University
    #   year: 2019
    - course: M.S. in Mathematics(Mathematical Data Science)
      institution: Korea University
      year: 2026
    - course: B.S. in Mathematics
      institution: Korea University
      year: 2024

# Social/Academic Networking
# For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: 'mailto:baeshstar@korea.ac.kr'
  - icon: github
    icon_pack: fab
    link: https://github.com/Ricepunchb
  - icon: linkedin
    icon_pack: fab
    link: https://www.linkedin.com/in/suhyun-bae-869043286
  - icon: cv
    icon_pack: ai
    link: cv/CV_SuhyunBae_20260623.pdf
  # - icon: twitter
  #   icon_pack: fab
  #   link: https://twitter.com/GeorgeCushen
  # - icon: google-scholar
  #   icon_pack: ai
  #   link: https://scholar.google.com/citations?user=I-XhaYgAAAAJ
  # - icon: orcid
  #   icon_pack: ai
  #   link: https://orcid.org/0009-0002-7449-5336


# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ''

# Highlight the author in author lists? (true/false)
highlight_name: false

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
  - Alumni


sections:
  - block: about.biography
    id: about
    content:
      username: suhyunbae

  - block: markdown
    content:
      title: Research Focus
      # subtitle: What I am currently focusing on in my research
      text: My ultimate goal is to research and develop next-generation AI models that are verifiable and reliable, fully grounded in mathematical rigor.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

  - block: markdown
    content:
      title: Research Goal
      # subtitle: What I aim to achieve with my research
      text: My ultimate goal is to develop highly reliable and verifiable AI models built upon solid mathematical foundations.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

  - block: experience
    content:
      title: Research Experience
      # subtitle: The key research achievements and experiences
      date_format: Jan 2006
      items:
        - title: 'Core AI R&D: Algebraic Number Theory for LLM Reasoning'
          # company: University X
          date_start: '2025-03-01'
          date_end: ''
          description: |
            - **Phase 1 (2025.07 - 2025.12) | *Numbers Already Carry Their Own Embeddings***<br>Proposed a novel embedding mechanism leveraging the Adele Ring and $p$-adic algebraic structures to resolve the preservation loss of numerical semantics in conventional LLM tokenizers. This work was accepted at the NeurIPS 2025 Workshop MATHAI.
            - **Phase 2 (2026.01 - 2026.05) | *Prime Fourier Embeddings: A Principled Basis for Modular Arithmetic***<br>Introduced the concept of Pontryagin Dual Space to construct a mapping pipeline that projects numbers onto $(\cos, \sin)$ on the complex plane, experimentally demonstrating its intrinsic efficiency in learning the Chinese Remainder Theorem (CRT). This work was accepted at the ICML 2026 Workshop AI4MATH.
            - **Phase 3 (2026.05 - PRESENT)**<br>Currently developing a highly practical, production-ready embedding module that can be seamlessly integrated into arbitrary LLMs as a plug-in component.

        - title: Internship at SK Magic
          date_start: '2024-07-01'
          date_end: '2025-01-01'
          description: Served as a Data Scientist Intern within the AI Business Development Team at SK Magic. Spearheaded the R&D and design of a hybrid optimization algorithm for the optimal spatial placement of auxiliary air quality sensors paired with the autonomous driving air purifier (NAMUHX).

        - title: KCC 2024 and Hallucination
          date_start: '2024-03-01'
          date_end: '2024-06-01'
          description: Classified hallucination phenomena in Question-Answering (QA) generation tasks into five fine-grained taxonomies. Evaluated the capabilities and limitations of standard natural language metrics (BLEU, METEOR, ROUGE) in detecting specific types of hallucinations. This work was published at KCC 2024.

        - title: AI Grand Challenge 2023
          date_start: '2023-07-01'
          date_end: '2023-12-01'
          description: Built a robust synthetic dataset generation and refinement pipeline for multi-answer question answering tasks utilizing the OpenAI API (GPT-3.5), directly contributing to the lab consortium's final 7th place achievement.

    design:
      columns: '2'

---
<!-- 짧은 자기소개 -->
I am currently working as a Research Associate at the Artificial Intelligence and Mathematical Learning Lab (AIML@K), Department of Mathematics, Korea University.

<!-- 연구분야/주제 관심사 소개 -->
Believing that the ultimate paradigm of artificial intelligence will manifest as a fully converged system of robotics and AI—akin to Jarvis—I am profoundly interested in its foundational architectures, specifically Agentic AI and Large Action Models (LAM).

<!-- 그 외의 것/trivia -->
Outside the lab, I am discreetly conducting practical experiments on building automated AI-driven quantitative trading systems to generate passive income streams.