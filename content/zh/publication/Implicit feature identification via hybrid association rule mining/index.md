---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Implicit feature identification via hybrid association rule mining
subtitle: ''
summary: ''
authors:
- WeiWang
- HuaXu
- WeiWan
tags:
- '"Opinion mining"'
- '"Implicit features"'
- '"Hybrid association rule mining"'
- '"Collocation extraction"'
categories: []
date: '2013-01-01'
lastmod: 2020-09-19T21:38:45+08:00
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
publishDate: '2020-09-19T13:38:44.974341Z'
publication_types:
- 2
abstract: In sentiment analysis, a finer-grained opinion mining method not only focuses
  on the view of the product itself, but also focuses on product features, which can
  be a component or attribute of the product. Previous related research mainly relied
  on explicit features but ignored implicit features. However, the implicit features,
  which are implied by some words or phrases, are so significant that they can express
  the users’ opinion and help us to better understand the users’ comments. It is a
  big challenge to detect these implicit features in Chinese product reviews, due
  to the complexity of Chinese. This paper is mainly centered on implicit features
  identification in Chinese product reviews. A novel hybrid association rule mining
  method is proposed for this task. The core idea of this approach is mining as many
  association rules as possible via several complementary algorithms. Firstly, we
  extract candidate feature indicators based word segmentation, part-of-speech (POS)
  tagging and feature clustering, then compute the co-occurrence degree between the
  candidate feature indicators and the feature words using five collocation extraction
  algorithms. Each indicator and the corresponding feature word constitute a rule
  (feature indicator → feature word). The best rules in five different rule sets are
  chosen as the basic rules. Next, three methods are proposed to mine some possible
  reasonable rules from the lower co-occurrence feature indicators and non indicator
  words. Finally, the latest rules are used to identify implicit features and the
  results are compared with the previous. Experiment results demonstrate that our
  proposed approach is competent at the task, especially via using several expanding
  methods. The recall is effectively improved, suggesting that the shortcomings of
  the basic rules have been overcome to certain extent. Besides those high co-occurrence
  degree indicators, the final rules also contain uncommon rules.
publication: '*Expert Systems with Applications*'
url_pdf: http://www.sciencedirect.com/science/article/pii/S0957417412013012
doi: https://doi.org/10.1016/j.eswa.2012.12.060
---
