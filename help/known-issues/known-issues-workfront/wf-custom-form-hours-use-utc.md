---
title: ""
description: ""
hidefromtoc: true
source-git-commit: 63a50bd96799fb0c5338119dc4283100b0b01582
workflow-type: tm+mt
source-wordcount: '44'
ht-degree: 9%

---


# Formulaires personnalisés : La fonction HOUR des champs calculés utilise UTC

Lorsqu’un champ calculé comprend la fonction HOUR, la fonction renvoie des valeurs basées sur le fuseau horaire UTC plutôt que sur celui attendu. Par conséquent, tous les calculs basés sur la valeur HOUR sont incorrects.

_Premier signalement le 17 octobre 2022._

