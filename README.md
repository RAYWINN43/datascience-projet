# Mon Projet Data Science
Étudiant(e) 1 : \[Blain Antoine\], Étudiant(e) 2 : \[Martin
Evan\], Étudiant(e) 3 : \[Pecontal Corentin\]
2026-05-20

- [Introduction et Contexte Métier](#sec-intro)
  - [Contexte du Projet](#contexte-du-projet)
  - [Objectif Analytique](#objectif-analytique)
- [Acquisition et Préparation des Données (Data
  Wrangling)](#sec-wrangling)
  - [Chapitre 1 : Acquisition
    Multi-Sources](#chapitre-1--acquisition-multi-sources)
- [📥 Étape 1 : Acquisition des Données & Multi-Sources (Squelette
  Étudiant)](#inbox_tray-étape-1--acquisition-des-données--multi-sources-squelette-étudiant)
  - [→ À voir si on ajoute d’autres
    données](#-à-voir-si-on-ajoute-dautres-données)
  - [Chapitre 2 : Nettoyage et Préparation
    (Wrangling)](#chapitre-2--nettoyage-et-préparation-wrangling)
- [🧹 Étape 2 : Préparation & Nettoyage de Données (Data Wrangling)
  (Squelette
  Étudiant)](#broom-étape-2--préparation--nettoyage-de-données-data-wrangling-squelette-étudiant)
- [Visualisation Multidimensionnelle (Insights)](#sec-viz)
  - [Chapitre 3 : Travaux Pratiques d’Exploration
    Visuelle](#chapitre-3--travaux-pratiques-dexploration-visuelle)
- [📊 Étape 4 : Visualisation Multidimensionnelle (Squelette
  Étudiant)](#bar_chart-étape-4--visualisation-multidimensionnelle-squelette-étudiant)
- [Analyse Exploratoire des Données (EDA)](#sec-eda)
  - [Chapitre 4 : Travaux Pratiques d’Exploration
    (EDA)](#chapitre-4--travaux-pratiques-dexploration-eda)
- [🔎 Étape 3 : Analyse Exploratoire des Données (EDA) (Squelette
  Étudiant)](#mag_right-étape-3--analyse-exploratoire-des-données-eda-squelette-étudiant)
- [Modélisation et Apprentissage](#sec-modelling)
  - [Chapitre 5 : Travaux Pratiques de Modélisation (ML &
    DL)](#chapitre-5--travaux-pratiques-de-modélisation-ml--dl)
- [🧠 Étape 5 : Modélisation (Machine Learning & Deep Learning)
  (Squelette
  Étudiant)](#brain-étape-5--modélisation-machine-learning--deep-learning-squelette-étudiant)
- [Évaluation Métrique et Validation](#sec-evaluation)
  - [Chapitre 6 : Travaux Pratiques d’Évaluation &
    Robustesse](#chapitre-6--travaux-pratiques-dévaluation--robustesse)
- [🧪 Étape 6 : Évaluation Métrique & Robustesse (Squelette
  Étudiant)](#test_tube-étape-6--évaluation-métrique--robustesse-squelette-étudiant)
- [Data Storytelling et Communication](#sec-storytelling)
  - [Chapitre 7 : Travaux Pratiques de
    Storytelling](#chapitre-7--travaux-pratiques-de-storytelling)
- [📢 Étape 7 : Data Storytelling & Communication (Squelette
  Étudiant)](#loudspeaker-étape-7--data-storytelling--communication-squelette-étudiant)
  - [Présentation des Résultats (Livrables
    Interactifs)](#présentation-des-résultats-livrables-interactifs)
- [Utilisation de l’Intelligence Artificielle](#sec-ai)
  - [Cartographie de l’utilisation de
    l’IA](#cartographie-de-lutilisation-de-lia)
  - [Principes de Rigueur et
    Responsabilité](#principes-de-rigueur-et-responsabilité)
- [Bibliographie](#bibliographie)

# Introduction et Contexte Métier

Présentez ici le contexte global de votre projet, la problématique
métier que vous cherchez à résoudre, les questions scientifiques
soulevées et les opportunités d’aide à la décision sur la base de vos
données. Dans le cadre de ce projet, nous travaillons sur une base de
données artificielle générée en 2024 reproduisant des trajets Uber et
les informations associées aux courses.

L’objectif principal de cette étude est de déterminer et prédire le prix
d’une course à partir de plusieurs variables, notamment le lieu de prise
en charge du client, la distance parcourue ainsi que d’autres
caractéristiques présentes dans les données.

Plusieurs questions se posent :  
- Quels sont les paramètres ayant le plus d’impact sur le prix d’une
course ?  
- Existe-t-il une relation forte entre la distance et le tarif ?  
- Le lieu de prise en charge influence-t-il significativement le prix
final ?  
- Peut-on construire un modèle prédictif fiable à partir des données
disponibles ?

Afin de répondre à ces questions, différentes étapes seront réalisées :
préparation et nettoyage des données, analyse, visualisation des
tendances ETC.

## Contexte du Projet

- *Quels sont les objectifs globaux et le domaine d’étude de votre
  projet ?*
- *En quoi ce sujet de recherche est-il pertinent et stratégique ?*
- *Pourquoi l’analyse quantitative de ce jeu de données est-elle
  indispensable pour répondre à votre problématique ?*

Ce projet s’inscrit dans le domaine de la data science appliquée à la
mobilité du service UBER. Les plateformes de VTC exploitent de grandes
quantités de données afin d’optimiser leurs services, améliorer
l’expérience utilisateur et adapter leurs stratégies tarifaires.

Ce sujet est particulièrement pertinent car la prédiction des prix
représente un enjeu important pour les entreprises de transport. Une
meilleure compréhension des facteurs influençant les tarifs permet
d’optimiser les revenus et de proposer des prix cohérents aux diffèrent
utilisateurs.

L’analyse quantitative des données est essentielle pour répondre à cette
problématique. L’étude statistique et l’exploitation des données
permettent d’identifier les tendances, de mesurer l’impact des
différentes variables et de construire des modèles prédictifs fiables.
Les résultats obtenus peuvent ainsi servir d’aide pour améliorer les
stratégies de tarification.

## Objectif Analytique

- *Quelles sont les variables cibles principales et la tâche globale de
  modélisation (classification, régression, clustering, etc.) ?*
- *Comment le couplage de données multi-sources et l’intégration de
  différents types de données (tabulaires, images, signaux, etc.)
  enrichissent-ils l’analyse ?*
- *Quels sont les livrables analytiques attendus pour répondre à votre
  problématique et guider les prises de décisions ?*

La variable cible principale de ce projet est le *Booking Value*,
correspondant au prix du trajet. L’objectif est de prédire le coût d’une
réservation à partir de plusieurs variables comme la localisation de
départ (*Pickup Location*), la destination (*Drop Location*), la
distance du trajet (*Ride Distance*), le type de véhicule ou encore le
mode de paiement.

Les données tabulaires permettent d’analyser les relations entre les
différentes caractéristiques des trajets afin d’identifier les facteurs
ayant le plus d’impact sur le prix.

Les livrables attendus incluent des visualisations de données, des
indicateurs statistiques et un modèle prédictif capable d’estimer le
prix d’un trajet afin d’aider à l’optimisation des réservations et à la
prise de décision.

------------------------------------------------------------------------

# Acquisition et Préparation des Données (Data Wrangling)

Le succès de tout projet de Data Science repose sur la qualité de la
préparation des données ([McKinney 2020](#ref-pandas2020)). Cette
section documente l’audit de qualité et les étapes de nettoyage
appliquées à vos jeux de données bruts.

## Chapitre 1 : Acquisition Multi-Sources

# 📥 Étape 1 : Acquisition des Données & Multi-Sources (Squelette Étudiant)

Cette étape correspond au premier chapitre du pipeline de Data Science.
L’objectif est d’identifier, d’importer et de consolider vos jeux de
données bruts issus de différentes sources (fichiers CSV locaux,
requêtes API, bases de données, etc.).

### 1. Initialisation de l’environnement

### 2. Chargement de la source de données principale

Chargement de notre jeu de données grace a un fichier CSV stocké dans
data/raw/

## → À voir si on ajoute d’autres données

### 3. Intégration de données secondaires (Multi-Sources)

**À COMPLÉTER PAR L’ÉTUDIANT :** Mettez en place la récupération de vos
données complémentaires (par exemple, appels d’API fictifs ou réels,
données météo, géographiques, ou financiers complémentaires).

### 4. Fusion des sources (Optionnel)

**À COMPLÉTER PAR L’ÉTUDIANT :** Associez vos différentes sources de
données en utilisant des jointures (`pd.merge`) pertinentes.

### 5. Consignation des données d’entrée brutes

Sauvegardez l’état brut de vos données d’entrée pour la suite du
pipeline.

## Chapitre 2 : Nettoyage et Préparation (Wrangling)

# 🧹 Étape 2 : Préparation & Nettoyage de Données (Data Wrangling) (Squelette Étudiant)

Cette étape correspond au deuxième chapitre du projet. L’objectif est
d’effectuer un audit de qualité de vos données brutes, puis de mettre en
œuvre un nettoyage rigoureux à l’aide de votre package personnalisé
`src.data_clean`.

### 1. Initialisation et imports

### 2. Chargement du dataset brut et Audit Initial

**À COMPLÉTER PAR L’ÉTUDIANT :** Chargez les données brutes et inspectez
la qualité du dataset (taux de valeurs manquantes, présence de doublons,
types erronés).

### 3. Uniformisation des Formats de Dates

**À COMPLÉTER PAR L’ÉTUDIANT :** Uniformisez la colonne temporelle pour
la convertir dans un type datetime standardisé via la fonction
pd.to_datetime.

### 4. Identification et Filtrage des Valeurs Aberrantes (Outliers)

**À COMPLÉTER PAR L’ÉTUDIANT :** Identifiez les anomalies physiques et
utilisez votre fonction `dc.handle_outliers` pour transformer ces
valeurs aberrantes en NaNs.

Vérifier correspondances entre Booking ID et colonnes Cancelled Rides

### 6. Sauvegarde des données propres

Enregistrez vos données de base nettoyées dans le répertoire
`data/processed/`.

------------------------------------------------------------------------

# Visualisation Multidimensionnelle (Insights)

Nous présentons ici les résultats visuels clés permettant de dégager des
insights exploitables pour les décideurs, en s’appuyant sur notre module
`src/utils_viz.py`.

## Chapitre 3 : Travaux Pratiques d’Exploration Visuelle

# 📊 Étape 4 : Visualisation Multidimensionnelle (Squelette Étudiant)

Cette étape correspond au quatrième chapitre du cours. L’objectif est de
concevoir des représentations visuelles premium pour identifier des
tendances et insights clés à l’aide de votre package personnalisé de
tracé `src.utils_viz`.

### 1. Préparation de l’environnement

### 2. Chargement du dataset enrichi

### 3. Tracés et analyses graphiques

#### A. Évolution des tendances dans le temps

**À COMPLÉTER PAR L’ÉTUDIANT :** Tracez les tendances globales à l’aide
de la fonction `uv.plot_generic_trends`.

#### B. Carte de chaleur des corrélations

**À COMPLÉTER PAR L’ÉTUDIANT :** Visualisez graphiquement les
corrélations de Pearson à l’aide de `uv.plot_correlation_matrix`.

#### C. Nuage de points bivarié

**À COMPLÉTER PAR L’ÉTUDIANT :** Générez une analyse graphique bivariée
en utilisant `uv.plot_bivariate_scatter`.

------------------------------------------------------------------------

# Analyse Exploratoire des Données (EDA)

Dans cette section, nous analysons les relations statistiques
fondamentales qui régissent votre domaine d’étude au sein du jeu de
données.

## Chapitre 4 : Travaux Pratiques d’Exploration (EDA)

# 🔎 Étape 3 : Analyse Exploratoire des Données (EDA) (Squelette Étudiant)

Cette étape correspond au troisième chapitre du cours. L’objectif est
d’explorer et de résumer les propriétés statistiques fondamentales de
vos données et de réaliser du **Feature Engineering** pour enrichir vos
modèles.

### 1. Préparation de l’environnement

### 2. Chargement des données nettoyées

### 3. Statistiques Descriptives

**À COMPLÉTER PAR L’ÉTUDIANT :** Générez les résumés statistiques
globaux et par groupes/catégories de votre jeu de données.

### 4. Ingénierie de variables (Feature Engineering)

**À COMPLÉTER PAR L’ÉTUDIANT :** Appliquez la fonction
`feature_engineering` de `src.data_clean` pour extraire des indicateurs
temporels de base, et ajoutez d’autres variables dérivées complexes
adaptées à votre problématique.

### 5. Analyse des Corrélations

**À COMPLÉTER PAR L’ÉTUDIANT :** Analysez la matrice des corrélations
des caractéristiques numériques à l’aide de Pandas.

------------------------------------------------------------------------

# Modélisation et Apprentissage

Le pipeline complet intègre à la fois la branche analytique tabulaire
(Machine Learning) et la branche d’analyse visuelle ou de signaux
complexes (Deep Learning CNN) :

``` mermaid
graph TD
    A[Données Brutes Multi-Sources CSV/API] -->|Formatage & Alignement| B(data_clean.clean_dates)
    C[Données Externes Complémentaires] -->|Imputation & Interpolation| D(data_clean.impute_missing_values)
    B & D -->|Gestion Outliers| E[Jeu de données Propre & Fusionné]
    E -->|Extraction Temporelle/Caractéristiques| F[Feature Engineering]
    F -->|Splits Temporels ou Stratifiés| G[Modèle Machine Learning Tabulaire]
    H[Flux Multimédias Réels Images/Signaux] -->|Prétraitement d'images/signaux| I[Réseau Convolutif CNN TensorFlow]
    G -->|Prédictions de la Problématique Métier| J[Livrables & Aide à la Décision]
    I -->|Détection de Motifs Complexes| J
    
    style E fill:#e0f2fe,stroke:#0284c7,stroke-width:2px
    style J fill:#f0fdf4,stroke:#16a34a,stroke-width:2px
    style G fill:#fef3c7,stroke:#d97706,stroke-width:2px
    style I fill:#fef3c7,stroke:#d97706,stroke-width:2px
```

---

## 🛠️ Exécuter et compiler localement

Toutes les tâches du projet sont orchestrées simplement via le gestionnaire de tâches **Go-Task** (`task`).

### 1. Prérequis

Assurez-vous d'avoir installé :
- [Python 3.12](https://www.python.org/)
- [Quarto CLI](https://quarto.org/docs/get-started/)
- [Go-Task](https://taskfile.dev/installation/)

Installez ensuite les dépendances du projet :
```bash
pip install -r requirements.txt
```

### 2. Commandes de compilation rapides

Depuis la racine du projet, lancez :

* **Compiler l'intégralité du pipeline et des rapports** (génère tout dans `build/`) :
  ```bash
  task render
  ```
* **Prévisualiser dynamiquement le rapport dans le navigateur** (rechargement automatique lors de la saisie) :
  ```bash
  task preview
  ```
* **Compiler uniquement le guide d'installation** :
  ```bash
  task install-guide
  ```
* **Nettoyer tous les fichiers temporaires et compilations locales** :
  ```bash
  task clean
  ```

---

*Développé dans le cadre du projet fil rouge de Data Science.*
