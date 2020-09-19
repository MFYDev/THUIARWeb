---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A heuristic-based hybrid genetic-variable neighborhood search algorithm for
  task scheduling in heterogeneous multiprocessor system
subtitle: ''
summary: ''
authors:
- YunWen
- HuaXu
- JiadongYang
tags:
- '"Variable neighborhood search"'
- '"Genetic algorithm"'
- '"Hybrid metaheuristic"'
- '"Memetic algorithm"'
- '"Heterogeneous multiprocessor scheduling"'
categories: []
date: '2011-01-01'
lastmod: 2020-09-19T21:38:49+08:00
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
publishDate: '2020-09-19T13:38:49.188341Z'
publication_types:
- 2
abstract: Effective task scheduling, which is essential for achieving high performance
  in a heterogeneous multiprocessor system, remains a challenging problem despite
  extensive studies. In this article, a heuristic-based hybrid genetic-variable neighborhood
  search algorithm is proposed for the minimization of makespan in the heterogeneous
  multiprocessor scheduling problem. The proposed algorithm distinguishes itself from
  many existing genetic algorithm (GA) approaches in three aspects. First, it incorporates
  GA with the variable neighborhood search (VNS) algorithm, a local search metaheuristic,
  to exploit the intrinsic structure of the solutions for guiding the exploration
  process of GA. Second, two novel neighborhood structures are proposed, in which
  problem-specific knowledge concerned with load balancing and communication reduction
  is utilized respectively, to improve both the search quality and efficiency of VNS.
  Third, the proposed algorithm restricts the use of GA to evolve the task-processor
  mapping solutions, while taking advantage of an upward-ranking heuristic mostly
  used by traditional list scheduling approaches to determine the task sequence assignment
  in each processor. Empirical results on benchmark task graphs of several well-known
  parallel applications, which have been validated by the use of non-parametric statistical
  tests, show that the proposed algorithm significantly outperforms several related
  algorithms in terms of the schedule quality. Further experiments are carried out
  to reveal that the proposed algorithm is able to maintain high performance within
  a wide range of parameter settings.
publication: '*Information Sciences*'
url_pdf: http://www.sciencedirect.com/science/article/pii/S0020025510004925
doi: https://doi.org/10.1016/j.ins.2010.10.001
---
