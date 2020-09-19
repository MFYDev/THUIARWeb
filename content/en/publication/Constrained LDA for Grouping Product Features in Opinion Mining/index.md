---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Constrained LDA for Grouping Product Features in Opinion Mining
subtitle: ''
summary: ''
authors:
- ZhongwuZhai
- BingLiu
- HuaXu
- PeifaJia
tags: []
categories: []
date: '2011-01-01'
lastmod: 2020-09-19T21:55:49+08:00
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
publishDate: '2020-09-19T13:55:48.426867Z'
publication_types:
- 1
abstract: In opinion mining of product reviews, one often wants to produce a summary
  of opinions based on product features. However, for the same feature, people can
  express it with different words and phrases. To produce an effective summary, these
  words and phrases, which are domain synonyms, need to be grouped under the same
  feature. Topic modeling is a suitable method for the task. However, instead of simply
  letting topic modeling find groupings freely, we believe it is possible to do better
  by giving it some pre-existing knowledge in the form of automatically extracted
  constraints. In this paper, we first extend a popular topic modeling method, called
  Latent Dirichlet Allocation (LDA), with the ability to process large scale constraints.
  Then, two novel methods are proposed to extract two types of constraints automatically.
  Finally, the resulting constrained-LDA and the extracted constraints are applied
  to group product features. Experiments show that constrained-LDA outperforms the
  original LDA and the latest mLSA by a large margin.
publication: '*Advances in Knowledge Discovery and Data Mining*'
---
