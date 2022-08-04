---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'FedSTN: Graph Representation Driven Federated Learning for Edge Computing Enabled Urban Traffic Flow Prediction'
subtitle: ''
summary: ''
authors:
- Xiaoming Yuan
- Jiahui Chen
- Jiayu Yang
- Ning Zhang
- Tingting Yang
- Tao Han
- Amir Taherkordi
tags: []
categories: []
date: '2022-03-01'
lastmod: 2022-03-01T22:37:23-04:00
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
publishDate: '2022-03-01T02:37:22.245006Z'
publication_types:
- '2'
abstract: 'Predicting traffic flow plays an important role in reducing traffic congestion and improving transportation efficiency for smart cities. Traffic Flow Prediction (TFP) in the smart city requires efficient models, highly reliable networks, and data privacy. As traffic data, traffic trajectory can be transformed into a graph representation, so as to mine the spatio-temporal information of the graph for TFP. However, most existing work adopt a central training mode where the privacy problem brought by the distributed traffic data is not considered. In this paper, we propose a Federated Deep Learning based on the Spatial-Temporal Long and Short-Term Networks (FedSTN) algorithm to predict traffic flow by utilizing observed historical traffic data. In FedSTN, each local TFP model deployed in an edge computing server includes three main components, namely Recurrent Long-term Capture Network (RLCN) module, Attentive Mechanism Federated Network (AMFN) module, and Semantic Capture Network (SCN) module. RLCN can capture the long-term spatial-temporal information in each area. AMFN shares short-term spatio-temporal hidden information when it trains its local TFP model by the additive homomorphic encryption approach based on Vertical Federated Learning (VFL). We employ SCN to capture semantic features such as irregular non-Euclidean connections and Point of Interest (POI). Compared with existing baselines, several simulations are conducted on practical data sets and the results prove the effectiveness of our algorithm.'
publication: '*IEEE Transactions on Intelligent Transportation Systems*'
url_pdf: https://ieeexplore.ieee.org/abstract/document/9737410
doi: 10.1109/TITS.2022.3157056
---
