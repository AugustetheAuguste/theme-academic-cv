---
title: "Reinforcement Learning Atari - DQN"
slug: "rl-atari-dqn"
date: 2024-10-15
summary: "Agent DQN entraîné sur Breakout avec optimisations stabilisantes et suivi des scores."
featured: true
tags:
  - Reinforcement Learning
  - DQN
  - Gym
  - Python
authors:
  - me
role: "Développement et tuning DQN"
context: "Projet académique / démo RL"
duration: "3 semaines"
stack:
  - Python
  - PyTorch
  - OpenAI Gym
  - Matplotlib
links:
  - type: github
    url: ""
  - type: report
    url: ""
image:
  filename: /img/projects/rl-atari-dqn/cover.png
  alt: "Placeholder pour l'agent DQN sur Atari Breakout"
---

## Contexte

Projet RL pour entraîner un agent à jouer à Breakout. Focus sur la stabilité d'apprentissage et l'analyse des gains.

## Approche

- Environnement Atari via Gym, observation grayscale et downsampling.
- Réseau convolutionnel avec Experience Replay et epsilon-greedy schedule.
- Cible gelée et prioritisation simple des transitions pour mieux couvrir les situations rares.

## Résultats

- Score en progression stable après tuning du learning rate et du replay buffer.
- Visualisation des épisodes clefs pour illustrer les stratégies apprises.
- Code structuré pour tester d'autres environnements Atari.

## Stack

Python, PyTorch, OpenAI Gym, Matplotlib pour le suivi des courbes.

## Prochaines étapes

Tester des variantes Double/Noisy DQN, ajouter une évaluation automatique et publier une démo vidéo. Les liens et visuels sont des placeholders : ils seront remplacés par les assets finaux sans changer les chemins.
