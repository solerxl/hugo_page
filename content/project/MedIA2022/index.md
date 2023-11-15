---
title: Multi-modal sequence learning for Alzheimer’s disease progression prediction with incomplete variable-length longitudinal data
summary: <b> <font color="red">Medical Image Analysis</font></b>, **Lei Xu**, Lei Chen, Rong Wang, Feiping Nie, Xuelong Li.
tags:
  - Journal
  - Alzhermer's Disease
date: '2022-08-22'

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
url_code: 'https://github.com/solerxl/Code_For_MIA_2022'
url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S1361841522002717'
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

Alzheimer’s disease (AD) is a neurodegenerative disorder with a long prodromal phase. Predicting AD progression will clinically help improve diagnosis and empower sufferers in taking proactive care. However, most existing methods only target individuals with a fixed number of historical visits, and only predict the cognitive scores once at a fixed time horizon in the future, which cannot meet practical requirements. In this study, we consider a flexible yet more challenging scenario in which individuals may suffer from the (arbitrary) modality-missing issue, as well as the number of individuals’ historical visits and the length of target score trajectories being not prespecified. To address this problem, a multi-modal sequence learning framework, highlighted by deep latent representation collaborated sequence learning strategy, is proposed to flexibly handle the incomplete variable-length longitudinal multi-modal data. Specifically, the proposed framework first employs a deep multi-modality fusion module that automatically captures complementary information for each individual with incomplete multi-modality data. A comprehensive representation is thus learned and fed into a sequence learning module to model AD progression. In addition, both the multi-modality fusion module and sequence learning module are collaboratively trained to further promote the performance of AD progression prediction. Experimental results on Alzheimer’s Disease Neuroimaging Initiative (ADNI) dataset validate the superiority of our method.