---
title: '« Workfront Fusion : RuntimeError avec réponse 200 du module Workfront »'
description: Un module Workfront peut renvoyer une réponse « RuntimeError [200] ». La réponse 200 implique une réponse réussie, mais l’erreur indique que la requête a échoué.
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: d99f5b467f31d4e4a77cabe25671470beb847eed
workflow-type: ht
source-wordcount: '90'
ht-degree: 100%

---

# Workfront Fusion : RuntimeError avec réponse 200 du module Workfront

<!--

>[!NOTE]
>
>This issue was fixed on May 9, 2024.

-->

Un module Workfront peut renvoyer une réponse `RuntimeError [200]`. La réponse 200 implique une réponse réussie, mais l’erreur indique que la requête a échoué.

Cela peut se produire si la réponse est extrêmement longue. Les données sont renvoyées à Fusion, mais ne peuvent pas être traitées par Fusion.

_Premier signalement le jeudi 3 janvier 2024._
