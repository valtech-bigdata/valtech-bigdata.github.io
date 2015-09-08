---
layout: post
title: "Détection de spam avec le langage R"
date: 2015-07-17
author: Géraud Dugé de Bernonville
---


![R](/images/Rlogo.png)

## Programme

R est un langage de programmation et outil d'analyse statistique dont la popularité ne cesse
de croître, pour preuve la [création récente d'un consortium](http://blog.revolutionanalytics.com/2015/06/r-consortium.html) regroupant notamment Microsoft, RStudio, TIBCO, Google...
Au cours de cet atelier, nous allons travailler autour du sujet de la détection de spam
et ainsi:

* découvrir les bases du langages R
* apprendre à charger et manipuler des jeux de données
* découvrir et appliquer des algorithmes de Machine Learning pour la détection de spam
* interpréter et évaluer les modèles prédictifs

## Pré-requis

Vous devez avoir installé les outils suivants:

* R 3.2:
    * [Windows](http://cran.rstudio.com/bin/windows/base/)
    * [MacOS](http://cran.rstudio.com/bin/macosx/)
    * [Linux](http://cran.rstudio.com/bin/linux/)
* RStudio Desktop: http://www.rstudio.com/products/rstudio/download/

Les packages suivants doivent être installés (lancer Rstudio puis menu Tools -> Install packages...):

* rpart
* rpart.plot

![Installation package](/images/rstudio-package.png)

Les jeux de données doivent être téléchargés depuis les urls suivantes:

* [Données d'entraînement](https://raw.githubusercontent.com/geraudster/spamdata/master/emails_train.csv)
* [Données de test](https://raw.githubusercontent.com/geraudster/spamdata/master/emails_test.csv)


