---
title: "ShortGPT: Layers in Large Language Models are More Redundant Than You Expect"
authors:
- Xin Men*
- Mingyu Xu*
- admin* # This will link to your profile (Qingyu Zhang)
- Qianhao Yuan*
- Bingning Wang
- Hongyu Lin
- Yaojie Lu
- Xianpei Han
- Weipeng Chen

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Corresponding author"

date: '2025-05-01T00:00:00Z' # Publication date
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-01T00:00:00Z'


publication_types: ['Conference']

# Publication name and optional abbreviated publication name.
publication: "In *Findings of the Association for Computational Linguistics: ACL 2025*"
publication_short: In *ACL Findings 2025*

abstract: 'As Large Language Models (LLMs) continue to advance, their computational overhead has increased significantly. In this study, we identify notable redundancy across the layers of LLMs, where some layers contribute minimally to the overall network functionality. To quantify this, we introduce a metric called Block Influence (BI), which measures the importance of each layer based on the similarity between its input and output. Based on the observation of layer redundancy, we propose straightforward pruning methods for different tasks: ShortGPT for multiple-choice tasks and ShortGPT-gen for generative tasks. They prune redundant layers based on their BI scores. Our methods demonstrate superior performance over previous pruning methods. The ability to achieve better results through simple layer pruning, as opposed to more complex pruning techniques, suggests a high degree of redundancy across layers. We hope this work will contribute to future research for improving LLM efficiency.'

# Summary. An optional shortened abstract.
summary: We investigate the redundancy within Transformer layers and propose an effective layer-based pruning method.

tags:
  - Model Compression
  - LLM Redundancy
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overview of ShortGPT'
  focal_point: ''
  preview_only: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://aclanthology.org/2025.findings-acl.1035.pdf' # Link to your PDF
# url_code: '' # Link to your code
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''
---