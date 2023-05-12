---
title: '« Formulaires personnalisés : la modification des champs des formulaires personnalisés interobjet exige un accès de niveau Gérer ou Modifier »'
description: Lorsque l’utilisateur crée un formulaire interobjet qui autorise uniquement un accès de niveau Gérer ou Modifier, puis supprime ce type d’objet, le formulaire personnalisé continue d’exiger un accès de niveau Gérer ou Modifier pour modifier les champs. Rien n’indique que les champs exigent un accès de niveau Gérer ou Modifier, et il est impossible de réinitialiser le formulaire.
hidefromtoc: true
exl-id: 3f7ad4f5-1480-4514-8543-7e699743a8ef
source-git-commit: 35fb85acf0c4b8675c3b6dad72c373ac6192055d
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 100%

---

# Formulaires personnalisés : la modification des champs des formulaires personnalisés interobjet exige un accès de niveau [!UICONTROL Gérer] ou [!UICONTROL Modifier]

<!--Won't fix, live for workaround-->

>[!NOTE]
>
>Ce problème a été résolu.

Lorsque l’utilisateur crée un formulaire interobjet qui autorisent uniquement un accès de niveau [!UICONTROL Gérer] ou [!UICONTROL Modifier], puis supprime ce type d’objet, le formulaire personnalisé continue d’exiger un accès de niveau [!UICONTROL Gérer] ou [!UICONTROL Modifier] pour modifier les champs. Rien n’indique que les champs exigent un accès de niveau Gérer ou Modifier, et il est impossible de réinitialiser le formulaire.

**Solution**

1. Ajouter un saut de section au formulaire avec les valeurs renseignées par défaut.
2. Déplacer le saut de section en haut du formulaire.
3. Enregistrer le formulaire.
4. Supprimer le saut de section ajouté et enregistrer de nouveau le formulaire.

_Premier signalement le 9 novembre 2022._
