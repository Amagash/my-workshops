---
title: Data Science in the Cloud
---

--sep--
---
title: Introduction
---

# Microsoft Dev Roadshow - Data Science in the Cloud

## Introduction

Dans ce workshop, nous allons apprendre comment entraîner, déployer et consommer un modèle de machine learning sur Azure en low-code/no-code. Nous utiliserons un dataset en open source sur Kaggle afin de créer un modèle de machine learning d'aide au diagnostique de patients suceptibles de faire une crise cardiaque. Afin de mener à bien ce projet, nous allons suivre l'architecture suivante:

![schema](media/schema.png)

## Pré-requis

Afin de réaliser ce workshop, vous aurez besoin: 

- D'un ordinateur avec un navigateur internet
- D'un [compte Azure](https://ms.portal.azure.com/). Si vous n'en avez pas, suivez les étapes dans la partie suivante.
- Et c'est tout !

## Créer un compte Azure

Si vous êtes étudiants, vous devriez avoir accès à des crédits Azure gratuitement. Pour réclamer vos crédits suivez les étapes suivantes:

1. Allez sur le [portail Azure](https://ms.portal.azure.com/) et connectez-vous avec votre adresse mail de votre école. 
2. Une fois sur le portail, écrivez "Education" dans la barre de recherche et allez dans la section Education. 
3. Cliquez sur l'encadré en bleu "Claim you Azure credit now".

![schema](media/credit.png)

4. Vous devriez être redirigé vers une nouvelle page. Cliquez sur le bouton "Start free".

![schema](media/start.png)

5. A l'issue du formulaire à remplir, un code vous sera envoyé par SMS afin d'activer vos crédits.
6. Retournez sur le portail Azure et écrivez "Subscriptions" ou "Abonnements" si vous êtes en français.
7. Dans la liste de vos abonnements, vous devriez voir votre souscription étudiante (Décocher la case "Show only subscriptions selected in the global subscriptions filter").
8. Vous êtes prêt.e pour la suite du workshop!

--sep--
---
title: Objectifs du workshop
---

## Objectifs du workshop

Ce workshop, accessible à **tous les développeurs même sans connaissance en programmation**, vous permettra de découvrir les outils sur Azure qui vous permettrons de faire un projet de machine learning de bout en bout. 

1. Créer un Azure ML workspace
2. Choisir les bonnes ressources de calculs
3. Charger un dataset
4. Entraîner un modèle de machine learning avec AutoML
5. Déployer le modèle sur Azure
6. Consommer le modèle

--sep--
---
title: Dataset
---

## Trouver un dataset

Kaggle est un site où il est possible de faire des projets de Data Science/Machine Learning. On peut y trouver de nombreux datasets en open source. Dans ce workshop, nous allons travailler avec le [Heart Failure dataset](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data). Dans le Kaggle, il est possible de télécharger le dataset en cliquant sur le bouton "Download Dataset".

1. Téléchargez le dataset.
2. Explorez l'excel et regardez la description des données sur Kaggle afin de bien comprendre le dataset.


