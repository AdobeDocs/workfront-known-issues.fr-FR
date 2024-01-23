---
title: "Gestion des ressources : calculs financiers incorrects dus à des problèmes de rôle de tâche"
description: "Les calculs des heures et de la finance peuvent être incorrects, affichant un coût de 0, même si les heures sont enregistrées dans un rôle d’emploi avec un taux de coût."
hidefromtoc: true
feature: Resource Management
source-git-commit: e9a7ff289e7c9fcc9c9ff13b7c4b5b554e303c11
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 3%

---


# Gestion des ressources : calculs financiers incorrects en raison de problèmes liés au rôle de tâche

Les calculs des heures et des finances peuvent être incorrects, affichant un coût de 0, même si les heures sont enregistrées dans un rôle de tâche avec un taux de coût.

Cela est dû au fait que les rôles de tâche créent automatiquement des taux en double sans date de début ou de fin. Comme elles n’ont pas de date de début ou de fin, elles sont traitées comme une valeur de 0 lorsque les calculs financiers sont exécutés.

**Solution de contournement**

1. Assurez-vous que vos anciennes données correctes sont enregistrées.
1. Supprimez les taux en double sans date de début ou de fin.
1. Recalculer les finances.

_Premier signalement le 18 janvier 2023._
