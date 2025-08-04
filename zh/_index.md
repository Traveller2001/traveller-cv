---
# Leave the homepage title empty to use the site title
title: '陈宇豪 - 中科大自然语言处理与人工智能硕士研究生'
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
      title: 个人简介
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
      title: 最新消息
      subtitle: ""
      text: |
            - **2025年6月25日** 一篇论文 "[Streamlining the Collaborative Chain of Models into A Single Forward Pass in Generation-Based Tasks](https://arxiv.org/abs/2502.11083)" 被 ACL 2025 接收。
            - **2024年9月23日** 荣获2024年度一等奖学金。
            - **2024年5月29日** 荣获福州大学优秀毕业生称号。
            - **2024年3月27日** 一篇论文 "[基于大语言模型的隐式语义增强细粒度假新闻检测方法](https://crad.ict.ac.cn/cn/article/doi/10.7544/issn1000-1239.202330967?viewType=HTML)" 被《计算机研究与发展》接收。
            - **2023年12月20日** 荣获2023年度国家奖学金。  

    design:
      view: compact
      columns: '2'
      
  
      
  - block: collection
    id: section-collection
    content:
      title: 近期发表
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
      title: 联系方式
      
      email: isyuhaochen@mail.ustc.edu.cn
      address:
        street: 安徽省合肥市高新区复兴路100号
        city: 合肥
        region: 安徽, 中国
        postcode: '230094'
      office_hours:
        - '周一至周五 08:00 至 22:00'
        - '周六至周日 10:00 至 18:00'
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
