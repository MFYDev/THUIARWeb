---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Deep Unknown Intent Detection with Margin Loss
subtitle: ''
summary: ''
authors:
- TingenLin
- HuaXu
tags: []
categories: []
date: '2019-07-01'
lastmod: 2020-09-19T20:37:11+08:00
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
publishDate: '2020-09-19T12:37:10.244831Z'
publication_types:
- 1
abstract: Identifying the unknown (novel) user intents that have never appeared in
  the training set is a challenging task in the dialogue system. In this paper, we
  present a two-stage method for detecting unknown intents. We use bidirectional long
  short-term memory (BiLSTM) network with the margin loss as the feature extractor.
  With margin loss, we can learn discriminative deep features by forcing the network
  to maximize inter-class variance and to minimize intra-class variance. Then, we
  feed the feature vectors to the density-based novelty detection algorithm, local
  outlier factor (LOF), to detect unknown intents. Experiments on two benchmark datasets
  show that our method can yield consistent improvements compared with the baseline
  methods.
publication: '*Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics*'
url_pdf: https://www.aclweb.org/anthology/P19-1548
doi: 10.18653/v1/P19-1548
---
