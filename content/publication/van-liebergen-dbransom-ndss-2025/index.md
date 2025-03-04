---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'All your (data)base are belong to us: Characterizing Database Ransom(ware) Attacks'
subtitle: ''
summary: ''
authors:
- Kevin van Liebergen
- Gibran Gomez
- Srdjan Matic
- Juan Caballero
tags:
- Computer Science - Cryptography and Security
categories: []
date: '2025-02-24'
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
publishDate: '2025-02-24T15:01:54.093102Z'
publication_types:
- '1'
abstract: We present the first systematic study of database ransom(ware) attacks, a class of attacks where attackers scan for database servers, log in by leveraging the lack of authentication or weak credentials, drop the database contents, and demand a ransom to return the deleted data. We examine 23,736 ransom notes collected from 60,427 compromised database servers over three years, and set up database honeypots to obtain a first-hand view of current attacks. Database ransom(ware) attacks are prevalent with 6K newly infected servers in March 2024, a 60% increase over a year earlier. Our honeypots get infected in 14 hours since they are connected to the Internet. Weak authentication issues are two orders of magnitude more frequent on Elasticsearch servers compared to MySQL servers due to slow adoption of the latest Elasticsearch versions. To analyze who is behind database ransom(ware) attacks we implement a clustering approach that first identifies campaigns using the similarity of the ransom notes text. Then, it determines which campaigns are run by the same group by leveraging indicator reuse and information from the Bitcoin blockchain. For each group, it computes properties such as the number of compromised servers, the lifetime, the revenue, and the indicators used. Our approach identifies that the 60,427 database servers are victims of 91 campaigns run by 32 groups. It uncovers a dominant group responsible for 76% of the infected servers and 90% of the financial impact. We find links between the dominant group, a nation-state, and a previous attack on Git repositories.

publication: '*NDSS 2025*'
links:
- name: URL
  url: https://www.ndss-symposium.org/ndss-paper/all-your-database-are-belong-to-us-characterizing-database-ransomware-attacks/
---
