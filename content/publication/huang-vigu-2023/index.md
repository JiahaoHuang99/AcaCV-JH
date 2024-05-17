---
title: 'ViGU: Vision GNN U-Net for fast MRI'
authors:
- Jiahao Huang
- Angelica I. Aviles-Rivero
- Carola-Bibiane Schönlieb
- Guang Yang
date: '2023-04-01'
publishDate: '2024-05-17T11:41:32.924155Z'
publication_types:
- paper-conference
publication: '*2023 IEEE 20th International Symposium on Biomedical Imaging (ISBI)*'
doi: 10.1109/ISBI53787.2023.10230600
abstract: Deep learning models have been widely applied for fast MRI. The majority
  of existing deep learning models, e.g., convolutional neural networks, work on data
  with Euclidean or regular grids structures. However, high-dimensional features extracted
  from MR data could be encapsulated in non-Euclidean manifolds. This disparity between
  the go-to assumption of existing models and data requirements limits the flexibility
  to capture irregular anatomical features in MR data. In this work, we introduce
  a novel Vision GNN type network for fast MRI called Vision GNN U-Net (ViGU). More
  precisely, the pixel array is first embedded into patches and then converted into
  a graph. Secondly, a U-shape network is developed using several graph blocks in
  symmetrical encoder and decoder paths. Moreover, we show that the proposed ViGU
  can also benefit from Generative Adversarial Networks yielding to its variant ViGU-GAN.
  We demonstrate, through numerical and visual experiments, that the proposed ViGU
  and GAN variant outperform existing CNN and GAN-based methods. Moreover, we show
  that the proposed network readily competes with approaches based on Transformers
  while requiring a fraction of the computational cost. More importantly, the graph
  structure of the network reveals how the network extracts features from MR images,
  providing intuitive explainability. The code is publicly available at https://github.com/ayanglab/ViGU.
tags:
- Deep learning
- Neural networks
- Magnetic resonance imaging
- Generative adversarial networks
- Feature extraction
- Fast MRI
- Visualization
- '#READ'
- Manifolds
- Graph Neural Network (GNN)
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/10230600
---
