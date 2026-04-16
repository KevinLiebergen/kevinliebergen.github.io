---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Family Ties: A Close Look at the Influence of Static Features on the Precision of Malware Family Clustering'
subtitle: ''
summary: ''
authors:
- Antonino Vitale
- Kevin van Liebergen
- Juan Caballero
- Savino Dambra
- Platon Kotzias
- Simone Aonzo
tags:
- Computer Science - Cryptography and Security
categories: []
date: '2025-11-07'
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
publishDate: '2025-11-07T15:01:54.093102Z'
publication_types:
- '1'
abstract: Malware family clustering plays a crucial role in many security tasks, 
  including malware analysis, classification, labeling, triage, threat hunting, and lineage studies. 
  This work takes a close look at the influence on malware family clustering of 11 
  popular static similarity features, including whole-file fuzzy hashes (e.g., SSDeep, TLSH), 
  structural hashes (e.g., PE Hash, Import Hash, VirusTotal’s VHash), certificate-based features, 
  and icon-based features. 
  Our goal is not to propose new features or clustering approaches. 
  Instead, we aim to measure how often these 11 features make clustering errors, i.e., 
  cluster together samples belonging to different malware families. 
  We also investigate the root causes behind those errors, which often lead to 
  misinterpretations of malware relationships, hinder effective threat detection, 
  and propagate inaccuracies in downstream analyses. 
  To study this phenomenon, we leverage three public datasets comprising 79,993 labeled Windows malware samples. 
  We cluster those samples by using each of the analyzed features, measure their accuracy with a focus on their precision, 
  and examine the reasons that caused some clusters to contain samples from different families. 
  Our analysis identifies intrinsic limitations of some of the features and highlights the severe impact 
  of EXE-building tools (like software protectors, installers, and self-extracting archives) on malware clustering. 
  Finally, we discuss mitigations and evaluate potential improvements to address the problems we observed. 
  Our findings provide a critical foundation for improving static malware clustering methodologies 
  by emphasizing the importance of dataset curation and feature refinement for robust and precise clustering outcomes.

publication: '*eCrime 2025*'
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/11327864
---
