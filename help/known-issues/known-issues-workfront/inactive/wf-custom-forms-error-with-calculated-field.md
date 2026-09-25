---
title: 'Formulaires personnalisés : erreur Oups lors de la configuration d’un champ calculé'
description: Lorsqu’un utilisateur crée ou modifie le champ calculé d’un formulaire personnalisé et inclut un champ personnalisé dans l’expression du champ calculé, l’expression est considérée comme non valide. Le bouton Enregistrer est désactivé et l’utilisateur ou l’utilisatrice ne peut pas quitter le champ personnalisé. De plus, l’utilisateur ou l’utilisatrice voit un message Oups sous le champ.
feature: Custom Forms
exl-id: e499c680-2fdf-40cb-a1fa-b0d4ae799ad2
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: d87de1f9-8e24-4c4d-aa4c-a403075091a1
    internal-label: Custom forms
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 94%
---
# Formulaires personnalisés : erreur « [!UICONTROL Oups] » lors de la configuration d’un champ calculé

<!--Requested: Do not delete without approval from Alex Beach-->

>[!NOTE]
>
>Ce problème a été résolu le 12 janvier 2023.

Lorsqu’un utilisateur ou une utilisatrice crée ou modifie le champ calculé d’un formulaire personnalisé et inclut un champ personnalisé dans l’expression du champ calculé, l’expression est considérée comme non valide. Le bouton [!UICONTROL Enregistrer] est désactivé et l’utilisateur ou l’utilisatrice ne peut pas quitter le champ personnalisé. De plus, l’utilisateur ou l’utilisatrice voit le message suivant sous le champ :

« [!UICONTROL Oups ! Un problème est survenu. Contactez Workfront pour nous aider à comprendre l’erreur et y remédier.] »

La suppression du champ personnalisé de l’expression permet à l’utilisateur d’enregistrer et de quitter le champ.

_Premier signalement le mercredi 11 octobre 2022._
