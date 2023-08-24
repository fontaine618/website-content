---
title: MISCELLANEOUS
summary: 
date: 2023-03-10
type: landing

sections: 
  - block: hero
    content:
      title: MISCELLANEOUS
      text: 
    design:
      columns: 2
      background:
        gradient_start: '#c31432'
        gradient_end: '#240b36'
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
        publication_type: '7'
    design:
      columns: '2'
      view: compact
  - block: collection
    id: reports
    content:
      title: COURSE WORK
      filters:
        folders: 
          - publication
        publication_type: '4'
        category: "Course work"
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
---

