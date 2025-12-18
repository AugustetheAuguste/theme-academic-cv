---
title: "Reconnaissance faciale avec FaceNet"
slug: "facenet-reconnaissance-faciale"
date: 2024-12-01
summary: "Pipeline de vérification d'identité basé sur FaceNet et OpenCV, documenté et prêt à être rebranché sur des flux vidéo."
tags:
  - Vision
  - OpenCV
  - FaceNet
  - Python
featured: true
authors:
  - me
role: "Développement vision par ordinateur"
context: "Prototype démonstration sécurité"
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
  alt: "Placeholder pour la vérification faciale avec FaceNet"
---

## Contexte

Prototype de vérification d'identité à partir d'images. Objectif : offrir une démo claire et reproductible pour des cas d'usage sécurité ou contrôle d'accès.

## Approche

- Prétraitement OpenCV (alignement visage, détection des landmarks).
- Extraction d'embeddings avec FaceNet et comparaison de distance.
- Calibration d'un seuil de similarité et évaluation sur échantillons de tests.

## Résultats

- Vérification robuste sur jeux de tests internes.
- Explicabilité minimale via visualisation des matches et distances.
- Tutoriel d'utilisation pour rejouer les expériences.

## Stack

Python, FaceNet, OpenCV, NumPy.

## Prochaines étapes

Intégrer un module de gestion utilisateurs, collecter des jeux de tests plus variés et brancher une supervision du drift. Les visuels et liens sont en placeholder : la structure de dossiers est déjà stabilisée pour ajout d'assets réels.
