---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Bayesian Fréchet Regression"
subtitle: ''
summary: ''
authors:
- Simon Fontaine
- Lingzhou Xue
- Bing Li
tags:
categories: ["Misc"]
date: '2025-10-20'
featured: false
draft: false

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: ["Misc"]
publishDate: '2025-10-01T16:06:35.531219Z'
publication_types:
- 'paper'
abstract: Fréchet regression is a statistical method that extends traditional regression to model responses in metric spaces by minimizing the Fréchet mean, which generalizes the concept of an average to non-Euclidean spaces. It is particularly useful for analyzing complex data such as probability distributions, points in Riemannian manifolds, trees, or networks, where standard regression techniques are insufficient. We propose a Bayesian version of Fréchet regression, which allows us to incorporate prior information to guide or shrink predictions towards explicit values. This is achieved through Bayesian nonlinear regression of the squared distance to any point of the metric space. By controlling the strength of the prior, we interpolate between the association implied by the prior and that obtained from frequentist estimation. While we derive our Bayesian Fréchet regression under Gaussian assumptions, we show that weaker moment assumptions are sufficient in the context of weak conditional expectations. We apply our methodology to microbiome compositional data where using a larger related cohort to construct a prior for the regression in a smaller cohort produces improved predictions.
publication: "In Preparation"
doi: ""

url_code: "https://github.com/fontaine618/BFR"
links: 
---

