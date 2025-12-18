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

  - block: markdown
    content:
      title: "Expérience snapshot"
      text: |-
        - **FALC'On (co-fondateur)** : produit IA pour la traduction facile à lire, prototypage LangChain/LLM, démos partenaires.
        - **Ambassadeur Efrei** : ateliers IA/Data, prise de parole, accompagnement étudiants.
        - **Westline** : immersion robotique/optoélectronique et documentation technique.
        - **Prof particulier** : pédagogie sciences, structuration des supports.

        [Voir le détail des expériences](/experience/)
    design:
      columns: '1'

  - block: markdown
    content:
      title: "Compétences et domaines"
      text: |-
        - **Techniques** : Python, PyTorch/TensorFlow, OpenCV, LangChain, pipelines data (Pandas/NumPy), Git/Docker.
        - **Domaines** : vision, RL (DQN, PPO), LLM/RAG orientés documents internes.
        - **Pratiques** : démos rapides, documentation, communication bilingue.

        [Parcourir les projets](/projets/)  
        [Consulter le CV](/cv/)
    design:
      columns: '1'

  - block: markdown
    content:
      title: "Formation en bref"
      text: |-
        - **UQAC** : maîtrise IA (en cours) orienté deep learning, vision, RL, LLM/RAG.
        - **Efrei** : master Data & IA, socle logiciel + projets data/ML.
        - **APU (Malaisie)** : ouverture internationale et collaboration multiculturelle.
        - **Bac OIB** : rigueur académique bilingue.

        [Voir la formation](/formation/)
    design:
      columns: '1'

  - block: markdown
    content:
      title: "Activités & leadership"
      text: |-
        - **Leadership** : président association théâtre (organisation de spectacles, ateliers d'impro).
        - **Communication** : jury English Debate (évaluation fond/forme).
        - **Arts & sport** : piano/jazz depuis 12 ans, rock acrobatique et transmission.

        [Découvrir les activités](/activites/)
    design:
      columns: '1'

  - block: markdown
    content:
      title: "Contact rapide"
      text: |-
        Pour toute opportunité ou question : [auguste.doyet@efrei.net](mailto:auguste.doyet@efrei.net).
    design:
      columns: '1'
---
