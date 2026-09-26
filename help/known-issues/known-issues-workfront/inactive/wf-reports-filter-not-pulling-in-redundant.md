---
title: 'Rapports : le filtre de rapports ne renvoie pas les résultats attendus.'
description: Un filtre dans un rapport peut ne pas renvoyer tous les résultats attendus. Une solution de contournement est disponible.
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c6dd2ac5-f5bd-4e59-9101-25b156918623
    internal-label: Reports and dashboards
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '100'
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
