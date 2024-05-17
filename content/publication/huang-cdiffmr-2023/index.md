---
title: 'CDiffMR: Can We Replace the Gaussian Noise with K-Space Undersampling for Fast
  MRI?'
authors:
- Jiahao Huang
- Angelica I. Aviles-Rivero
- Carola-Bibiane Schönlieb
- Guang Yang
date: '2023-01-01'
publishDate: '2024-05-17T11:41:32.932053Z'
publication_types:
- paper-conference
publication: '*Medical Image Computing and Computer Assisted Intervention – MICCAI
  2023*'
doi: 10.1007/978-3-031-43999-5_1
abstract: Deep learning has shown the capability to substantially accelerate MRI reconstruction
  while acquiring fewer measurements. Recently, diffusion models have gained burgeoning
  interests as a novel group of deep learning-based generative methods. These methods
  seek to sample data points that belong to a target distribution from a Gaussian
  distribution, which has been successfully extended to MRI reconstruction. In this
  work, we proposed a Cold Diffusion-based MRI reconstruction method called CDiffMR.
  Different from conventional diffusion models, the degradation operation of our CDiffMR
  is based on k-space undersampling instead of adding Gaussian noise, and the restoration
  network is trained to harness a de-aliaseing function. We also design starting point
  and data consistency conditioning strategies to guide and accelerate the reverse
  process. More intriguingly, the pre-trained CDiffMR model can be reused for reconstruction
  tasks with different undersampling rates. We demonstrated, through extensive numerical
  and visual experiments, that the proposed CDiffMR can achieve comparable or even
  superior reconstruction results than state-of-the-art models. Compared to the diffusion
  model-based counterpart, CDiffMR reaches readily competing results using only 1.6–3.4%
  for inference time. The code is publicly available at https://github.com/ayanglab/CDiffMR.
tags:
- Deep Learning
- Fast MRI
- '#READ'
- '#PRIORITY'
- Diffusion Models
---
