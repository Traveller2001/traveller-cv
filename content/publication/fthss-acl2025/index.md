---
title: 'Streamlining the Collaborative Chain of Models into A Single Forward Pass in Generation-Based Tasks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yuanjie Lyu
  - Chao Zhang
  - admin
  - Yong Chen
  - Tong Xu

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - 'Corresponding author'

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

abstract: In Retrieval-Augmented Generation (RAG) and agent-based frameworks, the 'Chain of Models' approach is widely used, where multiple specialized models work sequentially on distinct sub-tasks. However, this approach often suffers from inefficiency due to the need for multiple forward passes and lack of information sharing between models. We propose FTHSS, a novel prompt-tuning method that enables models to share hidden states, improving inference efficiency in multi-model generation tasks while maintaining performance quality.

# Summary. An optional shortened abstract.
summary: A novel prompt-tuning method called FTHSS that enables models to share hidden states, improving inference efficiency in multi-model generation tasks for RAG and agent-based frameworks.

tags: ['RAG', 'Chain of Models', 'NLP']

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


## Key Contributions

- **Efficient Model Collaboration**: FTHSS allows multiple specialized models to share hidden states, reducing the need for multiple forward passes
- **Maintained Performance**: The method preserves the quality of generation while improving computational efficiency
- **Broad Applicability**: The approach is applicable to various RAG and agent-based frameworks
