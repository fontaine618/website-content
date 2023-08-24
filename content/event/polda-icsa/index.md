---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "POLDA: Pooling Overdispersed Logistic Regressions for Microbiome Differential Abundance Analysis"
event: "ICSA Applied Symposium 2023"
event_url: https://symposium2023.icsa.org/
location: "Ann Arbor, MI"
abstract: "Differential abundance (DA) analysis aims to identify microbiome taxa whose abundances are different between two or more conditions. Microbiome read counts are usually normalized as compositional data vectors, which suggests the use of ratio-based methods for DA analysis.  However, the excessive zero values in microbiome data prohibit the direct calculation of ratios and further distort DA analysis.  We propose POLDA (Pooling Overdispersed Logistic Regressions for Microbiome Differential Abundance Analysis) to address the challenge. POLDA first uses overdispersed logistic regressions to model the read counts for each pair of taxa and estimate the log odds ratio  between conditions. Then, it exploits a weighted linear regression with backward selection method to identify a reference set of non-differentially-abundant taxa. Finally, overdispersed logistic regressions are used to call differentially abundant taxa based on ratios with the reference set. Simulation studies show that the proposed method outperforms existing methods in power and type-I error rate control. Application to five diarrhea case-control datasets reveals that POLDA can identify differentially abundant taxa more consistently across similar studies than other methods."

date: 2023-06-13T10:00:00-04:00
date_end:  
all_day: false
publishDate: 2023-06-13T10:00:00-04:00

authors: 
  - Mukai Wang
  - Simon Fontaine
  - Hui Jiang
  - Gen Li
author_notes:
  - "Presenting"
  - ""
  - ""
  - ""
tags: []
categories: ["Microbiome"]
featured: false
image:
  caption: ""
  focal_point: ""
  preview_only: false
url_slides: 
url_code:
url_pdf:
url_video:
slides: ""
projects: []
---


