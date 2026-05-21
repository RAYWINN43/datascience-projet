---
title: "Mon Projet Data Science"
subtitle: "Projet Fil Rouge Data Science - Sujet Libre"
author:
  - "Étudiant(e) 1 : [Blain Antoine]"
  - "Étudiant(e) 2 : [Martin Evan]"
  - "Étudiant(e) 3 : [Pecontal Corentin]"
date: today
format:
  html:
    theme: cosmo
    toc: true
    toc-depth: 3
    number-sections: true
    code-fold: show
    code-tools: true
    highlight-style: github
  typst:
    toc: true
    number-sections: true
  gfm:
    output-file: "rapport.md"
    toc: true
    toc-depth: 2
execute:
  eval: false
  echo: false
  warning: false
bibliography: references.bib
link-citations: true
---

# Introduction et Contexte Métier {#sec-intro}

Dans le cadre de ce projet, nous travaillons sur une base de données artificielle générée en 2024 reproduisant des trajets Uber et les informations associées aux courses.  

L’objectif principal de cette étude est de déterminer et prédire le prix d’une course à partir de plusieurs variables, notamment le lieu de prise en charge du client, la distance parcourue ainsi que d’autres caractéristiques présentes dans les données.  

Plusieurs questions se posent :  
- Quels sont les paramètres ayant le plus d’impact sur le prix d’une course ?  
- Existe-t-il une relation forte entre la distance et le tarif ?  
- Le lieu de prise en charge influence-t-il significativement le prix final ?  
- Peut-on construire un modèle prédictif fiable à partir des données disponibles ?  

Afin de répondre à ces questions, différentes étapes seront réalisées : préparation et nettoyage des données, analyse, visualisation des tendances ETC.  


## Contexte du Projet

Ce projet s’inscrit dans le domaine de la data science appliquée à la mobilité du service UBER. Les plateformes de VTC exploitent de grandes quantités de données afin d’optimiser leurs services, améliorer l’expérience utilisateur et adapter leurs stratégies tarifaires.  

Ce sujet est particulièrement pertinent car la prédiction des prix représente un enjeu important pour les entreprises de transport. Une meilleure compréhension des facteurs influençant les tarifs permet d’optimiser les revenus et de proposer des prix cohérents aux diffèrent utilisateurs.  

L’analyse quantitative des données est essentielle pour répondre à cette problématique. L’étude statistique et l’exploitation des données permettent d’identifier les tendances, de mesurer l’impact des différentes variables et de construire des modèles prédictifs fiables. Les résultats obtenus peuvent ainsi servir d’aide pour améliorer les stratégies de tarification.  

## Objectif Analytique

Nous travaillons sur la base du Dataset BRUT qui contient les colonnes suivantes :

| Nom de la colonne | Description |
|---|---|
| Date | Date de la réservation |
| Time | Heure de la réservation |
| Booking ID | Identifiant unique de chaque réservation de trajet |
| Booking Status | Statut de la réservation (Terminée, Annulée par le client, Annulée par le chauffeur, etc.) |
| Customer ID | Identifiant unique des clients |
| Vehicle Type | Type de véhicule (Go Mini, Go Sedan, Auto, eBike/Bike, UberXL, Premier Sedan) |
| Pickup Location | Lieu de départ du trajet |
| Drop Location | Destination du trajet |
| VTAT | Temps moyen pour que le chauffeur atteigne le point de prise en charge (en minutes) |
| CTAT | Durée moyenne du trajet entre le départ et la destination (en minutes) |
| Cancelled Rides by Customer | Indicateur d’annulation du trajet par le client |
| Reason for cancelling by Customer | Raison de l’annulation par le client |
| Cancelled Rides by Driver | Indicateur d’annulation du trajet par le chauffeur |
| Driver Cancellation Reason | Raison de l’annulation par le chauffeur |
| Incomplete Rides | Indicateur de trajet incomplet |
| Incomplete Rides Reason | Raison du trajet incomplet |
| Booking Value | Montant total de la course |
| Ride Distance | Distance parcourue pendant le trajet (en km) |
| Driver Ratings | Note attribuée au chauffeur (échelle de 1 à 5) |
| Customer Rating | Note donnée par le client (échelle de 1 à 5) |
| Payment Method | Méthode de paiement utilisée (UPI, espèces, carte bancaire, portefeuille Uber, carte de débit) |

Après affinement nous avons gardé les colonnes suivantes :
| Nom de la colonne | Description |
|---|---|
| Date | Date de la réservation |
| Vehicle Type | Type de véhicule utilisé pour le trajet |
| Pickup Location | Lieu de départ du trajet |
| Drop Location | Destination du trajet |
| VTAT | Temps moyen pour que le chauffeur atteigne le point de prise en charge (en minutes) |
| CTAT | Durée moyenne du trajet entre le départ et la destination (en minutes) |
| Booking Value | Montant total de la course |
| Ride Distance | Distance parcourue pendant le trajet (en km) |
| Payment Method | Méthode de paiement utilisée |
| Completed | Indique si le trajet a été complété ou non |

La variable cible principale de ce projet est le (*Booking Value*),
correspondant au prix du trajet. L’objectif est de prédire le coût d’une
réservation à partir de plusieurs variables comme le temps que le chauffeur mets pour atteindre le point de prise en charge (*VTAT*),
la durée entre le départ et la destination (*CTAT*), la distance du trajet (*Ride Distance*), le type de véhicule (*Vehicle Type*) ou encore le mode de paiement(*Payment Method*).


# Acquisition et Préparation des Données (Data Wrangling) {#sec-wrangling}

## Chapitre 1 : Acquisition Multi-Sources
{{< include ../build/notebooks/01_acquisition.qmd >}}

## Chapitre 2 : Nettoyage et Préparation (Wrangling)
{{< include ../build/notebooks/02_wrangling.qmd >}}

## Chapitre 3 : Travaux Pratiques d'Exploration Visuelle
{{< include ../build/notebooks/03_visualisation.qmd >}}


# Analyse Exploratoire des Données (EDA) {#sec-eda}

Dans cette section, nous analysons les relations statistiques fondamentales qui régissent votre domaine d'étude au sein du jeu de données.

## Chapitre 4 : Travaux Pratiques d'Exploration (EDA)
{{< include ../build/notebooks/04_eda.qmd >}}

## Chapitre 5 : Travaux Pratiques de Modélisation (ML & DL)
{{< include ../build/notebooks/05_modelisation.qmd >}}

---

# Évaluation Métrique et Validation {#sec-evaluation}

## Chapitre 6 : Travaux Pratiques d'Évaluation & Robustesse
{{< include ../build/notebooks/06_evaluation.qmd >}}

---

# Data Storytelling et Communication {#sec-storytelling}

## Chapitre 7 : Travaux Pratiques de Storytelling
{{< include ../build/notebooks/07_communication.qmd >}}

## Présentation des Résultats (Livrables Interactifs)

::: {.panel-tabset}

### 📊 Dashboard Dynamique (OJS / Plotly)

  {{< include ../DashBord.html >}}
 
---

# Utilisation de l'Intelligence Artificielle {#sec-ai}

Dans une démarche de transparence scientifique et académique, cette section détaille la manière dont les outils d'Intelligence Artificielle (IA) générative ont été intégrés tout au long de la réalisation de ce projet.


## Cartographie de l'utilisation de l'IA

| Outil d'IA | Cas d'usage (Pourquoi ?) | Méthode d'utilisation (Comment ?) | Rôle et Validation Humaine |
| :--- | :--- | :--- | :--- |
| CHATGPT | BUG GIT fork et prompte pour codex | demande a l'IA de maniere stucturer,en expliquan le contexte | supervision relecture du prompt et execution de commande pour syncroniser GIT(verrification sur internet) |
| CODEX | generation du Dashboard | envoi d'un prompt fait par CHATGPT | supervision, verrification des action et verrification de l'HTML a chaque corection |


## Principes de Rigueur et Responsabilité

1. **Responsabilité intellectuelle** : L'équipe assume l'entière responsabilité des analyses, des choix de modèles et des conclusions présentées dans ce rapport.
2. **Lutte contre les hallucinations** : Chaque suggestion technique a fait l'objet d'une validation empirique.
3. **Protection des données** : Aucun jeu de données confidentiel ou sensible n'a été soumis à des modèles tiers en ligne.
