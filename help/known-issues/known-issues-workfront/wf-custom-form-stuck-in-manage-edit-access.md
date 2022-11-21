---
title: "Formulaires personnalisés : Les formulaires personnalisés multi-objets requièrent un accès Gérer ou Modifier pour modifier les champs."
description: "Lorsqu’un utilisateur crée un formulaire avec des objets croisés qui autorisent uniquement l’accès à Gérer ou à Modifier, puis supprime ce type d’objet, le formulaire personnalisé continue d’exiger l’accès à Gérer ou Modifier pour modifier les champs. Il n’existe aucune indication visuelle indiquant que les champs requièrent l’accès Gérer ou Modifier, et qu’il n’existe aucun moyen de réinitialiser le formulaire."
hidefromtoc: true
source-git-commit: be498327ea7bb2a49be0fc65e53806ddb217aa8c
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 2%

---


# Formulaires personnalisés : Les formulaires personnalisés multi-objets requièrent [!UICONTROL Gérer] ou [!UICONTROL Modifier] accès aux champs d&#39;édition

>[!NOTE]
>
>Ce problème a été résolu.

Lorsqu’un utilisateur crée un formulaire avec des croix d’objets qui autorisent uniquement [!UICONTROL Gérer] ou [!UICONTROL Modifier] puis supprime ce type d’objet, le formulaire personnalisé continue d’exiger [!UICONTROL Gérer] ou [!UICONTROL Modifier] accès pour modifier les champs. Il n’existe aucune indication visuelle indiquant que les champs requièrent l’accès Gérer ou Modifier, et qu’il n’existe aucun moyen de réinitialiser le formulaire.

**Solution**

1. Ajoutez un saut de section au formulaire avec les valeurs par défaut si vous renseignez avec .
2. Déplacez le saut de section en haut du formulaire.
3. Enregistrez le formulaire.
4. Supprimez le saut de section ajouté et réenregistrez le formulaire.

_Premier signalement le 9 novembre 2022._

