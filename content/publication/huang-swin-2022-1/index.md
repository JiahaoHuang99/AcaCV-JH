---
title: Swin transformer for fast MRI
authors:
- Jiahao Huang
- Yingying Fang
- Yinzhe Wu
- Huanjun Wu
- Zhifan Gao
- Yang Li
- Javier Del Ser
- Jun Xia
- Guang Yang
date: '2022-07-01'
publishDate: '2024-05-17T12:57:58.314504Z'
publication_types:
- article-journal
publication: '*Neurocomputing*'
doi: 10.1016/j.neucom.2022.04.051
abstract: Magnetic resonance imaging (MRI) is an important non-invasive clinical tool
  that can produce high-resolution and reproducible images. However, a long scanning
  time is required for high-quality MR images, which leads to exhaustion and discomfort
  of patients, inducing more artefacts due to voluntary movements of the patients
  and involuntary physiological movements. To accelerate the scanning process, methods
  by k-space undersampling and deep learning based reconstruction have been popularised.
  This work introduced SwinMR, a novel Swin transformer based method for fast MRI
  reconstruction. The whole network consisted of an input module (IM), a feature extraction
  module (FEM) and an output module (OM). The IM and OM were 2D convolutional layers
  and the FEM was composed of a cascaded of residual Swin transformer blocks (RSTBs)
  and 2D convolutional layers. The RSTB consisted of a series of Swin transformer
  layers (STLs). The shifted windows multi-head self-attention (W-MSA/SW-MSA) of STL
  was performed in shifted windows rather than the multi-head self-attention (MSA)
  of the original transformer in the whole image space. A novel multi-channel loss
  was proposed by using the sensitivity maps, which was proved to reserve more textures
  and details. We performed a series of comparative studies and ablation studies in
  the Calgary-Campinas public brain MR dataset and conducted a downstream segmentation
  experiment in the Multi-modal Brain Tumour Segmentation Challenge 2017 dataset.
  The results demonstrate our SwinMR achieved high-quality reconstruction compared
  with other benchmark methods, and it shows great robustness with different undersampling
  masks, under noise interruption and on different datasets. The code is publicly
  available at https://github.com/ayanglab/SwinMR.
tags:
- MRI reconstruction
- Compressed sensing
- Transformer
- Parallel imaging
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0925231222004179
---
