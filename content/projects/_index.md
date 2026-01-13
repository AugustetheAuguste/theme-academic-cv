---
title: 'Projets'
date: 2024-05-19
type: landing
url: /projets/
image:
  filename: og/projets.png
  alt: "Projets IA et Data - Auguste Doyet"

design:
  spacing: '4rem'

# Page sections
sections:
  - block: collection
    content:
      title: Projets phares
      text: "Sélection rapide pour comprendre les sujets majeurs."
      count: 3
      filters:
        folders:
          - projects
        featured_only: true
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_author: false
      show_date: false
      show_read_time: false
      show_read_more: true

  - block: collection
    content:
      title: Liste complète
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_author: false
      show_date: false
      show_read_time: false
      show_read_more: true
      
    design:
      columns: '1'
---
