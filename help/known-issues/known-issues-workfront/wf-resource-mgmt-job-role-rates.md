---
title: '« Gestion des ressources : calculs financiers incorrects en raison de problèmes liés à la fonction »'
description: « Les heures et les calculs financiers peuvent être incorrects, affichant un coût de 0, même si les heures sont enregistrées dans une fonction avec un taux de dépenses. »
hidefromtoc: true
feature: Resource Management
source-git-commit: f8579e17458f702580e1a4cf3600c14376d7591b
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 100%

---


# Gestion des ressources : calculs financiers incorrects en raison de problèmes liés à la fonction

>[!NOTE]
>
>Ce problème a été résolu le vendredi 8 février 2024.

Les heures et les calculs financiers peuvent être incorrects, affichant un coût de 0, même si les heures sont enregistrées dans une fonction avec un taux de dépenses.

Cela est dû au fait que les fonctions créent automatiquement des taux en double sans date de début ou de fin. Comme elles n’ont pas de date de début ou de fin, elles sont traitées comme une valeur de 0 lorsque les calculs financiers sont exécutés.

**Solution de contournement**

1. Vérifiez que vos anciennes données correctes sont enregistrées.
1. Supprimez les taux en double sans date de début ou de fin.
1. Recalculez les finances.

_Premier signalement le 18 janvier 2023._
