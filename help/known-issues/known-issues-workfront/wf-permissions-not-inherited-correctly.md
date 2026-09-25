---
title: 'Autorisations : les autorisations d’objet ne sont pas héritées correctement.'
description: Les autorisations héritées ne sont pas correctement appliquées aux objets. Cela peut être dû à leur complexité.
feature: Projects, Tasks, Work Management
exl-id: 589733a7-2bd6-4b73-afb8-a14cc1f5076a
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
subfeature_v2:
  - id: f0dd7b45-76b5-49d4-afe3-39f436b6fbd3
    internal-label: Projects
  - id: b91c0848-76c4-4da4-8b81-3aade0518dd0
    internal-label: Tasks
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
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
