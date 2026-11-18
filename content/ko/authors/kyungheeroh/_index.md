---
# Display name
title: 노경희
type: landing

# Full Name (for SEO)
first_name: 경희
last_name: 노

# Is this the primary user of the site?
superuser: false

# Role/position
role: 석사과정 학생

# Organizations/Affiliations
organizations:
  - name: 고려대학교
    url: 'http://www.korea.edu'

# Short bio (displayed in user profile at end of posts)
bio: 차분하면서도 포부가 있는 여성

interests:
  - 베이지안 최적화
  - 컴퓨터 비전

education:
  courses:
    # - course: Ph.D. in Computer Science
    #   institution: Princeton University
    #   year: 2019
    - course: 수학(MDS) 석사과정
      institution: 고려대학교
      year: 2025 (예정)
    - course: 물리학 학사
      institution: 건국대학교
      year: 2024

# Social/Academic Networking
# For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: 'mailto:@rkh97@naver.com'
  # - icon: twitter
  #   icon_pack: fab
  #   link: https://twitter.com/GeorgeCushen
  # - icon: google-scholar
  #   icon_pack: ai
  #   link: https://scholar.google.com/citations?user=I-XhaYgAAAAJ
  # - icon: orcid
  #   icon_pack: ai
  #   link: https://orcid.org/0009-0002-7449-5336
  - icon: github
    icon_pack: fab
    link: https://github.com/kyungheee
  # - icon: cv
  #   icon_pack: ai
  #   link: https://docs.google.com/document/d/1QZI5EFBZ3Xsw4TMAHOI6sB7T_JsBC7y4UUIAGhU-sXo/edit?usp=sharing

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ''

# Highlight the author in author lists? (true/false)
highlight_name: false

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
  - 석사과정학생

sections:
  - block: about.biography
    id: about
    content:
      username: kyungheeroh

  - block: markdown
    content:
      title: 연구 주제
      subtitle: 현재 집중하고 있는 연구
      text: 현재 스쿼트, 바벨 리프트, 오버헤드 프레스와 같은 운동 동작의 영상 프레임에서 키포인트 좌표를 추출하는 연구에 집중하고 있습니다. 이러한 동작의 속도 변화를 감지하기 위해 Temporal Shift Module(TSM)을 활용하고 있습니다. 모바일 기기에서 실시간으로 작동할 수 있도록 지연 시간을 최소화하면서 성능을 유지하는 모델을 설계하기 위해 MobileNetV2, ResNet50, ResNet101, HRNetw32, HRNetw48 등 다양한 백본 모델로 실험하고 있습니다. 연구의 핵심은 PCKh와 지연 시간 사이의 균형을 이루는 최적의 백본 모델을 찾는 동시에 전반적인 성능을 높이는 방법을 살펴보는 것입니다
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

  - block: markdown
    content:
      title: 연구 목표
      subtitle: 연구를 통해 이루고자 하는 목표
      
      text: 백본 모델인 MobileNet V2는 Galaxy Note 8에서 시험했을 때 PCKh 86.278과 지연 시간 34.5ms를 보였습니다. 이 연구의 목표는 운동 동작 분석에 사용하는 AI 모델을 개선하여 PCKh를 90 이상으로 높이고 지연 시간을 30ms 미만으로 줄이는 것입니다. 실제 적용 가능성을 확인하기 위해 실제 사용 환경에서 모델의 성능과 사용성을 평가하고, 사용자 피드백을 반영하여 지속적으로 개선하고자 합니다. 또한 운동 동작 데이터셋을 확장하여 실제 데이터에 내재한 변동성에도 강건한 모델을 개발하고자 합니다. 마지막으로, 개발한 AI 피트니스 애플리케이션의 출시 목표를 2025년 10월로 설정했습니다
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

  - block: experience
    content:
      title: 연구 경험
      subtitle: 주요 연구 성과와 경험
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: 🏋🏻‍♂️ AI 헬스 트레이너
          # company: GenCoin
          # company_url: ''
          # company_logo: org-gc
          # location: California
          date_start: '2025-01-01'
          date_end: ''
          description: 인턴으로서 사람의 동작을 인식하고 반복 횟수를 세며 속도 변화를 파악하는 AI 피트니스 애플리케이션을 개발하고 있습니다

        - title: 📊 베이지안 최적화
          # company: University X
          # company_url: ''
          # company_logo: org-x
          # location: California
          date_start: '2024-09-01'
          date_end: '2024-12-01'
          description: 연구실 저널 클럽을 통해 베이지안 최적화, 가우시안 프로세스, 지식 기울기를 심도 있게 공부했습니다

        - title: 📱 반도체 공정  
          # company: University X
          # company_url: ''
          # company_logo: org-x
          # location: California
          date_start: '2024-08-01'
          date_end: '2024-09-01'
          description: Samsung AI Challenge 2024에서 반도체 공정의 최적 매개변수를 찾는 모델 기반 최적화 과제를 수행했습니다

        - title: 🚙 자율주행 
          # company: University X
          # company_url: ''
          # company_logo: org-x
          # location: California
          date_start: '2024-03-01'
          date_end: '2024-06-01'
          description: 자율주행 차량용 AI 알고리즘의 입출력 데이터를 분석하고 각 모델에 적합한 저장 시스템 개선안을 제안하는 논문을 KCC에 발표했습니다

        - title: 🪢 줄넘기
          # company: University X
          # company_url: ''
          # company_logo: org-x
          # location: California
          date_start: '2023-08-01'
          date_end: '2024-02-01'
          description: 시계열 센서 데이터를 활용하여 싱글/더블 줄넘기를 구분하는 머신러닝 분류 모델을 개발했습니다

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

---

<!-- 짧은 자기소개 -->
저는 노경희이며, 고려대학교 수학과(MDS) 석사과정 학생으로 AIML@K에서 인공지능을 연구하고 있습니다. 


<!-- 연구분야/주제 관심사 소개 -->
베이지안 최적화와 컴퓨터 비전에 관심이 있습니다.


<!-- 그 외의 것/trivia -->
건국대학교 물리학과를 졸업했습니다. 양자역학을 공부한 뒤 물리학이 제가 나아갈 길은 아니라는 것을 깨달았습니다. 



