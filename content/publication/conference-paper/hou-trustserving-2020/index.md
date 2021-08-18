---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'TrustServing: A Quality Inspection Sampling Approach for Remote DNN Services'
subtitle: ''
summary: ''
authors:
- Xueyu Hou
- Tao Han
tags: []
categories: []
date: '2020-06-01'
lastmod: 2021-08-12T17:50:12-04:00
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
publishDate: '2021-08-13T02:20:04.662385Z'
publication_types:
- '1'
abstract: 'Deep neural networks (DNNs) are being applied to various areas such as computer vision, autonomous vehicles, and healthcare, etc. However, DNNs are notorious for their high computational complexity and cannot be executed efficiently on resource constrained Internet of Things (IoT) devices. Various solutions have been proposed to handle the high computational complexity of DNNs. Offloading computing tasks of DNNs from IoT devices to cloud/edge servers is one of the most popular and promising solutions. While such remote DNN services provided by servers largely reduce computing tasks on IoT devices, it is challenging for IoT devices to inspect whether the quality of the service meets their service level objectives (SLO) or not. In this paper, we address this problem and propose a novel approach named QIS (quality inspection sampling) that can efficiently inspect the quality of the remote DNN services for IoT devices. To realize QIS, we design a new ID-generation method to generate data (IDs) that can identify the serving DNN models on edge servers. QIS inserts the IDs into the input data stream and implements sampling inspection on SLO violations. The experiment results show that the QIS approach can reliably inspect, with a nearly 100% success rate, the service qualtiy of remote DNN services when the SLA level is 99.9% or lower at the cost of only up to 0.5% overhead.'
publication: '*IEEE International Conference on Sensing, Communication and Networking
  (SECON)*'
---

