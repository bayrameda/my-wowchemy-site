---
math: true
title: "Node Attribute Completion in Knowledge Graphs with Multi-Relational Propagation"
authors:
- Eda Bayram
- Alberto Garcia-Duran
- Robert West
date: "2020-11-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ICASSP 2021, IEEE International Conference on Acoustics, Speech and Signal Processing*
publication_short: In *ICASSP*

abstract: The existing literature on knowledge graph completion mostly focuses on the link prediction task. However, knowledge graphs have an additional incompleteness problem; their nodes possess numerical attributes, whose values are often missing. Our approach, denoted as MrAP, imputes the values of missing attributes by propagating information across the multi-relational structure of a knowledge graph. It employs regression functions for predicting one node attribute from another depending on the relationship between the nodes and the type of the attributes. The propagation mechanism operates iteratively in a message passing scheme that collects the predictions at every iteration and updates the value of the node attributes. Experiments over two benchmark datasets show the effectiveness of our approach.

# Summary. An optional shortened abstract.
summary: In this study, we address the incompleteness in the numerical node attributes of a knowledge graph. We propose the algorithm MrAP, Multi-Relational Attribute Propagation, which we formulate within a message passing scheme.

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: https://arxiv.org/pdf/2011.05301.pdf
url_code: 'https://github.com/bayrameda/MrAP'
# url_dataset: '#'
url_poster: 'https://drive.google.com/file/d/12pnn7h3ozl3FBcvXUu3oponTcCWMu16Z/view?usp=sharing'
#  url_project: ''
#  url_slides: ''
#  url_source: '#'
url_video: 'https://confcats-event-sessions.s3.amazonaws.com/icassp21/videos/4911.mp4?cyrwu13SqZgFyTMo1jq7VTWx8JgF9Ubk='
 # 'https://drive.google.com/file/d/1o-MP0OJBy9yQDa1K0yo3PGwgHVE7kWWB/view?usp=sharing'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  placement: 1
  focal_point: "TopLeft"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
