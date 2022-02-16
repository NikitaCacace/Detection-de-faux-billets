# Detection-de-faux-billets

*Projet effectué dans le cadre de ma formation chez OpenClassrooms* 

* Réaliser une analyse prédictive : Création d'un algorithme de détection des faux billets grâce à leurs dimensions. 
* Mise en place de modèle de régression linéaire.
* Opérer des classifications automatiques pour partitionner les données : régression logistique et prédiction par K-means. 
* Analyses uni et bi variées basique des données. 
* Visualisation des données.

  L’Organisation nationale de lutte contre le faux-monnayage (ONCFM) veux identifier les contrefaçons de billets en mettant en place une modélisation capable d’identifier automatiquement les vrais des faux billets seulement à partir de certaines dimensions du billet ou des éléments qui le composent. On souhaite voir quels sont les traitements et analyses que vous avez réalisés en amont, les différentes pistes explorées pour la construction de l’algorithme, ainsi que le modèle final retenu.

__Améliorations prévues sur ce projet__ : ajout d'une ACP, K-NN, détection des individus atypiques influents de la régression logistique (avec pyOD), faire un pipeline de traitement des données, faire ce projet sous R. 

*All of my projects are in french, if you would like to see them translated please contact me on LinkedIn.*

Les données :
- billet_complet.csv = training set avec données manquantes complétées par régression linéaire
- billets.csv = training set brut
- billets_production_test.csv = testing set
- billets_test.csv = testing set d'évaluation
