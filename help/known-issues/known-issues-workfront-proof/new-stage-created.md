---
title: '''Bons à tirer : Nouvelle étape créée car la date limite ne peut pas correspondre à la date limite de l’étape existante"'
description: Lors de la création d'un BAT, la date limite peut être fixée par incréments de 15 minutes (10:00, 10:15, 10:30, 20:45, etc.). Cependant, lorsqu'un utilisateur est ajouté à un BAT après la création du BAT, la date limite ne peut être définie que par incréments de 30 minutes (10h00, 10h30, 11h00, etc.).
exl-id: b86c1c83-c647-4762-bc13-9687a7dada78
hidefromtoc: true
source-git-commit: 993b46816bed20ad7e75b7e0719f4b3b5442cabc
workflow-type: tm+mt
source-wordcount: '197'
ht-degree: 0%

---

# Bons à tirer : Nouvelle étape créée car la date limite ne peut pas correspondre à la date limite de l’étape existante

>[!NOTE]
>
>Ce problème a été corrigé.

Lors de la création d&#39;un BAT, la date limite peut être fixée par incréments de 15 minutes (10:00, 10:15, 10:30, 20:45, etc.). Cependant, lorsqu&#39;un utilisateur est ajouté à un BAT après la création du BAT, la date limite ne peut être définie que par incréments de 30 minutes (10h00, 10h30, 11h00, etc.). Par conséquent, le nouvel utilisateur ne peut pas être ajouté à une étape dont l’échéance se termine à : 15 ou : 45, car les échéances ne peuvent pas être respectées. Le nouvel utilisateur est ajouté à une nouvelle étape, avec une échéance définie par incréments de 30 minutes.

**Solution**:

* Si vous sélectionnez une date limite pour un nouveau BAT, définissez cette date limite sur une heure qui se termine par 00 ou 0003 (10, 10:30, 11:00, etc.).
* Si l&#39;échéance est définie automatiquement au moment de la création du BAT, définissez manuellement l&#39;échéance du BAT sur une heure qui se termine par : 00 ou : 30 (10:00, 10:30, 11:00, etc.).
