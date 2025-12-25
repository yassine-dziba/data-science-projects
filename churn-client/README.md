# Prédiction du churn client

## 🎯 Objectif du projet
L’objectif de ce projet est de prédire le churn client (résiliation)
dans un service par abonnement à partir de données
comportementales, contractuelles et financières.

Ce projet adopte une démarche complète de data science,
allant de l’analyse exploratoire à l’interprétation des modèles,
dans un contexte proche de problématiques industrielles réelles.

---

## 📊 Jeu de données
- **Source** : Telco Customer Churn (Kaggle)
- **Description** : Données clients incluant :
  - informations contractuelles
  - services souscrits
  - ancienneté
  - charges mensuelles et totales
- Le jeu de données n’est pas inclus dans ce dépôt.

---

## 🗂️ Structure du projet


### Description des notebooks
- **01_exploration.ipynb**
  - Analyse exploratoire des données
  - Étude de la variable cible
  - Analyses univariées et bivariées

- **02_preparation_donnees.ipynb**
  - Nettoyage des données
  - Encodage des variables catégorielles
  - Séparation train / test
  - Modèle de référence (régression logistique)
  - Interprétation des coefficients

- **03_modelisation.ipynb**
  - Pipelines de modélisation
  - Random Forest
  - Gradient Boosting
  - XGBoost
  - Comparaison des modèles (ROC-AUC)
  - Feature importance
  - Interprétation avec SHAP

---

## 🧠 Méthodologie
- Analyse exploratoire et compréhension métier
- Préparation et transformation des données
- Modélisation avec plusieurs approches
- Comparaison des performances
- Interprétation globale et locale des modèles

Une attention particulière est portée à la reproductibilité,
à l’absence de fuite de données et à l’explicabilité des résultats.

---

## 📈 Résultats principaux
- Les modèles de boosting (Gradient Boosting, XGBoost)
  offrent les meilleures performances globales.
- Les variables liées au type de contrat, à l’ancienneté
  et aux charges mensuelles sont déterminantes dans le churn.
- L’utilisation de SHAP permet une interprétation fine
  des prédictions au niveau individuel.

---

## 🛠️ Outils et technologies
- Python
- pandas, numpy
- scikit-learn
- XGBoost
- SHAP
- matplotlib / seaborn

---

## 🚀 Perspectives d’amélioration
- Optimisation des hyperparamètres
- Validation croisée
- Seuils de décision orientés métier
- Déploiement du modèle sous forme d’API

---

## 👤 Auteur
Projet réalisé dans le cadre d’un parcours **Master 2 Data Science**.
