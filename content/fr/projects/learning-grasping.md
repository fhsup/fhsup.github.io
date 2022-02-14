+++
author = "François Hélénon"
title = "Learning grasping from authorised and prohibited demonstrations"
date = "2019-03-102022-01-24"
description = "Learning grasping from authorised and prohibited demonstrations"
tags = [
]
+++

*Work jointly done with Laurent Bimont, Stéphane Thiery, Éric Nyiri and Olivier Gibaru*

This work led to a publication as a [conference article](https://doi.org/10/gk8djs) at RO-MAN 2020.


Our motivation is to ease robots’ reconfiguration for pick and place tasks in an industrial context. We propose a fast learner neural network model trained from one or a few demonstrations in less than 5 minutes, able to efficiently predict grasping locations on a specific object.

The proposed methodology is easy to apply in an industrial context as it is exclusively based on the operator’s demonstrations and does not require a CAD model, existing database or simulator. As predictions of a neural network can be erroneous especially when trained with very few data, we propose to indicate both authorised and prohibited locations for safety reasons. It allows us to handle fragile objects or to perform task-oriented grasping.

Our model learns the semantic representation of objects (prohibited/authorised) thanks to a simplified data representation, a simplified neural network architecture and an adequate training framework. 

We trained specific networks for different objects and conducted experiments on a real 7-DOF robot which showed good performances (70 to 100% depending on the object), using only one demonstration. The proposed model is able to generalise well as performances remain good even when grasping several similar objects with the same network trained on one of them.

{{< youtube  1UjehV1RCLc>}}

