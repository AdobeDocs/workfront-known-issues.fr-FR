---
title: '« Workfront Fusion : formatage des sorties pour les dates »'
description: « Lorsque les dates sont générées sous forme de chaînes, le format peut être UTC ou ISO. Cela dépend de la logique dans un panneau de mappage. »
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: ht
source-wordcount: '120'
ht-degree: 100%

---


# Workfront Fusion : formatage des sorties pour les dates

Lorsque les dates sont générées sous forme de chaînes, le format peut être UTC ou ISO. Cela dépend de la logique dans un panneau de mappage :

* si une date d’une fonction est associée à une chaîne, la chaîne est générée au format **UTC** ;
* si la date n’est pas associée à une fonction, elle est générée en tant que **chaîne ISO**.

Les clientes et clients doivent utiliser les fonctions `toString` (pour ISO) ou `formatDate` pour s’assurer que les sorties sont dans le format correct.
