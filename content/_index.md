---
# Leave the homepage title empty to use the site title
title: 'Qingyu Zhang'
date: 2024-08-05
type: landing

# SEO description for homepage
description: 'Qingyu Zhang - Master''s student at the Institute of Software, Chinese Academy of Sciences (ISCAS). Research interests in Large Language Models, including long-text capabilities and multi-turn dialogue abilities.'

# SEO keywords
keywords:
  - Large Language Models
  - Model Compression
  - Long Context
  - Post-training
  - Reinforcement Learning
  - ISCAS
  - Qingyu Zhang

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # The username directs to the user profile found in `content/authors/admin/`
      username: admin

  - block: markdown
    id: news
    content:
      title: News
      subtitle: ''
      text: |
        - **May, 2025** One paper "[*ShortGPT*](publication/shortgpt-acl2025/)" is accepted by ACL Findings 2025.
        - **Sep, 2024** One paper "[*Base of RoPE Bounds Context Length*](publication/base-of-rope-neurips2024/)" is accepted by NeurIPS 2024.
        - **Jun, 2024** Honored as an Outstanding Graduate at Fuzhou University.
        - **May, 2023** Won the **First Prize** in the 10th ASC Student Supercomputer Challenge.
        - **Nov, 2022** Won the **First Prize** in the 13th National College Student Mathematics Competition.
    design:
      view: compact
      columns: '2'

  - block: collection
    id: experience
    content:
      title: Experience
      filters:
        folders:
          - experience
    design:
      columns: '2'
      view: compact

  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: "Here are some of my recent publications. You can find the full list in my CV."
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
      

  - block: contact
    id: contact
    content:
      title: Contact
      email: ttraveller2001@gmail.com
      address:
        street: No. 4, South Fourth Street, Zhongguancun
        city: Beijing
        region: Haidian District
        postcode: '100190'
        country: China
        country_code: CN
      coordinates:
        latitude: '39.9837'
        longitude: '116.327'
      autolink: true
    design:
      columns: '2'
---