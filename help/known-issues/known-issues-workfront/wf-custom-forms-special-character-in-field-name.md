---
title: '« Formulaires personnalisés : impossible d’utiliser le champ dans le calcul si le nom du champ contient des guillemets ou une apostrophe »'
description: '« Lorsqu’un utilisateur crée une expression de champ calculée et tente d’inclure un champ de saisie semi-automatique dont le nom comporte une apostrophe ou un guillemet, le calcul n’est pas accepté, et le message suivant apparaît : « Cette expression client n’est pas valide, veuillez réessayer. »'
hidefromtoc: true
source-git-commit: 3307a9be28555d0b9561e8ae96e3667cb1fee711
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 100%

---


# Formulaires personnalisés : impossible d’utiliser le champ dans le calcul si le nom du champ contient des apostrophes ou des guillemets

>[!NOTE]
>
>Ce problème a été résolu le 2 mars 2023.

Lorsqu’un utilisateur crée une expression de champ calculée et tente d’inclure un champ de saisie semi-automatique dont le nom comporte une `'` ou un `"`, le calcul n’est pas accepté, et le message suivant apparaît : « [!UICONTROL Cette expression client n’est pas valide, veuillez réessayer.] »

Ce problème ne concerne que les champs de saisie semi-automatique. Les champs de texte dont le nom comporte une `'` ou un `"` peuvent être utilisés dans les expressions de champ calculées sans problème.

_Premier signalement le 10 novembre 2022._

