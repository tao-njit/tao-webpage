---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'EdgeSlice: Slicing Wireless Edge Computing Network with Decentralized Deep
  Reinforcement Learning'
subtitle: ''
summary: ''
authors:
- Qiang Liu
- Tao Han
- Ephraim Moges
tags: []
categories: []
date: '2020-07-01'
lastmod: 2021-08-12T17:50:11-04:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-07-01T02:20:02.968195Z'
publication_types:
- '1'
abstract: '5G and edge computing will serve various emerging use cases that have diverse requirements of multiple resources, e.g., radio, transportation, and computing. Network slicing is a promising technology for creating virtual networks that can be customized according to the requirements of different use cases. Provisioning network slices requires end-to-end resource orchestration which is challenging. In this paper, we design a decentralized resource orchestration system named EdgeSlice for dynamic end-to-end network slicing. EdgeSlice introduces a new decentralized deep reinforcement learning (D-DRL) method to efficiently orchestrate end-to-end resources. D-DRL is composed of a performance coordinator and multiple orchestration agents. The performance coordinator manages the resource orchestration policies in all the orchestration agents to ensure the service level agreement (SLA) of network slices. The orchestration agent learns the resource demands of network slices and orchestrates the resource allocation accordingly to optimize the performance of the slices under the constrained networking and computing resources. We design radio, transport and computing manager to enable dynamic configuration of end-to-end resources at runtime. We implement EdgeSlice on a prototype of the end-to-end wireless edge computing network with OpenAirInterface LTE network, OpenDayLight SDN switches, and CUDA GPU platform. The performance of EdgeSlice is evaluated through both experiments and trace-driven simulations. The evaluation results show that EdgeSlice achieves much improvement as compared to baseline in terms of performance, scalability, compatibility.'
publication: '*IEEE International Conference on Distributed Computing Systems (ICDCS)*'
url_pdf: https://arxiv.org/pdf/2003.12911.pdf
---
