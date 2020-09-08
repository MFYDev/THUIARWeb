---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "FastBTM: Reducing the Sampling Time for Biterm Topic Model"
authors: [XingweiHe,HuaXu, JiaLi]
date: 2017-9-15T15:24:04+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-31T15:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Knowledge-based Systems"
publication_short: "KBS"

abstract: "Due to the popularity of social networks, such as microblogs and Twitter, a vast amount of short text data is created every day. Much recent research in short text becomes increasingly significant, such as topic inference for short text. Biterm topic model (BTM) benefits from the word co-occurrence patterns of the corpus, which makes it perform better than conventional topic models in uncovering latent semantic relevance for short text. However, BTM resorts to Gibbs sampling to infer topics, which is very time consuming, especially for large-scale datasets or when the number of topics is extremely large. It requires O(K) operations per sample for K topics, where K denotes the number of topics in the corpus. In this paper, we propose an acceleration algorithm of BTM, FastBTM, using an efficient sampling method for BTM, which converges much faster than BTM without degrading topic quality. FastBTM is based on Metropolis-Hastings and alias method, both of which have been widely adopted in Latent Dirichlet Allocation (LDA) model and achieved outstanding speedup. Our FastBTM can effectively reduce the sampling complexity of biterm topic model from O(K) to O(1) amortized time. We carry out a number of experiments on three datasets including two short text datasets, Tweets2011 Collection dataset and Yahoo! Answers dataset, and one long document dataset, Enron dataset. Our experimental results show that when the number of topics K increases, the gap in running time speed between FastBTM and BTM gets especially larger. In addition, our FastBTM is effective for both short text datasets and long document datasets."


tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0950705117302782
url_code: 
url_dataset: 
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
