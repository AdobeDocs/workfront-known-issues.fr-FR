---
title: "Approbations\_: la délégation d’approbation est définie pour un nombre de jours incorrect"
description: Lorsque l’utilisateur planifie un Temps de congé personnel et délègue son approbation pour sa période de congé, la délégation d’approbation peut inclure des jours avant ou après la période de congé prévue.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
hidefromtoc: true
source-git-commit: de7f66f7acba1a0ac32a1257b2e643a767eae7fb
workflow-type: ht
source-wordcount: '141'
ht-degree: 100%

---

# Approbations : la délégation d’approbation est définie pour un nombre de jours incorrect

>[!NOTE]
>
>Ce problème a été résolu, car il ne s’agit pas d’un problème.

Lorsque l’utilisateur planifie un temps de congé personnel et délègue son approbation pour sa période de congé, la délégation d’approbation peut inclure des jours avant ou après la période de congé prévue.

**Solution**

Cette incohérence résulte d’une différence entre le fuseau horaire du profil de l’utilisateur et celui du planning affecté à l’utilisateur.

Nous vous recommandons de créer une planification unique pour chaque fuseau horaire dans lequel travaillent les utilisateurs et d’affecter chaque utilisateur à la planification correspondant au fuseau horaire renseigné dans son profil d’utilisateur.

_Premier signalement le 24 mars 2022._
