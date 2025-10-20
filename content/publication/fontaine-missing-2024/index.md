---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Missing Value Imputation in Relational Data using Variational Inference"
subtitle: ''
summary: ''
authors:
- Simon Fontaine
- Jian Kang
- Ji Zhu
tags:
categories: ["Misc"]
date: '2025-05-20'
featured: false
draft: false

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: ["Misc"]
publishDate: '2024-03-17T16:06:35.531219Z'
publication_types:
- 'article-journal'
abstract: In real-world networks, node attributes are often only partially observed, necessitating imputation to support analysis or enable downstream tasks. However, most existing imputation methods overlook the rich information contained within the connectivity among nodes. This research is inspired by the premise that leveraging all available information should yield improved imputation, provided sufficient association between attributes and edges.Consequently, we introduce a joint latent space model that produces a low-dimensional representation of the data and simultaneously captures the edge and node attribute information. This model relies on the pooling of information induced by shared latent variables, thereby enhancing the prediction of node attributes and providing a more effective attribute imputation method. Our approach uses variational inference to approximate posterior distributions for these latent variables, resulting in predictive distributions for missing values. Through numerical experiments, conducted on both simulated data and real-world networks, we demonstrate that our proposed method successfully harnesses the joint structure information and significantly improves the imputation of missing attributes, specifically when the observed information is weak.
publication: "*JCGS*"
doi: "https://doi.org/10.1080/10618600.2025.2510494"

url_code: "https://github.com/fontaine618/NAIVI"
links: 
---

