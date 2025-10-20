---
title: MICROBIOME DATA ANALYSIS
summary: 
date: 2023-03-10
type: landing

sections: 
  - block: hero
    content:
      title: MICROBIOME DATA ANALYSIS
      text: |2-
        Advances in high-throughput sequencing technologies have enabled the study of the human microbiome, which is the collection of microorganisms that live in and on the human body. The microbiome is a key component of human health and disease; many recent works have shown that the microbiome is associated with a wide range of diseases and conditions, including obesity, diabetes, and cancer.

        Microbiome data features many important characteristics that need to be accounted for:
        * **High dimensionality**: the number of features (taxa) is generally much larger than the number of samples.
        * **Sparsity**: in a given study, many microbial species are not present in many individuals (true zeros) and the sequencing procedure can produce null counts even if a specie is present (sampling zeros).
        * **Compositionality**: due to the sequencing process, total read count varies between samples and is not directly comparable between taxa. 
        For this reason, only relative comparisons are generally feasible, though some methods have been proposed to overcome this issue.
        * **Heterogeneity**: the microbial compositions can differ widely between individuals or body sites, making direct comparison often difficult.
        There is some interest in *enterotypes*, which are essentially clusters of individuals with similar microbial compositions.
        * **Tree-structured**: taxonomic or phylogenetic information is often available in addition to the abundance data, and there is often interest or necessity in analyzing the composition in relation to the tree structure.

        I am currently working on the following projects:
        * **Bayesian Fréchet Regression** (*with Prof. Lingzhou Xue, PSU Statistics, and Prof. Bing Li, PSU Statistics*): we recognize microbial compositions as metric-space-valued objects and propose a Bayesian Fréchet regression model to study the association between the microbiome and a response variable. 
        * **Longitudinal Differential Analysis** (*with Prof. Gen Li, UM Biostatistics, and Prof. Ji Zhu, UM Statistics*): the goal is to identify time points or intervals where microbial composition differs between conditions. This work is motivated by an application to oral cancer progression in relation to the oral microbiome and a tumor-supressor gene in collaboration with *Dr Nisha D'Silva* (UM Periodontics and Oral Medicine) and her team. 
    design:
      columns: 2
      background:
        gradient_start: '#96BEE6'
        gradient_end: '#001E44'
        gradient_angle: 180
        text_color_light: true
      # background:
      #   image:
      #     filename: "microbes_cover.png"
      #     size: cover
      #     filters:
      #       brightness: 0.4
      #     parallax: false
  - block: collection
    id: methodology
    content:
      title: PUBLICATIONS
      filters:
        folders: 
          - publication
        category: "Microbiome"
    design:
      columns: '2'
      view: compact
  - block: collection
    id: talks
    content:
      title: TALKS
      filters:
        folders: 
          - event
        category: "Microbiome"
    design:
      columns: '2'
      view: compact
---

