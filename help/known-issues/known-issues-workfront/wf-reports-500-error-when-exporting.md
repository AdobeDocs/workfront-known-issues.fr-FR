---
title: '« Rapports : erreur 500 lors de l’export d’un rapport »'
description: Lors de la tentative d’export d’un rapport, l’export échoue et renvoie une erreur 500.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 45cea090d9e54514be9983b5443e7ee54b1f2d94
workflow-type: ht
source-wordcount: '59'
ht-degree: 100%

---

# Rapports : erreur 500 lors de l’export d’un rapport

Lors de la tentative d’export d’un rapport, l’export échoue et renvoie l’erreur suivante :

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Ce problème a été signalé dans les rapports qui utilisent une `valueexpression` pour référencer le texte de la note `lastNote`.

_Premier signalement le 8 novembre 2023._
