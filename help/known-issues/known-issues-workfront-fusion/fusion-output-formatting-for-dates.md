---
title: "Workfront Fusion : Formatage des valeurs de sortie pour les dates"
description: "Lorsque les dates sont générées sous forme de chaînes, la date peut être générée sous la forme d’une chaîne UTC ou ISO. Cela dépend de la logique dans un panneau de mappage."
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# Fusion Workfront : formatage des valeurs de sortie pour les dates

Lorsque les dates sont générées sous la forme de chaînes, la date peut être générée sous la forme d’une chaîne UTC ou ISO. Cela dépend de la logique dans un panneau de mappage :

* Si une date d’une fonction est associée à une chaîne, la chaîne est générée dans la variable **UTC** format.
* Si la date n’est pas associée à une fonction, elle est générée en tant que **Chaîne ISO**.

Les clients doivent utiliser la variable `toString` (pour ISO) ou `formatDate` pour s’assurer que les sorties sont dans le format dont elles ont besoin.
