---
title: "Rapports : erreur 500 lors de l'export d'un rapport"
description: "Lorsqu’un utilisateur tente d’exporter un rapport, l’exportation échoue avec une erreur 500."
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 8fcd13b3586664d7540e64fb855f7f84e6e7cdc7
workflow-type: tm+mt
source-wordcount: '59'
ht-degree: 0%

---


# Rapports : erreur 500 lors de l&#39;export d&#39;un rapport

Lorsqu&#39;un utilisateur tente d&#39;exporter un rapport, l&#39;export échoue avec l&#39;erreur suivante :

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Cela a été signalé dans les rapports qui utilisent une `valueexpression` pour référencer la variable `lastNote` texte de la remarque.

_Premier article du 8 novembre 2023._
