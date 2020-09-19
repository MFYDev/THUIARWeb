---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Chinese comments sentiment classification based on word2vec and SVMperf
subtitle: ''
summary: ''
authors:
- DongwenZhang
- HuaXu
- ZengcaiSu
- YunfengXu
tags:
- '"Sentiment classification"'
- '"Word2vec"'
- '"SVM"'
- '"Semantic features"'
categories: []
date: '2015-01-01'
lastmod: 2020-09-19T21:38:40+08:00
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
publishDate: '2020-09-19T13:38:40.089341Z'
publication_types:
- 2
abstract: Since the booming development of e-commerce in the last decade, the researchers
  have begun to pay more attention to extract the valuable information from consumers
  comments. Sentiment classification, which focuses on classify the comments into
  positive class and negative class according to the polarity of sentiment, is one
  of the studies. Machine learning-based method for sentiment classification becomes
  mainstream due to its outstanding performance. Most of the existing researches are
  centered on the extraction of lexical features and syntactic features, while the
  semantic relationships between words are ignored. In this paper, in order to get
  the semantic features, we propose a method for sentiment classification based on
  word2vec and SVMperf. Our research consists of two parts of work. First of all,
  we use word2vec to cluster the similar features for purpose of showing the capability
  of word2vec to capture the semantic features in selected domain and Chinese language.
  And then, we train and classify the comment texts using word2vec again and SVMperf.
  In the process, the lexicon-based and part-of-speech-based feature selection methods
  are respectively adopted to generate the training file. We conduct the experiments
  on the data set of Chinese comments on clothing products. The experimental results
  show the superior performance of our method in sentiment classification.
publication: '*Expert Systems with Applications*'
url_pdf: http://www.sciencedirect.com/science/article/pii/S0957417414005508
doi: https://doi.org/10.1016/j.eswa.2014.09.011
---
