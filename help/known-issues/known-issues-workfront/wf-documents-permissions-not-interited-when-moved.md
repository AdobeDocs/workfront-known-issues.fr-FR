---
title: '« Documents : lorsqu’un document est déplacé vers un nouveau projet, les autorisations ne sont pas héritées. »'
description: « Lorsqu’un utilisateur déplace un document vers un autre projet, il n’hérite pas des autorisations de partage de ce dernier. Le document n’est pas partagé avec les utilisateurs avec lesquels le projet est partagé.   »
hidefromtoc: true
source-git-commit: 05592905aecebd7c6f99f4ffa7513630baae5692
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 57%

---


# Documents : lorsqu’un document est déplacé vers un nouveau projet, les autorisations ne sont pas héritées.

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

Lorsqu’un utilisateur déplace un document vers un autre projet, il n’hérite pas des autorisations de partage de ce dernier. Le document n’est pas partagé avec les utilisateurs avec lesquels le projet est partagé.

**Solution :**

1. Accédez à l’objet parent du document tel que Projet, Tâche ou Problème.

1. Supprimez les autorisations héritées de la liste de partage d’objet parent en cliquant sur le &quot;x&quot; en regard des autorisations héritées, puis cliquez sur **[!UICONTROL Enregistrer]**.

1. Ajoutez à nouveau les autorisations héritées en revenant à la liste de partage d’objet parent et en cliquant sur **[!UICONTROL Annuler]** en regard des autorisations héritées, cliquez sur **[!UICONTROL Enregistrer]**.

Vous pouvez également prendre note de l’ID du document (qui se trouve dans l’URL de la page Détails du document) et contacter le service clientèle de Workfront.

_Premier signalement le 6 janvier 2023._

