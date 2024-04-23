---
title: '« Rapports : erreur 500 lors de l’export d’un rapport »'
description: Lorsqu’un utilisateur ou une utilisatrice tente d’exporter un rapport, celui-ci n’est pas exporté et une erreur s’affiche. Une solution de contournement est disponible.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: ht
source-wordcount: '105'
ht-degree: 100%

---

# Rapports : erreur 500 lors de l’export d’un rapport

>[!NOTE]
>
>Ce problème a été résolu le samedi 5 avril 2024.

Lorsqu’un utilisateur ou une utilisatrice tente d’exporter un rapport, celui-ci n’est pas exporté et l’erreur suivante s’affiche :

500 : impossible d’appeler « com.attask.biz.Parameter.getDisplayType() » car « parameter » est nul /attask/api-internal/report/export.

Cela se produit lorsque le rapport fait référence à un champ de devise personnalisé au niveau du projet.

**Solution de contournement**

Supprimez la colonne faisant référence au champ de devise personnalisé et exportez à nouveau le rapport.

_Premier signalement le vendredi 4 avril 2024._
