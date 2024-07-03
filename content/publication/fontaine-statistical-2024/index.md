---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Statistical Models for Dependent Data
subtitle: ''
summary: ''
authors:
- Simon Fontaine
tags: []
categories: ["Misc"]
date: '2024-06-01'
lastmod: 2024-07-01T14:01:46-04:00
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
publishDate: '2024-07-01T14:01:46-04:00'
publication_types:
- 'thesis'
abstract: Dependency among observations can arise from a multitude of sources, including spatial or temporal correlation, grouped, clustered or repeated measurements, hierarchical structures, and dyadic interactions. Neglecting these interdependencies in statistical analyses may result in incorrect inferences or loss of statistical power. Conversely, adequately modeling these dependencies not only enhances the validity of our statistical inferences but also deepens our comprehension of the intricate dynamics that generate the data. In this dissertation, we propose innovative methodologies tailored to three cases, each exemplifying unique challenges of dependent data. First, we consider an imputation task where dependency among subjects is captured by a network structure. Be leveraging both between-variable and between-subjects dependencies in a joint latent space model, we obtain more accurate predictions for the missing data. Second, we study a differential analysis task within the context of longitudinal data, driven by a study on microbial abundance data. To accommodate the temporal dependencies and the continuous nature of the biological data, we opt for a varying-coefficient mixed model estimated through penalized kernel smoothing, producing locally sparse varying-coefficients. Crucially, accounting for time dependence is shown to improve estimation accuracy as well as support recovery. Third, we explore a modeling task emerging from a brain-computer interface setting. Specifically, we aim to construct a model of the brain's electrical activity, in relation to its response to visual stimuli presented under an oddball paradigm, in which only certain stimuli are pertinent. By adopting a dynamic latent factor approach, we obtain an interpretable decomposition across electrodes and time. Further, we capture temporal variation in the spatial covariance, providing additional insight into the functional connectivity.
publication: ''
url_pdf: NA
---
