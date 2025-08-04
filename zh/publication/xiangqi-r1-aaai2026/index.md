---
title: "Xiangqi-R1: Enhancing Spatial Strategic Reasoning in LLMs for Chinese Chess via Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - yuhao-chen
  - Shuochen Liu
  - Yuanjie Lyu
  - Chao Zhang
  - Jiayao Shi
  - Tong Xu

# Author notes (optional)
author_notes:
  - ""
  - ""
  - ""
  - ""
  - ""
  - "Corresponding author"

date: '2025-07-17T00:00:00Z'
doi: '10.48550/arXiv.2507.12215'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-07-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
# publication: In *AAAI 2026*
# publication_short: In *AAAI 2026*
publication: Preprint
publication_short: Preprint

abstract: 大语言模型（LLMs）在序列推理任务中展现出了卓越的能力，然而它们在空间战略推理方面的能力仍有待深入探索。在本研究中，我们提出了Xiangqi-R1，这是一个综合性框架，利用中国象棋作为测试平台，系统地评估和提升大语言模型的空间战略推理能力。我们开发了一个70亿参数规模的模型，使用500万个棋盘-走子对进行强化学习训练。实验结果表明，与基线模型相比，我们的方法在走子合法性方面提升了18%，在战略准确性方面提升了22%。这项工作为如何通过强化学习有效提升语言模型的空间推理能力提供了宝贵见解，为策略博弈和空间理解研究开辟了新的途径。

# Summary. An optional shortened abstract.
summary: 使用中国象棋测试大语言模型的空间战略能力；通过强化学习在500万个棋盘-走子对上训练70亿参数模型，走子合法性提升18%，准确性提升22%。

tags: ['大语言模型', '强化学习', '中国象棋']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2507.12215'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

## 主要贡献

- **空间战略推理增强**：Xiangqi-R1系统地利用中国象棋作为复杂测试环境来评估大语言模型的空间战略能力
- **强化学习应用**：开发了在500万个棋盘-走子对上使用强化学习技术训练的70亿参数模型
- **显著的性能提升**：与基线模型相比，在走子合法性方面实现了18%的改进，在战略准确性方面实现了22%的提升
