---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Discovering New Intents via Constrained Deep Adaptive Clustering with Cluster Refinement"
authors: [TingenLin, HuaXu, HanleiZhang]
date: 2020-02-7T15:24:04+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-08-31T15:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Association for the Advancement of Artificial Intelligence (CCF A类会议)"
publication_short: "AAAI"

abstract: "Identifying new user intents is an essential task in the dialogue system. However, it is hard to get satisfying clustering results since the definition of intents is strongly guided by prior knowledge. Existing methods incorporate prior knowledge by intensive feature engineering, which not only leads to overfitting but also makes it sensitive to the number of clusters. In this paper, we propose constrained deep adaptive clustering with cluster refinement (CDAC+), an end-to-end clustering method that can naturally incorporate pairwise constraints as prior knowledge to guide the clustering process. Moreover, we refine the clusters by forcing the model to learn from the high confidence assignments. After eliminating low confidence assignments, our approach is surprisingly insensitive to the number of clusters. Experimental results on the three benchmark datasets show that our method can yield significant improvements over strong baselines."


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

url_pdf: https://arxiv.org/pdf/1911.08891
url_code: https://github.com/thuiar/CDAC-plus
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
