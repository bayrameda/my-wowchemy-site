---
math: true
title: "Propagation on Multi-relational Graphs for Node Regression"
authors:
- Eda Bayram
date: "2021-11-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
#publication: In *IJCLR2021, 10th International Workshop on Statistical Relational AI*
#publication_short: In *StarAI*
publication: In *IJCLR2021, 10th International Workshop on Statistical Relational AI*
publication_short: In *StarAI*

abstract: Recent years have witnessed a rise in real-world data captured with rich structural information that can be conveniently depicted by multi-relational graphs. While inference of continuous node features across a simple graph is rather under-studied by the current relational learning research, we go one step further and focus on node regression problem on multi-relational graphs. We take inspiration from the well-known label propagation algorithm aiming at completing categorical features across a simple graph and propose a novel propagation framework for completing missing continuous features at the nodes of a multi-relational and directed graph. Our multi-relational propagation algorithm is composed of iterative neighborhood aggregations which originate from a relational local generative model. Our findings show the benefit of exploiting the multi-relational structure of the data in several node regression scenarios in different settings.

# Summary. An optional shortened abstract.
summary: Multi-relational Propagation (MrP) suggests a propagation approach designed for CONTINUOUS labels, and how to complete them on multi-relational and directed graphs.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/pdf/2110.08185.pdf
url_code: 'https://github.com/bayrameda/MrAP'
# url_dataset: '#'
url_poster: 'http://lr2020.iit.demokritos.gr/posters/57.pdf'
#  url_project: ''
#  url_slides: ''
#  url_source: '#'
url_video: 'https://drive.google.com/file/d/1QRJBdK3krVoSHyjkVF1INnMiMXEdnlYJ/view?usp=sharing'
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
