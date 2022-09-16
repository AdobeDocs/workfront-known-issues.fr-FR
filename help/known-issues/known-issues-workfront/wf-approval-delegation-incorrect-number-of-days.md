---
title: '''Validations : La délégation de validation est définie pour un nombre de jours incorrect.'
description: Lorsqu’un utilisateur planifie une heure de congé personnel et délègue son approbation pour cette période, la délégation d’approbation peut inclure des jours avant ou après l’heure de congé prévue.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
hidefromtoc: true
source-git-commit: de7f66f7acba1a0ac32a1257b2e643a767eae7fb
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 0%

---

# Validations : La délégation d’approbation est définie pour un nombre de jours incorrect

>[!NOTE]
>
>Ce problème a été résolu car il ne s’agit pas d’un problème.

Lorsqu’un utilisateur planifie des congés personnels et délègue ses validations pour cette période, la délégation de validation peut inclure des jours avant ou après l’heure planifiée.

**Solution**

Cette incohérence résulte d’une différence entre le fuseau horaire du profil d’un utilisateur et celui du planning affecté à l’utilisateur.

Nous vous recommandons de créer une planification unique pour chaque fuseau horaire à partir duquel les utilisateurs travaillent et d’affecter chaque utilisateur à la planification correspondant au fuseau horaire dans son profil utilisateur.

_Premier article du 24 mars 2022._
