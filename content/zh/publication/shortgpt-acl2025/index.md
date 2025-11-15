---
title: "ShortGPT: Layers in Large Language Models are More Redundant Than You Expect"
date: '2025-05-01T00:00:00Z'
publishDate: '2025-05-01T00:00:00Z'
publication_types: ['Conference']
publication: "In *Findings of the Association for Computational Linguistics: ACL 2025*"
publication_short: In *ACL Findings 2025*
abstract: 'As Large Language Models (LLMs) continue to advance, their computational overhead has increased significantly. In this study, we identify notable redundancy across the layers of LLMs, where some layers contribute minimally to the overall network functionality. To quantify this, we introduce a metric called Block Influence (BI), which measures the importance of each layer based on the similarity between its input and output. Based on the observation of layer redundancy, we propose straightforward pruning methods for different tasks: ShortGPT for multiple-choice tasks and ShortGPT-gen for generative tasks. They prune redundant layers based on their BI scores. Our methods demonstrate superior performance over previous pruning methods. The ability to achieve better results through simple layer pruning, as opposed to more complex pruning techniques, suggests a high degree of redundancy across layers. We hope this work will contribute to future research for improving LLM efficiency.'
summary: We investigate the redundancy within Transformer layers and propose an effective layer-based pruning method.
tags:
  - Model Compression
  - LLM Redundancy
featured: true
url_pdf: 'https://aclanthology.org/2025.findings-acl.1035.pdf'
---
