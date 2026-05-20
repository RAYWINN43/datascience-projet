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

\*À rédiger par les étudiants : Présentez ici le contexte global de
votre projet, la problématique métier que vous cherchez à résoudre, les
questions scientifiques soulevées et les opportunités d’aide à la
décision sur la base de vos données. Dans le cadre de ce projet, nous
travaillons sur une base de données artificielle générée en 2024
reproduisant des trajets Uber et les informations associées aux courses.

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
\*

## Contexte du Projet

*À rédiger par les étudiants — Pistes de réflexion :*

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
problématique. l’étude statistique et l’exploitation des données
permettent d’identifier les tendances, de mesurer l’impact des
différentes variables et de construire des modèles prédictifs fiables.
Les résultats obtenus peuvent ainsi servir d’aide pour améliorer les
stratégies de tarification.

## Objectif Analytique

*À rédiger par les étudiants — Pistes de réflexion :*

- *Quelles sont les variables cibles principales et la tâche globale de
  modélisation (classification, régression, clustering, etc.) ?*
- *Comment le couplage de données multi-sources et l’intégration de
  différents types de données (tabulaires, images, signaux, etc.)
  enrichissent-ils l’analyse ?*
- *Quels sont les livrables analytiques attendus pour répondre à votre
  problématique et guider les prises de décisions ?*

\[Rédiger votre paragraphe d’objectifs ici\]

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

## Chapitre 5 : Travaux Pratiques de Modélisation (ML & DL)

# 🧠 Étape 5 : Modélisation (Machine Learning & Deep Learning) (Squelette Étudiant)

Cette étape correspond au cinquième chapitre du cours. L’objectif est
d’implémenter d’une part un modèle de Machine Learning tabulaire (ex:
RandomForest) et d’autre part un réseau de neurones convolutif (CNN)
sous TensorFlow pour traiter des images ou signaux complexes.

### 1. Préparation de l’environnement

### 2. Modélisation Tabulaire (Machine Learning)

**À COMPLÉTER PAR L’ÉTUDIANT :** Entraînez un modèle d’apprentissage
supervisé (ex: forêt aléatoire) sur les caractéristiques extraites de
votre jeu de données.

### 3. Modélisation Vision / Deep Learning (CNN & TensorFlow)

**À COMPLÉTER PAR L’ÉTUDIANT :** Pour des motifs complexes
(images/signaux), mettez en place un réseau convolutif (Conv2D, Pooling,
Dense) pour classifier ou enrichir vos prédictions.

------------------------------------------------------------------------

# Évaluation Métrique et Validation

## Chapitre 6 : Travaux Pratiques d’Évaluation & Robustesse

# 🧪 Étape 6 : Évaluation Métrique & Robustesse (Squelette Étudiant)

Cette étape correspond au sixième chapitre du cours. L’objectif est de
mettre en place un protocole d’évaluation rigoureux (splits d’évaluation
adaptés) et de calculer les métriques clés de performance pour valider
scientifiquement la qualité de vos modèles.

### 1. Préparation de l’environnement

### 2. Évaluation du modèle Tabulaire

**À COMPLÉTER PAR L’ÉTUDIANT :** Calculez et interprétez les métriques
d’erreur sur vos prédictions (MAE, RMSE, R²).

### 3. Protocole de Validation Croisée (Out-of-Fold / Chronologique)

**À COMPLÉTER PAR L’ÉTUDIANT :** Décrivez et codez (ou documentez) une
stratégie de validation croisée adaptée au comportement temporel de vos
données pour valider la robustesse de votre modèle sans fuite
d’information.

------------------------------------------------------------------------

# Data Storytelling et Communication

## Chapitre 7 : Travaux Pratiques de Storytelling

# 📢 Étape 7 : Data Storytelling & Communication (Squelette Étudiant)

Cette étape correspond au septième et dernier chapitre de data science.
L’objectif est de synthétiser vos résultats pour des profils métiers ou
décideurs et de proposer des visualisations interactives ou dynamiques
pour valoriser vos conclusions.

### 1. Préparation de l’environnement

### 2. Synthèse métier et Storytelling

**À COMPLÉTER PAR L’ÉTUDIANT :** Traduisez vos métriques techniques en
impacts stratégiques (par exemple, gains financiers, réduction de coûts,
amélioration de la sécurité, etc.).

### 3. Visualisation Interactive (Plotly)

**À COMPLÉTER PAR L’ÉTUDIANT :** Générez un graphique interactif (par
exemple en utilisant Plotly ou des éléments OJS dans le document final)
pour permettre aux décideurs d’interagir dynamiquement avec vos données.

## Présentation des Résultats (Livrables Interactifs)

<div class="panel-tabset">

### 📺 Diaporama de Soutenance (RevealJS)

Ci-dessous est intégré le squelette de votre diaporama de soutenance
RevealJS. Utilisez-le pour présenter votre démarche aux décideurs de
façon professionnelle.

<iframe src="slides.html" width="100%" height="500px" style="border: 1px solid #e2e8f0; border-radius: 8px; background: white;">

</iframe>

### 📊 Exemple de Dashboard Dynamique (OJS / Plotly)

Voici un exemple minimal de code montrant comment intégrer un graphique
dynamique contrôlé par un composant d’interface utilisateur en
Observable JS (OJS).

``` {ojs}
//| echo: true
// Boutons de sélection interactifs OJS
viewof selectedCategory = Inputs.select(["Toutes", "A", "B", "C"], {value: "Toutes", label: "Filtrer par Catégorie :"})
```

``` {ojs}
//| echo: false
// Données simulées réactives
data = [
  {timestamp: "2026-05-18T00:00:00Z", value: 10.5, category: "A"},
  {timestamp: "2026-05-18T02:00:00Z", value: 12.1, category: "A"},
  {timestamp: "2026-05-18T04:00:00Z", value: 14.7, category: "A"},
  {timestamp: "2026-05-18T05:00:00Z", value: 15.2, category: "A"},
  {timestamp: "2026-05-18T06:00:00Z", value: 16.0, category: "B"},
  {timestamp: "2026-05-18T07:00:00Z", value: 18.3, category: "B"},
  {timestamp: "2026-05-18T09:00:00Z", value: 21.5, category: "B"},
  {timestamp: "2026-05-18T10:00:00Z", value: 22.0, category: "B"},
  {timestamp: "2026-05-18T12:00:00Z", value: 25.4, category: "C"},
  {timestamp: "2026-05-18T13:00:00Z", value: 26.1, category: "C"},
  {timestamp: "2026-05-18T15:00:00Z", value: 28.9, category: "C"},
  {timestamp: "2026-05-18T16:00:00Z", value: 30.2, category: "C"}
]

// Filtrage réactif de la donnée
filteredData = selectedCategory === "Toutes" 
  ? data 
  : data.filter(d => d.category === selectedCategory)

// Tracé interactif avec la librairie Plotly
Plotly.newPlot('dynamic-chart', [{
  x: filteredData.map(d => d.timestamp),
  y: filteredData.map(d => d.value),
  type: 'scatter',
  mode: 'lines+markers',
  marker: {color: '#1A73E8', size: 8},
  line: {shape: 'spline', color: '#1A73E8', width: 3}
}], {
  title: 'Évolution Dynamique des Valeurs (Filtrée)',
  margin: {t: 50, b: 50, l: 50, r: 50},
  paper_bgcolor: 'rgba(0,0,0,0)',
  plot_bgcolor: 'rgba(0,0,0,0)',
  xaxis: {gridcolor: '#E5E7EB'},
  yaxis: {gridcolor: '#E5E7EB'}
})
```

<div id="dynamic-chart"
style="width:100%; height:400px; background: white; border-radius: 8px; box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);">

</div>

</div>

------------------------------------------------------------------------

# Utilisation de l’Intelligence Artificielle

Dans une démarche de transparence scientifique et académique, cette
section détaille la manière dont les outils d’Intelligence Artificielle
(IA) générative ont été intégrés tout au long de la réalisation de ce
projet.

## Cartographie de l’utilisation de l’IA

| Outil d’IA | Cas d’usage (Pourquoi ?) | Méthode d’utilisation (Comment ?) | Rôle et Validation Humaine |
|:---|:---|:---|:---|
| **\[Outil d’IA\]** | *\[À compléter par les étudiants\]* | *\[À compléter par les étudiants\]* | *\[À compléter par les étudiants\]* |

## Principes de Rigueur et Responsabilité

1.  **Responsabilité intellectuelle** : L’équipe assume l’entière
    responsabilité des analyses, des choix de modèles et des conclusions
    présentées dans ce rapport.
2.  **Lutte contre les hallucinations** : Chaque suggestion technique a
    fait l’objet d’une validation empirique.
3.  **Protection des données** : Aucun jeu de données confidentiel ou
    sensible n’a été soumis à des modèles tiers en ligne.

------------------------------------------------------------------------

# Bibliographie

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-pandas2020" class="csl-entry">

McKinney, Wes. 2020. *Python for Data Analysis: Data Wrangling with
Pandas, NumPy, and IPython*. O’Reilly Media.

</div>

</div>
