---
title: 'MMNeRF: Multi-modal and multi-view optimized cross-scene neural radiance fields'
authors:
- Qi Zhang
- Bo Han Wang
- Ming Chuan Yang
- Hang Zou
date: '2023-01-01'
publishDate: '2024-05-07T09:59:02.163683Z'
publication_types:
- article-journal
publication: '*IEEE Access*'
doi: 10.1109/ACCESS.2023.3254548
abstract: We present MMNeRF, a simple yet powerful learning framework for highly photo-realistic
  novel view synthesis by learning Multi-modal and Multi-view features to guide neural
  radiance fields to a generic model. Novel view synthesis has achieved great improvement
  with the significant success of NeRFseries methods. However, how to make the method
  generic across scenes has always been a challenging task. A good idea is to introduce
  2D image features as prior knowledge for adaptive modeling, yet RGB features lack
  geometry and 3D spatial information, which causes shape-radiance ambiguity issues
  and lead to blurry and low-resolution results in the synthesis images. We propose
  a multi-modal multi-view method to make up for the existing methods. Specifically,
  we introduce depth features besides RGB features into the model and effectively
  fuse these multi-modal features by modality-based attention. Furthermore, Our framework
  innovatively adopts the transformer encoder to fuse multi-view features and uses
  the transformer decoder to adaptively incorporate the target view with global memory.
  Extensive experiments are carried out on both categories-specific and category-agnostic
  benchmarks, and the results demonstrate that our MMNeRF achieves state-of-the-art
  neural rendering performance.
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10064260/
---
