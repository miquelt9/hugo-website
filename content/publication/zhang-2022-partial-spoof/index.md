---
# Documentation: https://wowchemy.com/docs/managing-content/

title: The PartialSpoof Database and Countermeasures for the Detection of Short Fake
  Speech Segments Embedded in an Utterance
subtitle: ''
summary: ''
authors:
- Lin Zhang
- Xin Wang
- Erica Cooper
- Nicholas Evans
- Junichi Yamagishi
tags: []
categories: []
date: '2023-01-01'
lastmod: 2023-02-01T23:44:57+09:00
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
publishDate: '2023-02-01T14:44:57.000799Z'
publication_types:
- '2'
abstract: 'Automatic speaker verification is susceptible to various manipulations and spoofing, such as text-to-speech synthesis, voice conversion, replay, tampering, adversarial attacks, and so on. We consider a new spoofing scenario called “Partial Spoof” (PS) in which synthesized or transformed speech segments are embedded into a bona fide utterance. While existing countermeasures (CMs) can detect fully spoofed utterances, there is a need for their adaptation or extension to the PS scenario. We propose various improvements to construct a significantly more accurate CM that can detect and locate short-generated spoofed speech segments at finer temporal resolutions. First, we introduce newly developed self-supervised pre-trained models as enhanced feature extractors. Second, we extend our PartialSpoof database by adding segment labels for various temporal resolutions. Since the short spoofed speech segments to be embedded by attackers are of variable length, six different temporal resolutions are considered, ranging from as short as 20 ms to as large as 640 ms. Third, we propose a new CM that enables the simultaneous use of the segment-level labels at different temporal resolutions as well as utterance-level labels to execute utterance- and segment-level detection at the same time. We also show that the proposed CM is capable of detecting spoofing at the utterance level with low error rates in the PS scenario as well as in a related logical access (LA) scenario. The equal error rates of utterance-level detection on the PartialSpoof database and ASVspoof 2019 LA database were 0.77 and 0.90%, respectively.'
publication: '*IEEE/ACM Transactions on Audio, Speech, and Language Processing*'
doi: 10.1109/TASLP.2022.3233236
links:
  - name: Preprint
    url: https://arxiv.org/abs/2204.05177
---
