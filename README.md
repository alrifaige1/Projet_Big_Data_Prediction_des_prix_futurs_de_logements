# 🌟 Projet Big Data: Prédiction des prix futurs de location avec Apprentissage Automatique 🏠

## Description du Projet
Ce projet de science des données vise à prédire les prix de location de logements en France en utilisant des techniques d'apprentissage automatique avancées. En combinant des modèles tels que XGBoost, Lasso, ElasticNet et d'autres techniques d'arbres décisionnels, nous cherchons à offrir des prédictions précises et efficaces sur les prix de location.

## 🔍 Objectif 
L'objectif principal est de prédire avec précision les prix de location des appartements et maisons en France à partir de données extraites par web scraping et enrichies par des informations géospatiales (distances aux stations de métro, Points d'Intérêt, etc.).

## 🚀 Pourquoi ce projet est important ???

Ce projet montre l'importance de l'ingénierie des fonctionnalités et du choix des bons modèles pour prédire avec précision les prix immobiliers, en particulier pour la location. Il met en lumière les avantages des modèles d'apprentissage automatique dans l'immobilier, en offrant des prédictions plus fiables et en contribuant à des décisions stratégiques dans le secteur.

### ⚙️ Méthodologie

#### Prétraitement des données :

Extraction de données à partir de 10 029 annonces.
Nettoyage et normalisation avec l'échelonnage maximal absolu pour gérer des colonnes à densité variable.

#### Modélisation :

Test de plusieurs modèles de régression (Lasso, ElasticNet, KNeighbors, Decision Tree, etc.).
XGBoost s'est révélé être le meilleur modèle après optimisation des hyperparamètres via la recherche bayésienne.

#### Évaluation :

Utilisation de métriques telles que le R², l'erreur quadratique moyenne (MSE) et l'erreur absolue moyenne (MAE) pour évaluer la performance des modèles.

### 📈 Résultats :

XGBoost a largement surpassé tous les autres modèles avec une performance exceptionnelle. L'ajout de variables géospatiales (comme les distances aux stations de métro) a amélioré significativement la précision des prédictions.

### 🛠️ Technologies Utilisées

- ****Langage**** : Python 🐍
- ****Bibliothèques**** :
    -  ****pandas**** 📊
    -  ****NumPy**** 🔢
    -  ****XGBoost**** 🌳
    -  ****scikit-learn**** 🔧
    -  ****Optuna**** 🔍
- ****Plateforme**** : vast.ai 💻 (GPU Nvidia RTX 2080 Ti, 16 Go de RAM)


