---
title: "RAG LangChain pour documentation UQAC"
slug: "rag-langchain-uqac"
date: 2025-01-15
summary: "Scraping du manuel UQAC et mise en place d'un RAG pour répondre aux questions internes, avec pipeline documenté et reproductible."
tags:
  - LLM/RAG
  - LangChain
  - Python
  - Selenium
  - Vector DB
featured: true
authors:
  - me
role: "Développement et intégration RAG"
context: "Projet académique orienté support interne"
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

Création d'un assistant pour naviguer dans la documentation UQAC. Objectif : répondre rapidement aux questions des étudiants et du personnel en capitalisant les ressources internes.

## Approche

- Scraping ciblé des pages (manuel et FAQ) avec Selenium et nettoyage HTML.
- Vectorisation des passages et indexation dans une base vectorielle.
- Pipeline LangChain pour retrieval + génération, avec garde-fous sur la pertinence.
- Évaluation rapide sur des jeux de questions internes et ajustements de seuils.

## Résultats

- Réponses contextualisées en quelques secondes, avec citations des sources.
- Structure modulable pour ajouter de nouvelles ressources (PDF/HTML) sans refonte.
- Documentation du flux (scraping -> index -> chaînes) pour transfert équipe.

## Stack

Python, LangChain, Selenium, Vector DB, évaluation manuelle sur jeux de questions internes.

## Prochaines étapes

Intégrer une authentification simple, suivre les retours utilisateurs et industrialiser le monitoring des réponses. Les assets visuels et dépôts sont en placeholder : chemins et slugs sont fixés pour accueillir les versions finales.
