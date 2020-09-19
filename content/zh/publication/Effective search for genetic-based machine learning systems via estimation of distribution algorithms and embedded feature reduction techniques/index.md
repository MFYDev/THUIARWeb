---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Effective search for genetic-based machine learning systems via estimation
  of distribution algorithms and embedded feature reduction techniques
subtitle: ''
summary: ''
authors:
- JiadongYang
- HuaXu
- PeifaJia
tags:
- '"Genetic-based machine learning systems"'
- '"Estimation of distribution algorithms"'
- '"Features reduction"'
- '"Evolutionary computation"'
categories: []
date: '2013-01-01'
lastmod: 2020-09-19T21:38:44+08:00
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
publishDate: '2020-09-19T13:38:43.598345Z'
publication_types:
- 2
abstract: Genetic-based machine learning (GBML) systems, which employ evolutionary
  algorithms (EAs) as search mechanisms, evolve rule-based classification models to
  represent target concepts. Compared to Michigan-style GBML, Pittsburgh-style GBML
  is expected to achieve more compact solutions. It has been shown that standard recombination
  operators in EAs do not assure an effective evolutionary search to solve sophisticated
  problems that contain strong interactions between features. On the other hand, when
  dealing with real-world classification tasks, irrelevant features not only complicate
  the problem but also incur unnecessary matchings in GBML systems, which increase
  the computational cost a lot. To handle the two problems mentioned above in an integrated
  manner, a new Pittsburgh-style GBML system is proposed. In the proposed method,
  classifiers are generated and recombined at two levels. At the high level, classifiers
  are recombined by rule-wise uniform crossover operators since each classifier consists
  of a variable-size rule set. At the low level, single rules contained in classifiers
  are reproduced via sampling Bayesian networks that characterize the global statistical
  information extracted from promising rules found so far. Furthermore, according
  to the statistical information in the rule population, an embedded approach is presented
  to detect and remove redundant features incrementally following the evolution of
  rule population. Results of empirical evaluation show that the proposed method outperforms
  the original Pittsburgh-style GBML system in terms of classification accuracy while
  reducing the computational cost. Furthermore, the proposed method is also competitive
  to other non-evolutionary, highly used machine learning methods. With respect to
  the performance of feature reduction, the proposed embedded approach is able to
  deliver solutions with higher classification accuracy when removing the same number
  of features as other feature reduction techniques do.
publication: '*Neurocomputing*'
url_pdf: http://www.sciencedirect.com/science/article/pii/S092523121300177X
doi: https://doi.org/10.1016/j.neucom.2013.01.014
---
