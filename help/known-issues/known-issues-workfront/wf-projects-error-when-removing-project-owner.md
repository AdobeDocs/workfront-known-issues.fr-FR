---
title: 'Projets : Erreur lors de la suppression du propriétaire du projet de l’en-tête'
description: Lorsqu’un utilisateur tente de supprimer un propriétaire de projet de l’en-tête d’un projet, il n’est pas supprimé et un message d’erreur s’affiche.
hidefromtoc: true
exl-id: 3a995df4-5d6a-44e4-a644-997931c044bf
source-git-commit: 7570b2a560505d66e0e83656c9a601226998c11c
workflow-type: tm+mt
source-wordcount: '97'
ht-degree: 0%

---

# Projets : Erreur lors de la suppression de la variable [!UICONTROL Propriétaire du projet] de l’en-tête

>[!NOTE]
>
>Ce problème a été résolu le 9 septembre 2022.

Lorsqu’un utilisateur tente de supprimer une [!UICONTROL Propriétaire du projet] dans l’en-tête d’un projet, la variable [!UICONTROL Propriétaire du projet] n’est pas supprimé et l’utilisateur voit le message d’erreur suivant :

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Solution**

Supprimez le[!UICONTROL  Propriétaire du projet] du projet [!UICONTROL Détails] zone.

_Premier article du 9 août 2022._
