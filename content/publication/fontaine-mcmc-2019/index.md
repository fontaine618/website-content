---
# Documentation: https://wowchemy.com/docs/managing-content/

title: MCMC adaptatifs à essais multiples
subtitle: ''
summary: ''
authors:
- Simon Fontaine
tags: []
categories: ["Misc"]
date: '2019-01-01'
lastmod: 2021-10-21T14:01:46-04:00
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
publishDate: '2021-10-21T18:01:46.913232Z'
publication_types:
- '7'
abstract: This memoir aims at introducing adaptation within the Multiple-Try Metropolis
  (MTM) algorithms which are a special case of the Markov chain Monte Carlo (MCMC)
  methods. The MCMC methods, along with their adaptive and multiple-try extensions,
  are thoroughly explored (both in their possible variations and in their theoretical
  properties) in order to firmly anchor the study of the proposed adaptive Multiple-Try
  Metropolis (aMTM) algorithm. Moreover, some existing results on the properties of
  MTM algorithms are generalized to enable more general results about the aMTM algorithm.
  The ergodicity of the algorithm is then established using well known results of
  Roberts and Rosenthal (2007), Andrieu and Moulines (2006) and Craiu et al. (2015)
  and its empirical performance is studied through a series of simulation experiments.
  The aMTM algorithm achieves notably better performance than simpler samplers (non-adaptive
  or single-try) when applied to distributions that are multimodal or that exhibit
  complex geometry. Finally, many variations of the algorithm are proposed and compared
  to identify settings that are particularly more efficient. An implementation of
  the algorithm is provided in a R package called aMTM available at https://github.com/fontaine618/aMTM.
publication: ''
url_pdf: https://umontreal.on.worldcat.org/oclc/1147919072
---
