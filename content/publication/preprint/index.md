---
title: "A Deep Dive into VirusTotal: Characterizing and Clustering a Massive File Feed"
authors:
- admin
- Juan Caballero
- Platon Kotzias
- Chris Gates
date: "2022-10-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Online scanners analyze user-submitted files with a large number of security tools and provide access to the analysis results. As the most popular online scanner, VirusTotal (VT) is often used for determining if samples are malicious, labeling samples with their family, hunting for new threats, and collecting malware samples. We analyze 328M VT reports for 235M samples collected for one year through the VT file feed. We use the reports to characterize the VT file feed in depth and compare it with the telemetry of a large security vendor. We answer questions such as How diverse is the feed? Does it allow building malware datasets for different filetypes? How fresh are the samples it provides? What is the distribution of malware families it sees? Does that distribution really represent malware on user devices? 


We then explore how to perform threat hunting at scale by investigating scalable approaches that can produce high purity clusters on the 235M feed samples. We investigate three clustering approaches: hierarchical agglomerative clustering (HAC), a more scalable HAC variant for TLSH digests (HAC-T), and a simple feature value grouping (FVG). Our results show that HAC-T and FVG using selected features produce high precision clusters on ground truth datasets. However, only FVG scales to the daily influx of samples in the feed. Moreover, FVG takes 15 hours to cluster the whole dataset of 235M samples. Finally, we use the produced clusters for threat hunting, namely for detecting 190K samples thought to be benign (i.e., with zero detections) that may really be malicious because they belong to 29K clusters where most samples are detected as malicious."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2210.15973.pdf
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!--
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}
-->

<!--
 Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
-->

---
title: "Cybercrime Bitcoin Revenue Estimations: Quantifying the Impact of Methodology and Coverage"
authors:
- Gibrán Gómez
- admin
- Platon Kotzias
date: "2022-10-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Multiple works have leveraged the public Bitcoin ledger to estimate the revenue cybercriminals obtain from their victims. Estimations focusing on the same target often do not agree, due to the use of different methodologies, seed addresses, and time periods. These factors make it challenging to understand the impact of their methodological differences. Furthermore, they underestimate the revenue due to the (lack of) coverage on the target's payment addresses, but how large this impact remains unknown.

In this work, we perform the first systematic analysis on the estimation of cybercrime bitcoin revenue. We implement a tool that can replicate the different estimation methodologies. Using our tool we can quantify, in a controlled setting, the impact of the different methodology steps. In contrast to what is widely believed, we show that the revenue is not always underestimated. There exist methodologies that can introduce huge overestimation. We collect 30,424 payment addresses and use them to compare the financial impact of 6 cybercrimes (ransomware, clippers, sextortion, Ponzi schemes, giveaway scams, exchange scams) and of 141 cybercriminal groups. We observe that the popular multi-input clustering fails to discover addresses for 40% of groups. We quantify, for the first time, the impact of the (lack of) coverage on the estimation. For this, we propose two techniques to achieve high coverage, possibly nearly complete, on the DeadBolt server ransomware. Our expanded coverage enables estimating DeadBolt's revenue at $2.47M, 39 times higher than the estimation using two popular Internet scan engines."



# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2309.03592v1

