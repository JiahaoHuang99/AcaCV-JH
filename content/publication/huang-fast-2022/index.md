---
title: 'Fast MRI Reconstruction: How Powerful Transformers Are?'
authors:
- Jiahao Huang
- Yinzhe Wu
- Huanjun Wu
- Guang Yang
date: '2022-07-01'
publishDate: '2024-05-17T12:39:15.045096Z'
publication_types:
- paper-conference
publication: '*2022 44th Annual International Conference of the IEEE Engineering in
  Medicine & Biology Society (EMBC)*'
doi: 10.1109/EMBC48229.2022.9871475
abstract: Magnetic resonance imaging (MRI) is a widely used non-radiative and non-invasive
  method for clinical interro-gation of organ structures and metabolism, with an inherently
  long scanning time. Methods by k-space undersampling and deep learning based reconstruction
  have been popularised to accelerate the scanning process. This work focuses on investigating
  how powerful transformers are for fast MRI by exploiting and comparing different
  novel network architectures. In particular, a generative adversarial network (GAN)
  based Swin transformer (ST-GAN) was introduced for the fast MRI reconstruction.
  To further preserve the edge and texture information, edge enhanced GAN based Swin
  transformer (EES-GAN) and texture enhanced GAN based Swin transformer (TES-GAN)
  were also developed, where a dual-discriminator GAN structure was applied. We compared
  our proposed GAN based transformers, standalone Swin transformer and other convolutional
  neural networks based GAN model in terms of the evaluation metrics PSNR, SSIM and
  FID. We showed that transformers work well for the MRI reconstruction from different
  undersampling conditions. The utilisation of GAN's adversarial structure improves
  the quality of images reconstructed when undersampled for 30% or higher. The code
  is publicly available at https://github.comJayanglab/SwinGANMR.
tags:
- Magnetic resonance imaging
- Generative adversarial networks
- Transformers
- Visualization
- Measurement
- Biological system modeling
- Network architecture
---
