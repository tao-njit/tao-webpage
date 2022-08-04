---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'OnSlicing: Online end-to-end network slicing with reinforcement learning'
subtitle: ''
summary: ''
authors:
- Qiang Liu
- Nakjung Choi
- Tao Han
tags: []
categories: []
date: '2021-12-01'
lastmod: 2021-12-12T21:35:07-04:00
featured: false
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
publishDate: '2021-12-13T02:20:26.421721Z'
publication_types:
- '1'
abstract: 'Network slicing allows mobile network operators to virtualize infrastructures and provide customized slices for supporting various use cases with heterogeneous requirements. Online deep reinforcement learning (DRL) has shown promising potential in solving network problems and eliminating the simulation-to-reality discrepancy. Optimizing cross-domain resources with online DRL is, however, challenging, as the random exploration of DRL violates the service level agreement (SLA) of slices and resource constraints of infrastructures. In this paper, we propose OnSlicing, an online end-to-end network slicing system, to achieve minimal resource usage while satisfying slice SLA. OnSlicing allows individualized learning for each slice and maintains its SLA by using a novel constraint-aware policy update method and proactive baseline switching mechanism. OnSlicing complies with resource constraints of infrastructures by using a unique design of action modification in slices and parameter coordination in infrastructures. OnSlicing further mitigates the poor performance of online learning during the early learning stage by offline imitating a rule-based solution. Besides, we design four new domain managers to enable dynamic resource configuration in radio access, transport, core, and edge networks, respectively, at a timescale of subseconds. We implement OnSlicing on an end-to-end slicing testbed designed based on OpenAirInterface with both 4G LTE and 5G NR, OpenDayLight SDN platform, and OpenAir-CN core network. The experimental results show that OnSlicing achieves 61.3% usage reduction as compared to the rule-based solution and maintains nearly zero violation (0.06%) throughout the online learning phase. As online learning is converged, OnSlicing reduces 12.5% usage without any violations as compared to the state-of-the-art online DRL solution.'
publication: '*The 17th International Conference on emerging Networking EXperiments and Technologies (ACM CoNEXT)*'
url_pdf: https://dl.acm.org/doi/10.1145/3485983.3494850
---

