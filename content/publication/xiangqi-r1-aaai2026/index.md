---
title: "Xiangqi-R1: Enhancing Spatial Strategic Reasoning in LLMs for Chinese Chess via Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
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
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
# publication: In *AAAI 2026*
# publication_short: In *AAAI 2026*
publication_types: ['preprint']
publication: Preprint
publication_short: Preprint

abstract: Large language models (LLMs) have demonstrated remarkable capabilities in sequential reasoning tasks, yet their spatial strategic reasoning abilities remain underexplored. In this work, we introduce Xiangqi-R1, a comprehensive framework that leverages Chinese Chess (Xiangqi) as a testbed to systematically evaluate and enhance LLMs' spatial strategic reasoning capabilities. We develop a 7B parameter model trained on 5 million board-move pairs using reinforcement learning techniques. Our experimental results demonstrate significant improvements in both move legality (18% increase) and strategic accuracy (22% increase) compared to baseline models. This work provides valuable insights into how reinforcement learning can be effectively employed to enhance spatial reasoning in language models, opening new avenues for research in strategic game playing and spatial understanding.

# Summary. An optional shortened abstract.
summary: Uses Chinese Chess to test LLMs' spatial strategy; trains a 7B model on 5M board-move pairs with RL, boosting legality by 18% and accuracy by 22%.

tags: ['LLMs', 'Reinforcement Learning', 'Chinese Chess', 'Strategic Games']

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


## Key Contributions

- **Spatial Strategic Reasoning Enhancement**: Xiangqi-R1 systematically evaluates LLMs' spatial strategic capabilities using Chinese Chess as a complex test environment
- **Reinforcement Learning Application**: Developed a 7B parameter model trained on 5M board-move pairs with RL techniques
- **Significant Performance Gains**: Achieved 18% improvement in move legality and 22% increase in strategic accuracy over baseline models
