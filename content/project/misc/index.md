---
title: STATISTICAL METHODOLOGY
summary: 
date: 2023-03-10
type: landing

sections: 
  - block: hero
    content:
      title: STATISTICAL METHODOLOGY
      text: 
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
        category: "Misc"
        publication_type: 'article-journal'
    design:
      columns: '2'
      view: compact
  - block: collection
    id: publications
    content:
      title: WORKING PAPERS
      filters:
        folders: 
          - publication
        category: "Misc"
        publication_type: 'paper'
    design:
      columns: '2'
      view: compact
  - block: collection
    id: theses
    content:
      title: THESES
      filters:
        folders: 
          - publication
        publication_type: 'thesis'
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
        category: "Misc"
    design:
      columns: '2'
      view: compact
  - block: collection
    id: reports
    content:
      title: COURSE WORK & REPORTS
      filters:
        folders: 
          - publication
        publication_type: 'report'
        category: "Course work"
    design:
      columns: '2'
      view: compact
---
