---
title: NETWORK ANALYSIS
summary:
date: 2023-03-10
weight: 4
type: landing

sections:
  - block: hero
    content:
      title: NETWORK ANALYSIS
      text: |2-
        Relational data combine information about individual entities with the connections between them. My research develops statistical methods that use both sources of information, with a current focus on imputing missing node attributes by jointly modeling attributes and network structure.
    design:
      columns: 2
      background:
        gradient_start: '#96BEE6'
        gradient_end: '#001E44'
        gradient_angle: 180
        text_color_light: true
  - block: collection
    id: publications
    content:
      title: PUBLICATIONS
      filters:
        folders:
          - publication
        category: "Network"
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
        category: "Network"
    design:
      columns: '2'
      view: compact
---
