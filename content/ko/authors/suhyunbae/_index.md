---
# Display name
title: 배수현

# Full Name (for SEO)
first_name: 수현
last_name: 배

# Is this the primary user of the site?
superuser: false

# Role/position
role: 석사후연구원

# Organizations/Affiliations
organizations:
  - name: 고려대학교
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
    - course: 수학과 MDS 석사
      institution: Korea University
      year: 2026 (expected)
    - course: 수학과 학사
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
    link: ko/cv/CV_SuhyunBae_20260623_kor.pdf
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
email: 'baeshstar@korea.ac.kr'

# Highlight the author in author lists? (true/false)
highlight_name: false

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
  - 졸업생    # 연구원




sections:
  - block: about.biography
    id: about
    content:
      username: suhyunbae

  - block: markdown
    content:
      title: Research Focus
      # subtitle: What I am currently focusing on in my research
      text: 제 최종 목표는 수학적 엄밀성을 바탕으로 검증 가능하고 신뢰할 수 있는 차세대 AI 모델을 연구 및 개발하는 것입니다.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

  - block: markdown
    content:
      title: Research Goal
      # subtitle: What I aim to achieve with my research
      text: 제 최종 목표는 수학적 엄밀성을 바탕으로 검증 가능하고 신뢰성 높은 AI 모델을 개발하는 것입니다.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

  - block: experience
    content:
      title: Research Experience
      # subtitle: The key research achievements and experiences
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: 'Core AI R&D: Algebraic Number Theory for LLM Reasoning'
          # company: University X
          # company_url: ''
          # company_logo: org-x
          # location: California
          date_start: '2025-03-01'
          date_end: ''
          description: |
            - Phase 1 (2025.07 - 2025.12) | *Numbers Already Carry Their Own Embeddings*
            Adele Ring 및 p-adic 대수적 구조를 활용하여 기존 LLM 토크나이저의 숫자 의미 훼손 문제를 해결하는 신규 임베딩 제안. 이 연구는 NIPS 2025 Workshop MATHAI에 억셉되었습니다.
            - Phase 2 (2026.01 - 2026.05) | *Prime Fourier Embeddings: A Principled Basis for Modular Arithmetic*
            Pontryagin Dual Space 개념을 도입하여 숫자를 복소평면 위 (cos, sin)으로 매핑하는 메커니즘 구축 및 CRT 학습 효율성 입증. 이 연구는 ICML 2026 Workshop AI4MATH에 억셉되었습니다.
            - Phase 3 (2026.05 - PRESENT) | 
            LLM에 플러그인 형태로 적용 가능한 실용적 임베딩 모듈 개발 중.

        - title: Internship at SK Magic
          # company: University X
          # company_url: ''
          # company_logo: org-x
          # location: California
          date_start: '2024-07-01'
          date_end: '2025-01-01'
          description: SK매직에서 AI사업개발팀에서 데이터 사이언티스트로서 근무. 자율주행 공기청정기(NAMUHX) 관련 보조 공기질 센서 최적 배치 알고리즘 개발을 주도

        - title: KCC 2024 and Hallucination
          # company: University X
          # company_url: ''
          # company_logo: org-x
          # location: California
          date_start: '2024-03-01'
          date_end: '2024-06-01'
          description: QA(질의응답) 작업에서 발생하는 환각 현상을 5가지 유형으로 분류하고, 자연어 평가 지표인 BLEU, METEOR, ROUGE가 각각 특정 유형의 환각 현상을 탐지하는 데 강점과 한계가 있음을 밝혀냄. 이 연구는 KCC 2024에 게재되었습니다.

        - title: AI Grand Challenge 2023
          # company: University X
          # company_url: ''
          # company_logo: org-x
          # location: California
          date_start: '2023-07-01'
          date_end: '2023-12-01'
          description: OpenAI API(GPT-3.5)를 활용한 다중 답변 질의 응답용 합성 데이터셋 생성 및 정제 파이프라인 구축. 연구실 최종 7위 단체 수상에 기여.

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'



---
<!-- 짧은 자기소개 -->
고려대학교 수학과 인공지능수학 연구실(AIML@K)에서 석사후연구원으로 재직하고 있습니다.

<!-- 연구분야/주제 관심사 소개 -->
인공지능의 종착지는 자비스처럼 로보틱스와 AI가 융합된 궁극의 시스템이라 믿으며, 그것의 전신인 Agentic AI와 LAM에 관심을 갖고 있습니다.

<!-- 그 외의 것/trivia -->
AI 자동 투자로 불로소득 창출하는 실험을 은밀히 진행중입니다.