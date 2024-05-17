---
title: Swin Deformable Attention U-Net Transformer (SDAUT) for Explainable Fast MRI
authors:
- Jiahao Huang
- Xiaodan Xing
- Zhifan Gao
- Guang Yang
date: '2022-01-01'
publishDate: '2024-05-17T11:41:32.885263Z'
publication_types:
- paper-conference
publication: '*Medical Image Computing and Computer Assisted Intervention – MICCAI
  2022*'
doi: 10.1007/978-3-031-16446-0_51
abstract: Fast MRI aims to reconstruct a high fidelity image from partially observed
  measurements. Exuberant development in fast MRI using deep learning has been witnessed
  recently. Meanwhile, novel deep learning paradigms, e.g., Transformer based models,
  are fast-growing in natural language processing and promptly developed for computer
  vision and medical image analysis due to their prominent performance. Nevertheless,
  due to the complexity of the Transformer, the application of fast MRI may not be
  straightforward. The main obstacle is the computational cost of the self-attention
  layer, which is the core part of the Transformer, can be expensive for high resolution
  MRI inputs. In this study, we propose a new Transformer architecture for solving
  fast MRI that coupled Shifted Windows Transformer with U-Net to reduce the network
  complexity. We incorporate deformable attention to construe the explainability of
  our reconstruction model. We empirically demonstrate that our method achieves consistently
  superior performance on the fast MRI task. Besides, compared to state-of-the-art
  Transformer models, our method has fewer network parameters while revealing explainability.
  The code is publicly available at https://github.com/ayanglab/SDAUT.
tags:
- Transformer
- Fast MRI
- XAI
---
