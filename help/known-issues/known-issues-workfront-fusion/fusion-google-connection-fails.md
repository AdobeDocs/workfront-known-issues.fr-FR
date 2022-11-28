---
title: "Workfront Fusion : Impossible de créer une connexion à Google"
description: "Lorsqu’un utilisateur tente de créer une connexion dans l’un des connecteurs Google (tels que Google Sheets ou Google Drive), la connexion n’est pas créée et l’utilisateur voit divers messages d’erreur."
hidefromtoc: true
source-git-commit: 7d50ddbd99edf3421ce92564590a2d8db76ae939
workflow-type: tm+mt
source-wordcount: '103'
ht-degree: 3%

---


# [!DNL Workfront Fusion]: Impossible de créer la connexion à [!DNL Google]

Lorsqu’un utilisateur tente de créer une connexion dans l’une des [!DNL Google] les connecteurs (tels que [!DNL Google Sheets] ou [!DNL Google Drive]), une fenêtre s’ouvre avec l’erreur suivante :

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

Lorsque l’utilisateur ferme cette fenêtre, la connexion échoue avec l’erreur suivante dans [!DNL Fusion]:

&quot;[!UICONTROL Erreur : La requête a échoué en raison de l’échec d’une requête précédente. Aucun jeton d’accès spécifié.]&quot;

_Premier signalement le 21 novembre 2022._

