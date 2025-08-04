---
title: "Base of RoPE Bounds Context Length"
authors:
- Xin Men*
- Mingyu Xu*
- Bingning Wang†
- admin # "admin" will automatically link to your profile
- Hongyu Lin
- Xianpei Han
- Weipeng Chen

author_notes:
- "Equal contribution"
- "Equal contribution"
- "Corresponding author"

date: '2024-09-20T00:00:00Z'
doi: ''

publishDate: '2024-09-20T00:00:00Z'

publication_types: ['1']

publication: In *Conference on Neural Information Processing Systems (NeurIPS 2024)*
publication_short: In *NeurIPS 2024*

abstract: 'Position embedding is a core component of current Large Language Models(LLMs). Rotary position embedding (RoPE), a technique that encodes the position information with a rotation matrix, has been the de facto choice for position embedding in many LLMs, such as the Llama series. RoPE has been further
utilized to extend long context capability, which is roughly based on adjusting the base parameter of RoPE to mitigate out-of-distribution (OOD) problems in position embedding. However, in this paper, we find that LLMs may obtain a superficial long-context ability based on the OOD theory. We revisit the role of RoPE in LLMs and propose a novel property of long-term decay, deriving that thebase of RoPE bounds context length: there is an absolute lower bound for the base value to obtain certain context length capability. Our work reveals the relationship between context length and RoPE base both theoretically and empirically, which may shed light on future long context training.'

summary: This work contributes to the investigation of the lower bounds of the Base in RoPE, providing a theoretical foundation for the long-context extrapolation of models.

tags:
  - Long Context
  - Positional Encoding
  - RoPE
featured: true

image:
  caption: ''
  focal_point: ''
  preview_only: false

url_pdf: 'https://papers.nips.cc/paper_files/paper/2024/file/9f12dd32d552f3ad9eaa0e9dfec291be-Paper-Conference.pdf'
# url_code: ''
---