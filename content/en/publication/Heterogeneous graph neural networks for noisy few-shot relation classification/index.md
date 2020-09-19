---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Heterogeneous graph neural networks for noisy few-shot relation classification
subtitle: ''
summary: ''
authors:
- YuxiangXie
- HuaXu
- JiaoeLi
- CongcongYang
- KaiGao
tags:
- '"Relation extraction"'
- '"Heterogeneous graph neural networks"'
- '"Few-shot learning"'
- '"Adversarial learning"'
categories: []
date: '2020-01-01'
lastmod: 2020-09-19T21:38:35+08:00
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
publishDate: '2020-09-19T13:38:34.616343Z'
publication_types:
- 2
abstract: Relation classification is an essential and fundamental task in natural
  language processing. Distant supervised methods have achieved great success on relation
  classification, which improve the performance of the task through automatically
  extending the dataset. However, the distant supervised methods also bring the problem
  of wrong labeling. Inspired by people learning new knowledge from only a few samples,
  we focus on predicting formerly unseen classes with a few labeled data. In this
  paper, we propose a heterogeneous graph neural network for few-shot relation classification,
  which contains sentence nodes and entity nodes. We build the heterogeneous graph
  based on the message passing between entity nodes and sentence nodes in the graph,
  which can capture rich neighborhood information of the graph. Besides, we introduce
  adversarial learning for training a robust model and evaluate our heterogeneous
  graph neural networks under the scene of introducing different rates of noise data.
  Experimental results have demonstrated that our model outperforms the state-of-the-art
  baseline models on the FewRel dataset.
publication: '*Knowledge-Based Systems*'
url_pdf: http://www.sciencedirect.com/science/article/pii/S0950705120300447
doi: https://doi.org/10.1016/j.knosys.2020.105548
---
