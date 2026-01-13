---
title: 'Accueil'
date: 2022-10-24
type: landing
image:
  filename: og/home.png
  alt: "Portfolio Auguste Doyet"

design:
  spacing: '4rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: "Étudiant en double diplôme UQAC/Efrei entre Paris et Chicoutimi. Portfolio Data & IA orienté preuves (vision, reinforcement learning, LLM/RAG) avec CTAs clairs vers les projets et le CV."
      button:
        text: "Voir les projets"
        url: /projets/
        icon: ''
      button_alt:
        text: "Consulter le CV"
        url: /cv/
        icon: ''
      headings:
        about: ''
        education: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: 4xl
      avatar:
        size: medium
        shape: circle

  - block: collection
    content:
      title: Projets phares
      text: "Cartes cliquables vers les projets phares (sélection automatique via le flag featured)."
      filters:
        folders:
          - projects
        featured_only: true
    design:
      view: article-grid
      columns: 3
      show_author: false
      show_date: false
      show_read_time: false
      show_read_more: true

  - block: features
    content:
      title: Expérience snapshot
      text: "Parcours construit sur la pratique : de la co-création produit IA à l'enseignement, en passant par l'industrie."
      items:
        - name: FALC'On
          description: Co-fondateur — Produit IA pour traduction accessible (LangChain/LLM), prototypage & démos clients.
          icon: star
        - name: Ambassadeur Efrei
          description: Ateliers IA/Data, jury English Debate, accompagnement et vulgarisation technique.
          icon: users
        - name: Westline
          description: Stage robotique/optoélectronique en contexte industriel, documentation & qualité.
          icon: cog
        - name: Prof particulier
          description: 6 ans de pédagogie active maths/physique. Supports progressifs, clarté, suivi.
          icon: book
      button:
        text: Voir le détail
        url: /experience/
    design:
      columns: '2'

  - block: features
    content:
      title: Compétences & domaines
      text: "Stack complète IA appliquée : vision, apprentissage par renforcement, LLM/RAG."
      items:
        - name: Techniques
          description: Python • PyTorch/TensorFlow • OpenCV • LangChain • Pandas/NumPy • Git/Docker
          icon: code
        - name: Domaines
          description: Vision par ordinateur • Reinforcement Learning (DQN, PPO) • LLM/RAG documents
          icon: brain
        - name: Pratiques
          description: Démos rapides • Documentation claire • Communication bilingue FR/EN
          icon: presentation
      button:
        text: Explorer les projets
        url: /projets/
    design:
      columns: '3'

  - block: features
    content:
      title: Activités & leadership
      text: "Au-delà du code : arts, leadership et transmission."
      items:
        - name: Leadership
          description: Président association théâtre — spectacles, ateliers d'impro, gestion d'équipe.
          icon: star
        - name: Communication
          description: Jury English Debate — évaluation fond/forme, partage d'expertise.
          icon: chat
        - name: Arts & sport
          description: Piano/jazz (12 ans) • Rock acrobatique • Transmission et créativité.
          icon: music
      button:
        text: Découvrir
        url: /activites/
    design:
      columns: '3'

  - block: markdown
    content:
      title: "Contact rapide"
      text: |-
        Pour toute opportunité ou question : [auguste.doyet@efrei.net](mailto:auguste.doyet@efrei.net).
    design:
      columns: '1'
---
