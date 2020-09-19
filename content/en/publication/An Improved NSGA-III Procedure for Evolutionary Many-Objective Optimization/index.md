---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: An Improved NSGA-III Procedure for Evolutionary Many-Objective Optimization
subtitle: ''
summary: ''
authors:
- YuanYuan
- HuaXu
- BoWang
tags:
- '"non-dominated sorting"'
- '"NSGA-III"'
- '"many-objective optimization"'
- '"牟-dominance"'
categories: []
date: '2014-01-01'
lastmod: 2020-09-19T21:55:42+08:00
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
publishDate: '2020-09-19T13:55:41.389860Z'
publication_types:
- 1
abstract: Many-objective (four or more objectives) optimization problems pose a great
  challenge to the classical Pareto-dominance based multi-objective evolutionary algorithms
  (MOEAs), such as NSGA-II and SPEA2. This is mainly due to the fact that the selection
  pressure based on Pareto-dominance degrades severely with the number of objectives
  increasing. Very recently, a reference-point based NSGA-II, referred as NSGA-III,
  is suggested to deal with many-objective problems, where the maintenance of diversity
  among population members is aided by supplying and adaptively updating a number
  of well-spread reference points. However, NSGA-III still relies on Pareto-dominance
  to push the population towards Pareto front (PF), leaving room for the improvement
  of its convergence ability. In this paper, an improved NSGA-III procedure, called
  牟-NSGA-III, is proposed, aiming to better tradeoff the convergence and diversity
  in many-objective optimization. In 牟-NSGA-III, the non-dominated sorting scheme
  based on the proposed 牟-dominance is employed to rank solutions in the environmental
  selection phase, which ensures both convergence and diversity. Computational experiments
  have shown that 牟-NSGA-III is significantly better than the original NSGA-III and
  MOEA/D on most instances no matter in convergence and overall performance.
publication: '*Proceedings of the 2014 Annual Conference on Genetic and Evolutionary
  Computation*'
url_pdf: https://doi.org/10.1145/2576768.2598342
doi: 10.1145/2576768.2598342
---
