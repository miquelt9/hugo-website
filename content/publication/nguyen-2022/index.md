---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Capsule-Forensics Networks for Deepfake Detection
subtitle: ''
summary: ''
authors:
- Huy H. Nguyen
- Junichi Yamagishi
- Isao Echizen
tags: []
categories: []
date: '2022-01-01'
lastmod: 2023-01-01T00:23:08+09:00
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
publishDate: '2022-12-31T15:23:08.516970Z'
publication_types:
- '6'
abstract: SeveralCapsule-Forensics sophisticated convolutional neural network (CNN)Convolutional
  Neural Networks (CNN) architectures have been devised that have achieved impressive
  results in various domains. One downside of this success is the advent of attacks
  using deepfakesDeepFake, a family of tools that enable anyone to use a personal
  computer to easily create fake videos of someone from a short video found online.
  Several detectors have been introduced to deal with such attacks. To achieve state-of-the-art
  performance, CNN-basedConvolutional Neural Networks (CNN) detectors have usually
  been upgraded by increasing their depth and/or their width, adding more internal
  connections, or fusing several features or predicted probabilities from multiple
  CNNsConvolutional Neural Networks (CNN). As a result, CNN-basedConvolutional Neural
  Networks (CNN) detectors have become bigger, consume more memory and computation
  power, and require more training data. Moreover, there is concern about their generalizability
  to deal with unseen manipulation methods. In this chapter, we argue that our forensic-oriented
  capsule networkCapsule network overcomes these limitations and is more suitable
  than conventional CNNsConvolutional Neural Networks (CNN) to detect deepfakesDeepFake.
  The superiority of our ``Capsule-Forensics'' Capsule-Forensics network is due to
  the use of a pretrained feature extractor, statistical pooling layers, and a dynamic
  routing algorithm. This design enables the Capsule-ForensicsCapsule-Forensics network
  to outperform a CNNConvolutional Neural Networks (CNN) with a similar design and
  to be from 5 to 11 times smaller than a CNNConvolutional Neural Networks (CNN) with
  similar performance.
publication: '*Handbook of Digital Face Manipulation and Detection: From DeepFakes
  to Morphing Attacks*'
url_pdf: https://doi.org/10.1007/978-3-030-87664-7_13
doi: 10.1007/978-3-030-87664-7_13
---
