---
title: "Accueil : les tâches des projets dont l’état est Approuvé ou Planification ne sont pas incluses dans Mes tâches ou la liste de tâches à domicile"
description: "Les tâches des projets dont le statut est Approuvé ou Planification ne s’affichent pas dans Accueil. Une solution de contournement est disponible."
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: tm+mt
source-wordcount: '166'
ht-degree: 3%

---


# Accueil : les tâches des projets dont l’état est Approuvé ou Planification ne sont pas incluses dans Mes tâches ou la liste de tâches à domicile

Les tâches des projets dont le statut est Approuvé ou Planification ne s’affichent pas dans les zones suivantes :

* Accueil classique : liste de travail
* Nouvelle page d’accueil : widget Mes tâches

Cela est dû au fait que les tâches des projets dans ces états sont actuellement incluses dans la limite de requête de 2 000 éléments, mais elles ne sont pas affichées dans Mes tâches ou la liste Travail à domicile. Cela peut créer une situation où un utilisateur qui a moins de 2 000 tâches, ces tâches ne sont pas visibles.

**Solution de contournement**

Créez un rapport Affectations personnalisé qui comprend les filtres de mode de texte suivants :

Lorsque l’affectation attend l’ACCEPTATION, incluez les projets ACTUELS|APPROUVÉS :

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

Lorsque l’affectation est ACCEPTÉE, incluez CURRENT|APPROVED|PLANNING projects :

```
OR:1:assignedToID=$$USER.ID
OR:1:status=AD
OR:1:status_Mod=eq
OR:1:project:statusEquatesWith=CUR,APR,PLN
OR:1:project:statusEquatesWith_Mod=in
OR:1:task:statusEquatesWith=CPL
OR:1:task:statusEquatesWith_Mod=ne
```

_Premier signalement le 6 novembre 2023._
