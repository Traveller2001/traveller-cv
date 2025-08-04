---
# Leave the homepage title empty to use the site title
title: 'Yuhao Chen'
date: 2022-10-24
type: landing

# # SEO description for homepage
# description: 'Yuhao Chen - Master''s student in Natural Language Processing and Large Language Models at University of Science and Technology of China (USTC). Research focus on enhancing reasoning capabilities of LLMs, document analysis, social media understanding, and strategic reasoning tasks.'

# # SEO keywords
# keywords:
#   - Natural Language Processing
#   - Large Language Models
#   - USTC
#   - Document Analysis
#   - Social Media Understanding
#   - Multimodal Intelligence
#   - Reinforcement Learning
#   - Strategic Reasoning
#   - Academic Research
#   - Artificial Intelligence
#   - Machine Learning

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin
  # - block: skills
  #   id: skills
  #   content:
  #     title: Skills
  #     text: ''
  #     username: admin
  #   design:
  #     columns: '1'
  
  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: CEO
  #         company: GenCoin
  #         company_url: ''
  #         company_logo: org-gc
  #         location: California
  #         date_start: '2021-01-01'
  #         date_end: ''
  #         description: |2-
  #             Responsibilities include:

  #             * Analysing
  #             * Modelling
  #             * Deploying
  #       - title: Professor of Semiconductor Physics
  #         company: University X
  #         company_url: ''
  #         company_logo: org-x
  #         location: California
  #         date_start: '2016-01-01'
  #         date_end: '2020-12-31'
  #         description: Taught electronic engineering and researched semiconductor physics.
  #   design:
  #     columns: '2'
  - block: markdown
    id: news
    content:
      title: News
      subtitle: ""
      text: |
            - **Jun 25, 2025** One paper "[Streamlining the Collaborative Chain of Models into A Single Forward Pass in Generation-Based Tasks](https://arxiv.org/abs/2502.11083)" is accepted by ACL 2025.
            - **SEP 23, 2024** Honored to receive the First Class Scholarship in 2024. 
            - **May 29, 2024** Honored as an Outstanding Graduate at Fuzhou University.
            - **Mar 27, 2024** One paper "[An Implicit Semantic Enhanced Fine-Grained Fake News Detection Method Based on Large Language Models](https://crad.ict.ac.cn/cn/article/doi/10.7544/issn1000-1239.202330967?viewType=HTML)" is accepted by Journal of Computer Research and Development.
            - **Dec 20, 2023** Honored to receive the National Scholarship in 2023.  

    design:
      view: compact
      columns: '2'
      
  
      
  - block: collection
    id: section-collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: contact
    id: contact
    content:
      title: Contact
      
      email: isyuhaochen@mail.ustc.edu.cn
      address:
        street: 100 Fuxing Road, High-Tech Zone
        city: Hefei
        region: Anhui, China
        postcode: '230094'
      office_hours:
        - 'Monday to Friday 08:00 to 22:00'
        - 'Saturday to Sunday 10:00 to 18:00'
      coordinates: 
        latitude: '31.82057311201721'
        longitude: '117.1250753555994'  
      autolink: true
    design:
      columns: '2'

  # 
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card

  
  
---
