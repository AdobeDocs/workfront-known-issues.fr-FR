---
title: 'Épreuves : une nouvelle étape a été créée, car la date limite ne correspond pas à celle de l’étape existante.'
description: Lors de la création d’une nouvelle épreuve, la date limite peut être déterminée par incréments de 15 minutes (10:00, 10:15, 10:30, 20:45, etc.). Cependant, lorsque l’utilisateur est ajouté à une épreuve après sa création, la date limite peut uniquement être déterminée par incréments de 30 minutes (10:00, 10:30, 11:00, etc.).
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '224'
ht-degree: 44%

---

# Épreuves : une nouvelle étape a été créée, car la date limite ne correspond pas à celle de l’étape existante.

<!--Requested article-->

Lors de la création d’une nouvelle épreuve, la date limite peut être déterminée par incréments de 15 minutes (10:00, 10:15, 10:30, 20:45, etc.). Cependant, lorsque l’utilisateur est ajouté à une épreuve après sa création, la date limite ne peut être définie que par incréments de 30 minutes (10:00, 10:30, 11:00, etc.). Par conséquent, le nouvel utilisateur ne peut pas être ajouté à une étape avec une date limite se terminant par :15 ou :45, car les dates limites ne correspondent pas. Au lieu de cela, le nouvel utilisateur est ajouté à une nouvelle étape, avec une date limite définie par incréments de 30 minutes.

**Solution** :

* Si vous sélectionnez une date limite pour une nouvelle épreuve, définissez une heure qui se termine par :00 ou :30 (10:00, 10:30, 11:00, etc.).
* Si la date limite est définie automatiquement au moment de la création de l’épreuve, définissez manuellement la date limite de l’épreuve sur une heure qui se termine par :00 ou :30 (10:00, 10:30, 11:00, etc.).
