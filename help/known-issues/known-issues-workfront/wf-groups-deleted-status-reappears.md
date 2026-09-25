---
title: Problèmes lors de la suppression du statut du groupe
description: Après la suppression de l’état d’un groupe, bien que le groupe n’affiche plus son état et que la durée de suppression apparaisse dans les mises à jour du groupe, il réapparaît finalement sans être modifié par un utilisateur ou une utilisatrice.
feature: People Teams and Groups
exl-id: 061bfacc-5350-4e5f-91c1-89b32835d6e5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: 254442ca-6997-5cfa-963e-f420870aea53
    internal-label: People Teams and Groups
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '138'
ht-degree: 100%
---
# Groupes : problèmes lors de la suppression du statut du groupe

>[!NOTE]
>
>Ce problème a été clos, car il n’a pas pu être reproduit.

Les problèmes suivants liés à la suppression des statuts des groupes ont été signalés :

* Après la suppression de l’état d’un groupe, bien que le groupe n’affiche plus son état et que la durée de suppression apparaisse dans les mises à jour du groupe, il réapparaît finalement sans être modifié par un utilisateur ou une utilisatrice.
* Lorsqu’une personne tente de supprimer un statut de groupe, le système ne répond pas, la fenêtre est mise en surbrillance et le statut n’est pas supprimé.

**Solution de contournement**

1. Accédez à **Configuration** > **Préférences** > **Statuts**.
1. Recherchez le groupe correspondant.
1. Supprimez le statut.

_Premier signalement le jeudi 26 juin 2024._
