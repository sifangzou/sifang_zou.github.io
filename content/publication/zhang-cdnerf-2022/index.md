---
title: 'CDNeRF: A multi-modal feature guided neural radiance fields'
authors:
- Qi Zhang
- Qiaoqiao Liu
- Hang Zou
date: '2022-01-01'
publishDate: '2024-05-07T09:59:02.173645Z'
publication_types:
- paper-conference
publication: '*Artificial Intelligence*'
abstract: We present CDNeRF, a simple yet powerful learning framework that creates
  novel view synthesis by reconstructing neural radiance fields from a single view
  RGB image. Novel view synthesis by neural radiance fields has achieved great improvement
  with the development of deep learning. However, how to make the method generic across
  scenes has always been a challenging task. A good idea is to introduce 2D image
  features as prior knowledge for adaptive modeling, yet RGB features (C) lack geometry
  and 3D spacial information. To compensate, we introduce depth features into the
  model. Our method uses a variant depth estimation network to extract depth features
  (D) without the need for additional input. In addition, we also introduce the transformer
  module to effectively fuse the multi-modal features of RGB and depth. Extensive
  experiments are carried out on two categories specific benchmarks (i.e., Chair,
  Car) and two category agnostic benchmarks (i.e., ShapeNet, DTU). The results demonstrate
  that our CDNeRF outperforms the previous methods, and achieves state-of-the-art
  neural rendering performance.
---
