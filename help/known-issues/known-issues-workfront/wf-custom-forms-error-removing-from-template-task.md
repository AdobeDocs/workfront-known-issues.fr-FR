---
title: "Formulaires personnalisés : impossible d’ajouter ou de supprimer des formulaires personnalisés en masse sur des tâches de modèle"
description: "Si un utilisateur tente d’ajouter ou de supprimer en masse un formulaire personnalisé pour une tâche de modèle, ce dernier n’est pas ajouté ni supprimé et une erreur s’affiche."
hidefromtoc: true
feature: Custom Forms
source-git-commit: 41df80641db82b225753338d8564e12b90566c40
workflow-type: tm+mt
source-wordcount: '153'
ht-degree: 5%

---


# Formulaires personnalisés : impossible d’ajouter ou de supprimer des formulaires personnalisés en masse sur des tâches de modèle

Si un utilisateur tente d’ajouter ou de supprimer en masse un formulaire personnalisé en vue d’une tâche de modèle, ce dernier n’est pas ajouté ni supprimé et l’utilisateur affiche l’erreur suivante :

[!UICONTROL Réessayons. Paramètre non valide : valeur templateID &quot;XXXXXXXXXXXXXX&quot;]

Si l’utilisateur localise le modèle avec le GUID spécifié, puis tente d’ajouter ou de supprimer des formulaires personnalisés sur le reste des tâches du modèle, l’erreur se produit à l’aide d’un autre templateID.

Les formulaires personnalisés peuvent être ajoutés ou supprimés sur une seule tâche de modèle. Cette erreur s’applique uniquement à l’ajout ou la suppression en masse.

_Premier signalement le 10 novembre 2023._
