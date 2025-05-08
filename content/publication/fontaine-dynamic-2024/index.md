---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Dynamic Latent Factor Regression for EEG-Based Brain-Computer Interfaces"
subtitle: ''
summary: ''
authors:
- Simon Fontaine
- Jane E. Huggins
- Ji Zhu
- Jian Kang
tags:
categories: ["BCI"]
date: '2024-07-01'
featured: false
draft: false

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: ["BCI"]
publishDate: '2024-07-01T16:48:04.768455Z'
publication_types:
- 'paper'
abstract: Brain-computer interfaces (BCI) provide direct communication from the brain to an external device by inferring the user's intent from the brain activity. Specifically, current BCI technology often rely on analysing event-related potentials (ERP), such as the P300 signal, as measurable electroencephalography (EEG) responses to stimuli presented to the user. However, crucial information is often overlooked by focusing solely on well-characterized ERPs. In particular, studying the whole EEG measurements following the onset of a stimulus throughout the scalp can improve the performance of BCIs as well as our understanding of the brain functions responsible for information processing and decision-making. We propose a novel Bayesian model based on dynamic latent factor models, which provide two crucial improvements over existing methods. First, we learn latent factors across EEG electrodes and time which allows dimensionality reduction, abstraction of the BCI design and decomposition of complex electrode-wise responses into interpretable sub-components.  Second, we allow spatial correlation across electrodes to vary both with time and stimulus type (target or nontarget), which captures changes in functional connectivity following the onset of a stimulus, along with variations associated with intent. The application of our model to real BCI sessions provide valuable insight by recovering and refining some of the known ERPs, discovering new signals and highlighting variations in functional connectivity that were mostly unexplored so far.
publication: "Under revision at *JASA*"
doi: ""

url_code: "https://github.com/fontaine618/BFFM-BCI"
links: 
- name: "Paper code"
  url: "https://github.com/fontaine618/BCI-Experiments"
---

