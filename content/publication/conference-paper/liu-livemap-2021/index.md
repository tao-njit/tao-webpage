---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'LiveMap: Real-Time Dynamic Map in Automotive Edge Computing'
subtitle: ''
summary: ''
authors:
- Qiang Liu
- Tao Han
- Jiang Linda Xie
- BaekGyu Kim
tags: []
categories: []
date: '2021-05-01'
lastmod: 2021-08-12T21:35:06-04:00
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
publishDate: '2021-08-13T02:20:25.599205Z'
publication_types:
- '1'
abstract: 'Autonomous driving needs various line-of-sight sensors to perceive surroundings that could be impaired under diverse environment uncertainties such as visual occlusion and extreme weather.
To improve driving safety, we explore to wirelessly share perception information among connected vehicles within automotive edge computing networks.
Sharing massive perception data in real time, however, is challenging under dynamic networking conditions and varying computation workloads.
In this paper, we propose _LiveMap_, a real-time dynamic map, that detects, matches, and tracks objects on the road with crowdsourcing data from connected vehicles in sub-second.
We develop the data plane of _LiveMap_ that efficiently processes individual vehicle data with object detection, projection, feature extraction, object matching, and effectively integrates objects from multiple vehicles with object combination.
We design the control plane of _LiveMap_ that allows adaptive offloading of vehicle computations, and develop an intelligent vehicle scheduling and offloading algorithm to reduce the offloading latency of vehicles based on deep reinforcement learning (DRL) techniques.
We implement _LiveMap_ on a small-scale testbed and develop a large-scale network simulator.
We evaluate the performance of _LiveMap_ with both experiments and simulations, and the results show _LiveMap_ reduces 34.1% average latency than the baseline solution.'
publication: '*IEEE Conference on Computer Communications (INFOCOM)*'
url_pdf: https://ieeexplore.ieee.org/document/9488872/
doi: 10.1109/INFOCOM42981.2021.9488872
---
