---
title: "Projets / problèmes : Le projet ne résout pas correctement le problème"
description: "Lorsqu’un utilisateur modifie l’état d’un projet qui est l’objet de résolution d’un problème, l’état du problème est remplacé par un état qui ne correspond pas à la même clé que l’état du projet."
hidefromtoc: true
feature: Projects
source-git-commit: 3d2c392fdb9cdf2eb7ea46cd4444895bc45a5b7d
workflow-type: tm+mt
source-wordcount: '106'
ht-degree: 4%

---


# Projets/problèmes : Le projet ne résout pas correctement le problème

Lorsqu’un utilisateur modifie l’état d’un projet qui est l’objet de résolution d’un problème, celui-ci passe à un état qui ne correspond pas à la même clé que l’état du projet.

**Solution de contournement**

Supprimez la relation de résolution et définissez les états indépendamment.

_Premier signalement le 17 juillet 2023._
