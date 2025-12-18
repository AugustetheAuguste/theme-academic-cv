---
title: "Reconnaissance faciale avec FaceNet"
slug: "facenet-reconnaissance-faciale"
date: 2024-12-01
summary: "Pipeline de verification d'identite base sur FaceNet et OpenCV, documente et pret a etre rebranche sur des flux video."
tags:
  - Vision
  - OpenCV
  - FaceNet
  - Python
featured: true
authors:
  - me
role: "Developpement vision par ordinateur"
context: "Prototype demonstration securite"
duration: "3 semaines"
stack:
  - Python
  - FaceNet
  - OpenCV
  - NumPy
links:
  - type: github
    url: ""
  - type: report
    url: ""
image:
  filename: /img/projects/facenet-reconnaissance-faciale/cover.png
  alt: "Placeholder pour la verification faciale avec FaceNet"
---

## Contexte

Prototype de verification d'identite a partir d'images. Objectif : offrir une demo claire et reproductible pour des cas d'usage securite ou controle d'acces.

## Approche

- Pretraitement OpenCV (alignement visage, detection des landmarks).
- Extraction d'embeddings avec FaceNet et comparaison de distance.
- Calibration d'un seuil de similarite et evaluation sur echantillons de tests.

## Resultats

- Verification robuste sur jeux de tests internes.
- Explicabilite minimale via visualisation des matches et distances.
- Tutoriel d'utilisation pour rejouer les experiments.

## Stack

Python, FaceNet, OpenCV, NumPy.

## Prochaines etapes

Integre un module de gestion utilisateurs, collecter des jeux de tests plus varies et brancher une supervision du drift. Les visuels et liens sont en placeholder : la structure de dossiers est deja stabilisee pour ajout d'assets reels.
