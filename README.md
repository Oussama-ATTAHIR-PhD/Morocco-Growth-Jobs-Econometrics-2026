# 📊 Morocco Growth–Jobs Econometric Lab

<p align="center">
  <a href="#-english-version">
    <img src="https://img.shields.io/badge/Read-English-red?style=for-the-badge">
  </a>
  <a href="#-version-française">
    <img src="https://img.shields.io/badge/Lire-Français-green?style=for-the-badge">
  </a>
</p>

---

# 🇬🇧 English Version

## Overview

This repository contains an independent econometric research program focused on the relationship between economic growth, structural transformation, and employment creation in Morocco.

The project was initiated following the publication of the World Bank report:

> *Scaling the Atlas: Growth and Jobs for a Prosperous Morocco* (April 2026)

The objective is to evaluate whether Morocco can realistically achieve the target of creating **1.7 million jobs by 2035**.

---

# Research Series

## Week 1 — Employment Elasticity Analysis

### Research Question

Does economic growth in Morocco effectively translate into job creation?

### Methodology

- Log-log econometric modeling
- Augmented Dickey-Fuller (ADF) stationarity tests
- First-difference regressions

Main equation:

\[
\Delta \ln L = \alpha + \beta \Delta \ln Y
\]

### Main Findings

- Weak employment elasticities across sectors
- Negative elasticity in industry
- Evidence of “job-poor growth”

### Key Insight

Morocco’s economic growth remains insufficiently connected to labor absorption dynamics.

---

## Week 2 — Structural Transformation & Shift-Share Analysis

### Research Question

Which sectors are truly absorbing labor in Morocco’s economic transformation?

### Methodology

- Shift-share decomposition
- Sector employment growth analysis
- Structural employment share analysis
- Sectoral comparative dynamics

### Main Findings

- Agriculture is structurally losing labor share
- Industry gains remain moderate
- Services are the main labor absorption engine

### Key Insight

Morocco is undergoing a gradual structural transformation:
- labor is moving away from agriculture,
- toward services,
- while industrial labor absorption remains limited.

---

# Data Sources

## Moroccan Institutions

- High Commission for Planning (HCP)
- National Accounts
- Employment Surveys

## International Sources

- World Bank WDI
- ILO
- UN Women

---

# Repository Structure

```text
data/
├── raw/
├── processed/

notebooks/
├── 01_data_processing.ipynb
├── 02_employment_elasticity_model.ipynb
├── 03_shift_share_analysis.ipynb

outputs/
├── tables/
├── figures/
```

---

# Technical Stack

- Python
- Pandas
- NumPy
- Statsmodels
- Matplotlib
- Seaborn

---

# Reproducibility

The repository follows reproducible research standards:

- transparent data cleaning,
- documented econometric workflow,
- exportable outputs,
- reproducible tables and visualizations.

---

# Future Research Directions

Female Labor Force Participation Shock Simulation

---

# Author

**Oussama ATTAHIR**  
PhD in Applied Economics

LinkedIn:  
www.linkedin.com/in/oussama-attahir-9a7795194

---

<br><br>

# 🇫🇷 Version Française

## Présentation

Ce repository contient un programme de recherche économétrique indépendant consacré aux relations entre croissance économique, transformation structurelle et création d’emplois au Maroc.

Le projet a été initié suite à la publication du rapport de la Banque mondiale :

> *Scaling the Atlas: Growth and Jobs for a Prosperous Morocco* (Avril 2026)

L’objectif est d’évaluer si le Maroc peut réellement atteindre la cible de **1,7 million d’emplois créés d’ici 2035**.

---

# Série de Recherche

## Semaine 1 — Analyse des Élasticités Emploi-Croissance

### Question de recherche

La croissance économique marocaine se traduit-elle réellement par des créations d’emplois ?

### Méthodologie

- Modélisation économétrique log-log
- Tests de stationnarité ADF
- Régressions en différences premières

Équation principale :

\[
\Delta \ln L = \alpha + \beta \Delta \ln Y
\]

### Principaux Résultats

- Élasticités emploi-croissance faibles
- Élasticité négative dans l’industrie
- Mise en évidence d’une croissance peu génératrice d’emplois

### Insight Principal

La croissance économique marocaine reste insuffisamment connectée à la dynamique de création d’emplois.

---

## Semaine 2 — Analyse Shift-Share et Transformation Structurelle

### Question de recherche

Quels secteurs absorbent réellement la main-d’œuvre dans la transformation économique du Maroc ?

### Méthodologie

- Décomposition shift-share
- Analyse sectorielle de la croissance de l’emploi
- Analyse des parts sectorielles de l’emploi
- Comparaison des dynamiques sectorielles

### Principaux Résultats

- L’agriculture perd structurellement de l’emploi
- L’industrie progresse faiblement
- Les services constituent le principal moteur d’absorption de la main-d’œuvre

### Insight Principal

Le Maroc connaît une transformation structurelle progressive :
- transfert du travail hors de l’agriculture,
- montée du secteur tertiaire,
- absorption industrielle encore limitée.

---

# Sources de Données

## Institutions Marocaines

- Haut-Commissariat au Plan (HCP)
- Comptes Nationaux
- Enquêtes Emploi

## Sources Internationales

- Banque mondiale
- ILO
- UN Women

---

# Structure du Repository

```text
data/
├── raw/
├── processed/

notebooks/
├── 01_data_processing.ipynb
├── 02_employment_elasticity_model.ipynb
├── 03_shift_share_analysis.ipynb

outputs/
├── tables/
├── figures/
```

---

# Stack Technique

- Python
- Pandas
- NumPy
- Statsmodels
- Matplotlib
- Seaborn

---

# Reproductibilité

Le projet suit les standards de la recherche reproductible :

- nettoyage transparent des données,
- workflow documenté,
- résultats exportables,
- visualisations reproductibles.

---

# Perspectives de Recherche

Participation féminine au marché du travail Shock Simulation

---

# Auteur

**Oussama ATTAHIR**  
Docteur en Économie Appliquée

LinkedIn :  
www.linkedin.com/in/oussama-attahir-9a7795194