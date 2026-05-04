---
title: 'Feuilles de temps : la feuille de temps épinglée dirige vers une page vierge.'
description: Lorsqu’une personne clique sur une épingle de Workfront destinée à atteindre sa feuille de temps, l’épingle conduit à une page vierge. Une solution de contournement est disponible.
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
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
