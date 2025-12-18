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
  - block: markdown
    content:
      title: "Portefeuille projets IA/Data"
      text: |-
        Projets orientes preuves : vision, reinforcement learning, LLM/RAG, audio/NLP. Les visuels sont en placeholders pour le MVP et pourront etre remplaces a l'identique (chemins stabilises dans `/img/projects/<slug>/cover.png` et `/og/projets.png`).
    design:
      columns: '1'
  - block: collection
    content:
      title: Projets phares
      text: "Selection rapide pour comprendre les sujets majeurs. Les projets phares restent visibles ci-dessous pour conserver le contexte complet."
      filters:
        folders:
          - projects
        featured_only: true
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: true
  - block: markdown
    content:
      title: "Explorer les projets"
      text: |-
        Recherche et navigation par cartes : titres, resumes, tags et liens vers le detail. Les filtres integres de la barre de navigation HugoBlox restent actifs pour restreindre par mots-cles si besoin.
    design:
      columns: '1'
  - block: collection
    content:
      title: Liste complete
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: true
  - block: markdown
    content:
      title: "Envie d'en voir plus ?"
      text: "[Telecharger le CV](/cv/) | [Voir l'experience pro](/experience/) | [Me contacter](mailto:auguste.doyet@efrei.net)"
    design:
      columns: '1'
---
