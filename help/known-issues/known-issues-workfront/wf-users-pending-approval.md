---
title: 'Utilisateurs et utilisatrices : le badge Approbation en attente s’affiche pour les nouvelles personnes'
description: Les nouveaux utilisateurs et utilisatrices de Workfront peuvent s’afficher dans la liste avec un badge Approbation en attente. Le badge apparaît pendant plusieurs minutes et reste affiché si la page est actualisée.
hidefromtoc: true
feature: People Teams and Groups
exl-id: 27db1155-f6aa-465d-a42b-1147cf5431e1
source-git-commit: 39a085b629d6d2afc5a198e47ca639d2bb431b0d
workflow-type: ht
source-wordcount: '245'
ht-degree: 100%

---

# Utilisateurs et utilisatrices : le badge « Approbation en attente » s’affiche pour les nouvelles personnes.

>[!NOTE]
>
>Ce problème peut se produire dans les organisations qui ont migré vers Adobe Admin Console.

Les nouveaux utilisateurs et utilisatrices de Workfront peuvent s’afficher dans la liste avec un badge « Approbation en attente ». Le badge apparaît pendant plusieurs minutes et reste affiché si la page est actualisée.

Ce problème est exacerbé lorsque les utilisateurs et utilisatrices sont chargés par lots volumineux, notamment à partir d’une feuille de calcul ou d’un kickstart Workfront.

Normalement, le badge disparaît au bout de quelques minutes et ne réapparaît pas lorsque la page est actualisée.

## Solutions

Cela se produit lorsque les utilisateurs et utilisatrices ajoutés à Workfront ne se synchronisent pas avec Adobe Admin Console.

Nous vous recommandons les solutions suivantes :

### Valider les utilisateurs et utilisatrices individuels

Vous pouvez valider des utilisateurs et utilisatrices individuels dans la liste Utilisateurs et utilisatrices.

1. Sélectionnez la ou les personnes dans la liste Utilisateurs et utilisatrices.
1. Cliquez sur le menu à trois points dans l’en-tête de la liste.
1. Sélectionnez **Approuver**.
1. Après quelques minutes, actualisez la page.

### Valider les utilisateurs et utilisatrices ajoutés dans un lot volumineux

Pour valider les utilisateurs et utilisatrices ajoutés dans un lot volumineux, vous pouvez ajouter ce lot de personnes directement dans Adobe Admin Console.

Pour obtenir des instructions, voir la section [Gérer plusieurs utilisateurs et utilisatrices | Chargement CSV en masse](https://helpx.adobe.com/enterprise/using/bulk-upload-users.html?lang=fr) dans la documentation Adobe.


_Premier signalement le 8 mai 2025_
