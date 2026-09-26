---
title: 'Feuilles de temps : la feuille de temps épinglée dirige vers une page vierge.'
description: Lorsqu’une personne clique sur une épingle de Workfront destinée à atteindre sa feuille de temps, l’épingle conduit à une page vierge. Une solution de contournement est disponible.
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: ce22a157-dd2c-405f-b740-c2f204bb4c1a
    internal-label: Timesheets
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '126'
ht-degree: 100%
---
# Feuilles de temps : la feuille de temps épinglée dirige vers une page vierge.

<!--article live for workaround-->

Lorsqu’une personne clique sur une épingle de Workfront destinée à atteindre sa feuille de temps, l’épingle conduit à une page vierge.

Cela se produit parce que l’URL de la feuille de temps a changé. L’élément `/own` à la fin de l’URL n’est plus l’URL correcte. Si la personne a épinglé une URL qui inclut `/own`, cette épingle conduit à une page vierge.

**Solution de contournement**

1. Retirez l’épingle de la feuille de temps.
1. Supprimez `/own` de la fin de l’URL.
1. Épinglez à nouveau la feuille de temps.

_Premier signalement le mercredi 7 mai 2024._
