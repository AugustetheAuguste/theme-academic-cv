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
      text: "Etudiant en double diplome UQAC/Efrei entre Paris et Chicoutimi. Portfolio Data & IA oriente preuves (vision, reinforcement learning, LLM/RAG) avec CTAs clairs vers les projets et le CV."
      button:
        text: "Voir les projets"
        url: /projets/
      button_alt:
        text: "Consulter le CV"
        url: /cv/
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: "Preuves rapides"
      text: |-
        - **Domaines** : vision par ordinateur, reinforcement learning, LLM/RAG, audio/NLP.
        - **Formation** : double diplome UQAC (IA) et Efrei (Data & IA), semestre international en Malaisie.
        - **Entrepreneuriat** : co-fondateur FALC'On (solution IA de traduction facile a lire).
        - **Livrables** : demos documentees, pipelines Python reproductibles, communication bilingue.
    design:
      columns: '1'

  - block: collection
    content:
      title: Projets phares
      text: "Cartes cliquables vers les projets phares (selection automatique via le flag featured)."
      filters:
        folders:
          - projects
        featured_only: true
    design:
      view: article-grid
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: true

  - block: markdown
    content:
      title: "Experience snapshot"
      text: |-
        - **FALC'On (co-fondateur)** : produit IA pour la traduction facile a lire, prototypage LangChain/LLM, demos partenaires.
        - **Ambassadeur Efrei** : ateliers IA/Data, prise de parole, accompagnement etudiants.
        - **Westline** : immersion robotique/optoelectronique et documentation technique.
        - **Prof particulier** : pedagogie sciences, structuration des supports.
        [Voir le detail des experiences](/experience/).
    design:
      columns: '1'

  - block: markdown
    content:
      title: "Competences et domaines"
      text: |-
        - **Techniques** : Python, PyTorch/TensorFlow, OpenCV, LangChain, pipelines data (Pandas/NumPy), Git/Docker.
        - **Domaines** : vision, RL (DQN, PPO), LLM/RAG orientes documents internes.
        - **Pratiques** : demos rapides, documentation, communication bilingue.
        [Parcourir les projets](/projets/) | [Consulter le CV](/cv/).
    design:
      columns: '1'

  - block: markdown
    content:
      title: "Formation en bref"
      text: |-
        - **UQAC** : maitrise IA (en cours) oriente deep learning, vision, RL, LLM/RAG.
        - **Efrei** : master Data & IA, socle logiciel + projets data/ML.
        - **APU (Malaisie)** : ouverture internationale et collaboration multiculturelle.
        - **Bac OIB** : rigueur academique bilingue.
        [Voir la formation](/formation/).
    design:
      columns: '1'

  - block: markdown
    content:
      title: "Activites & leadership"
      text: |-
        - **Leadership** : president association theatre (organisation de spectacles, ateliers d'impro).
        - **Communication** : jury English Debate (evaluation fond/forme).
        - **Arts & sport** : piano/jazz depuis 12 ans, rock acrobatique et transmission.
        [Decouvrir les activites](/activites/).
    design:
      columns: '1'

  - block: markdown
    content:
      title: "Contact rapide"
      text: |-
        Pour toute opportunite ou question : [auguste.doyet@efrei.net](mailto:auguste.doyet@efrei.net). Les liens GitHub et LinkedIn seront ajoutes ici des que disponibles.
    design:
      columns: '1'
---
