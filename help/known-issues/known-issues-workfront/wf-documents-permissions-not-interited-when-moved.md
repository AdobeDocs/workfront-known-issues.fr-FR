---
title: '"Documents : Les autorisations ne sont pas héritées lorsqu’un document est déplacé vers un nouveau projet.'
description: '''Lorsqu’un utilisateur déplace un document vers un autre projet, il n’hérite pas des autorisations de partage de ce dernier. Le document n’est pas partagé avec les utilisateurs et utilisatrices qui ont le projet partagé. »'
hidefromtoc: true
exl-id: 56dfaf55-7438-4569-b9a1-b62fbdd3f4d9
source-git-commit: 17906db6aadc416c8be01e60d1b796143c97c061
workflow-type: tm+mt
source-wordcount: '179'
ht-degree: 92%

---

# Documents : lorsqu’un document est déplacé vers un nouveau projet, les autorisations ne sont pas héritées.

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

<!--Valid issue, won't fix.-->

Lorsqu’un utilisateur déplace un document vers un autre projet, il n’hérite pas des autorisations de partage de ce dernier. Le document n’est pas partagé avec les utilisateurs et utilisatrices qui ont le projet partagé.

**Solution :**

1. Accédez à l’objet parent du document tel que Projet, Tâche ou Problème.

1. Supprimez les autorisations héritées de la liste de partage de l’objet parent en cliquant sur le « x » en regard des autorisations héritées, puis cliquez sur **[!UICONTROL Enregistrer]**.

1. Ajoutez à nouveau les autorisations héritées en revenant à la liste de partage de l’objet parent et en cliquant sur **[!UICONTROL Annuler]** en regard des autorisations héritées, puis cliquez sur **[!UICONTROL Enregistrer]**.

Vous pouvez également noter l’ID du document (qui se trouve dans l’URL de la page [!UICONTROL Détails du document]) et contacter le service clientèle de [!DNL Workfront].

_Premier signalement le 6 janvier 2023._
