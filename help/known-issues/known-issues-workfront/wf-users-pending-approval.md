---
title: 'Utilisateurs : le badge Approbation en attente s’affiche pour les nouveaux utilisateurs.'
description: Les nouveaux utilisateurs et nouvelles utilisatrices de Workfront peuvent s’afficher dans la liste des utilisateurs avec un badge Approbation en attente . Le badge persiste pendant plus de quelques minutes et est toujours présent lorsque la page est actualisée.
hidefromtoc: true
feature: People Teams and Groups
source-git-commit: 9c46f9006fa25481a012619a16d627e16f23c15e
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 1%

---


# Utilisateurs : le badge « Approbation en attente » s’affiche pour les nouveaux utilisateurs

>[!NOTE]
>
>Ce problème peut être présent dans les organisations qui ont été migrées vers Adobe Admin Console.

Les nouveaux utilisateurs et nouvelles utilisatrices de Workfront peuvent s’afficher dans la liste des utilisateurs et utilisatrices avec un badge « Approbation en attente ». Le badge persiste pendant plus de quelques minutes et est toujours présent lorsque la page est actualisée.

Ce problème est exacerbé lorsque les utilisateurs sont chargés par lots volumineux, comme à partir d’une feuille de calcul ou d’un démarrage rapide de Workfront.

Le badge disparaît au bout de quelques minutes et n’est pas présent lorsque la page est actualisée.

## Solutions

Cela se produit lorsque les utilisateurs ajoutés à Workfront ne se synchronisent pas avec Adobe Admin Console.

Nous vous recommandons les solutions suivantes :

### Résoudre les problèmes d’utilisateurs individuels

Vous pouvez résoudre des utilisateurs individuels dans la liste Utilisateurs .

1. Sélectionnez l’utilisateur ou les utilisateurs dans la liste Utilisateurs .
1. Cliquez sur le menu à trois points dans l’en-tête de la liste.
1. Sélectionnez **Approuver**.
1. Au bout de quelques minutes, actualisez la page.

### Résoudre les utilisateurs ajoutés dans un lot volumineux

Pour résoudre le problème des utilisateurs ajoutés dans un lot volumineux, vous pouvez ajouter directement le lot d’utilisateurs au Adobe Admin Console.

Pour obtenir des instructions, voir [Gérer plusieurs utilisateurs | Chargement CSV en masse](https://helpx.adobe.com/fr/enterprise/using/bulk-upload-users.html) dans la documentation d’Adobe.


_Premier signalement le vendredi 8 mai 2025._
