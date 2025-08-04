---
title: 'Streamlining the Collaborative Chain of Models into A Single Forward Pass in Generation-Based Tasks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yuanjie Lyu
  - Chao Zhang
  - yuhao-chen
  - Yong Chen
  - Tong Xu

# Author notes (optional)
author_notes:
  - ""
  - ""
  - ""
  - ""
  - "Corresponding author"

date: '2024-12-01T00:00:00Z'
doi: '10.48550/arXiv.2502.11083'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ACL 2025*
publication_short: In *ACL 2025*

abstract: 在检索增强生成（RAG）和基于智能体的框架中，广泛使用"模型链"方法，其中多个专门的模型依次处理不同的子任务。然而，这种方法由于需要多次前向传递以及模型之间缺乏信息共享而经常遇受效率低下的问题。我们提出了FTHSS，这是一种新颖的提示调优方法，使模型能够共享隐藏状态，在保持性能质量的同时提高多模型生成任务的推理效率。

# Summary. An optional shortened abstract.
summary: 一种名为FTHSS的新颖提示调优方法，使模型能够共享隐藏状态，在RAG和基于智能体的框架中提高多模型生成任务的推理效率。

tags: ['检索增强生成', '模型链', '大语言模型']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2502.11083'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

- **高效的模型协作**：FTHSS允许多个专门的模型共享隐藏状态，减少了多次前向传递的需要
- **保持性能质量**：该方法在提高计算效率的同时保持了生成质量
- **广泛的适用性**：该方法适用于各种RAG和基于智能体的框架
