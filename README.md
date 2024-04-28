## Classification de l'iris avec R Shiny et randomForest sur Heroku

Ce projet utilise les bibliothèques R Shiny et "randomForest" pour créer une application web permettant de classifier les espèces d'iris en fonction de leurs caractéristiques.

### Fonctionnalités

- Affichage des caractéristiques de l'iris (longueur et largeur des sépales et des pétales).
- Classification de l'espèce d'iris (setosa, versicolor ou virginica) en utilisant l'algorithme random forest.
- Interface conviviale permettant à l'utilisateur de saisir les valeurs des caractéristiques de l'iris et d'obtenir la prédiction de l'espèce.

### Technologies utilisées

- R Shiny : Framework web R pour la création d'applications interactives.
- randomForest : Package R pour la construction de modèles de forêt aléatoire.
- Heroku : Plateforme de déploiement d'applications cloud.

### Déploiement

L'application est déployée sur Heroku et est accessible à l'adresse suivante : [lien de l'application](lien_de_votre_application).

Pour exécuter localement l'application, vous pouvez cloner ce dépôt et exécuter le fichier `app.R` à l'aide de RStudio ou de la ligne de commande R :

```R
library(shiny)
runApp("app.R")


![Capture d’écran (32)](https://github.com/assielking/R-shiny/assets/145512245/dc9fedfb-82a7-48c2-b40e-9fb0948bf7c9)
