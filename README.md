<<<<<<< HEAD

=======
# 📊 Morocco Growth–Jobs Econometric Lab

[🇫🇷 Version Française](#-version-française) | [🇬🇧 English Version](#-english-version)

---

# 🇬🇧 English Version

## 🎯 Objective

This project investigates the feasibility of the World Bank's target of creating **1.7 million jobs by 2035 in Morocco**.

We estimate **sectoral employment elasticities** to understand how economic growth translates into job creation.

---

## 📌 Key Question

> Which sectors in Morocco actually create jobs?

---

## 🧠 Methodology

- Data sources:
  - High Commission for Planning (HCP)
  - World Bank (WDI)
- Period: 2015–2025
- Method:
  - Log-log econometric model
  - First-difference regression:
  
  \[
  \Delta \ln L = \alpha + \beta \Delta \ln Y
  \]

---

## 📊 Main Findings

- Employment elasticities are **low and statistically insignificant across all sectors**
- Industry shows **negative elasticity (labor shedding)**
- Services, despite growth, show **weak job creation**

👉 This suggests **“job-poor growth” dynamics**

---

## ⚠️ Limitations

- Small sample size (n = 10)
- No capital variable
- Sectoral employment approximated from shares

---

## 🚀 Next Steps

- Structural decomposition (shift-share analysis)
- Gender employment analysis
- Capital and productivity integration

---

## 📂 Repository Structure
data/
notebooks/


---

# 🇫🇷 Version Française

## 🎯 Objectif

Ce projet analyse la faisabilité de l'objectif de la Banque mondiale de créer **1,7 million d’emplois d’ici 2035 au Maroc**.

Nous estimons les **élasticités emploi-croissance par secteur**.

---

## 📌 Question principale

> Quels secteurs créent réellement de l’emploi au Maroc ?

---

## 🧠 Méthodologie

- Sources :
  - HCP
  - Banque mondiale
- Période : 2015–2025
- Modèle :
  
  \[
  \Delta \ln L = \alpha + \beta \Delta \ln Y
  \]

---

## 📊 Résultats principaux

- Élasticités faibles et non significatives
- Industrie : destruction nette d’emplois
- Services : création d’emplois limitée

👉 Indication d’une **croissance peu génératrice d’emplois**

---

## ⚠️ Limites

- Taille d’échantillon réduite
- Absence du capital
- Approximation des données sectorielles

---

## 🚀 Perspectives

- Analyse shift-share
- Focus emploi féminin
- Modélisation avec capital

---

## 👤 Author

Oussama ATTAHIR  
PhD in Applied Economics
>>>>>>> dcbc5bc (Complete econometric analysis of employment elasticity for Morocco 2026 study)
