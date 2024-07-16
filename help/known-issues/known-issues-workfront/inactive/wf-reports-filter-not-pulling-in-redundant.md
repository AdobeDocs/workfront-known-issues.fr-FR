---
title: '« Rapports : le filtre de rapports ne renvoie pas les résultats attendus. »'
description: Un filtre dans un rapport peut ne pas renvoyer tous les résultats attendus. Une solution de contournement est disponible.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
source-git-commit: 9457b520c469c729f8727b1efd21bbde117b9546
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 100%

---

# Rapports : le filtre de rapports ne renvoie pas les résultats attendus.

>[!NOTE]
>
>Ce problème a été résolu.

Un filtre dans un rapport peut ne pas renvoyer tous les résultats attendus.

Cela peut se produire lorsque le filtre est configuré pour renvoyer des résultats avec certains critères et inclut une règle OU qui renvoie des résultats qui sont un sous-ensemble de ces mêmes critères.

**Solution de contournement**

Assurez-vous que les blocs OU de votre filtre n’incluent pas de critères d’évaluation identiques.

_Premier signalement le mardi 11 mars 2024._
