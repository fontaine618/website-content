---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Unified Approach to Sparse Tweedie Modeling of Multisource Insurance Claim
  Data
subtitle: ''
summary: ''
authors:
- Simon Fontaine
- Yi Yang
- Wei Qian
- Bowen Gu
- Bo Fan
tags:
- 'Insurance data'
- 'Multi-task'
- 'Regularization'
- 'Tweedie model'
- 'Variable selection'
categories: ["Misc"]
date: '2020-01-01'
lastmod: 2021-10-21T12:48:04-04:00
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
publishDate: '2021-10-21T16:48:04.768455Z'
publication_types:
- '2'
abstract: 'Actuarial practitioners now have access to multiple sources of insurance
  data corresponding to various situations: multiple business lines, umbrella coverage,
  multiple hazards, and so on. Despite the wide use and simple nature of single-target
  approaches, modeling these types of data may benefit from an approach performing
  variable selection jointly across the sources. We propose a unified algorithm to
  perform sparse learning of such fused insurance data under the Tweedie (compound
  Poisson) model. By integrating ideas from multitask sparse learning and sparse Tweedie
  modeling, our algorithm produces flexible regularization that balances predictor
  sparsity and between-sources sparsity. When applied to simulated and real data,
  our approach clearly outperforms single-target modeling in both prediction and selection
  accuracy, notably when the sources do not have exactly the same set of predictors.
  An efficient implementation of the proposed algorithm is provided in our R package
  MStweedie, which is available at https://github.com/fontaine618/MStweedie. Supplementary
  materials for this article are available online.'
publication: '*Technometrics*'
doi: 10.1080/00401706.2019.1647881

url_code: "https://github.com/fontaine618/MSTweedie"
links: 
  - name: Supplementary material
    url: "fontaine-unified-2020-supp.pdf"
---
