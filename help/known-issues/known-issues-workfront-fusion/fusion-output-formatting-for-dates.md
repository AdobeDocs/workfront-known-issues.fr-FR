---
title: 'Workfront Fusion : formatage de sortie pour les dates'
description: Lorsque les dates sont générées sous forme de chaînes, le format peut être UTC ou ISO. Cela dépend de la logique d’un panneau de mappage.
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 92%

---

# Workfront Fusion : formatage de sortie pour les dates

Lorsque les dates sont générées sous forme de chaînes, le format peut être UTC ou ISO. Cela dépend de la logique dans un panneau de mappage :

* si une date d’une fonction est associée à une chaîne, la chaîne est générée au format **UTC** ;
* si la date n’est pas associée à une fonction, elle est générée en tant que **chaîne ISO**.

Les clientes et clients doivent utiliser les fonctions `toString` (pour ISO) ou `formatDate` pour s’assurer que les sorties sont dans le format correct.
