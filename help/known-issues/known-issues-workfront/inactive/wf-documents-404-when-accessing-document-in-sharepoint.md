---
title: 'Documents : erreur 404 lors de l’accès au document lié par SharePoint'
description: Lorsqu’un utilisateur ou une utilisatrice tente d’accéder à un document lié par SharePoint, cette personne est redirigée vers une page contenant une erreur 404.
feature: Digital Content and Documents, Workfront Integrations and Apps
exl-id: b86ec92b-a27f-4ec3-acc2-0f0118014760
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a1f87682-0525-5459-aa06-3560bb4c3b2a
    internal-label: Workfront Integrations and Apps
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
    internal-label: Digital content and documents
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '110'
ht-degree: 91%
---
# Documents : erreur 404 lors de l’accès à un document lié par [!DNL SharePoint]

<!--Requested article. This issue is on the WF and WFP TOCs.-->

Lorsqu’un utilisateur ou une utilisatrice tente d’accéder à un document lié par [!DNL SharePoint], cette personne est redirigée vers une page contenant l’erreur suivante :

« [!UICONTROL Erreur 404 : page introuvable. Cette page n’est pas disponible. Essayez de vérifier l’URL ou consultez une autre page.] »

Il s’agit d’un problème de [!DNL SharePoint] connu qui se produit lorsque le lien du site contient le symbole « @ ».

**Solution de contournement**

[!DNL SharePoint] recommande de générer une URL courte comme nouveau lien.

_Premier signalement le mercredi 14 mars 2023._
