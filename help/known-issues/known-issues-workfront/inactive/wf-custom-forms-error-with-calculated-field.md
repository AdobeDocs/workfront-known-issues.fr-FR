---
title: 'Formulaires personnalisés : erreur Oups lors de la configuration d’un champ calculé'
description: Lorsqu’un utilisateur crée ou modifie le champ calculé d’un formulaire personnalisé et inclut un champ personnalisé dans l’expression du champ calculé, l’expression est considérée comme non valide. Le bouton Enregistrer est désactivé et l’utilisateur ou l’utilisatrice ne peut pas quitter le champ personnalisé. De plus, l’utilisateur ou l’utilisatrice voit un message Oups sous le champ.
feature: Custom Forms
exl-id: e499c680-2fdf-40cb-a1fa-b0d4ae799ad2
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
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
