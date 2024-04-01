---
title: "Rapports : le filtre de rapport ne renvoie pas les résultats attendus"
description: '"Un filtre dans un rapport peut ne pas renvoyer tous les résultats attendus. Une solution de contournement est disponible. »'
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: ed1fbb6e6c13ad41430e7351e0c9a28cefd46d12
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 14%

---


# Rapports : le filtre de rapport ne renvoie pas les résultats attendus

>[!NOTE]
>
>Ce problème a été résolu.

Un filtre dans un rapport peut ne pas renvoyer tous les résultats attendus.

Cela peut se produire lorsque le filtre est configuré pour renvoyer des résultats avec certains critères et inclut une règle OU qui renvoie des résultats qui sont un sous-ensemble de ces mêmes critères.

**Solution de contournement**

Assurez-vous que les blocs OU de votre filtre n’incluent pas de critères d’évaluation identiques.

_Premier signalement le mardi 11 mars 2024._

