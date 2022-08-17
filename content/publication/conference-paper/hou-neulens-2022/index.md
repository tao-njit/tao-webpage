---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'NeuLens: Spatial-based Dynamic Acceleration of Convolutional Neural Networks on Edge'
subtitle: ''
summary: ''
authors:
- Xueyu Hou
- Yongjie Guan
- Tao Han
tags: []
categories: []
date: '2022-08-17'
lastmod: 2022-08-17T17:50:12-04:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'System Overview'
  focal_point: 'Smart'
  preview_only: false
  

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-08-17T02:20:04.662385Z'
publication_types:
- '1'
abstract: 'Convolutional neural networks (CNNs) play an important role in mobile and edge computing systems for vision-based tasks like object classification and detection. However, state-of-the-art methods on CNN acceleration are trapped in either limited practical latency speed-up on general computing platforms or latency speed-up with severe accuracy loss. In this paper, we propose a spatial-based dynamic CNN acceleration framework, NeuLens, for mobile and edge platforms. Specially, we design a novel dynamic inference mechanism, assemble region-aware convolution (ARAC) supernet, that peels off redundant operations inside CNN models as many as possible based on spatial redundancy and channel slicing. In ARAC supernet, the CNN inference flow is split into multiple independent \textit{micro}-flows, and the computational cost of each can be autonomously adjusted based on its tiled-input content and application requirements. These micro-flows can be loaded into hardware like GPUs as single models. Consequently, its operation reduction can be well translated into latency speed-up and is compatible with hardware-level accelerations like cuDNN. Moreover, the inference accuracy can be well preserved by identifying critical regions on images and processing them in the original resolution with large micro-flow. Based on our evaluation, NeuLens outperforms baseline methods by 47.9% latency reduction with the same accuracy and by 67.9% accuracy improvement under the same latency/memory constraints.'
publication: '*The 28th Annual International Conference On Mobile Computing And Networking (ACM MobiCom)*'
url_pdf: 
---

