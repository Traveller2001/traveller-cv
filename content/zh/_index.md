---
# 主页标题将默认使用网站标题，此处留空
title: '张清宇 (Qingyu Zhang)'
date: 2025-08-05
type: landing

# SEO (搜索引擎优化) 描述
description: '张清宇 - 中国科学院软件研究所硕士生。研究方向为大语言模型，包括长文本能力和多轮对话能力。'

# SEO 关键词
keywords:
  - 大语言模型
  - 模型压缩
  - 长文本
  - 预训练后微调
  - 强化学习
  - 中科院软件所
  - 张清宇

sections:
  - block: about.biography
    id: about
    content:
      title: 个人简介
      # 用户名指向 `content/authors/admin/` 文件夹中的作者配置
      username: admin

  - block: markdown
    id: news
    content:
      title: 最新动态
      subtitle: ''
      text: |
        - **2025年5月** 一篇论文 "[*ShortGPT*](publication/shortgpt-acl2025/)" 被 ACL Findings 2025 接收。
        - **2024年9月** 一篇论文 "[*Base of RoPE Bounds Context Length*](publication/base-of-rope-neurips2024/)" 被 NeurIPS 2024 接收。
        - **2024年6月** 荣获福州大学“优秀毕业生”称号。
        - **2023年5月** 荣获第十届ASC世界大学生超级计算机竞赛一等奖。
        - **2022年11月** 荣获第十三届全国大学生数学竞赛一等奖。
    design:
      view: compact
      columns: '2'

  - block: experience
    id: experience
    content:
      title: 实习经历
      date_format: Jan 2006
      # 在下方添加/删除经历条目
      items:
        - title: 算法实习生
          company: 美团
          company_url: 'https://www.meituan.com/'
          location: 中国, 北京
          date_start: '2024-12-01'
          date_end: ''
          description: |2-
              * 主导研发了基于强化学习的大模型对话优化系统。
              * 系统在真实业务场景上线，核心业务转化率提升约20%。
              * 相关研究成果已投稿至 AAAI 2026。
        - title: 基座模型实习生
          company: 百川智能
          company_url: 'https://www.baichuan-ai.com/'
          location: 中国, 北京
          date_start: '2024-01-01'
          date_end: '2024-10-31'
          description: |2-
              * 探究Transformer模型冗余性，提出基于层的剪枝方法 (**ShortGPT**, *ACL Findings*, 2025)。
              * 研究RoPE位置编码的Base下界 (**Base of RoPE Bounds Context Length**, *NeurIPS*, 2024)。
              * 提出“大海捞针”评测的变体方法（专利已授权）。
        - title: 科研实习生
          company: 中国科学院软件研究所
          company_url: 'http://www.iscas.ac.cn/'
          location: 中国, 北京
          date_start: '2023-10-01'
          date_end: '2024-09-30'
          description: |2-
              * 为Megatron框架适配并优化SFT和DPO算法 (*ACL Demo*, 2025)。
              * 使用ModelLink框架，在昇腾910b上实现大规模分布式训练。
    design:
      columns: '2'

  - block: collection
    id: publications
    content:
      title: 近期论文
      text: "此处展示近期发表的论文，完整列表请见我的简历。"
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
      title: 项目经历
      filters:
        folders:
          - project
    design:
      # 视图样式: card, compact, stream, showcase
      view: card
      columns: '2'
      
  - block: contact
    id: contact
    content:
      title: 联系方式
      email: ttraveller2001@gmail.com
      address:
        street: 中关村南四街4号
        city: 北京
        region: 海淀区
        postcode: '100190'
        country: 中国
        country_code: CN
      coordinates:
        latitude: '39.9837'
        longitude: '116.327'
      autolink: true
    design:
      columns: '2'
---