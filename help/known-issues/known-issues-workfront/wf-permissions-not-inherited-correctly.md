---
title: 'Autorisations : les autorisations d’objet ne sont pas héritées correctement.'
description: Les autorisations héritées ne sont pas correctement appliquées aux objets. Cela peut être dû à leur complexité.
feature: Projects, Tasks, Work Management
exl-id: 589733a7-2bd6-4b73-afb8-a14cc1f5076a
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '146'
ht-degree: 100%

---

# Autorisations : les autorisations d’objet ne sont pas héritées correctement.

>[!NOTE]
>
>L’équipe produit évalue actuellement la résolution de ce problème, qui peut nécessiter des améliorations du produit. Les améliorations apportées aux produits sont communiquées dans les annonces de produit et non dans les mises à jour de maintenance.

Les autorisations héritées ne sont pas correctement appliquées aux objets. Cela peut être dû à la complexité des autorisations héritées, qui peuvent être affectées par les éléments suivants :

* L’objet est partagé avec un grand nombre de personnes.
* Un grand nombre d’objets sont affectés par un changement d’autorisation héritée.

**Solution de contournement**

Limiter la taille ou la complexité des objets peut permettre d’éviter ce problème. Nous vous recommandons de ne pas dépasser 10 000 objets enfants sous un objet parent.

_Premier signalement le samedi 21 mars 2025._
