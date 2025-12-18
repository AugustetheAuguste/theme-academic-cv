---
title: "PPO pour jeu de cartes"
slug: "ppo-jeu-de-cartes"
date: 2024-08-20
summary: "Entrainement d'un agent PPO sur un jeu de cartes simplifie, avec evaluation sur differentes strategies."
featured: true
tags:
  - Reinforcement Learning
  - PPO
  - Python
  - Gym
authors:
  - me
role: "Experimentations reinforcement learning"
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

Tester PPO sur un environnement cartes pour explorer la generalisation et l'ajustement des hyperparametres.

## Approche

- Modele actor-critic avec clipping PPO.
- Shaping des recompenses pour encourager la gestion du risque et du tempo.
- Suivi tensorboard des rewards et de la longueur des episodes.

## Resultats

- Politique stable apres quelques centaines de milliers d'etapes.
- Comparaison avec une baseline heuristique pour quantifier le gain.
- Documentation des hyperparametres et scripts de relance.

## Stack

Python, PyTorch, Gym, TensorBoard.

## Prochaines etapes

Renforcer l'exploration par des techniques de priorisation, comparer PPO a d'autres algorithmes et publier les courbes d'apprentissage. Les visuels et depots sont pour l'instant des placeholders : les chemins sont fixes pour integrer les assets definitifs.
