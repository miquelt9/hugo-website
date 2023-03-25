---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Outlier-Aware Training for Improving Group Accuracy Disparities
subtitle: ''
summary: ''
authors:
- Li-Kuang Chen
- Canasai Kruengkrai
- Junichi Yamagishi
tags: []
categories: []
date: '2022-11-01'
lastmod: 2023-02-19T19:06:33+09:00
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
publishDate: '2023-02-19T10:06:33.102730Z'
publication_types:
- '1'
abstract: Methods addressing spurious correlations such as Just Train Twice (JTT,
  Liu et al. 2021) involve reweighting a subset of the training set to maximize the
  worst-group accuracy. However, the reweighted set of examples may potentially contain
  unlearnable examples that hamper the model′s learning. We propose mitigating this
  by detecting outliers to the training set and removing them before reweighting.
  Our experiments show that our method achieves competitive or better accuracy compared
  with JTT and can detect and remove annotation errors in the subset being reweighted
  in JTT.
publication: '*Proceedings of the 2nd Conference of the Asia-Pacific Chapter of the
  Association for Computational Linguistics and the 12th International Joint Conference
  on Natural Language Processing: Student Research Workshop*'
url_pdf: https://aclanthology.org/2022.aacl-srw.8
links:
  - name: Preprint
    url: https://arxiv.org/abs/2210.15183
  - name: Codes
    url: https://github.com/nii-yamagishilab/jtt-m
  - name: Pre-trained models
    url: https://doi.org/10.5281/zenodo.7260028
---
