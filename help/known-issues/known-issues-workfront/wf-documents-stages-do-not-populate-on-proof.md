---
title: 'BAT : le champ [!UICONTROL Étapes de BAT actives] est vide'
description: Lorsque l’utilisateur crée une épreuve puis l’affiche dans un rapport comme [!UICONTROL Version du document] ou [!UICONTROL Approbation de l’épreuve], le champ [!UICONTROL Étapes d’épreuve actives] est vide. Cela se produit lorsque l’épreuve est créée après le chargement du document, sous la forme d’une [!UICONTROL Épreuve simple] ou d’une [!UICONTROL Épreuve avancée] avec un [!UICONTROL Workflow basique].
hidefromtoc: true
exl-id: 1cd7baed-b561-48fa-ba58-e0533db01696
source-git-commit: a9e0c0cc9bd1d69b22fcf9ef755a715d37ba658d
workflow-type: ht
source-wordcount: '200'
ht-degree: 100%

---

# Épreuves : le champ [!UICONTROL Étapes d’épreuve actives] est vide

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof. Article created by request.-->

>[!NOTE]
>
>L’équipe produit évalue actuellement la résolution de ce problème, qui peut nécessiter des améliorations du produit. Les améliorations apportées aux produits sont communiquées dans les annonces de produit et non dans les mises à jour de maintenance.

Lorsque l’utilisateur crée une épreuve puis l’affiche dans un rapport comme [!UICONTROL Version du document] ou [!UICONTROL Approbation de l’épreuve], le champ [!UICONTROL Étapes d’épreuve actives] est vide. Cela se produit lorsque l’épreuve est créée après le chargement du document, sous la forme d’une [!UICONTROL Épreuve simple] ou d’une [!UICONTROL Épreuve avancée] avec un [!UICONTROL Workflow basique].

**Solution**

Utilisez l’une des méthodes suivantes :

* Lors de l’ajout d’un nouveau document, ajoutez-le en tant qu’épreuve en sélectionnant [!UICONTROL Ajouter] > [!UICONTROL Épreuve].
* Lors de la création d’une épreuve à partir d’un document existant, créez-la en tant qu’[!UICONTROL Épreuve avancée] avec un [!UICONTROL Workflow automatisé].

_Premier signalement le 31 août 2022._
