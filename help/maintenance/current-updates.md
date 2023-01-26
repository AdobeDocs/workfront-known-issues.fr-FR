---
title: Mises à jour de maintenance pour Workfront
description: Mises à jour de maintenance pour [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 441062239d07963454e1cc57e4dff54e0c5a06bb
workflow-type: tm+mt
source-wordcount: '1071'
ht-degree: 67%

---

# Mises à jour de maintenance pour [!DNL Workfront]

Les mises à jour de maintenance suivantes ont été effectuées en 2023.

>[!NOTE]
>
>Ces mises à jour incluent également d’autres correctifs mineurs ou moins conséquents. L’assistance [!DNL Workfront]vous avertira lorsqu’un problème que vous avez soumis est résolu.

Pour connaître les mises à jour de maintenance antérieures à 2023, consultez les [Mises à jour de maintenance précédentes](#previous-maintenance-updates)

## Mises à jour de janvier 2023

+++**Mise à jour de maintenance le 26 janvier 2023**

**Erreur lors de l’envoi d’une requête depuis[!DNL Outlook]**

_Intégrations_

Lorsque l’utilisateur tente de soumettre une demande comprenant des pièces jointes dans un e-mail [!DNL Outlook], une ou plusieurs des pièces jointes ne se chargent pas et le message d’erreur suivant apparaît :

&quot;[!UICONTROL L’erreur suivante s’est produite : Le fichier contenant l’identificateur xxxx n’existe pas.]&quot;

Cela se produit uniquement lorsqu’une affectation est effectuée pour la nouvelle demande, soit au moyen de la file d’attente des demandes, soit manuellement lors de la création de la demande.

**Nouvelle version de la visionneuse de vérification de l’appli de bureau**

_Relecture_

Pour résoudre un problème de blocage dans la visionneuse de vérification de l’appli de bureau, nous avons déployé une nouvelle version de la visionneuse de vérification de l’appli de bureau. Les utilisateurs qui disposent déjà de la visionneuse de vérification de l’appli de bureau seront automatiquement informés de cette mise à jour.

Les utilisateurs peuvent également afficher manuellement la dernière version. Pour plus d’informations, voir [Installation de la visionneuse de vérification de l’appli de bureau](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=en).

* Version précédente : 2.1.19
* Nouvelle version : 2.1.20

**L’utilisateur ne peut pas modifier son propre paramètre d’utilisateur.**

_Utilisateurs_

Lorsqu’un utilisateur disposant d’une licence de travail, de révision ou de requête tente de modifier ses propres paramètres utilisateur, la fenêtre contextuelle qui s’ouvre est vide et l’utilisateur ne peut pas apporter de modifications. Pour quitter la fenêtre contextuelle, l’utilisateur doit actualiser la page.

+++

+++**Mise à jour de maintenance le 19 janvier 2023**

**Les filtres de colonne d’entrée peuvent désormais être partagés.**

_Panoramas_

Lorsque la fonction Colonne d’ingestion a été diffusée sur les panoramas, les filtres pour configurer la colonne d’ingestion n’étaient visibles que par la personne qui les avait créés. Désormais, le créateur peut partager les filtres avec d’autres utilisateurs ou équipes.

**Fonctionnalité Épingle disponible dans le menu [!UICONTROL Plus]**

_Navigation_

Les fonctionnalités suivantes sont désormais disponibles dans la [!UICONTROL Plus] pour les pin’s, dans l’environnement de production :

* Renommer des épingles
* Réorganisation des épingles dans le menu [!UICONTROL Plus]
* Retrait d’une épingle du menu [!UICONTROL Plus] (en procédant de la sorte, la dernière épingle de la barre de navigation supérieure est déplacée vers le menu [!UICONTROL Plus])

+++

+++**Mise à jour de maintenance le 18 janvier 2023**

**Les expressions avec des caractères génériques ne sont pas valides dans les champs personnalisés**

_Formulaires personnalisés_

Lorsqu’un utilisateur utilise un caractère générique tel que \$$TODAY ou $$NOW avec un modificateur (tel que &quot;-30d&quot;) dans un champ personnalisé, le programme de validation n’accepte pas le caractère générique comme valide. Les caractères génériques sans modificateurs sont considérés comme valides.

**[!UICONTROL Équilibreur de charge de travail] affiche les heures non associées à un projet/une tâche/un problème**

_[!UICONTROL Équilibreur de charge de travail]_

Lorsqu’un utilisateur affiche la variable [!UICONTROL Équilibreur de charge de travail], ils voient les heures enregistrées pour un utilisateur qui n’est associé à aucun projet, tâche ou problème, et ils ne sont pas enregistrés en tant que [!UICONTROL Général] heures. Ces heures peuvent s’afficher uniquement en mode 4 semaines ou 6 semaines.

+++

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

**Formulaires Ctrl+F ou Cmd+F ne fonctionne pas comme prévu dans les champs de liste déroulante**

_Formulaires personnalisés_

Lorsqu’un utilisateur remplit un formulaire personnalisé et effectue une recherche dans une liste déroulante à l’aide de Ctrl+F ou Cmd+F, puis tente d’accéder à l’instance suivante de cette recherche, la liste déroulante revient en haut de la liste plutôt que d’accéder à l’instance suivante de la recherche. Cela se produit lorsqu’une liste déroulante est définie pour autoriser plusieurs sélections.

l’écran « **[!UICONTROL Modifier le rapport] » est vide**

_Rapports_

Lorsqu’un utilisateur consulte un rapport et tente de le modifier, il est redirigé vers une page vide et ne peut pas le modifier.

**Les tâches mises en avant ne restent pas mises en avant**

_Tâches_

Lorsqu’un utilisateur consulte une liste de tâches et met en avant une tâche, la tâche revient immédiatement à son état d’origine (mise en retrait).

+++

+++**Mise à jour de maintenance le 5 janvier 2023**

**Fonctionnalité Épingle disponible dans le menu [!UICONTROL Plus]**

_Navigation_

Les fonctionnalités suivantes sont désormais disponibles dans le menu [!UICONTROL Plus] pour les épingles, dans l’environnement de prévisualisation uniquement :

* Renommer des épingles
* Réorganisation des épingles dans le menu [!UICONTROL Plus]
* Retrait d’une épingle du menu [!UICONTROL Plus] (en procédant de la sorte, la dernière épingle de la barre de navigation supérieure est déplacée vers le menu [!UICONTROL Plus])

**Suppression de la restriction du groupe du projet empêchant l’ajout d’utilisateurs à l’équipe du projet**

_Équipes_

Nous avons supprimé la restriction qui obligeait les utilisateurs devant être ajoutés à une équipe de projet à faire partie du groupe associé au projet. Vous pouvez désormais ajouter n’importe quel utilisateur actif à une équipe de projet, quels que soient les groupes auxquels il appartient.

**Nouvelles icônes d’informations pour les feuilles de temps, les profils de feuille de temps et les préférences de la feuille de temps**

>[!NOTE]
>
>Cette mise à jour de est sortie dans l’environnement de prévisualisation le 3 novembre 2022 et passe désormais en production

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
