---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Two-Stage Attention Network for Aspect-Level Sentiment Classification
subtitle: ''
summary: ''
authors:
- KaiGao
- HuaXu
- ChengliangGao
- XiaominSun
- JunhuiDeng
- XiaomingZhang
tags: []
categories: []
date: '2018-01-01'
lastmod: 2020-09-19T21:55:32+08:00
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
publishDate: '2020-09-19T13:55:31.487527Z'
publication_types:
- 1
abstract: 'Currently, most of attention-based works adopt single-stage attention processes
  during generating context representations toward aspect, but their work lacks the
  deliberation process: A generated and aspect-related representation is directly
  used as final output without further polishing. In this work, we introduce the deliberation
  process to model context for further polishing of attention weights, and then propose
  a two-stage attention network for aspect-level sentiment classification. The network
  uses of a two-level attention model with LSTM, where the first-stage attention generates
  a raw aspect-related representation and the second-stage attention polishes and
  refines the raw representation by deliberation process. Since the deliberation component
  has global information what the representation to be generated might be, it has
  the potential to generate a better aspect-related representation by secondly looking
  into hidden state produced by LSTM. Experimental results on the dataset of SemEval-2016
  task 5 about Laptop indicates that our model achieved the state-of-the-art accuracy
  of 76.56%.'
publication: '*Neural Information Processing*'
---
