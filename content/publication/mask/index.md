---
title: "Mask Combination of Multi-layer Graphs for Global Structure Inference"
authors:
- Eda Bayram
- Dorina Thanou
- Elif Vural
- Pascal Frossard
date: "2020-05-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Signal and Information Processing over Networks*
publication_short: In *IEEE TSIPN*

abstract: Structure inference is an important task for network data processing and analysis in data science. In recent years, quite a few approaches have been developed to learn the graph structure underlying a set of observations captured in a data space. Although real-world data is often acquired in settings where relationships are influenced by a priori known rules, such domain knowledge is still not well exploited in structure inference problems. In this paper, we identify the structure of signals defined in a data space whose inner relationships are encoded by multi-layer graphs. We aim at properly exploiting the information originating from each layer to infer the global structure underlying the signals. We thus present a novel method for combining the multiple graphs into a global graph using mask matrices, which are estimated through an optimization problem that accommodates the multi-layer graph information and a signal representation model. The proposed mask combination method also estimates the contribution of each graph layer in the structure of signals. The experiments conducted both on synthetic and real-world data suggest that integrating the multi-layer graph representation of the data in the structure inference framework enhances the learning procedure considerably by adapting to the quality and the quantity of the input data.

# Summary. An optional shortened abstract.
summary: The structure of the data very often depends on complex relationships of multiple types. In this study, our main research question is "Can we support the structure inference process with a priori relational information about the data domain?"

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/pdf/1910.10114.pdf
url_code: 'https://github.com/bayrameda/MaskLearning'
# url_dataset: '#'
# url_poster: '#'
#  url_project: ''
#  url_slides: ''
#  url_source: '#'
#  url_video: '#' -->

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
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
