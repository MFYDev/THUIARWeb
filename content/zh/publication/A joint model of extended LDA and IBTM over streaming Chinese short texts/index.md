---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A joint model of extended LDA and IBTM over streaming Chinese short texts"
authors: [HuaXu, JiaLi]
date: 2019-4-15T15:24:04+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-31T15:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Intelligent Data Analysis, vol. 23, no. 3, pp. 681-699, 2019"
publication_short: "IDA"

abstract: "With the prevalent of short texts, discovering the topics within them has become an important task. Biterm Topic Model (BTM) is more suitable to discover topics on short texts than traditional topic models. However, there are still some challenges that dealing short texts with BTM will always ignore the document-topic semantic information and lack the true intentions of users. In addition, it is a static method and can not manage streaming short texts when a new one arrives immediately. In order to keep document-topic information and get the topic distribution of a new short text at once, we propose a joint model based on online algorithms of Latent Dirichlet Allocation (LDA) and BTM, which combines the merits of both models. Not only does it alleviate the sparsity when addressing short texts with the online algorithm of BTM, namely Incremental Biterm Topic Model (IBTM), but also keeps document-topic information with extended LDA. And considering the differences between English and Chinese text in writing, we use combined words in short texts as key words to extend the length of short texts and keep the true intensions of users. As shown in the experiment results on two real world datasets, our method is better than other baseline methods. In the end, we explain an application of our method in the task of discovering user interest tags."


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

url_pdf: https://content.iospress.com/articles/intelligent-data-analysis/ida183836
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
