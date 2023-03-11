---
title: Miscellaneous
summary: Does this work?
date: 2023-03-10
type: landing

sections: 
  - block: hero
    content:
      title: Brain-Computer Interfaces
      text: 
    design:
      background:
        # gradient_end: '#000000'
        # gradient_start: '#004ba0'
        # text_color_light: true
        image: 
          filename: "IMG_6896.jpg"
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: true
  - block: collection
    id: methodology
    content:
      title: Methodology
      filters:
        folders: 
          - publication
        exclude_featured: false
        tags: 
           - microbiome_methodology
    design:
      columns: '2'
      view: card
  - block: collection
    id: application
    content:
      title: Application
      filters:
        folders: 
          - publication
        exclude_featured: false
        tags: 
           - microbiome_application
    design:
      columns: '2'
      view: card
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders: 
          - talks
        exclude_featured: false
        tags: 
           - microbiome
    design:
      columns: '2'
      view: card
---

