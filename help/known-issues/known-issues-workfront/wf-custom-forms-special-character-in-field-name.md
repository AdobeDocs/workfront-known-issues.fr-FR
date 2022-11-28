---
title: "Formulaires personnalisés : Impossible d’utiliser le champ dans le calcul si le nom du champ contient des guillemets ou une apostrophe"
description: "Lorsqu’un utilisateur crée une expression de champ calculée et tente d’inclure un champ de type devant dont le nom comporte une apostrophe ou un guillemet, le calcul n’est pas accepté, et l’utilisateur voit le message Il s’agit d’une expression personnalisée non valide, veuillez réessayer."
hidefromtoc: true
source-git-commit: 0c260518bc0b268d734e309bef11b613fee90172
workflow-type: tm+mt
source-wordcount: '148'
ht-degree: 2%

---


# Formulaires personnalisés : Impossible d’utiliser un champ dans le calcul si le nom du champ contient des apostrophes ou des guillemets

Lorsqu’un utilisateur crée une expression de champ calculé et tente d’inclure un champ de saisie anticipée dont le nom comporte un `'` ou `"`, le calcul n’est pas accepté et l’utilisateur voit le message &quot;[!UICONTROL Il s’agit d’une expression personnalisée non valide, veuillez réessayer.]&quot;

Ce problème n’existe qu’avec les champs de saisie anticipée. Champs de texte avec `'` ou `"` dans le nom peut être utilisé dans les expressions de champ calculées sans problème.

_Premier signalement le 10 novembre 2022._

