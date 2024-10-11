---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Locally sparse varying coefficient mixed model with
application to longitudinal microbiome differential
abundance"
subtitle: ''
summary: ''
authors:
- Simon Fontaine
- Nisha J. D'Silva
- Marcell Costa de Medeiros
- Grace Y. Chen
- Ji Zhu
- Gen Li
tags:
categories: ["Microbiome"]
date: '2024-03-17'
featured: false
draft: false

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: ["Microbiome"]
publishDate: '2024-03-17T16:48:04.768455Z'
publication_types:
- 'paper'
abstract: Differential abundance (DA) analysis in microbiome studies has recently been used to uncover a plethora of associations between microbial composition and various health conditions. While current approaches to DA typically apply only to cross-sectional data, many studies feature a longitudinal design to better understand the underlying microbial dynamics. To study DA on longitudinal microbial studies, we introduce a novel varying coefficient mixed-effects model with local sparsity. The proposed method can identify time intervals of significant group differences while accounting for temporal dependence. Specifically, we exploit a penalized kernel smoothing approach for parameter estimation and include a random effect to account for serial correlation. In particular, it operates effectively regardless of whether sampling times are shared across subjects, accommodating irregular sampling or potentially missing observations. Simulation studies demonstrate the necessity of modelling dependence for precise estimation and support recovery. Our method's application to a longitudinal study of mice oral microbiome during cancer development revealed significant scientific insights that were otherwise not discernible through cross-sectional analyses.
publication: "Under review at *Biometrics*"
doi: ""

url_code: "https://github.com/fontaine618/LSVCMM"
links: 
- name: "Paper code"
  url: "https://github.com/fontaine618/LSVCMM-experiments"
---

