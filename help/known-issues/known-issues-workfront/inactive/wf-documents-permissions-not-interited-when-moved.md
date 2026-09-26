---
title: 'Documents : lorsqu’un document est déplacé vers un nouveau projet, les autorisations ne sont pas héritées.'
description: 'Lorsqu’un utilisateur déplace un document vers un autre projet, il n’hérite pas des autorisations de partage de ce dernier. Le document n’est pas partagé avec les utilisateurs et utilisatrices qui ont le projet partagé. '
feature: Digital Content and Documents
exl-id: 56dfaf55-7438-4569-b9a1-b62fbdd3f4d9
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
    internal-label: Digital content and documents
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '182'
ht-degree: 100%
---
# Documents : lorsqu’un document est déplacé vers un nouveau projet, les autorisations ne sont pas héritées.

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

<!--Won't fix tab: Valid issue, won't fix.-->

Lorsqu’un utilisateur déplace un document vers un autre projet, il n’hérite pas des autorisations de partage de ce dernier. Le document n’est pas partagé avec les utilisateurs et utilisatrices qui ont le projet partagé.

**Solution :**

1. Accédez à l’objet parent du document tel que Projet, Tâche ou Problème.

1. Supprimez les autorisations héritées de la liste de partage de l’objet parent en cliquant sur le « x » en regard des autorisations héritées, puis cliquez sur **[!UICONTROL Enregistrer]**.

1. Ajoutez à nouveau les autorisations héritées en revenant à la liste de partage de l’objet parent et en cliquant sur **[!UICONTROL Annuler]** en regard des autorisations héritées, puis cliquez sur **[!UICONTROL Enregistrer]**.

Vous pouvez également noter l’ID du document (qui se trouve dans l’URL de la page [!UICONTROL Détails du document]) et contacter le service clientèle de [!DNL Workfront].

_Premier signalement le samedi 6 janvier 2023._



<!--CHECK ME - 1 VIEW APRIL-JUNE 2025 (June 11 and 27)-->
