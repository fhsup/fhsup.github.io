+++
author = "François Hélénon"
title = "Apprendre les synergies entre saisir et pousser de manière autonome "
date = "2019-03-102022-01-24"
description = "Apprendre les synergies entre saisir et pousser de manière autonome "
tags = [
]
+++

*Avec Laurent Bimont, Stéphane Thiery, Éric Nyiri et Olivier Gibaru*.
   
  Le cas du dévracage est un exemple typique de tâche pour laquelle il peut être difficile d'expliquer de manière procédurale comment la réaliser, même pour un humain. Il n'est pas facile en effet d'expliquer pourquoi un tas d'objets doit être éparpiller d'une certaine manière plutôt qu'une autre.

  L'apprentissage par renforcement convient bien pour apprendre une telle tâche de manière autonome. Nous avons donc reproduit [Zeng et al., 2018](https://vpg.cs.princeton.edu/) et l'avons étendu expérimentalement à notre contexte industriel. Nous avons abordé les problèmes de dévracage comme une stratégie d'apprentissage par renforcement où l'agent robotique apprend des synergies entre d'action entre poussée et préhension. De plus, l'utilisation de l'apprentissage par renforcement et de l'apprentissage profond permet au robot d'apprendre à ramasser des pièces sans avoir besoin d'un modèle CAO, à partir d'un simple capteur de profondeur. Ceci est important car les robots collaboratifs peuvent être amenés à travailler avec des pièces qui n'ont pas été modélisées par des spécialistes de la CAO, comme dans certains cas de petites séries.

  
  ![Pipeline d'apprentissage par apprentissage par renforcement](/images/projects/vpg/pipeline_soft.png) 

