# Diagnostic médical prédictif par Gradient Boosting

Projet intermédiaire de Machine Learning basé sur l'algorithme Gradient Boosting pour de la classification binaire.

## Fonctionnement
À partir du dataset sur le cancer du sein, le modèle apprend à classer des échantillons cellulaires en deux catégories distinctes : tumeurs malignes ou bénignes.

## Paramètres du modèle
Ce projet met en avant l'utilisation d'hyperparamètres clés pour ajuster l'apprentissage :
- `n_estimators` : Le nombre d'arbres construits successivement.
- `learning_rate` : La vitesse d'apprentissage du modèle.
- `max_depth` : La profondeur maximale de chaque arbre de décision.
- `subsample` : La proportion de données allouées à chaque arbre pour limiter le surapprentissage.

## Visualisation
Le code produit un graphique d'importance des variables (*Feature Importances*), permettant de voir quels critères médicaux ont eu le plus de poids dans la décision du modèle.

## Bibliothèques utilisées
- Python
- Scikit-Learn
- NumPy / Matplotlib
