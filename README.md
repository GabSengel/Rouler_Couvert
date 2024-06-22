# Projet d'Étude : Rouler Couvert

## Objectif du Projet

L'objectif de ce projet est de sélectionner le meilleur modèle prédictif pour estimer l'intérêt des clients d'une assurance santé pour un nouveau contrat auto. Nous disposons d'une base de données comprenant des informations sur plus de 300 000 clients, incluant notamment :

- Âge
- Sexe
- Possession d'un permis de conduire
- Statut d'assurance actuelle
- Historique de sinistres
- etc
  
La dernière variable représente l'intérêt potentiel d'un client pour un contrat d'assurance auto (1 si intéressé, 0 sinon). Le but est d'entraîner nos modèles prédictifs avec une partie des données et de les tester sur l'autre afin de sélectionner le modèle le plus performant.

## Contenu du Dépôt

- index.html : Le fichier HTML du rendu fait avec Quarto, disponible au lien : [insérer lien].
- rouler_couvert_qmd_slides.qmd : Le code Quarto pour les slides.
- Rouler_Couvert.pdf : Le rendu PDF du projet.
- rouler_couvert_rmd-PDF.Rmd : Le code RMarkdown utilisé pour générer le PDF.

## Méthodologie

1. Préparation des Données :
    -    Chargement et nettoyage des données.
    -    Exploration et analyse descriptive des variables.

2. Entraînement des Modèles :
    -    Séparation des données en ensembles d'entraînement et de test.
    -    Entraînement de plusieurs modèles prédictifs (LDA, QDA, Logit, KNN, Decision Tree,    Random Forest, Boosting).

3. Évaluation des Modèles :
    -    Utilisation de métriques de performance (Accuracy, Sensibilité, Précision, etc.) pour évaluer les modèles.
Sélection du modèle le plus performant.

## Résultats
Le projet a permis d'identifier le modèle prédictif le plus adapté pour estimer l'intérêt des clients pour un nouveau contrat d'assurance auto, basé sur les critères de performance définis.

## Contributeurs
Paul Vidal & Gabin Sengel
