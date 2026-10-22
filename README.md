# Projet : Prédiction des prix immobiliers (California Housing)

## 1. Problème métier

L'agence immobilière souhaite automatiser l'estimation des prix des logements afin de gagner du temps, d'améliorer la précision des estimations et de réduire les erreurs humaines.

## 2. Pourquoi le Machine Learning ?

Une règle de calcul simple ne permet pas toujours d'estimer correctement le prix d'un logement. Un modèle de régression en Machine Learning peut apprendre les relations entre plusieurs caractéristiques, notamment le revenu médian du quartier, la localisation, le nombre de pièces et la population.

Le projet utilisera le jeu de données California Housing pour entraîner et évaluer un modèle de prédiction des prix immobiliers.

## 3. KPI (indicateur de succès)

L'indicateur principal est la MAE (Mean Absolute Error), ou erreur absolue moyenne.

**Objectif : obtenir une MAE inférieure à 0,40** sur une échelle de prix exprimée en centaines de milliers de dollars.

Cela correspond à une erreur absolue moyenne inférieure à 40 000 dollars.

Le modèle sera évalué sur un jeu de test distinct des données utilisées pour son entraînement.