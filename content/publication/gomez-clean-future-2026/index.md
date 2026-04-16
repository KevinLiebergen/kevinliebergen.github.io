---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Clean up the mess: Addressing data pollution in cryptocurrency abuse reporting services'

subtitle: ''
summary: ''
authors:
- Gibran Gomez
- Kevin van Liebergen
- Davide Sanvito
- Giuseppe Siracusano
- Roberto Gonzalez
- Juan Caballero
tags:
- Computer Science - Cryptography and Security
categories: []
date: '2026-06-01'
lastmod: 2026-06-01T17:01:54+02:00
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
publishDate: '2026-06-01T15:01:54.093102Z'
publication_types:
- '1'
abstract: Cryptocurrency abuse reporting services are a valuable data source about abusive blockchain addresses, 
  prevalent types of cryptocurrency abuse, and their financial impact on victims. 
  However, they may suffer data pollution due to their crowd-sourced nature. 
  This work analyzes the extent and impact of data pollution in cryptocurrency abuse reporting services 
  and proposes a novel LLM-based defense to address the pollution. 
  We collect 289K abuse reports submitted over 6 years to two popular services and use them to answer three research questions. 
  RQ1 analyzes the extent and impact of pollution. 
  We show that spam reports will eventually flood unchecked abuse reporting services, with BitcoinAbuse receiving 75% 
  of spam before stopping operations. 
  We build a public dataset of 19,443 abuse reports labeled with 19 popular abuse types and use it to reveal the 
  inaccuracy of user-reported abuse types. We identified 91 (0.1 %) benign addresses reported, responsible for 60% 
  of all the received funds. RQ2 examines whether we can automate identifying valid reports and their classification into abuse types. 
  We propose an unsupervised LLM-based classifier that achieves an F1 score of 0.95 when classifying reports, 
  an F1 of 0.89 when classifying out-of-distribution data, and an F1 of 0.99 when identifying spam reports. 
  Our unsupervised LLM-based classifier clearly outperforms two baselines, a supervised classifier and a naive usage of the LLM. 
  Finally, RQ3 demonstrates the usefulness of our LLM-based classifier for quantifying the financial impact of different cryptocurrency abuse types. 
  We show that victim-reported losses heavily underestimate cybercriminal revenue by estimating a 29 times higher revenue from deposit transactions. 
  We identified that investment scams have the highest financial impact and that extortions have 
  lower conversion rates but compensate for them with massive email campaigns.


publication: '*Future Generation Computer Systems 2026*'
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/abs/pii/S0167739X25006077
---
