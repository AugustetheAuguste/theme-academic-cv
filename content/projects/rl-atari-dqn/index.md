---
title: "Reinforcement Learning Atari - DQN"
slug: "rl-atari-dqn"
date: 2024-10-15
summary: "Agent DQN entraine sur Breakout avec optimisations stabilisantes et suivi des scores."
featured: true
tags:
  - Reinforcement Learning
  - DQN
  - Gym
  - Python
authors:
  - me
role: "Developpement et tuning DQN"
context: "Projet academique / demo RL"
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

Projet RL pour entrainer un agent a jouer a Breakout. Focus sur la stabilite d'apprentissage et l'analyse des gains.

## Approche

- Environnement Atari via Gym, observation grayscale et downsampling.
- Reseau convolutionnel avec Experience Replay et epsilon-greedy schedule.
- Cible gelée et prioritisation simple des transitions pour mieux couvrir les situations rares.

## Resultats

- Score en progression stable apres tuning du learning rate et du replay buffer.
- Visualisation des episodes clefs pour illustrer les strategies apprises.
- Code structure pour tester d'autres environnements Atari.

## Stack

Python, PyTorch, OpenAI Gym, Matplotlib pour le suivi des courbes.

## Prochaines etapes

Tester des variantes Double/Noisy DQN, ajouter une evaluation automatique et publier une demo video. Les liens et visuels sont des placeholders : ils seront remplaces par les assets finaux sans changer les chemins.
