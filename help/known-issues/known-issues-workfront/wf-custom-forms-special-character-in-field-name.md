---
title: '« Formulaires personnalisés : impossible d’utiliser le champ dans le calcul si le nom du champ contient des guillemets ou une apostrophe »'
description: '« Lorsqu’un utilisateur crée une expression de champ calculée et tente d’inclure un champ de saisie semi-automatique dont le nom comporte une apostrophe ou un guillemet, le calcul n’est pas accepté, et le message suivant apparaît : « Cette expression client n’est pas valide, veuillez réessayer. »'
hidefromtoc: true
source-git-commit: 0c260518bc0b268d734e309bef11b613fee90172
workflow-type: ht
source-wordcount: '148'
ht-degree: 100%

---


# Formulaires personnalisés : impossible d’utiliser le champ dans le calcul si le nom du champ contient des apostrophes ou des guillemets

Lorsqu’un utilisateur crée une expression de champ calculée et tente d’inclure un champ de saisie semi-automatique dont le nom comporte une `'` ou un `"`, le calcul n’est pas accepté, et le message suivant apparaît : « [!UICONTROL Cette expression client n’est pas valide, veuillez réessayer.] »

Ce problème ne concerne que les champs de saisie semi-automatique. Les champs de texte dont le nom comporte une `'` ou un `"` peuvent être utilisés dans les expressions de champ calculées sans problème.

_Premier signalement le 10 novembre 2022._

