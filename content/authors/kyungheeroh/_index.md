---
# Display name
title: Kyunghee Roh
type: landing

# Full Name (for SEO)
first_name: Kyunghee
last_name: Roh

# Is this the primary user of the site?
superuser: false

# Role/position
role: M.S. Student

# Organizations/Affiliations
organizations:
  - name: Korea University
    url: 'http://www.korea.edu'

# Short bio (displayed in user profile at end of posts)
bio: calm ambitious girl

interests:
  - Bayesian Optimization
  - Computer Vision

education:
  courses:
    # - course: Ph.D. in Computer Science
    #   institution: Princeton University
    #   year: 2019
    - course: M.S. in Mathematics (MDS)
      institution: Korea University
      year: 2025 (expected)
    - course: B.S. in Physics
      institution: Konkuk University
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
  - M.S. Students

sections:
  - block: about.biography
    id: about
    content:
      username: kyungheeroh

  - block: markdown
    content:
      title: Research Focus
      subtitle: What I am currently focusing on in my research
      text: My current research focus involves extracting keypoint coordinates from video frames of exercise movements, such as squats, barbell lifts, and overhead presses. I am utilizing the Temporal Shift Module (TSM) to detect speed changes in these movements. I am conducting experiments with various backbone models, including MobileNetV2, ResNet50, ResNet101, HRNetw32, and HRNetw48, to design a model that minimizes latency and maintains performance for real-time operation on mobile devices. A key aspect of my research is finding the optimal backbone model that balances PCKh and latency, while also investigating methods to enhance overall performance
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

  - block: markdown
    content:
      title: Research Goal
      subtitle: What I aim to achieve with my research
      
      text: Our backbone model MobileNet V2 demonstrates a PCKh of 86.278 and a latency of 34.5ms when tested on a Galaxy Note 8. The objective of this research is to improve the AI model used for analyzing exercise motions to achieve a PCKh of 90 or more and reduce latency to under 30ms. To ensure practical application, I will evaluate the model's performance and usability in real-world scenarios, incorporating user feedback for continuous refinement. Additionally, I intend to expand the exercise motion dataset, developing a model robust to the inherent variability of real-world data. Finally, I am committed to the goal of releasing the developed AI fitness application in October 2025
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

  - block: experience
    content:
      title: Research Experience
      subtitle: The key research achievements and experiences
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: 🏋🏻‍♂️ AI Health Trainer
          # company: GenCoin
          # company_url: ''
          # company_logo: org-gc
          # location: California
          date_start: '2025-01-01'
          date_end: ''
          description: As an intern, I'm working on creating an AI fitness application to recognize human motion, count repetitions, and identify speed variations

        - title: 📊 Bayesian Optimization
          # company: University X
          # company_url: ''
          # company_logo: org-x
          # location: California
          date_start: '2024-09-01'
          date_end: '2024-12-01'
          description: Through our lab's journal club, I engaged in in-depth study of Bayesian Optimization, Gaussian Process, and Knowledge Gradient

        - title: 📱 Semiconductor Processing  
          # company: University X
          # company_url: ''
          # company_logo: org-x
          # location: California
          date_start: '2024-08-01'
          date_end: '2024-09-01'
          description: In the Samsung AI Challenge 2024, I tackled a model-based optimization challenge aimed at determining the optimal parameters for semiconductor processing

        - title: 🚙 Autonomous Driving 
          # company: University X
          # company_url: ''
          # company_logo: org-x
          # location: California
          date_start: '2024-03-01'
          date_end: '2024-06-01'
          description: I published a paper in KCC that analyzes the I/O data of AI algorithms for autonomous vehicles and proposes improvements to the storage system for each model

        - title: 🪢 Jump Rope
          # company: University X
          # company_url: ''
          # company_logo: org-x
          # location: California
          date_start: '2023-08-01'
          date_end: '2024-02-01'
          description: I developed an ML classification model for single/double jump rope using time-series sensor data

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

---

<!-- 짧은 자기소개 -->
My name is Roh Kyunghee, and I am a master's student in the Department of Mathematics (MDS) at Korea University and researching artificial intelligence at AIML@K. 


<!-- 연구분야/주제 관심사 소개 -->
I'm interested in Bayesian Optimization and Computer Vision.


<!-- 그 외의 것/trivia -->
I graduated from the Department of Physics at Konkuk University. After studying Quantum Mechanics, I realized that physics was not my path. 



