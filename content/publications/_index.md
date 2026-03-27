---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  #- block: collection
  #  id: papers
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publications
  #      featured_only: true
  #  design:
  #    view: article-grid
  #    columns: 2
  - block: collection
    content:
      title: Publications
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 25
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
