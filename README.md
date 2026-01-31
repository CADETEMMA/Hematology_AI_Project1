# Hematology_AI_Project1

# Projet IA : Prédiction du Risque de Rechute en Hématologie

## Contexte
Ce projet vise à prédire la rechute des patients atteints de leucémie, en utilisant des données cliniques et biologiques. Ce modèle a une importance clinique pour prédire la survie des patients et ajuster les traitements.

## Démarche Méthodologique
Nous avons utilisé des modèles classiques de machine learning (régression logistique, forêt aléatoire, et XGBoost) et avons évalué leur performance avec des métriques adaptées aux enjeux cliniques (sensibilité, spécificité, AUC ROC).

## Structure du Projet
- `notebooks/03_ML_models.ipynb` : Entraînement des modèles.
- `notebooks/04_Evaluation.ipynb` : Évaluation des performances des modèles.
- `models/` : Modèles entraînés (Logistic Regression, Random Forest, XGBoost).
- `predictions/` : Prédictions réalisées par chaque modèle.

## Résultats
Les performances des modèles sont comparées, avec une attention particulière sur la sensibilité pour minimiser les faux négatifs dans un contexte clinique.

