---
title: "Listes : Les erreurs de modification en ligne par l’utilisateur ne provoquent pas de messages d’erreur"
description: "Lorsqu’un utilisateur édite en ligne un objet et qu’il génère une erreur qui doit créer un message d’erreur, aucun message d’erreur ne s’affiche. L’erreur elle-même n’est pas enregistrée dans Workfront. Par conséquent, les données ne sont pas affectées, mais l’absence de message d’erreur peut prêter à confusion."
hidefromtoc: true
source-git-commit: ed5bd591f4be66631dba19d666b7d280eda1e1ab
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 2%

---


# Listes : Les erreurs de modification en ligne par l’utilisateur ne provoquent pas de messages d’erreur

Lorsqu’un utilisateur édite en ligne un objet et qu’il génère une erreur qui doit créer un message d’erreur, aucun message d’erreur ne s’affiche. L’erreur elle-même n’est pas enregistrée dans Workfront. Par conséquent, les données ne sont pas affectées, mais l’absence de message d’erreur peut prêter à confusion.

Cela a été signalé pour les situations suivantes :

* Prédécesseurs : Une boucle précédente est créée, par exemple en se affectant une tâche.
* Dates : Une date impossible est définie, par exemple une date de fin antérieure à la date de début ou supérieure à la date de fin du projet.

_Premier signalement le 26 octobre 2022._

