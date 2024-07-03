---
# Leave the homepage title empty to use the site title
title:
date: 2023-03-10
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      username: simon
    design:
      theme: light
      background:
        gradient_start: '#c31432'
        gradient_end: '#240b36'
        gradient_angle: 180
        text_color_light: true
  - block: portfolio
    id: projects
    content:
      title: RESEARCH
      subtitle: 
      text: 
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    content:
      title: RECENT PUBLICATIONS
      subtitle: |-
        {{< cta cta_text="SEE ALL" cta_link="/publications/" cta_new_tab="false" >}}
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
        
    design:
      columns: '2'
      view: compact
  - block: collection
    content:
      title: WORKING PAPERS
      subtitle: |-
        {{< cta cta_text="SEE ALL" cta_link="/publications/" cta_new_tab="false" >}}
      filters:
        folders:
          - publication
        publication_type: 'paper'
        
    design:
      columns: '2'
      view: compact
  - block: collection
    id: talks
    content:
      title: RECENT & UPCOMING TALKS
      subtitle: |-
        {{< cta cta_text="SEE ALL" cta_link="/talks/" cta_new_tab="false" >}}
      filters:
        folders:
          - event
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
