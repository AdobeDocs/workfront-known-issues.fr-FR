---
title: Mises à jour de maintenance pour Workfront
description: Mises à jour de maintenance pour [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: f736d2d5eef0e77c56f1993ea32c92a4c6f17cb1
workflow-type: tm+mt
source-wordcount: '2227'
ht-degree: 94%

---

# Mises à jour de maintenance pour [!DNL Workfront]

Les mises à jour de maintenance suivantes ont été effectuées en 2023.

>[!NOTE]
>
>Ces mises à jour incluent également d’autres correctifs mineurs ou moins conséquents. L’assistance [!DNL Workfront]vous avertira lorsqu’un problème que vous avez soumis est résolu.

Pour connaître les mises à jour de maintenance antérieures à 2023, consultez les [Mises à jour de maintenance précédentes](#previous-maintenance-updates)

## Mises à jour de mars 2023

+++**(Planifiée) Mise à jour de maintenance du 23 mars 2023**

**[!UICONTROL Résumé] le contenu du panneau est trop large pour le panneau.**

_Documents_

« Lorsqu’un utilisateur ou une utilisatrice consulte le panneau [!UICONTROL Résumé] pour un document, le contenu est trop large pour être affiché dans le panneau. » Le panneau comporte désormais une barre de défilement horizontale et l’utilisateur doit faire défiler horizontalement pour voir le [!UICONTROL Résumé] contenu du panneau. Le problème est dû au fait que le nom de fichier du document ne s’ajuste pas. Ce problème est limité aux fichiers dont le nom comporte une extension de fichier HTML.

+++

+++**Mise à jour de maintenance le 16 mars 2023**

**Éléments de liste de contrôle non copiés lors de la copie d’une carte**

_Panoramas_

Lors de la copie d’une carte ad hoc (les cartes connectées ne peuvent pas être copiées), les éléments de liste de contrôle ne sont pas copiés dans la nouvelle carte.

**Champ personnalisé manquant lorsque le problème est converti en projet**

_Projets_

Lorsqu’un utilisateur ou une utilisatrice convertit un problème en projet à l’aide d’un modèle, un champ personnalisé qui se trouvait sur le problème ne s’affiche pas sur le projet. Ce problème affecte uniquement les personnes hors administration.

**Les messages personnalisés ne s’affichent pas dans les notifications électroniques**

_BAT_

Lorsqu’un utilisateur ou une utilisatrice partage un BAT et ajoute un message personnalisé, ce dernier n’apparaît pas dans l’e-mail de notification envoyé au ou à la destinataire. L’objet est le nom du BAT et le message n’apparaît pas dans l’e-mail.

+++

+++**Mise à jour de maintenance le 9 mars 2023**

**Le niveau d’accès n’est pas attribué lors de la réactivation d’un utilisateur ou d’une utilisatrice**

_Utilisateurs_

Lorsqu’un utilisateur en réactive un autre et tente de lui attribuer un niveau d’accès dans la fenêtre [!UICONTROL Réactiver un utilisateur], le menu déroulant ne s’affiche pas lors de la saisie. Il est donc impossible de sélectionner un niveau d’accès. Si l’utilisateur saisit intégralement un niveau d’accès et enregistre, il n’est pas attribué à l’utilisateur réactivé.

**Enregistrez le brouillon d’un commentaire dans le [!DNL Goals] area**

_[!DNL Workfront Goals]_

Maintenant, lorsque vous quittez le [!UICONTROL Mises à jour] page d’un objectif lors de la composition d’un message, le message est conservé lorsque vous revenez en arrière. Avant cette mise à jour, le commentaire non envoyé aurait été supprimé.

+++

+++**Mise à jour de maintenance le 2 mars 2023**

**Impossible d’ajouter des cartes lors de l’application du regroupement**

_Panoramas_

Lorsqu’un utilisateur ou une utilisatrice consulte un panorama comportant un regroupement et tente d’ajouter une carte, il ou elle ne peut saisir que le nom de la carte. Les autres champs de la carte sont désactivés, y compris le bouton [!UICONTROL Enregistrer].

Si l’utilisateur ou l’utilisatrice modifie le regroupement pour le définir sur [!UICONTROL Aucun], le problème persiste. Pour pouvoir à nouveau ajouter une carte, modifiez la valeur du regroupement sur [!UICONTROL Aucun], puis actualisez la page.

**Cartes connectées non ajoutées aux colonnes basées sur le statut**

_Panoramas_

Même si des politiques de colonne sont appliquées pour le statut, de nouvelles cartes connectées apparaissent dans la colonne tout à gauche et non dans la colonne correspondant à leur statut.


**Le lien vers un commentaire redirige vers la page [!UICONTROL Détails]**

_Mises à jour_

Lorsqu’un utilisateur suit un lien vers un commentaire sur un objet dans Workfront, le flux de mise à jour se charge brièvement, puis l’utilisateur est redirigé vers la zone [!UICONTROL Détails] de l’objet. Cela peut se produire si l’utilisateur clique sur le lien d’un e-mail ou s’il le colle dans son navigateur.

Actuellement, seuls les objets Document sont touchés par ce problème.

**Le résumé d’impression ne se charge pas**

_[!UICONTROL Workfront Proof]_

Lorsqu’un utilisateur ou une utilisatrice tente de charger la page de résumé d’impression, celle-ci semble être en cours de chargement, mais ne se charge jamais.

+++

## Mises à jour de février 2023

+++**Mise à jour de maintenance du 23 février 2023**

**Le lien vers un commentaire redirige vers la page [!UICONTROL Détails]**

_Mises à jour_

Lorsqu’un utilisateur suit un lien vers un commentaire sur un objet dans Workfront, le flux de mise à jour se charge brièvement, puis l’utilisateur est redirigé vers la zone [!UICONTROL Détails] de l’objet. Cela peut se produire si l’utilisateur clique sur le lien d’un e-mail ou s’il le colle dans son navigateur.

Actuellement, seuls les objets Document sont touchés par ce problème.

**L’utilisateur ou l’utilisatrice ne peut pas modifier ses propres paramètres de notification**

_Utilisateurs_

Lorsqu’un utilisateur ou une utilisatrice disposant d’une licence [!UICONTROL Employé] tente de modifier ses propres paramètres de notification, les options du menu [!UICONTROL Notifications] ne sont pas visibles dans la fenêtre [!UICONTROL Modifier] et l’utilisateur ou l’utilisatrice ne peut pas modifier ses paramètres.

+++

+++**Mise à jour de maintenance du 16 février 2023**

**Affectations de plusieurs équipes sur les panoramas**

_Panoramas_

Vous pouvez désormais affecter plusieurs équipes à une tâche ou à un problème sur un panorama, ainsi qu’au panorama lui-même.

**Augmentation du délai d’expiration des cartes**

_Panoramas_

Le délai d’expiration des cartes passe de 4 semaines/30 jours à 8 semaines/60 jours.

**La désactivation planifiée ne désactive pas l’utilisateur.**

_Utilisateurs_

Lorsque la désactivation d’un utilisateur est planifiée et que la date et l’heure programmées sont passées, il n’est pas désactivé.

+++

+++**Mise à jour de maintenance du 9 février 2023**

Champ **[!UICONTROL Points de l’histoire] ajouté aux listes et rapports de tâches et de problèmes**

_Rapports_

Le champ [!UICONTROL Points de l’histoire] est désormais disponible. Vous pouvez l’ajouter aux listes et aux rapports pour les tâches ou les problèmes. Il s’agit d’un champ de formulaire libre modifiable qui n’est pas lié au nombre d’heures prévues ou aux affectations d’équipe.

+++

+++**Mise à jour de maintenance du 8 février 2023**

**Bouton de filtre dans la colonne d’entrée**

_Panoramas_

La colonne d’entrée d’un panorama comprend désormais un bouton **[!UICONTROL Ajouter un filtre]** lorsqu’elle est vide et qu’aucun filtre n’a été créé. Le bouton ouvre la zone de configuration, dans laquelle vous pouvez ajouter des filtres pour importer des tâches et des problèmes dans la colonne d’entrée.

+++

+++**Mise à jour de maintenance du 2 février 2023**

Icône **[!UICONTROL Panoramas] dans le [!UICONTROL Menu principal] par défaut**

_Panoramas_

L’icône [!UICONTROL Panoramas] s’affiche maintenant dans le [!UICONTROL Menu principal] pour les utilisateurs qui ne disposent pas d’un modèle de disposition. Les panoramas sont également inclus par défaut dans le menu principal pour tous les nouveaux modèles de disposition créés. Les modèles existants n’ont pas été modifiés.

**Impossible d’enregistrer les modèles d’e-mail**

_Configuration_

Lorsqu’un utilisateur ou une utilisatrice tente de créer ou de modifier un modèle d’e-mail, le bouton [!UICONTROL Enregistrer] ne répond pas et l’utilisateur ou l’utilisatrice ne peut pas enregistrer le modèle.

+++

## Mises à jour de janvier 2023

+++**Mise à jour de maintenance du 30 janvier 2023**

**Raccourcis clavier ajoutés pour les actions courantes sur les feuilles de temps**

_Feuilles de temps_

Nous avons ajouté les raccourcis clavier suivants pour certaines actions courantes sur les feuilles de temps :

* Ajouter une ligne (Cmd + Option + Touche « + » / Ctrl + Option + Touche « + »)
* Supprimer une ligne (Cmd + Option + Touche « - » / Ctrl + Option + Touche « - »)
* Épingler ou désépingler un élément de travail (Option + P / Option + P)
* Ouvrir un commentaire (Maj + F2 / Maj + F2)
* Enregistrer un commentaire (Cmd + Entrée / Ctrl + Entrée)
* Développer (Maj + Option + Flèche du haut / Maj + Alt + Flèche du haut)
* Réduire (Maj + Option + Flèche du bas / Maj + Alt + Flèche du bas)

La zone où ces actions sont effectuées doit être mise en surbrillance pour qu’elles fonctionnent correctement.

**Nouvelles icônes d’informations pour les feuilles de temps, les profils de feuille de temps et les préférences de feuille de temps**

_Feuilles de temps_

>[!NOTE]
>
>Cette mise à jour est sortie dans l’environnement de prévisualisation le 3 novembre 2022 et passe désormais en production.

Nous avons ajouté plusieurs icônes d’informations pour les paramètres suivants :

* La case « [!UICONTROL Peut modifier l’heure] » lors de la création ou de la modification d’une feuille de temps ou d’un profil de feuille de temps indique, lorsqu’elle est cochée, que les approbateurs peuvent également envoyer, rouvrir ou modifier la feuille de temps, sauf si votre administrateur restreint ces actions dans les [!UICONTROL Préférences de la feuille de temps] de la section [!UICONTROL Configuration].
* L’option « [!UICONTROL Limiter la modification de la feuille de temps aux propriétaires et aux administrateurs] » dans la zone [!UICONTROL Préférences de la feuille de temps et d’heure] de la section [!UICONTROL Configuration] permet d’indiquer, lorsque cette case est décochée, que les utilisateurs suivants peuvent également modifier les feuilles de temps : les utilisateurs disposant d’un accès administratif aux feuilles de temps et d’heure, les approbateurs de feuilles de temps autorisés à modifier l’heure et les gestionnaires des propriétaires de feuilles de temps.

Notez que le fonctionnement de ces paramètres n’a pas été modifié et que seules des icônes d’informations ont été ajoutées pour clarifier leur utilisation.

+++

+++**Mise à jour de maintenance du 26 janvier 2023**

**Erreur de soumission d’une demande depuis [!DNL Outlook]**

_Intégrations_

Lorsque l’utilisateur tente de soumettre une demande comprenant des pièces jointes dans un e-mail [!DNL Outlook], une ou plusieurs des pièces jointes ne se chargent pas et le message d’erreur suivant apparaît :

« [!UICONTROL L’erreur suivante s’est produite : Le fichier contenant l’identificateur xxxx n’existe pas.] »

Cela se produit uniquement lorsqu’une affectation est effectuée pour la nouvelle demande, soit au moyen de la file d’attente des demandes, soit manuellement lors de la création de la demande.

**Nouvelle version du lecteur de vérification pour bureau**

_Vérification_

Pour résoudre un problème de blocage du lecteur de vérification pour bureau, nous en avons déployé une nouvelle version. Les utilisateurs ou utilisatrices qui disposent déjà du lecteur de vérification pour bureau recevront une notification automatique de cette mise à jour.

Les utilisateurs ou utilisatrices peuvent également afficher manuellement la dernière version. Pour plus d’informations, consultez [Installation du lecteur de vérification pour bureau](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=fr).

* Version précédente : 2.1.19
* Nouvelle version : 2.1.20

**L’utilisateur ne peut pas modifier ses propres paramètres utilisateur**

_Utilisateurs_

Lorsqu’un utilisateur ou une utilisatrice sous licence de Travail, Révision ou Demande tente de modifier ses propres paramètres utilisateur, la fenêtre contextuelle qui s’affiche est vide et l’utilisateur ou l’utilisatrice ne peut pas apporter de modifications. Pour quitter la fenêtre contextuelle, l’utilisateur ou l’utilisatrice doit actualiser la page.

+++

+++**Mise à jour de maintenance du 19 janvier 2023**

**Les filtres de colonne d’entrée peuvent désormais être partagés.**

_Panoramas_

Lors de la publication de la fonctionnalité Colonne d’entrée sur les tableaux, les filtres de configuration n’étaient visibles que par la personne qui les avait créés. Le créateur ou la créatrice des filtres peut maintenant les partager avec d’autres utilisateurs, utilisatrices ou équipes.

**Fonctionnalité Épingle disponible dans le menu [!UICONTROL Plus]**

_Navigation_

Les fonctionnalités suivantes sont désormais disponibles dans le menu [!UICONTROL Plus] pour les épingles, dans l’environnement de production :

* Renommer des épingles
* Réorganisation des épingles dans le menu [!UICONTROL Plus]
* Retrait d’une épingle du menu [!UICONTROL Plus] (en procédant de la sorte, la dernière épingle de la barre de navigation supérieure est déplacée vers le menu [!UICONTROL Plus])

+++

+++**Mise à jour de maintenance du 18 janvier 2023**

**Les expressions avec des caractères génériques ne sont pas valides dans les champs personnalisés**.

_Formulaires personnalisés_

Lorsqu’un utilisateur ou une utilisatrice utilise un caractère générique tel que \$$TODAY ou $$NOW avec un modificateur (tel que « -30d ») dans un champ personnalisé, le programme de validation ne reconnaît pas le caractère générique comme étant valide. Les caractères génériques sans modificateurs sont considérés comme valides.

L’**[!UICONTROL Équilibreur de charge de travail] affiche les heures non associées à un projet, une tâche ou un problème**.

_[!UICONTROL Équilibreur de charge de travail]_

Lorsqu’un utilisateur ou une utilisatrice consulte l’[!UICONTROL Équilibreur de charge de travail], il voit les heures enregistrées pour un utilisateur ou une utilisatrice qui ne sont associées à aucun projet, tâche ou problème, et qui ne sont pas non plus enregistrées en tant qu’heures [!UICONTROL Générales]. Ces heures peuvent s’afficher uniquement dans la vue 4 semaines ou 6 semaines.

+++

+++Mise à jour de maintenance pour **[!DNL Adobe Workfront Fusion] (correctif) le 12 janvier 2023**

**Erreurs 404 sur les modules [!DNL Workfront]**

_Workfront Fusion_

Lorsqu’un scénario s’exécute, un module [!DNL Workfront] renvoie une erreur 404.

Les modules suivants sont concernés :

* [!UICONTROL Lire un enregistrement]

+++

+++**Mise à jour de maintenance (correctif) le 12 janvier 2023**

**Erreur « [!UICONTROL Oups] » lors de la configuration d’un champ calculé**

_Formulaires personnalisés_

Lorsqu’un utilisateur crée ou modifie le champ calculé d’un formulaire personnalisé et inclut un champ personnalisé dans l’expression du champ calculé, l’expression est considérée comme non valide. Le bouton [!UICONTROL Enregistrer] est désactivé et l’utilisateur ne peut pas quitter le champ personnalisé. De plus, l’utilisateur voit le message suivant sous le champ :

« [!UICONTROL Oups ! Un problème est survenu. Contactez Workfront pour nous aider à comprendre l’erreur et y remédier.] »

La suppression du champ personnalisé de l’expression permet à l’utilisateur d’enregistrer et de quitter le champ.

**Impossible de définir les niveaux d’accès**

_Utilisateurs_

Lorsqu’un utilisateur ou une utilisatrice tente de modifier le niveau d’accès d’un autre utilisateur ou d’une autre utilisatrice, les niveaux d’accès sont grisés et l’utilisateur ou l’utilisatrice ne peut pas les modifier. Le problème se produit également si l’utilisateur ou l’utilisatrice qui tente d’effectuer la modification est un administrateur ou une administratrice système.

+++

+++**Mise à jour de maintenance du 12 janvier 2023**

**Formulaires Ctrl+F ou Cmd+F ne fonctionne pas comme prévu dans les champs de liste déroulante**

_Formulaires personnalisés_

Lorsqu’un utilisateur remplit un formulaire personnalisé et effectue une recherche dans une liste déroulante à l’aide de Ctrl+F ou Cmd+F, puis tente d’accéder à l’instance suivante de cette recherche, la liste déroulante revient en haut de la liste plutôt que d’accéder à l’instance suivante de la recherche. Cela se produit lorsqu’une liste déroulante est définie pour autoriser plusieurs sélections.

L’écran « **[!UICONTROL Modifier le rapport] » est vide**

_Rapports_

Lorsqu’un utilisateur consulte un rapport et tente de le modifier, il est redirigé vers une page vide et ne peut pas le modifier.

**Les tâches mises en avant ne restent pas mises en avant**

_Tâches_

Lorsqu’un utilisateur consulte une liste de tâches et met en avant une tâche, la tâche revient immédiatement à son état d’origine (mise en retrait).

+++

+++**Mise à jour de maintenance du 5 janvier 2023**

**Fonctionnalité Épingle disponible dans le menu [!UICONTROL Plus]**

_Navigation_

Les fonctionnalités suivantes sont désormais disponibles dans le menu [!UICONTROL Plus] pour les épingles, dans l’environnement de prévisualisation uniquement :

* Renommer des épingles
* Réorganisation des épingles dans le menu [!UICONTROL Plus]
* Retrait d’une épingle du menu [!UICONTROL Plus] (en procédant de la sorte, la dernière épingle de la barre de navigation supérieure est déplacée vers le menu [!UICONTROL Plus])

**Suppression de la restriction du groupe du projet empêchant l’ajout d’utilisateurs à l’équipe du projet**

_Équipes_

Nous avons supprimé la restriction qui obligeait les utilisateurs devant être ajoutés à une équipe de projet à faire partie du groupe associé au projet. Vous pouvez désormais ajouter n’importe quel utilisateur actif à une équipe de projet, quels que soient les groupes auxquels il appartient.

**Nouvelles icônes d’informations pour les feuilles de temps, les profils de feuille de temps et les préférences de feuille de temps**

>[!NOTE]
>
>Cette mise à jour de est sortie dans l’environnement de prévisualisation le 3 novembre 2022 et passe désormais en production

_Workfront_

Nous avons ajouté plusieurs icônes d’informations pour les paramètres suivants :

* La case « Peut modifier l’heure » lors de la création ou de la modification d’une feuille de temps ou d’un profil de feuille de temps indique, lorsqu’elle est cochée, que les approbateurs peuvent également envoyer, rouvrir ou modifier la feuille de temps, sauf si votre administrateur restreint ces actions dans les « Préférences de la feuille de temps » de la section « Configuration ».
* « Limiter la modification de la feuille de temps aux propriétaires et aux administrateurs » dans la zone « Préférences de la feuille de temps et d’heure » de la section « Configuration » pour indiquer que, lorsque cette case est décochée, les utilisateurs suivants peuvent également modifier les feuilles de temps : les utilisateurs disposant d’un accès administratif aux feuilles de temps et d’heure, les approbateurs de feuilles de temps autorisés à modifier l’heure et les gestionnaires des propriétaires de feuilles de temps.

Notez que le fonctionnement de ces paramètres n’a pas été modifié et que seules des icônes d’informations ont été ajoutées pour clarifier leur utilisation.

+++

## Mises à jour de maintenance précédentes

Les informations relatives aux mises à jour de maintenance précédentes sont disponibles ici :

* [[!DNL Workfront] Archive des mises à jour de maintenance - 2022](2022-updates.md)
* [[!DNL Workfront] Archive des mises à jour de maintenance - 2021](2021-updates.md)
