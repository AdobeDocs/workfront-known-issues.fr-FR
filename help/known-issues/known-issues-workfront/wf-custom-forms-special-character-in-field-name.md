---
title: '''Formulaires personnalisés : Impossible d’utiliser un champ dans le calcul si le nom du champ contient des guillemets ou une apostrophe.'
description: Lorsqu’un utilisateur crée une expression de champ calculée et tente d’inclure un champ de type caractère avec un nom doté d’une apostrophe ou d’un guillemet, le calcul n’est pas accepté et l’utilisateur voit le message Il s’agit d’une expression personnalisée non valide, veuillez réessayer.
hidefromtoc: true
feature: Custom Forms
exl-id: 7caa6b7a-87ab-40e8-aea2-05b41583a375
source-git-commit: 2a41264d6f477f51eaeda6ae3675b1a6d816249c
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 59%

---

# Formulaires personnalisés : impossible d’utiliser le champ dans le calcul si le nom du champ contient des apostrophes ou des guillemets

>[!NOTE]
>
>Ce problème a été résolu le 2 mars 2023.

Lorsqu’un utilisateur crée une expression de champ calculée et tente d’inclure un champ de saisie semi-automatique dont le nom comporte une `'` ou un `"`, le calcul n’est pas accepté, et le message suivant apparaît : « [!UICONTROL Cette expression client n’est pas valide, veuillez réessayer.] »

Ce problème ne concerne que les champs de saisie semi-automatique. Les champs de texte dont le nom comporte une `'` ou un `"` peuvent être utilisés dans les expressions de champ calculées sans problème.

_Premier signalement le 10 novembre 2022._
