---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'BitHash: An efficient bitwise Locality Sensitive Hashing method with applications'
subtitle: ''
summary: ''
authors:
- WenhaoZhang
- JianqiuJi
- JunZhu
- JianminLi
- HuaXu
- BoZhang
tags:
- '"Locality Sensitive Hashing"'
- '"BitHash"'
- '"Near-duplicate detection"'
- '"Machine learning"'
- '"Sentiment analysis"'
- '"Storage efficiency"'
categories: []
date: '2016-01-01'
lastmod: 2020-09-19T21:38:38+08:00
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
publishDate: '2020-09-19T13:38:37.383344Z'
publication_types:
- 2
abstract: Locality Sensitive Hashing has been applied to detecting near-duplicate
  images, videos and web documents. In this paper we present a Bitwise Locality Sensitive
  method by using only one bit per hash value (BitHash), the storage space for storing
  hash values is significantly reduced, and the estimator can be computed much faster.
  The method provides an unbiased estimate of pairwise Jaccard similarity, and the
  estimator is a linear function of Hamming distance, which is very simple. We rigorously
  analyze the variance of One-Bit Min-Hash (BitHash), showing that for high Jaccard
  similarity. BitHash may provide accurate estimation, and as the pairwise Jaccard
  similarity increases, the variance ratio of BitHash over the original min-hash decreases.
  Furthermore, BitHash compresses each data sample into a compact binary hash code
  while preserving the pairwise similarity of the original data. The binary code can
  be used as a compressed and informative representation in replacement of the original
  data for subsequent processing. For example, it can be naturally integrated with
  a classifier like SVM. We apply BitHash to two typical applications, near-duplicate
  image detection and sentiment analysis. Experiments on real user’s photo collection
  and a popular sentiment analysis data set show that, the classification accuracy
  of our proposed method for two applications could approach the state-of-the-art
  method, while BitHash only requires a significantly smaller storage space.
publication: '*Knowledge-Based Systems*'
url_pdf: http://www.sciencedirect.com/science/article/pii/S0950705116000423
doi: https://doi.org/10.1016/j.knosys.2016.01.022
---
