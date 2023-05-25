---
title: "Bon à tirer Workfront : Erreur 500 lors de l’accès au BAT Workfront via l’API ou Workfront Fusion"
description: "Lorsqu’un utilisateur accède à l’action getAllProofs de l’API de BAT, le serveur de BAT Workfront renvoie le message : 500 Internal Server Error"
hidefromtoc: true
source-git-commit: ef82f9a12925f2fc70a20f91f9278240fcee92fb
workflow-type: tm+mt
source-wordcount: '102'
ht-degree: 31%

---


# [!DNL Workfront Proof]: Erreur 500 lors de l’accès [!DNL Workfront Proof] via l’API ou [!DNL Workfront Fusion]

>[!NOTE]
>
>L’équipe produit évalue actuellement la résolution de ce problème, qui peut nécessiter des améliorations du produit. Les améliorations apportées aux produits sont communiquées dans les annonces de produit et non dans les mises à jour de maintenance.

<!--This article is on Proof and Fusion TOCs-->

Lorsqu’un utilisateur accède à la variable [!DNL Workfront Proof] API [!UICONTROL `getAllProofs`] , le serveur renvoie le message suivant :

[!UICONTROL Erreur interne 500 du serveur]

Parce que [!DNL Workfront Fusion] utilise la variable [!DNL Workfront Proof] API pour [!DNL Workfront Proof] , cette erreur peut être renvoyée à un module, arrêtant un scénario.

_Premier signalement le 28 avril 2023._

