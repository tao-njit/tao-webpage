---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Edge Learning for Low-Latency Video Analytics: Query Scheduling and Resource Allocation'
subtitle: ''
summary: ''
authors:
- Jie Lin
- Peng Yang
- Wen Wu
- Ning Zhang
- Tao Han
- Li Yu
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
abstract: 'Low-latency and accuracy-guaranteed video analytics is essential to many delay-sensitive camera-based applications. Analyzing video frames on edge nodes in proximity can effectively reduce the response delay compared with cloud-based solutions. However, the computation and bandwidth resources on an edge node are always limited. In this paper, we design a joint video query scheduling and resource allocation problem based on an edge coordinated architecture, in order to properly accommodate real-time video queries on end cameras, the edge nodes, or the cloud. This problem is challenging in that 1) the arrivals of video queries with different resource requirements are unknown in advance and 2) the design space (of both query scheduling and resource allocation) to provision video queries varies over time. Taking the two-fold uncertainty into consideration, we formulate the query provision problem as a mix integer non-linear program which is NP-hard and not solved directly. To deal with the NP-hardness and the absence of future information, the problem is re-formulated as a Markov decision process, which can leverage historical query information to make decisions about scheduling and resource allocation. The transformed problem calls for an online solution that can efficiently adapt to the dynamic design space. Hence, we propose an edge-coordinated reinforcement learning algorithm to continuously learn from the environment, and make decisions for query scheduling and resource allocation to achieve low latency and accurate video analytics. Extensive simulation results demonstrate the advantages of the proposed algorithm in latency and accuracy.'
publication: '*IEEE 18th International Conference on Mobile Ad Hoc and Smart Systems (MASS)*'
url_pdf: https://ieeexplore.ieee.org/document/9637817
---

