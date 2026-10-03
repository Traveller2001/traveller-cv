---
# Leave the homepage title empty to use the site title
title: 'Qingyu Zhang'
date: 2024-08-05
type: landing

# SEO description for homepage
description: 'Qingyu Zhang (张清宇), master''s student at the Institute of Software, Chinese Academy of Sciences (ISCAS). Research on LLM agents for reliable multi-turn conversation and on efficient large language models.'

# SEO keywords
keywords:
  - Large Language Models
  - LLM Agents
  - User Agent
  - Model Compression
  - Long Context
  - Post-training
  - Reinforcement Learning
  - ISCAS
  - Qingyu Zhang
  - 张清宇

sections:
  - block: about.biography
    id: about
    content:
      title: ''
      # The username directs to the user profile found in `content/authors/admin/`
      username: admin

  - block: markdown
    id: news
    content:
      title: News
      subtitle: ''
      text: |
        - **Jul 2026** [ShortOPD](publication/shortopd-arxiv2026/) released on arXiv (first author).
        - **Dec 2025** [AI-Salesman](publication/ai-salesman-aaai2026/) accepted to AAAI 2026 (first author).
        - **Nov 2025** Open-sourced [ShortX](https://github.com/icip-cas/ShortX), a unified pruning toolkit for AI models.
        - **Jun 2025** Contributed to [AutoAlign](https://github.com/icip-cas/AutoAlign), an open-source toolkit for automated LLM alignment.
        - **May 2025** [ShortV](publication/shortv-iccv2025/) accepted to ICCV 2025.
        - **May 2025** [ShortGPT](publication/shortgpt-acl2025/) accepted to ACL Findings 2025 (co-first author).
    design:
      view: compact
      columns: '2'

  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      # Experiences.
      items:
        - title: Algorithm Intern
          company: ByteDance
          company_url: 'https://www.bytedance.com/'
          company_logo: bytedance
          location: Beijing, China
          date_start: '2026-01-01'
          date_end: ''
          description: |2-
              * Led the R&D of a **User Agent** framework for multi-turn evaluation across business lines; over 80% of the evaluation data it generates is directly usable by the business.
              * Exploring how User Agents can power multi-turn RL for sales agents.
        - title: Algorithm Intern
          company: Meituan
          company_url: 'https://www.meituan.com/'
          company_logo: meituan
          location: Beijing, China
          date_start: '2024-12-01'
          date_end: '2026-01-31'
          description: |2-
              * Led the R&D of an RL-based dialogue optimization system for LLMs, covering the full training, inference, and evaluation pipeline.
              * Deployed in live business, lifting the core conversion rate by 10–20%.
              * Published as first author: **AI-Salesman** (*AAAI 2026*).
        - title: Foundation Model Intern
          company: Baichuan Intelligence
          company_url: 'https://www.baichuan-ai.com/'
          company_logo: baichuan
          location: Beijing, China
          date_start: '2024-01-01'
          date_end: '2024-10-31'
          description: |2-
              * Studied layer redundancy in Transformers and proposed a layer-pruning method (**ShortGPT**, *ACL Findings 2025*).
              * Studied the lower bound of the RoPE base for long context (**Base of RoPE Bounds Context Length**, *NeurIPS 2024*).
              * Proposed a variant of the Needle-in-a-Haystack evaluation (patent granted).
        - title: Research Intern
          company: Institute of Software, Chinese Academy of Sciences
          company_url: 'http://www.iscas.ac.cn/'
          company_logo: iscas
          location: Beijing, China
          date_start: '2023-10-01'
          date_end: '2024-09-30'
          description: |2-
              * Adapted and optimized SFT/DPO for the Megatron framework (**AutoAlign**, *ACL Demo 2025*).
              * Ran large-scale distributed training on Ascend 910B with the ModelLink framework.
    design:
      columns: '2'

  - block: collection
    id: publications
    content:
      title: Publications
      count: 0
      # text: "Here are some of my recent publications. You can find the full list in my CV."
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      # Choose a view for the collection: card, compact, stream, showcase.
      view: card
      columns: '2'

  - block: markdown
    id: awards
    content:
      title: Awards
      subtitle: ''
      text: |
        - **Jun 2024** Outstanding Graduate, Fuzhou University.
        - **May 2023** First Prize, 10th ASC Student Supercomputer Challenge.
        - **Nov 2022** First Prize, 13th National College Student Mathematics Competition.
    design:
      view: compact
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      email: ttraveller2001@gmail.com
      autolink: true
    design:
      columns: '2'

---
