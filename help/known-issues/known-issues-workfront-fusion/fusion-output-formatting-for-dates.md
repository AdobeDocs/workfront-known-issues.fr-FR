---
title: 'Workfront Fusion : formatage de sortie pour les dates'
description: Lorsque les dates sont générées sous forme de chaînes, le format peut être UTC ou ISO. Cela dépend de la logique d’un panneau de mappage.
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 92%
---
# Workfront Fusion : formatage de sortie pour les dates

Lorsque les dates sont générées sous forme de chaînes, le format peut être UTC ou ISO. Cela dépend de la logique dans un panneau de mappage :

* si une date d’une fonction est associée à une chaîne, la chaîne est générée au format **UTC** ;
* si la date n’est pas associée à une fonction, elle est générée en tant que **chaîne ISO**.

Les clientes et clients doivent utiliser les fonctions `toString` (pour ISO) ou `formatDate` pour s’assurer que les sorties sont dans le format correct.
