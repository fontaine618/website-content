---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "ADAPT: Analysis of Microbiome Differential Abundance by Pooling Tobit Models"
subtitle: ''
summary: ''
authors:
- Mukai Wang
- Simon Fontaine
- Hui Jiang
- Gen Li
tags:
categories: ["Microbiome"]
date: '2024-11-07'
featured: false
draft: false

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: ["Microbiome"]
publishDate: '2024-05-17T16:48:04.768455Z'
publication_types:
- 'article-journal'
abstract: Microbiome differential abundance analysis remains a challenging problem despite multiple methods proposed in the literature. The excessive zeros and compositionality of metagenomics data are two main challenges for differential abundance analysis. We propose a novel method called “analysis of differential abundance by pooling Tobit models” (ADAPT) to overcome these two challenges. ADAPT uniquely treats zero counts as left-censored observations to facilitate computation and enhance interpretation. ADAPT also encompasses a theoretically justified way of selecting non-differentially abundant microbiome taxa as a reference for hypothesis testing. We generate synthetic data using independent simulation frameworks to show that ADAPT has more consistent false discovery rate control and higher statistical power than competitors. We use ADAPT to analyze 16S rRNA sequencing of saliva samples and shotgun metagenomics sequencing of plaque samples collected from infants in the COHRA2 study. The results provide novel insights into the association between the oral microbiome and early childhood dental caries.
publication: "*Bioinformatics*"
doi: "10.1093/bioinformatics/btae661"

url_code: "https://github.com/mkbwang/ADAPT"
links: 
- name: "Paper code"
  url: "https://github.com/fontaine618/ADAPT_example"
---

