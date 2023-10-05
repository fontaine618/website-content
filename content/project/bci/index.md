---
title: BRAIN-COMPUTER INTERFACES
summary: 
date: 2023-03-10
type: landing

sections: 
  - block: hero
    content:
      title: BRAIN-COMPUTER INTERFACES
      text: |2-
        To restore communication and control to people with severe motor disabilities, brain-computer interfaces (BCIs) aim to decode brain activity into control signals for external devices. One such example is the P300 speller, which is a matrix of characters where the user focuses on the desired character and the system detects the corresponding P300 event in the EEG signal. The statistical task behind BCIs is to decode the user's intent from noisy and high-dimensional EEG data.

        I am currently working on a project with *Prof. Jian Kang* and *Prof. Ji Zhu* on **Bayesian functional factor models for EEG-based brain-computer interfaces**. The goal is to develop a flexible and interpretable model for the EEG data that can be used to improve the performance of the BCI system, but also in terms of understanding of the underlying brain functions. 
        
        This work is supported by a **Doctoral Training Scholarship** from the *Fond de Recherche du Québec - Nature et Technologies*.
    design:
      columns: 2
      background:
        gradient_start: '#c31432'
        gradient_end: '#240b36'
        gradient_angle: 180
        text_color_light: true
        # image:
        #   filename: "brain_cover.png"
        #   size: cover
        #   filters:
        #     brightness: 0.4
        #   parallax: false
  - block: collection
    id: methodology
    content:
      title: METHODOLOGY
      filters:
        folders: 
          - publication
        category: "BCI"
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
        category: "BCI"
    design:
      columns: '2'
      view: compact
---

