---
title: Generative Adversarial Network Powered Fast Magnetic Resonance Imaging—Comparative
  Study and New Perspectives
authors:
- Guang Yang
- Jun Lv
- Yutong Chen
- Jiahao Huang
- Jin Zhu
date: '2022-01-01'
publishDate: '2024-05-17T12:57:58.322466Z'
publication_types:
- chapter
publication: '*Generative Adversarial Learning: Architectures and Applications*'
doi: 10.1007/978-3-030-91390-8_13
abstract: Magnetic Resonance Imaging (MRI) is a vital component of medical imaging.
  When compared to other image modalities, it has advantages such as the absence of
  radiation, superior soft tissue contrast, and complementary multiple sequence information.
  However, one drawback of MRI is its comparatively slow scanning and reconstruction
  compared to other image modalities, limiting its usage in some clinical applications
  when imaging time is critical. Traditional compressive sensing based MRI (CS-MRI)
  reconstruction can speed up MRI acquisition, but suffers from a long iterative process
  and noise-induced artefacts. Recently, Deep Neural Networks (DNNs) have been used
  in sparse MRI reconstruction models to recreate relatively high-quality images from
  heavily undersampled k-space data, allowing for much faster MRI scanning. However,
  there are still some hurdles to tackle. For example, directly training DNNs based
  on L1/L2 distance to the target fully sampled images could result in blurry reconstruction
  because L1/L2 loss can only enforce overall image or patch similarity and does not
  take into account local information such as anatomical sharpness. It is also hard
  to preserve fine image details while maintaining a natural appearance. More recently,
  Generative Adversarial Networks (GAN) based methods are proposed to solve fast MRI
  with enhanced image perceptual quality. The encoder obtains a latent space for the
  undersampling image, and the image is reconstructed by the decoder using the GAN
  loss. In this chapter, we review the GAN powered fast MRI methods with a comparative
  study on various anatomical datasets to demonstrate the generalisability and robustness
  of this kind of fast MRI while providing future perspectives.
tags:
- Deep learning
- Compressive sensing
- Fast magnetic resonance imaging (mri)
- Generative adversarial networks (gan)
links:
- name: URL
  url: https://doi.org/10.1007/978-3-030-91390-8_13
---
