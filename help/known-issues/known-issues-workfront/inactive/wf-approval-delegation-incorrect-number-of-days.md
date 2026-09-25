---
title: 'Approbations : la délégation d’approbation est définie pour un nombre de jours incorrect.'
description: Lorsque l’utilisateur planifie un Temps de congé personnel et délègue son approbation pour sa période de congé, la délégation d’approbation peut inclure des jours avant ou après la période de congé prévue.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: b04e3dc0-3a59-45b1-aa02-b0b6d5f87eff
    internal-label: Approvals
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 100%
---
# Approbations : la délégation d’approbation est définie pour un nombre de jours incorrect.

<!--Live for workaround-->

>[!NOTE]
>
>Ce problème a été résolu, car il ne s’agit pas d’un problème.

Lorsque l’utilisateur planifie un temps de congé personnel et délègue son approbation pour sa période de congé, la délégation d’approbation peut inclure des jours avant ou après la période de congé prévue.

**Solution de contournement**

Cette incohérence résulte d’une différence entre le fuseau horaire du profil de l’utilisateur et celui du planning affecté à l’utilisateur.

Nous vous recommandons de créer une planification unique pour chaque fuseau horaire dans lequel travaillent les utilisateurs et d’affecter chaque utilisateur à la planification correspondant au fuseau horaire renseigné dans son profil d’utilisateur.

_Premier signalement le vendredi 24 mars 2022._
