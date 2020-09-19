---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Noisy Multiobjective Black-Box Optimization Using Bayesian Optimization
subtitle: ''
summary: ''
authors:
- HongyanWang
- HuaXu
- YuanYuan
- JunhuiDeng
- XiaominSun
tags:
- '"gaussian noise"'
- '"gaussian process"'
- '"ParEGO"'
- '"black-box optimization"'
- '"expensive multiobjective optimization"'
categories: []
date: '2019-01-01'
lastmod: 2020-09-19T21:55:29+08:00
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
publishDate: '2020-09-19T13:55:28.463251Z'
publication_types:
- 1
abstract: Expensive black-box problems are usually optimized by Bayesian Optimization
  (BO) since it can reduce evaluation costs via cheaper surrogates. The most popular
  model used in Bayesian Optimization is the Gaussian process (GP) whose posterior
  is based on a joint GP prior built by initial observations, so the posterior is
  also a Gaussian process. Observations are often not noise-free, so in most of these
  cases, a noisy transformation of the objective space is observed. Many single objective
  optimization algorithms have succeeded in extending efficient global optimization
  (EGO) to noisy circumstances, while ParEGO fails to consider noise. In order to
  deal with noisy expensive black-box problems, we extending ParEGO to noisy optimization
  according to adding a Gaussian noisy error while approximating the surrogate. We
  call it noisy-ParEGO and results of S-metric indicate that the algorithm works well
  on optimizing noisy expensive multiobjective black-box problems.
publication: '*Proceedings of the Genetic and Evolutionary Computation Conference
  Companion*'
url_pdf: https://doi.org/10.1145/3319619.3321898
doi: 10.1145/3319619.3321898
---
