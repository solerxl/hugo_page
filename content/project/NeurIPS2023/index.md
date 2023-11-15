---
title: Joint Feature and Differentiable k-NN Graph Learning using Dirichlet Energy
summary: <b>Proc. <font color="red"> NeurIPS 2023</font></b>, **Lei Xu**, Lei Chen, Rong Wang, Feiping Nie, Xuelong Li.
tags:
  - Conference
  - Feature Selection
date: '2023-09-22'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ''
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: 'https://openreview.net/forum?id=noMktb4ait'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

### Abstract

Feature selection (FS) plays an important role in machine learning, which extracts important features and accelerates the learning process. In this paper, we propose a deep FS method that simultaneously conducts feature selection and differentiable 
$k$-NN graph learning based on the Dirichlet Energy. The Dirichlet Energy identifies important features by measuring their smoothness on the graph structure, and facilitates the learning of a new graph that reflects the inherent structure in new feature subspace. We employ Optimal Transport theory to address the non-differentiability issue of learning $k$-NN graphs in neural networks, which theoretically makes our method applicable to other graph neural networks for dynamic graph learning. Furthermore, the proposed framework is interpretable, since all modules are designed algorithmically. We validate the effectiveness of our model with extensive experiments on both synthetic and real-world datasets.
