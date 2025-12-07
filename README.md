# 🏠 Home Loan Approval ML

Prédiction de l'éligibilité à un crédit immobilier à l’aide de techniques de Machine Learning.

Ce projet a été réalisé dans le cadre d’une démarche de formation visant à analyser, 
concevoir et développer un modèle prédictif permettant d’estimer si une demande de crédit immobilier peut être approuvée selon divers critères personnels,
financiers et professionnels.

---

## 📌 Objectifs du projet
- Analyser un dataset de demandes de prêts immobiliers.
- Identifier les variables influençant l’approbation d’un crédit.
- Construire un pipeline Machine Learning complet (préprocessing + modèle).
- Évaluer les performances du modèle selon des métriques pertinentes.
- Améliorer la capacité du modèle à reconnaître les demandes refusées.
- Produire un livrable structuré en accord avec les bonnes pratiques de la formation.

---

## 📂 Dataset
📦 **Source** : Kaggle — *Home Loan Approval Prediction*

https://www.kaggle.com/datasets/rishikeshkonapure/home-loan-approval?select=loan_sanction_test.csv

Le dataset contient des informations financières, personnelles et professionnelles telles que :
- Revenu
- Historique de crédit
- Score personnel
- Informations sur la propriété
- Informations sur le co-emprunteur
- Statut d’approbation du prêt

Ce jeu de données comporte un déséquilibre important entre les demandes approuvées et refusées,
ce qui nécessite des techniques spécifiques pour équilibrer l’apprentissage du modèle.

### 📂 Description

| gender             | genre                   |
|--------------------|-------------------------|
| married            | marié                   |
| dependents         | personnes à charge      |
| education          | éducation               |
| self employed      | travailleur indépendant |
| applicant income   | revenu du demandeur     |
| coapplicant income | revenu du codemandeur   |
| loan amount        | montant du prêt         |
| loan amount term   | durée du prêt           |
| credit history     | historique de crédit    |
| property area      | zone de propriété       |
| loan status        | statut du prêt          |

---

## 📈 Résultats
Les résultats finaux incluent :
- Performances du modèle avant et après rééquilibrage
- Interprétation des données du dataset
- Visualisations (matrice de confusion, courbes ROC, distributions)

---

## 🧩 Architecture du projet

```
home-loan-approval-ml/
  │
  ├── data/ # CSV 
  ├── notebooks/ # Jupyter Notebooks d'analyse
  ├── models/ # Modèles entraînés
  └── README.md
```

## 🛠 Technologies utilisées

* Python 3.11.x
* joblib
* pandas
* seaborn
* matplotlib.pyplot
* numpy
* scikit-learn
* Jupyter Notebook

## 🧑‍💼 Projet

Projet réalisé dans le cadre d’une certification RNCP (Bloc 3 — Réalisation d’un projet Data / ML).

