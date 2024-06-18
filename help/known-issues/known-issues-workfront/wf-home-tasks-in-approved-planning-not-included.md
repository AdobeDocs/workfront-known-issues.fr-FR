---
title: '« Accueil : les tâches des projets dont le statut est Approuvé ou Planification ne sont pas incluses dans Mes tâches ou la Liste de travail de l’accueil. »'
description: Les tâches des projets dont le statut est Approuvé ou Planification ne s’affichent pas dans l’accueil. Une solution de contournement est disponible.
hidefromtoc: true
feature: Get Started with Workfront
exl-id: 5994508b-ee9f-40a9-bca3-e17d7a7708b5
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: ht
source-wordcount: '195'
ht-degree: 100%

---

# Accueil : les tâches des projets dont le statut est Approuvé ou Planification ne sont pas incluses dans Mes tâches ou la liste de travail dans Accueil

>[!NOTE]
>
>L’équipe produit évalue actuellement la résolution de ce problème. Une fois la résolution trouvée, elle sera communiquée dans les annonces de produits et non pas dans les mises à jour de maintenance.

Les tâches des projets dont le statut est Approuvé ou Planification ne s’affichent pas dans les zones suivantes :

* Accueil classique : liste de travail
* Nouvelle page d’accueil : widget Mes tâches

Cela est dû au fait que les tâches des projets dans ces statuts sont actuellement incluses dans la limite de requête de 2 000 éléments, mais elles ne sont pas affichées dans Mes tâches ou la liste Travail dans Accueil. Cela peut créer une situation où, si un utilisateur ou une utilisatrice a moins de 2 000 tâches, ces tâches ne sont pas visibles.

**Solution de contournement**

Créez un rapport Affectations personnalisé qui comprend les filtres de mode de texte suivants :

Lorsque l’affectation est AWAITING_ACCEPTANCE, incluez les projets CURRENT|APPROVED :

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

Lorsque l’affectation est ACCEPTED, incluez les projets CURRENT|APPROVED|PLANNING :

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
