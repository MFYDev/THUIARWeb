---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: An Experimental Investigation of Variation Operators in Reference-Point Based
  Many-Objective Optimization
subtitle: ''
summary: ''
authors:
- YuanYuan
- HuaXu
- BoWang
tags:
- '"many-objective optimization"'
- '"differential evolution"'
- '"NSGA-III"'
- '"variation operators"'
- '"reference-point"'
categories: []
date: '2015-01-01'
lastmod: 2020-09-19T21:55:40+08:00
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
publishDate: '2020-09-19T13:55:39.432978Z'
publication_types:
- 1
abstract: Reference-point based multi-objective evolutionary algorithms (MOEAs) have
  shown promising performance in many-objective optimization. However, most of existing
  research within this area focused on improving the environmental selection procedure,
  and little work has been done on the effect of variation operators. In this paper,
  we conduct an experimental investigation of variation operators in a typical reference-point
  based MOEA, i.e., NSGA-III. First, we provide a new NSGA-III variant, i.e., NSGA-III-DE,
  which introduces differential evolution (DE) operator into NSGA-III, and we further
  examine the effect of two main control parameters in NSGA-III-DE. Second, we have
  an experimental analysis of the search behavior of NSGA-III-DE and NSGA-III. We
  observe that NSGA-III-DE is generally better at exploration whereas NSGA-III normally
  has advantages in exploitation. Third, based on this observation, we present two
  other NSGA-III variants, where DE operator and genetic operators are simply combined
  to reproduce solutions. Experimental results on several benchmark problems show
  that very encouraging performance can be achieved by three suggested new NSGA-III
  variants. Our work also indicates that the performance of NSGA-III is significantly
  bottlenecked by its variation operators, providing opportunities for the study of
  the other alternative ones.
publication: '*Proceedings of the 2015 Annual Conference on Genetic and Evolutionary
  Computation*'
url_pdf: https://doi.org/10.1145/2739480.2754655
doi: 10.1145/2739480.2754655
---
