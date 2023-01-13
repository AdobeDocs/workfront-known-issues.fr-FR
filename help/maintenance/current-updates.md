---
title: Mises à jour de maintenance pour Workfront
description: Mises à jour de maintenance pour [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 62d6d8659079211804d2a270b181272ac7b0eede
workflow-type: tm+mt
source-wordcount: '662'
ht-degree: 63%

---

# Mises à jour de maintenance pour [!DNL Workfront]

Les mises à jour de maintenance suivantes ont été effectuées en 2023.

>[!NOTE]
>
>Ces mises à jour incluent également d’autres correctifs mineurs ou moins conséquents. L’assistance [!DNL Workfront]vous avertira lorsqu’un problème que vous avez soumis est résolu.

Pour connaître les mises à jour de maintenance antérieures à 2023, consultez les [Mises à jour de maintenance précédentes](#previous-maintenance-updates)

## Mises à jour de janvier 2023

+++**[!DNL Adobe Workfront Fusion]Mise à jour de maintenance (correctif) le 12 janvier 2023**

**Erreurs 404 sur [!DNL Workfront] modules**

_Workfront Fusion_

Lorsqu’un scénario s’exécute, un module [!DNL Workfront] renvoie une erreur 404.

Les modules suivants sont concernés :

* [!UICONTROL Lire un enregistrement]

+++

+++**Mise à jour de maintenance (correctif) le 12 janvier 2023**

**&quot;[!UICONTROL Oups]&quot; lors de la configuration d’un champ calculé**

_Formulaires personnalisés_

Lorsqu’un utilisateur crée ou modifie le champ calculé d’un formulaire personnalisé et inclut un champ personnalisé dans l’expression du champ calculé, l’expression est considérée comme non valide. Le bouton [!UICONTROL Enregistrer] est désactivé et l’utilisateur ne peut pas quitter le champ personnalisé. De plus, l’utilisateur voit le message suivant sous le champ :

« [!UICONTROL Oups ! Un problème est survenu. Contactez Workfront pour nous aider à comprendre l’erreur et y remédier.] »

La suppression du champ personnalisé de l’expression permet à l’utilisateur d’enregistrer et de quitter le champ.

**Impossible de définir les niveaux d’accès**

_Utilisateurs_

Lorsqu’un utilisateur tente de modifier le niveau d’accès d’un autre utilisateur, les niveaux d’accès sont grisés et l’utilisateur ne peut pas les modifier. Cela se produit même lorsque l’utilisateur qui tente d’effectuer la modification est un administrateur système.

+++

+++**Mise à jour de maintenance le 12 janvier 2023**

**Ctrl+F ou Cmd+F ne fonctionnent pas comme prévu dans les champs de liste déroulante**

_Formulaires personnalisés_

Lorsqu’un utilisateur remplit un formulaire personnalisé et effectue une recherche dans une liste déroulante à l’aide de Ctrl+F ou Cmd+F, puis tente d’accéder à l’instance suivante de cette recherche, la liste déroulante revient en haut de la liste plutôt que d’accéder à l’instance suivante de la recherche. Cela se produit lorsqu’une liste déroulante est définie pour autoriser plusieurs sélections.

**[!UICONTROL Modifier le rapport] écran vide**

_Rapports_

Lorsqu’un utilisateur consulte un rapport et tente de le modifier, il est redirigé vers une page vide et ne peut pas le modifier.

**Les tâches en retrait ne restent pas en retrait**

_Tâches_

Lorsqu’un utilisateur consulte une liste de tâches et met une tâche en retrait, la tâche revient immédiatement à son état d’origine (obsolète).

+++

+++**Mise à jour de maintenance le 5 janvier 2023**

**Fonctionnalité d’épingle disponible dans [!UICONTROL Plus] menu**

_Navigation_

Les fonctionnalités suivantes sont désormais disponibles dans la [!UICONTROL Plus] pour les pin&#39;s, dans l’environnement Aperçu uniquement :

* Renommer les pin
* Réorganisation des pin’s dans [!UICONTROL Plus] menu
* Déplacement d’une épingle du [!UICONTROL Plus] (lorsque vous procédez de la sorte, la dernière épingle de la barre de navigation supérieure est déplacée vers le [!UICONTROL Plus] menu)

**Suppression de la limitation du groupe de projets de l’ajout d’utilisateurs à l’équipe de projet.**

_Équipes_

Nous avons supprimé la limitation qui obligeait les utilisateurs qui doivent être ajoutés à une équipe de projet à faire partie du groupe associé au projet. Vous pouvez désormais ajouter n’importe quel utilisateur principal à une équipe de projet, quels que soient les groupes auxquels il appartient.

**Nouvelles icônes d’informations pour les feuilles de temps, les profils de feuille de temps et les préférences de la feuille de temps**

>[!NOTE]
>
>Cette mise à jour a été publiée dans l’environnement Aperçu le 3 novembre 2022 et est désormais disponible dans l’environnement de production.

_Workfront_

Nous avons ajouté plusieurs icônes d’informations pour les paramètres suivants :

* La case « Peut modifier l’heure » lors de la création ou de la modification d’une feuille de temps ou d’un profil de feuille de temps indique, lorsqu’elle est cochée, que les approbateurs peuvent également envoyer, rouvrir ou modifier la feuille de temps, sauf si votre administrateur restreint ces actions dans les « Préférences de la feuille de temps » de la section « Configuration ».
* « Limiter la modification de la feuille de temps aux propriétaires et aux administrateurs » dans la zone « Préférences de la feuille de temps et d’heure » de la section « Configuration » pour indiquer que, lorsque cette case est décochée, les utilisateurs suivants peuvent également modifier les feuilles de temps : les utilisateurs disposant d’un accès administratif aux feuilles de temps et d’heure, les approbateurs de feuilles de temps autorisés à modifier l’heure et les gestionnaires des propriétaires de feuilles de temps.

Notez que la fonctionnalité de ces paramètres n’a pas été modifiée et que seules des icônes d’informations ont été ajoutées pour clarifier la fonction des paramètres.

+++

## Mises à jour de maintenance précédentes

Les informations relatives aux mises à jour de maintenance précédentes sont disponibles ici :

* [[!DNL Workfront] Archive des mises à jour de maintenance - 2022](2022-updates.md)
* [[!DNL Workfront] Archive des mises à jour de maintenance - 2021](2021-updates.md)
