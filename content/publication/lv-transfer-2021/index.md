---
title: Transfer learning enhanced generative adversarial networks for multi-channel
  MRI reconstruction
authors:
- Jun Lv
- Guangyuan Li
- Xiangrong Tong
- Weibo Chen
- Jiahao Huang
- Chengyan Wang
- Guang Yang
date: '2021-01-01'
publishDate: '2024-05-17T12:57:58.275597Z'
publication_types:
- article-journal
publication: '*Computers in Biology and Medicine*'
doi: 10.1016/j.compbiomed.2021.104504
abstract: Deep learning based generative adversarial networks (GAN) can effectively
  perform image reconstruction with under-sampled MR data. In general, a large number
  of training samples are required to improve the reconstruction performance of a
  certain model. However, in real clinical applications, it is difficult to obtain
  tens of thousands of raw patient data to train the model since saving k-space data
  is not in the routine clinical flow. Therefore, enhancing the generalizability of
  a network based on small samples is urgently needed. In this study, three novel
  applications were explored based on parallel imaging combined with the GAN model
  (PI-GAN) and transfer learning. The model was pre-trained with public Calgary brain
  images and then fine-tuned for use in (1) patients with tumors in our center; (2)
  different anatomies, including knee and liver; (3) different k-space sampling masks
  with acceleration factors (AFs) of 2 and 6. As for the brain tumor dataset, the
  transfer learning results could remove the artifacts found in PI-GAN and yield smoother
  brain edges. The transfer learning results for the knee and liver were superior
  to those of the PI-GAN model trained with its own dataset using a smaller number
  of training cases. However, the learning procedure converged more slowly in the
  knee datasets compared to the learning in the brain tumor datasets. The reconstruction
  performance was improved by transfer learning both in the models with AFs of 2 and
  6. Of these two models, the one with AF = 2 showed better results. The results also
  showed that transfer learning with the pre-trained model could solve the problem
  of inconsistency between the training and test datasets and facilitate generalization
  to unseen data.
tags:
- Generative adversarial networks
- Image reconstruction
- Transfer learning
- Multi-channel MRI
links:
- name: URL
  url: https://doi.org/10.1016/j.compbiomed.2021.104504
---
