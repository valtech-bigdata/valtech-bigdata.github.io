---
layout: post
title: "Azure ML - Prédiction de pathologies cardiaques"
date: 2015-09-08
author: David Toussaint
---

![R](/images/AzureMaml.png)

## Programme

### Le Machine Learning - De quoi s’agit-il ?
Le Machine Learning utilise des ordinateurs pour exécuter des modèles prédictifs qui apprennent à partir de données existantes afin de prévoir les tendances, résultats et comportements futurs.
Ces prévisions ou prédictions générées à partir du Machine Learning peuvent rendre les applications et les appareils plus intelligents. Lorsque vous faites vos achats en ligne, l’apprentissage automatique permet de recommander d’autres produits que vous êtes susceptible d’aimer, en fonction de ce que vous avez acheté. Lorsque vous utilisez votre carte de crédit, l'algorithme de machine learning compare la transaction à une base de données de transactions et aide la banque à détecter des fraudes.  

### Qu’est-ce que Machine Learning sur Microsoft Azure ?
Azure Machine Learning est un puissant service d’analyse prédictive sur le cloud qui permet de créer et de déployer rapidement des modèles prédictifs sous forme de solutions d’analyse.  

### Qu'allons nous faire ?  
Dans ce Lab sur le Machine Learning, nous allons créer un modèle qui prédit si une personne a une pathologie cardiaque ou non selon différentes variables. Pour ce faire, nous allons utiliser Microsoft Azure Machine Learning Studio (MAML) pour développer et effectuer une itération sur une expérience d’analyse prédictive simple.

### Composition du Lab :  
* Préparation des données  
* Elaboration et évaluation d’un modèle prédictif  
* Publication d’un service exploitant ce modèle


## Pré-requis

Un navigateur web suffit.

Le jeu de données doit être téléchargé depuis l'url suivante:

* [Données d'entraînement](https://raw.githubusercontent.com/valtech-bigdata/valtech-bigdata.github.io/master/azureMamlResx/Heart Disease Data Set (original).csv)

Autres ressources utiles:
* [Query SQL] https://raw.githubusercontent.com/valtech-bigdata/valtech-bigdata.github.io/master/azureMamlResx/SqlTransformationQuery.txt  
* [Algorithm Cheat Sheet] https://raw.githubusercontent.com/valtech-bigdata/valtech-bigdata.github.io/master/azureMamlResx/machine-learning-algorithm-cheat-sheet.png