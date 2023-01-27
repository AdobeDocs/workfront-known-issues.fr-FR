---
title: '« Workfront Fusion : impossible de créer une connexion à Google »'
description: Lorsqu’un utilisateur tente de créer une connexion dans l’un des connecteurs Google (tels que Google Sheets ou Google Drive), la connexion n’est pas créée et plusieurs messages d’erreur apparaissent.
hidefromtoc: true
exl-id: 068793be-63e5-40b5-bf10-c01d76c1b6e7
source-git-commit: dd093aff6103901898c561c9f6f544c1648682a3
workflow-type: ht
source-wordcount: '109'
ht-degree: 100%

---

# [!DNL Workfront Fusion] : impossible de créer une connexion à [!DNL Google]

>[!NOTE]
>
>Ce problème a été résolu le 9 janvier 2023.

Lorsqu’un utilisateur tente de créer une connexion dans l’une des connecteurs [!DNL Google] (tels que [!DNL Google Sheets] ou [!DNL Google Drive]), une fenêtre s’ouvre et le message d’erreur suivant apparaît :

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

Lorsque l’utilisateur ferme cette fenêtre, la connexion échoue et l’erreur suivante apparaît [!DNL Fusion] :

« [!UICONTROL Erreur : la demande a échoué en raison de l’échec d’une demande précédente. Aucun jeton d’accès spécifié.] »

_Premier signalement le 21 novembre 2022._
