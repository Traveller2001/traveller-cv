---
title: "ShortV: Efficient Multimodal Large Language Models by Freezing Visual Tokens in Ineffective Layers"
authors:
- Qianhao Yuan
- admin
- Yanjiang Liu
- Jiawei Chen
- Yaojie Lu
- Hongyu Lin
- Jia Zheng
- Xianpei Han
- Le Sun

date: '2025-06-01T00:00:00Z'
doi: ''

publishDate: '2025-06-01T00:00:00Z'

publication_types: ['Conference']

publication: "In *2025 IEEE/CVF International Conference on Computer Vision (ICCV)*"
publication_short: In *ICCV 2025*

abstract: 'Multimodal Large Language Models (MLLMs) suffer from high computational costs due to their massive size and the large number of visual tokens. In this paper, we investigate layer-wise redundancy in MLLMs by introducing a novel metric, Layer Contribution (LC), which quantifies the impact of a layer''s transformations on visual and text tokens, respectively. The calculation of LC involves measuring the divergence in model output that results from removing the layer''s transformations on the specified tokens. Our pilot experiment reveals that many layers of MLLMs exhibit minimal contribution during the processing of visual tokens. Motivated by this observation, we propose ShortV, a training-free method that leverages LC to identify ineffective layers, and freezes visual token updates in these layers. Experiments show that ShortV can freeze visual token in approximately 60% of the MLLM layers, thereby dramatically reducing computational costs related to updating visual tokens. For example, it achieves a 50% reduction in FLOPs on LLaVA-NeXT-13B while maintaining superior performance.'

summary: We propose ShortV, a training-free method that reduces computational costs of MLLMs by freezing visual tokens in ineffective layers.

tags:
  - Multimodal LLM
  - Model Efficiency
  - Computer Vision
featured: true

# url_pdf: ''
# url_code: ''
---
