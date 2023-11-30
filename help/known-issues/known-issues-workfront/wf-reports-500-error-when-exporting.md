---
title: '« Rapports : erreur 500 lors de l’export d’un rapport »'
description: Lors de la tentative d’export d’un rapport, l’export échoue et renvoie une erreur 500.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: tm+mt
source-wordcount: '65'
ht-degree: 100%

---

# Rapports : erreur 500 lors de l’export d’un rapport

>[!NOTE]
>
>Ce problème a été résolu le 30 novembre 2023.

Lors de la tentative d’export d’un rapport, l’export échoue et renvoie l’erreur suivante :

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Ce problème a été signalé dans les rapports qui utilisent une `valueexpression` pour référencer le texte de la note `lastNote`.

_Premier signalement le 8 novembre 2023._
