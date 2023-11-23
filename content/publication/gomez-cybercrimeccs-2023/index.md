---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Cybercrime Bitcoin Revenue Estimations: Quantifying the Impact of Methodology
  and Coverage'
subtitle: ''
summary: ''
authors:
- Gibran Gomez
- Kevin van Liebergen
- Juan Caballero
tags:
- Computer Science - Cryptography and Security
categories: []
date: '2023-09-07'
lastmod: 2023-09-13T17:01:54+02:00
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
publishDate: '2023-09-13T15:01:54.093102Z'
publication_types:
- '0'
abstract: Multiple works have leveraged the public Bitcoin ledger to estimate the
  revenue cybercriminals obtain from their victims. Estimations focusing on the same
  target often do not agree, due to the use of different methodologies, seed addresses,
  and time periods. These factors make it challenging to understand the impact of
  their methodological differences. Furthermore, they underestimate the revenue due
  to the (lack of) coverage on the target's payment addresses, but how large this
  impact remains unknown. In this work, we perform the first systematic analysis on
  the estimation of cybercrime bitcoin revenue. We implement a tool that can replicate
  the different estimation methodologies. Using our tool we can quantify, in a controlled
  setting, the impact of the different methodology steps. In contrast to what is widely
  believed, we show that the revenue is not always underestimated. There exist methodologies
  that can introduce huge overestimation. We collect 30,424 payment addresses and
  use them to compare the financial impact of 6 cybercrimes (ransomware, clippers,
  sextortion, Ponzi schemes, giveaway scams, exchange scams) and of 141 cybercriminal
  groups. We observe that the popular multi-input clustering fails to discover addresses
  for 40% of groups. We quantify, for the first time, the impact of the (lack of)
  coverage on the estimation. For this, we propose two techniques to achieve high
  coverage, possibly nearly complete, on the DeadBolt server ransomware. Our expanded
  coverage enables estimating DeadBolt's revenue at $2.47M, 39 times higher than the
  estimation using two popular Internet scan engines.
publication: '*Conference*'
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3576915.3623094
---
