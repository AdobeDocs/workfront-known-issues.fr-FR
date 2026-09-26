---
title: 'Workfront Proof : erreur 500 lors de l’accès à Workfront Proof via l’API ou Workfront Fusion'
description: 'Lorsqu’un utilisateur ou une utilisatrice accède à l’action getAllProofs de l’API Proof, le serveur Workfront Proof renvoie le message suivant : Erreur de serveur interne 500'
feature: Workfront Proof
exl-id: 3c968354-58e2-43fc-8c27-2670683ac862
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
    internal-label: Workfront Proof
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 69%
---
# [!DNL Workfront Proof] : erreur 500 lors de l’accès au [!DNL Workfront Proof] via l’API ou [!DNL Workfront Fusion]

>[!NOTE]
>
>L’équipe produit évalue actuellement la résolution de ce problème, qui peut nécessiter des améliorations du produit. Les améliorations apportées aux produits sont communiquées dans les annonces de produit et non dans les mises à jour de maintenance.

<!--This article is on Proof and Fusion TOCs-->

Lorsqu’un utilisateur ou une utilisatrice accède à l’action [!UICONTROL `getAllProofs`] de l’API [!DNL Workfront Proof], le serveur renvoie le message suivant :

[!UICONTROL Erreur interne du serveur 500]

[!DNL Workfront Fusion] utilise l’API [!DNL Workfront Proof] pour les modules [!DNL Workfront Proof], cette erreur peut donc être renvoyée à un module, arrêtant un scénario.

_Premier signalement le samedi 28 avril 2023._
