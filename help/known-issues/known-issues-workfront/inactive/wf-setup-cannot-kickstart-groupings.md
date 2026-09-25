---
title: 'Configuration : impossible d’utiliser les [!UICONTROL Démarrages] pour créer des regroupements'
description: Lorsqu’un utilisateur ou une utilisatrice tente un [!UICONTROL Kickstart] sur un regroupement, l’import échoue et un message d’erreur s’affiche.
feature: System Setup and Administration
exl-id: e1b0ba88-0af7-432f-89db-de4f50b20ff6
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 100%
---
# Configuration : impossible d’utiliser les [!UICONTROL Démarrages] pour créer des regroupements

>[!NOTE]
>
>L’équipe produit évalue actuellement la résolution de ce problème, qui peut nécessiter des améliorations du produit. Les améliorations apportées aux produits sont communiquées dans les annonces de produit et non dans les mises à jour de maintenance.

Lorsqu’un utilisateur ou une utilisatrice tente de [!UICONTROL Démarrer] un regroupement, l’import échoue et un message d’erreur similaire à celui-ci s’affiche :

* [!UICONTROL L’erreur suivante s’est produite : les données fournies semblent se trouver dans le XML d’Office 2007+. Vous appelez la partie du point ciblé qui traite des documents Office OLE2. Vous devez appeler une autre partie du point ciblé pour traiter ces données (par exemple, XSSF au lieu de HSSF)].
* [!UICONTROL Oups ! Un problème est survenu. Fichier de préférences introuvable. Clé de préférence : ligne temporaire : 3 feuille : UIGB]

Cela peut se produire même si les filtres et les vues [!UICONTROL Démarrent] correctement.

_Premier signalement le vendredi 1 juin 2023._
