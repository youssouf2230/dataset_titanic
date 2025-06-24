# dataset_titanic
La classification pour voir si un passager a survécu dans le crash titanic ou pas?

### Prédiction de survie des passagers du Titanic avec Random Forest
    Ce projet explore le jeu de données Titanic (via Seaborn) à travers un pipeline complet de machine learning. L'objectif est de prédire la survie des passagers à partir de leurs caractéristiques personnelles et de voyage.

### Technologies utilisées
    Python
    
    pandas, seaborn, numpy, matplotlib
    
    scikit-learn (RandomForestClassifier, LabelEncoder, learning_curve)

###  Étapes du projet
    Chargement et nettoyage des données
    
    Suppression des lignes incomplètes
    
    Sélection de variables pertinentes (pclass, sex, age, etc.)
    
    Encodage des variables catégorielles
    
    Utilisation de LabelEncoder avec gestion robuste de nouveaux exemples
    
    Séparation des données

    Train/test split avec validation croisée (train_test_split)
    
    Entraînement d’un modèle Random Forest
    
    Visualisation de l’importance des variables
    
    Analyse de la performance : matrice de confusion + classification report
    
    Prédiction d’un passager fictif
