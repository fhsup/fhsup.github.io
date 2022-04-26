+++
author = "François Hélénon"
title = "Learning synergies between grasping and pushing in an autonomous way"
date = "2019-03-102022-01-24"
description = "Learning synergies between grasping and pushing in an autonomous way"
tags = [
]
+++

*With Laurent Bimont, Stéphane Thiery, Éric Nyiri and Olivier Gibaru*.
   
  The case of bin picking is a typical example of a task for which it can be difficult to explain in a procedural way how to perform it, even for a human. It is not easy to explain why a pile of objects should be scattered in a certain way rather than another.

  Reinforcement learning is well suited to learn such a task autonomously. We therefore replicated [Zeng et al., 2018](https://vpg.cs.princeton.edu/) and extended it experimentally to our industrial setting. We approached the bin picking problems as a reinforcement learning strategy where the robotic agent learns from the synergies between push and grasp action. In addition, the use of reinforcement learning and deep learning allows the robot to learn to pick up parts without the need for a CAD model, from a simple depth sensor. This is important because collaborative robots may have to work with parts that have not been modeled by CAD specialists, such as in some cases of small scale series.

 {{<youtube T592ye7RPxQ>}}



