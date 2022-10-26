---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Atlas: Automate Online Service Configuration in Network Slicing'
subtitle: ''
summary: ''
authors:
- Qiang Liu
- Nakjung Choi
- Tao Han
tags: []
categories: []
date: '2022-10--25'
lastmod: 2022-10-25T21:35:07-04:00
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
publishDate: '2022-10-25T02:20:26.421721Z'
publication_types:
- '1'
abstract: 'Network slicing achieves cost-efficient slice customization to support heterogeneous applications and services. Configuring cross-domain resources to end-to-end slices based on service-level agreements, however, is challenging, due to the complicated underlying correlations and the simulation-to-reality discrepancy between simulators and real networks. In this paper, we propose Atlas, an online network slicing system, which automates the service configuration of slices via safe and sample-efficient learn-to-configure approaches in three interrelated stages. First, we design a learning-based simulator to reduce the sim-to-real discrepancy, which is accomplished by a new parameter searching method based on Bayesian optimization. Second, we offline train the policy in the augmented simulator via a novel offline algorithm with a Bayesian neural network and parallel Thompson sampling. Third, we online learn the policy in real networks with a novel online algorithm with safe exploration and Gaussian process regression. We implement Atlas on an end-to-end network prototype based on OpenAirInterface RAN, OpenDayLight SDN transport, OpenAir-CN core network, and Docker-based edge server. Experimental results show that, compared to state-of-the-art solutions, Atlas achieves 63.9% and 85.7% regret reduction on resource usage and slice quality of experience during the online learning stage, respectively.'
publication: '*The 18th International Conference on emerging Networking EXperiments and Technologies (ACM CoNEXT)*'
url_pdf: 
---

