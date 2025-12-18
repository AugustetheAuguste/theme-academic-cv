---
title: "PPO pour jeu de cartes"
slug: "ppo-jeu-de-cartes"
date: 2024-08-20
summary: "Entraînement d'un agent PPO sur un jeu de cartes simplifié, avec évaluation sur différentes stratégies."
featured: true
tags:
  - Reinforcement Learning
  - PPO
  - Python
  - Gym
authors:
  - me
role: "Expérimentations reinforcement learning"
context: "Projet personnel pour tester PPO sur un environnement cartes"
duration: "2 semaines"
stack:
  - Python
  - PyTorch
  - Gym
  - TensorBoard
links:
  - type: github
    url: ""
  - type: report
    url: ""
image:
  filename: /img/projects/ppo-jeu-de-cartes/cover.png
  alt: "Placeholder pour l'agent PPO sur jeu de cartes"
---

## Contexte

Tester PPO sur un environnement cartes pour explorer la généralisation et l'ajustement des hyperparamètres.

## Approche

- Modèle actor-critic avec clipping PPO.
- Shaping des récompenses pour encourager la gestion du risque et du tempo.
- Suivi TensorBoard des rewards et de la longueur des épisodes.

## Résultats

- Politique stable après quelques centaines de milliers d'étapes.
- Comparaison avec une baseline heuristique pour quantifier le gain.
- Documentation des hyperparamètres et scripts de relance.

## Stack

Python, PyTorch, Gym, TensorBoard.

## Prochaines étapes

Renforcer l'exploration par des techniques de priorisation, comparer PPO à d'autres algorithmes et publier les courbes d'apprentissage. Les visuels et dépôts sont pour l'instant des placeholders : les chemins sont fixés pour intégrer les assets définitifs.
