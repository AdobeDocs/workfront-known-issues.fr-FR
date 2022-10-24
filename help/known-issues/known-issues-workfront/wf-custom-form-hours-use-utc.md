---
title: "Formulaires personnalisés : La fonction HOUR des champs calculés utilise UTC"
description: "Lorsqu’un champ calculé inclut la fonction HOUR, la fonction renvoie des valeurs basées sur le fuseau horaire UTC plutôt que sur celui attendu. Par conséquent, tous les calculs basés sur la valeur HOUR sont incorrects."
hidefromtoc: true
source-git-commit: 3950404543b428f98b4952e6cd01e72c69585644
workflow-type: tm+mt
source-wordcount: '84'
ht-degree: 4%

---


# Formulaires personnalisés : [!UICONTROL HEURE] La fonction des champs calculés utilise le format UTC.

Lorsqu’un champ calculé inclut la variable [!UICONTROL HEURE] , la fonction renvoie des valeurs en fonction du fuseau horaire UTC plutôt que du fuseau horaire attendu. Par conséquent, tous les calculs basés sur la valeur HOUR sont incorrects.

_Premier signalement le 17 octobre 2022._

