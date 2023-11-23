---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'A Deep Dive into VirusTotal: Characterizing and Clustering a Massive File
  Feed'
subtitle: ''
summary: ''
authors:
- Kevin van Liebergen
- Juan Caballero
- Platon Kotzias
- Chris Gates
tags:
- Computer Science - Cryptography and Security
categories: []
date: '2022-10-31'
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
publishDate: '2023-09-13T15:01:54.731601Z'
publication_types:
- '0'
abstract: 'Online scanners analyze user-submitted files with a large number of security
  tools and provide access to the analysis results. As the most popular online scanner,
  VirusTotal (VT) is often used for determining if samples are malicious, labeling
  samples with their family, hunting for new threats, and collecting malware samples.
  We analyze 328M VT reports for 235M samples collected for one year through the VT
  file feed. We use the reports to characterize the VT file feed in depth and compare
  it with the telemetry of a large security vendor. We answer questions such as How
  diverse is the feed? Does it allow building malware datasets for different filetypes?
  How fresh are the samples it provides? What is the distribution of malware families
  it sees? Does that distribution really represent malware on user devices? We then
  explore how to perform threat hunting at scale by investigating scalable approaches
  that can produce high purity clusters on the 235M feed samples. We investigate three
  clustering approaches: hierarchical agglomerative clustering (HAC), a more scalable
  HAC variant for TLSH digests (HAC-T), and a simple feature value grouping (FVG).
  Our results show that HAC-T and FVG using selected features produce high precision
  clusters on ground truth datasets. However, only FVG scales to the daily influx
  of samples in the feed. Moreover, FVG takes 15 hours to cluster the whole dataset
  of 235M samples. Finally, we use the produced clusters for threat hunting, namely
  for detecting 190K samples thought to be benign (i.e., with zero detections) that
  may really be malicious because they belong to 29K clusters where most samples are
  detected as malicious.'
publication: '*arXiv*'
doi: 10.48550/arXiv.2210.15973
links:
- name: URL
  url: http://arxiv.org/abs/2210.15973
---
