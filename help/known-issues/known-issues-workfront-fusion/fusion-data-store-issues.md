---
title: "Workfront Fusion : problèmes liés à Data Store"
description: "Les problèmes suivants ont été signalés concernant les champs booléens dans les entrepôts de données : les entrepôts de données ne renvoient aucune valeur pour les champs dont la valeur est EMPTY et les utilisateurs ne peuvent pas définir les valeurs sur FALSE directement dans l’entrepôt de données."
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 2cbde79df7bb110e083f8e8b65b319d9c682e188
workflow-type: tm+mt
source-wordcount: '100'
ht-degree: 5%

---


# Workfront Fusion : problèmes liés à l’entrepôt de données

Les problèmes suivants ont été signalés concernant les champs booléens dans les entrepôts de données :

* Les entrepôts de données ne renvoient aucune valeur pour les champs dont la valeur est EMPTY.
* Les utilisateurs ne peuvent pas définir les valeurs sur FALSE directement dans l’entrepôt de données.

**Solution de contournement**

Pour définir une valeur sur FALSE, utilisez le module Update Records approprié.

_Premier signalement le vendredi 19 septembre 2024._
