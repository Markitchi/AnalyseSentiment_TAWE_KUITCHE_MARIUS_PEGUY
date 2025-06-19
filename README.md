# Analyse de sentiment de critiques de films ODC 2025

Ce projet consiste à construire un modèle de machine learning pour prédire si une critique de film est positive ou négative.

## Prénom / Nom

TAWE KUITCHE MARIUS PEGUY

## Outils utilisés

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- nltk

## Ce que contient ce projet

- Chargement et exploration d'un jeu de données de critiques de films
- Nettoyage et prétraitement des textes (suppression des caractères spéciaux, stopwords, etc.)
- Vectorisation des textes avec TF-IDF
- Séparation des données en jeu d'entraînement et de test
- Entraînement d'un modèle de régression logistique pour la classification binaire
- Évaluation du modèle avec différentes métriques (accuracy, precision, recall, F1-score, matrice de confusion)
- Analyse des mots les plus discriminants pour chaque classe
- Tests sur de nouveaux exemples
- Interface interactive pour prédire le sentiment d'une critique saisie par l'utilisateur

## Choix de modèle et résultats obtenus

Le modèle choisi est une régression logistique, adaptée à la classification binaire (positive/négative). Après entraînement et test sur le jeu de données fourni, le modèle atteint une précision de 100% sur le jeu de test, avec des scores parfaits pour la précision, le rappel et le F1-score. Les mots les plus discriminants pour chaque classe ont également été identifiés.

## Suggestions d'amélioration

- Tester le modèle sur un jeu de données plus varié ou réel pour vérifier sa robustesse
- Essayer d'autres modèles de classification (SVM, Random Forest, réseaux de neurones)
- Ajouter une étape de validation croisée pour mieux évaluer la performance
- Intégrer une interface web simple pour faciliter l'utilisation par des non-techniciens
- Enrichir le prétraitement (lemmatisation, correction orthographique, gestion des emojis, etc.)

## Installation des dépendances

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

## Utilisation

1. Place le fichier `movie_reviews_dataset.csv` dans le même dossier que le notebook.
2. Ouvre le notebook `Analyse_Sentiment_Movie_Reviews.ipynb` avec Jupyter Notebook ou VSCode.
3. Exécute les cellules dans l'ordre pour :
   - Charger et explorer les données
   - Nettoyer les textes
   - Entraîner et évaluer le modèle
   - Tester l'interface interactive

## Résultat

Le modèle entraîné permet de prédire automatiquement le sentiment d'une critique de film, et affiche également les mots les plus importants pour chaque classe.
