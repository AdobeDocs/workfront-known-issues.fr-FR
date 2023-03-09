---
title: '« Documents : lorsqu’un document est déplacé vers un nouveau projet, les autorisations ne sont pas héritées. »'
description: « Lorsqu’un utilisateur déplace un document vers un autre projet, il n’hérite pas des autorisations de partage de ce dernier. Le document n’est pas partagé avec les utilisateurs avec lesquels le projet est partagé.   »
hidefromtoc: true
source-git-commit: ca969341423e373a94faa677729fc2dccd9453d6
workflow-type: tm+mt
source-wordcount: '179'
ht-degree: 57%

---


# Documents : lorsqu’un document est déplacé vers un nouveau projet, les autorisations ne sont pas héritées.

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

<!--This issue has been closed as won't fix, but no reason.-->

Lorsqu’un utilisateur déplace un document vers un autre projet, il n’hérite pas des autorisations de partage de ce dernier. Le document n’est pas partagé avec les utilisateurs avec lesquels le projet est partagé.

**Solution :**

1. Accédez à l’objet parent du document tel que Projet, Tâche ou Problème.

1. Supprimez les autorisations héritées de la liste de partage d’objet parent en cliquant sur le &quot;x&quot; en regard des autorisations héritées, puis cliquez sur **[!UICONTROL Enregistrer]**.

1. Ajoutez à nouveau les autorisations héritées en revenant à la liste de partage d’objet parent et en cliquant sur **[!UICONTROL Annuler]** en regard des autorisations héritées, cliquez sur **[!UICONTROL Enregistrer]**.

Vous pouvez également prendre note de l’ID du document (figurant dans l’URL de la variable [!UICONTROL Détails du document] et contacter [!DNL Workfront] assistance clientèle.

_Premier signalement le 6 janvier 2023._

