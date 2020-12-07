---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "CM-BERT: Cross-Modal BERT for Text-Audio Sentiment Analysis"
authors: [KaichengYang, HuaXu]
date: 2020-10-12T16:24:04+08:00
doi: "10.1145/3394171.3413690"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 28th ACM International Conference on Multimedia"
publication_short: "ACM MM2020"

abstract: "Multimodal sentiment analysis is an emerging research field that aims to enable machines to recognize, interpret, and express emotion. Through the cross-modal interaction, we can get more comprehensive emotional characteristics of the speaker. Bidirectional Encoder Representations from Transformers (BERT) is an efficient pre-trained language representation model. Fine-tuning it has obtained new state-of-the-art results on eleven natural language processing tasks like question answering and natural language inference. However, most previous works fine-tune BERT only base on text data, how to learn a better representation by introducing the multimodal information is still worth exploring. In this paper, we propose the Cross-Modal BERT (CM-BERT), which relies on the interaction of text and audio modality to fine-tune the pre-trained BERT model. As the core unit of the CM-BERT, masked multimodal attention is designed to dynamically adjust the weight of words by combining the information of text and audio modality. We evaluate our method on the public multimodal sentiment analysis datasets CMU-MOSI and CMU-MOSEI. The experiment results show that it has significantly improved the performance on all the metrics over previous baselines and text-only finetuning of BERT. Besides, we visualize the masked multimodal attention and proves that it can reasonably adjust the weight of words by introducing audio modality information."


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

url_pdf: https://doi.org/10.1145/3394171.3413690
url_code: https://github.com/thuiar/Cross-Modal-BERT
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
