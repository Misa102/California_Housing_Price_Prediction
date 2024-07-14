# Projet Machine Learning : Prix Immobiliers en Californie

## 1. Introduction

Ce projet utilise le jeu de données "California Housing Prices" provenant de l'entrepôt de données StatLib. Ces données, issues du recensement californien de 1990, contiennent diverses informations pertinentes pour prédire les prix immobiliers.

## 2. Vision d'ensemble

L'objectif est de construire un modèle capable de prédire les prix immobiliers en Californie en se basant sur des variables telles que la population, le revenu médian et le prix médian des habitations de chaque bloc recensé. Ces blocs sont les plus petites subdivisions pour lesquelles les données du recensement sont publiées, regroupant généralement entre 600 et 3000 personnes. 

Le modèle sera entraîné à partir de ces données pour effectuer des prédictions de régression univariée (prédiction d'une seule valeur par district) et de régression multiple (utilisation de plusieurs variables pour effectuer une prédiction).

## 3. Récupérer les données

### 3.1 Télécharger les données

Les données sont téléchargées depuis un dépôt en ligne et extraites dans le répertoire de travail. Ce processus garantit que les données sont disponibles localement pour les étapes suivantes du projet.

### 3.2 Examiner la structure des données

L'examen initial des données permet de comprendre leur structure, les types de variables, et de vérifier les données manquantes. Les statistiques descriptives et les premières visualisations aident à avoir une vision claire des données.

### 3.3 Créer un jeu de test

Un jeu de test est créé pour évaluer la performance du modèle. Un échantillonnage stratifié basé sur les tranches de revenu médian est utilisé pour garantir la représentativité des données dans le jeu de test. Cette méthode est comparée à un échantillonnage aléatoire pour vérifier les biais potentiels.

## 4. Explorer et Visualiser les données

### 4.1 Visualisation des données géographiques

Les données géographiques (latitude et longitude) sont visualisées pour identifier les zones de forte densité et les tendances des prix immobiliers en fonction de la localisation et de la densité de population. Ces visualisations montrent clairement que les prix sont influencés par la proximité de l'océan et la densité de population.

## 5. Préparer les données pour les algorithmes de Machine Learning

Les données doivent être préparées avant d'être utilisées pour entraîner les modèles. Cette préparation inclut le nettoyage des données manquantes, la transformation des catégories de données, et la normalisation des caractéristiques numériques.

## 6. Sélectionner et Entraîner un modèle

Différents modèles de régression sont testés pour sélectionner le plus performant. Les modèles incluent la régression linéaire, les arbres de décision, et les forêts aléatoires. Chacun de ces modèles est évalué pour déterminer celui qui offre les meilleures prédictions.

## 7. Régler avec précision

Pour affiner les modèles, des techniques de validation croisée et de recherche d'hyperparamètres sont utilisées. Ces techniques permettent d'optimiser les modèles et d'améliorer leur performance prédictive.

---

Ce projet vise à fournir une prédiction précise des prix immobiliers en Californie en utilisant des données de recensement et des algorithmes de Machine Learning. Les étapes décrites ci-dessus assurent une approche méthodique pour atteindre cet objectif.
