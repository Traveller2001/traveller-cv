---
title: "ShortOPD: Recovering Pruned LLMs with Short-to-Long On-Policy Distillation"
authors:
- admin # This will link to your profile (Qingyu Zhang)
- Qianhao Yuan
- Hongyu Lin
- Yaojie Lu
- Xianpei Han
- Le Sun
- Xiang Li
- Ming Xu
- Jiarui Li
- Xiuyin Zhao

date: '2026-07-14T00:00:00Z' # Publication date
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-07-14T00:00:00Z'

publication_types: ['Preprint']

# Publication name and optional abbreviated publication name.
publication: "*arXiv preprint arXiv:2607.13124*"
publication_short: "*arXiv preprint*"

abstract: 'Structured pruning compresses Large Language Models in a hardware-friendly way, but is usually evaluated on multiple-choice tasks, while pruned models can fail badly at free-form generation. We identify two findings that explain this gap: pass@1 with greedy decoding collapses after compression while pass@k rebounds with repeated sampling, meaning useful generations are demoted rather than erased, and failures mostly manifest as repetitive suffixes. This motivates On-Policy Distillation (OPD), where the original model acts as a frozen teacher over the compressed model''s own rollouts. Since long rollouts waste early training on low-value repetitive text, we introduce ShortOPD, a short-to-long schedule that identifies teacher-confirmed repetitive suffixes, keeps the useful prefix as the effective rollout length, and budgets future rollouts accordingly. Across math, code, and open-ended tasks, ShortOPD lifts the compressed model''s score to roughly 9x its unrecovered level and 1.6-4.4x standard baselines, while matching a fixed 8192-token horizon within two points at about a quarter of the training time with 71% fewer rollout tokens.'

# Summary. An optional shortened abstract.
summary: We propose ShortOPD, a short-to-long on-policy distillation schedule that recovers the free-form generation ability of pruned LLMs at a fraction of the training cost.

tags:
  - Model Compression
  - Knowledge Distillation
  - Large Language Models
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

url_pdf: 'https://arxiv.org/pdf/2607.13124' # Link to your PDF
---
