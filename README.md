# Football Match Prediction using Deep Learning

Ce projet est un modèle de machine learning développé pour prédire les résultats de matches de football en utilisant un réseau de neurones. Il comprend la collecte de données, le prétraitement, la construction du modèle et la création d'une interface graphique pour l'interaction utilisateur.

## Fonctionnalités

- **Data Scraping** : Statistiques des matches collectées via le web scraping (BeautifulSoup) depuis [FBRef](https://fbref.com).
- **Modèle de Réseau de Neurones** : Construit avec Keras, avec une couche cachée utilisant ReLU et une couche de sortie softmax pour la prédiction des résultats.
- **Gestion des Données** : Utilisation de l'oversampling pour équilibrer le jeu de données.
- **Interface Graphique** : Une GUI construite avec CustomTkinter pour une utilisation facile.

## Aperçu du Modèle

Le réseau de neurones prédit les résultats des matches en fonction des données historiques, des performances des équipes et d'autres statistiques. Les composants clés du modèle incluent :

- **Entrée** : Données historiques des matches et prédictions.
- **Architecture** : Réseau de neurones séquentiel avec 128 unités cachées.
- **Sortie** : Probabilités des résultats des matches (Victoire/Défaite/Nul) en utilisant softmax.

## Jeu de Données

Les données incluent les résultats des matches et les performances des équipes provenant de plusieurs ligues de football, issues de jeux de données publics et de web scraping.

