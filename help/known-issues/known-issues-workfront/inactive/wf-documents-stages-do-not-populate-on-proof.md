---
title: 'Épreuves : le champ [!UICONTROL Étapes d’épreuve actives] est vide.'
description: Lorsque l’utilisateur crée une épreuve puis l’affiche dans un rapport comme [!UICONTROL Version du document] ou [!UICONTROL Approbation de l’épreuve], le champ [!UICONTROL Étapes d’épreuve actives] est vide. Cela se produit lorsque l’épreuve est créée après le chargement du document, sous la forme d’une [!UICONTROL Épreuve simple] ou d’une [!UICONTROL Épreuve avancée] avec un [!UICONTROL Workflow basique].
feature: Digital Content and Documents
exl-id: 1cd7baed-b561-48fa-ba58-e0533db01696
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
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
source-wordcount: '202'
ht-degree: 100%
---
# Épreuves : le champ [!UICONTROL Étapes d’épreuve actives] est vide.

<!--Requested article. This Known Issue is on the TOC for both Workfront and Workfront Proof.-->

>[!NOTE]
>
>L’équipe produit évalue actuellement la résolution de ce problème, qui peut nécessiter des améliorations du produit. Les améliorations apportées aux produits sont communiquées dans les annonces de produit et non dans les mises à jour de maintenance.

Lorsque l’utilisateur crée une épreuve puis l’affiche dans un rapport comme [!UICONTROL Version du document] ou [!UICONTROL Approbation de l’épreuve], le champ [!UICONTROL Étapes d’épreuve actives] est vide. Cela se produit lorsque l’épreuve est créée après le chargement du document, sous la forme d’une [!UICONTROL Épreuve simple] ou d’une [!UICONTROL Épreuve avancée] avec un [!UICONTROL Workflow basique].

**Solution de contournement**

Utilisez l’une des méthodes suivantes :

* Lors de l’ajout d’un nouveau document, ajoutez-le en tant qu’épreuve en sélectionnant [!UICONTROL Ajouter] > [!UICONTROL Épreuve].
* Lors de la création d’une épreuve à partir d’un document existant, créez-la en tant qu’[!UICONTROL Épreuve avancée] avec un [!UICONTROL Workflow automatisé].

_Premier signalement le jeudi 31 août 2022._
