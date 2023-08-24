---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Caught Looking: Analyzing Variation in Umpire Strike Zones'
subtitle: ''
summary: ''
authors:
- Simon Fontaine
- Moritz Korte-Stapff
- Brian Manzo
tags: []
categories: []
date: '2020-01-01'
lastmod: 2021-10-21T12:06:35-04:00
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
publishDate: '2021-10-21T16:06:35.802995Z'
publication_types:
- '4'
abstract: As technology advances, Major League Baseball (MLB) has faced increased
  pressure from fans, coaches, and players to use video technologies to aid umpires
  in making calls on the field, especially for the notoriously subjective ball and
  strike calls. With this project, we will assess the ability of umpires to make ball
  and strike calls that match the rulebook and that are consistent across different
  game situations. Using nonlinear classification methods such as kernel linear regression
  and support vector machines we can learn a strike zone for each umpire based on
  pitch location as well as game circumstances. After learning strike zone classifiers
  for each game situation and umpire combination, we use kernel PCA to create a low
  dimensional encoding of the strike zones that can be used for inference. We perform
  multiple analysis of variance and mixed effects multivariate regression on the principal
  components to determine which factors have a statistically significant effect on
  an umpire’s strike zone. Finally we compute a ranking of each umpire and compare
  our top umpires with those featured on other lists.
publication: ''

url_slides: fontaine-caught-2020-slides.pdf
url_code: "https://github.com/fontaine618/601-Project/"
---
