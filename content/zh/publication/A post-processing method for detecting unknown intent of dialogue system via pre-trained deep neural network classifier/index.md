---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A post-processing method for detecting unknown intent of dialogue system via pre-trained deep neural network classifier
subtitle: ''
summary: ''
authors:
- TingenLin
- HuaXu
tags:
- '"Novelty detection"'
- '"Open-world classification"'
- '"Probability calibration"'
- '"Platt scaling"'
- '"Dialogue system"'
- '"Deep neural network"'
categories: []
date: '2019-01-01'
lastmod: 2020-09-19T21:38:36+08:00
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
publishDate: '2020-09-19T13:38:35.985341Z'
publication_types:
- 2
abstract: With the maturity and popularity of dialogue systems, detecting user’s unknown
  intent in dialogue systems has become an important task. It is also one of the most
  challenging tasks since we can hardly get examples, prior knowledge or the exact
  numbers of unknown intents. In this paper, we propose SofterMax and deep novelty
  detection (SMDN), a simple yet effective post-processing method for detecting unknown
  intent in dialogue systems based on pre-trained deep neural network classifiers.
  Our method can be flexibly applied on top of any classifiers trained in deep neural
  networks without changing the model architecture. We calibrate the confidence of
  the softmax outputs to compute the calibrated confidence score (i.e., SofterMax)
  and use it to calculate the decision boundary for unknown intent detection. Furthermore,
  we feed the feature representations learned by the deep neural networks into traditional
  novelty detection algorithm to detect unknown intents from different perspectives.
  Finally, we combine the methods above to perform the joint prediction. Our method
  classifies examples that differ from known intents as unknown and does not require
  any examples or prior knowledge of it. We have conducted extensive experiments on
  three benchmark dialogue datasets. The results show that our method can yield significant
  improvements compared with the state-of-the-art baselines1 1The code will be available
  at https://github.com/tnlin/SMDN..
publication: '*Knowledge-Based Systems*'
url_pdf: http://www.sciencedirect.com/science/article/pii/S0950705119304034
doi: https://doi.org/10.1016/j.knosys.2019.104979
---
