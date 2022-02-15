+++
author = "François Hélénon"
title = "Apprentissage de la préhension en montrant des zones autorisées et interdites"
date = "2019-03-102022-01-24"
description = "Apprentissage de la préhension en montrant des zones autorisées et interdites"
tags = [
]
+++

*Avec Laurent Bimont, Stéphane Thiery, Éric Nyiri et Olivier Gibaru*.

Ce travail a conduit à une publication en tant qu'[article de conférence](https://doi.org/10/gk8djs) à RO-MAN 2020.


La motivation de ce travail est de faciliter la reconfiguration des robots pour des tâches de pick and place dans un contexte industriel. Nous avons proposé un modèle basé sur un réseau de neurones, apprenant rapidement à partir d'une ou de quelques démonstrations en moins de 5 minutes, capable de prédire efficacement les emplacements de préhension sur un objet spécifique.

La méthodologie proposée est facile à appliquer dans un contexte industriel car elle est exclusivement basée sur les démonstrations de l'opérateur et ne nécessite pas de modèle CAO, de base de données existante ou de simulateur. Comme les prédictions d'un réseau de neurones peuvent être erronées surtout lorsqu'il est entraîné avec très peu de données, nous proposons d'indiquer les emplacements autorisés et interdits pour des raisons de sécurité. Cela nous permet de manipuler des objets fragiles ou d'effectuer une préhension orientée tâche.

Notre modèle apprend la représentation sémantique des objets (interdit/autorisé) grâce à une représentation simplifiée des données, une architecture de réseau de neurones simplifiée et un cadre d'apprentissage adéquat. 

Nous avons entraîné des réseaux spécifiques pour différents objets et mené des expériences sur un vrai robot industriel (7-DOF) qui a montré de bonnes performances (70 à 100% selon l'objet), en utilisant une seule démonstration. Le modèle proposé est capable de généraliser car les performances restent bonnes même en saisissant des objets similaires à celui avec lequel le réseau a été entraîné.

{{< youtube  1UjehV1RCLc>}}

