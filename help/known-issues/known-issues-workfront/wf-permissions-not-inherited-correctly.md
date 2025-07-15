---
title: 'Autorisations : les autorisations d’objet ne sont pas héritées correctement'
description: Les autorisations héritées ne sont pas correctement appliquées aux objets . Cela peut se produire en raison de la complexité des autorisations héritées.
hidefromtoc: true
feature: Projects, Tasks, Work Management
source-git-commit: 798be3dd7ef5e7bf0ecf14484242f7758ac9d9a4
workflow-type: tm+mt
source-wordcount: '144'
ht-degree: 22%

---


# Autorisations : les autorisations d’objet ne sont pas héritées correctement

>[!NOTE]
>
>L’équipe produit évalue actuellement la résolution de ce problème, qui peut nécessiter des améliorations du produit. Les améliorations apportées aux produits sont communiquées dans les annonces de produit et non dans les mises à jour de maintenance.

Les autorisations héritées ne sont pas correctement appliquées aux objets . Cela peut se produire en raison de la complexité des autorisations héritées, qui peuvent être affectées par les éléments suivants :

* L’objet est partagé avec un grand nombre de personnes
* Un grand nombre d’objets sont affectés par un changement d’autorisation hérité

**Solution de contournement**

Limiter la taille ou la complexité des objets permet d’éviter ce problème. Nous vous recommandons de ne pas avoir plus de 10 000 objets enfants sous un objet parent.

_Premier signalement le samedi 21 mars 2025._
