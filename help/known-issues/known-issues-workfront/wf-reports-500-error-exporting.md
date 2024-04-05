---
title: "Rapports : erreur 500 lors de l'export d'un rapport"
description: '"Lorsqu’un utilisateur tente d’exporter un rapport, celui-ci n’est pas exporté et une erreur s’affiche. Une solution de contournement est disponible. »'
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 1f516bdbea40c2946dec1935b7ada63b28b3451c
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 16%

---


# Rapports : erreur 500 lors de l’export d’un rapport

Lorsqu’un utilisateur tente d’exporter un rapport, celui-ci n’est pas exporté et l’erreur suivante s’affiche :

500 : impossible d’appeler &quot;com.attask.biz.Parameter.getDisplayType()&quot; car &quot;parameter&quot; est null /attask/api-internal/report/export.

Cela se produit lorsque le rapport fait référence à un champ de devise personnalisée au niveau du projet.

**Solution de contournement**

Supprimez la colonne qui référence le champ de devise personnalisée et exportez à nouveau le rapport.

_Premier signalement le vendredi 4 avril 2024._
