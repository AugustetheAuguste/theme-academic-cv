---
title: "RAG LangChain pour documentation UQAC"
slug: "rag-langchain-uqac"
date: 2025-01-15
summary: "Scraping du manuel UQAC et mise en place d'un RAG pour repondre aux questions internes, avec pipeline documente et reproductible."
tags:
  - LLM/RAG
  - LangChain
  - Python
  - Selenium
  - Vector DB
featured: true
authors:
  - me
role: "Developpement et integration RAG"
context: "Projet academique oriente support interne"
duration: "2 semaines"
stack:
  - Python
  - LangChain
  - Selenium
  - Vector DB
links:
  - type: github
    url: ""
  - type: demo
    url: ""
  - type: report
    url: ""
image:
  filename: /img/projects/rag-langchain-uqac/cover.png
  alt: "Placeholder pour le pipeline RAG LangChain"
---

## Contexte

Creation d'un assistant pour naviguer dans la documentation UQAC. Objectif : repondre rapidement aux questions des etudiants et du personnel en capitalisant les ressources internes.

## Approche

- Scraping cible des pages (manuel et FAQ) avec Selenium et nettoyage HTML.
- Vectorisation des passages et indexation dans une base vectorielle.
- Pipeline LangChain pour retrieval + generation, avec garde-fous sur la pertinence.
- Evaluation rapide sur des jeux de questions internes et ajustements de seuils.

## Resultats

- Reponses contextualisees en quelques secondes, avec citations des sources.
- Structure modulable pour ajouter de nouvelles ressources (PDF/HTML) sans refonte.
- Documentation du flux (scraping -> index -> chaines) pour transfert equipe.

## Stack

Python, LangChain, Selenium, Vector DB, evaluation manuelle sur jeux de questions internes.

## Prochaines etapes

Brancher une authentification simple, suivre les retours utilisateurs et industrialiser le monitoring des reponses. Les assets visuels et depots sont en placeholder : chemins et slugs sont fixes pour accueillir les versions finales.
