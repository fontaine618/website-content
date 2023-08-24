---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An adaptive multiple try Metropolis algorithm
subtitle: ''
summary: ''
authors:
- Simon Fontaine
- Mylène Bédard
tags:
- 'Adaptive Metropolis'
- 'Bayesian inference'
- 'MCMC'
- 'Metropolis'
- 'Multiple-try Metropolis'
categories: [Misc]
date: '2022-08-01'
featured: false
draft: false

doi: 10.3150/21-BEJ1408

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
publishDate: '2021-10-21T16:48:37.632309Z'
publication_types:
- '2'
abstract: Markov  chain  Monte  Carlo  (MCMC)  methods,  specifically  samplers  based  on  random  walks,often
  have difficulty handling target distributions with complex geometry such as multi-modality.We
  propose an adaptive multiple-try Metropolis algorithm designed to tackle such problems
  bycombining the flexibility of multiple-proposal samplers with the user-friendliness
  and optimalityof  adaptive  algorithms.  We  prove  the  ergodicity  of  the  resulting  Markov  chain  with  respectto  the  target  distribution  using  common  techniques  in  the  adaptive  MCMC  literature.  In  aBayesian
  model for loss of heterozygosity in cancer cells, we find that our method outperformstraditional
  adaptive samplers, non-adaptive multiple-try Metropolis samplers, and various moresophisticated
  competing methods.
publication: '*Bernoulli*'
url_code: "https://github.com/fontaine618/aMTM"
links:
- name: "Simulation code"
  url: "https://github.com/fontaine618/aMTM-simulations"
- name: "Supplementary material"
  url: "bej1408suppa.pdf"
---
