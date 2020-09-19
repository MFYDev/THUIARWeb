---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Cross Entropy and Adaptive Variance Scaling in Continuous EDA
subtitle: ''
summary: ''
authors:
- YunpengCai
- XiaominSun
- HuaXu
- PeifaJia
tags:
- '"cross entropy"'
- '"adaptive variance scaling"'
- '"estimation of distirbution algorithms"'
- '"evolutionary computation"'
categories: []
date: '2007-01-01'
lastmod: 2020-09-19T21:55:55+08:00
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
publishDate: '2020-09-19T13:55:54.412453Z'
publication_types:
- 1
abstract: This paper deals with the adaptive variance scaling issue incontinuous Estimation
  of Distribution Algorithms. A phenomenon is discovered that current adaptive variance
  scaling method in EDA suffers from imprecise structure learning. A new type of adaptation
  method is proposed to overcome this defect. The method tries to measure the difference
  between the obtained population and the prediction of the probabilistic model, then
  calculate the scaling factor by minimizing the cross entropy between these two distributions.
  This approach calculates the scaling factor immediately rather than adapts it incrementally.
  Experiments show that this approach extended the class of problems that can be solved,
  and improve the search efficiency in some cases. Moreover, the proposed approach
  features in that each decomposed subspace can be assigned an individual scaling
  factor, which helps to solve problems with special dimension property.
publication: '*Proceedings of the 9th Annual Conference on Genetic and Evolutionary
  Computation*'
url_pdf: https://doi.org/10.1145/1276958.1277081
doi: 10.1145/1276958.1277081
---
