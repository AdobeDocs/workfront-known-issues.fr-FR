---
title: Mises à jour de maintenance pour Workfront
description: Mises à jour de maintenance pour [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: a21275163de2c7de2201971b125703f40b9983b8
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Mises à jour de maintenance pour [!DNL Workfront]

Les mises à jour de maintenance suivantes ont été effectuées en 2023.

>[!NOTE]
>
>Ces mises à jour incluent également d’autres correctifs mineurs ou moins conséquents. L’assistance [!DNL Workfront]vous avertira lorsqu’un problème que vous avez soumis est résolu.

Pour connaître les mises à jour de maintenance antérieures à 2023, consultez les [Mises à jour de maintenance précédentes](#previous-maintenance-updates)

## Mises à jour de février 2023

+++**Mise à jour de maintenance le 23 février 2023**

**Lien vers un commentaire redirige vers [!UICONTROL Détails] page**

_Mises à jour_

Lorsqu’un utilisateur suit un lien vers un commentaire sur un objet dans Workfront, le flux de mise à jour se charge brièvement, puis l’utilisateur est redirigé vers le [!UICONTROL Détails] zone. Cela peut se produire si l’utilisateur clique sur le lien d’un courrier électronique ou colle le lien dans son navigateur.

Cela affecte uniquement les objets Document actuellement.

**L’utilisateur ne peut pas modifier ses propres paramètres de notification**

_Utilisateurs_

Lorsqu’un utilisateur dispose d’un [!UICONTROL Worker] la licence tente de modifier ses propres paramètres de notification, [!UICONTROL Notifications] Les options ne sont pas visibles dans la variable [!UICONTROL Modifier] et l’utilisateur ne peut pas modifier les paramètres.

+++

+++**Mise à jour de maintenance le 16 février 2023**

**Affectations d’équipes multiples sur les panoramas**

_Tableaux_

Vous pouvez désormais affecter plusieurs équipes à une tâche ou à un problème sur un panorama, ainsi qu’au panorama lui-même.

**Augmentation de la limite de diffusion des cartes**

_Tableaux_

Les délais de remise des cartes ont été augmentés à 8 semaines / 60 jours au lieu de 4 semaines / 30 jours.

**La désactivation planifiée ne désactive pas l’utilisateur**

_Utilisateurs_

Lorsque la désactivation d’un utilisateur est planifiée et que la date et l’heure programmées sont passées, il n’est pas désactivé.

+++

+++**Mise à jour de maintenance le 9 février 2023**

**[!UICONTROL Points d’article] champ ajouté aux listes et rapports de tâches et de problèmes**

_Rapports_

Le [!UICONTROL Points d’article] est désormais disponible pour être ajouté aux listes et aux rapports pour les tâches ou les problèmes. Il s’agit d’un champ de formulaire libre modifiable qui n’est pas lié aux heures planifiées ou aux affectations d’équipe.

+++

+++**Mise à jour de maintenance le 8 février 2023**

**Bouton Filtrer dans la colonne d’entrée**

_Tableaux_

La colonne d’ingestion d’un panorama comprend désormais une **[!UICONTROL Ajouter un filtre]** lorsque la colonne est vide et qu’aucun filtre n’a été créé. Le bouton ouvre la zone de configuration, dans laquelle vous pouvez ajouter des filtres pour importer les tâches et les problèmes dans la colonne d’entrée.

+++

+++**Mise à jour de maintenance le 2 février 2023**

**[!UICONTROL Panoramas] apparaît dans [!UICONTROL Menu Principal] par défaut**

_Tableaux_

Le [!UICONTROL Panoramas] s’affiche maintenant dans la [!UICONTROL Menu Principal] pour les utilisateurs qui n’ont pas de modèle de mise en page. Les panoramas sont également inclus par défaut dans le menu principal pour tous les nouveaux modèles de mise en page créés. Les modèles de mise en page existants n’ont pas été modifiés.

**Impossible d’enregistrer les modèles d’email**

_Configuration_

Lorsqu’un utilisateur ou une utilisatrice tente de créer ou de modifier un modèle d’e-mail, le bouton [!UICONTROL Enregistrer] ne répond pas et l’utilisateur ou l’utilisatrice ne peut pas enregistrer le modèle.

+++

## Mises À Jour En Janvier 2023

+++**Mise à jour de maintenance le 30 janvier 2023**

**Raccourcis clavier ajoutés pour les actions de feuille de temps courantes**

_Feuilles de temps_

Nous avons introduit les raccourcis clavier suivants pour les actions courantes suivantes dans une feuille de temps :

* Ajouter une ligne (Cmd+Option++ / Ctrl+Option++)
* Supprimer la ligne (Cmd+Option+- / Ctrl+Option+-)
* Epingler ou détacher un élément de travail (Option+P / Option+P)
* Ouvrir le commentaire (Maj+F2 / Maj+F2)
* Enregistrer le commentaire (Cmd+Entrée / Ctrl+Entrée)
* Développer (Maj+Option+Flèche Haut/ Maj+Alt+Flèche Haut)
* Réduire (Maj+Option+Flèche Bas/ Maj+Alt+Flèche Bas)

La zone où ces actions sont effectuées doit être mise en surbrillance pour qu’elles s’appliquent.

**Nouvelles icônes d’informations pour les feuilles de temps, les profils de feuille de temps et les préférences de la feuille de temps**

_Feuilles de temps_

>[!NOTE]
>
>Cette mise à jour a été publiée uniquement dans l’environnement Aperçu le 3 novembre 2022 et est désormais disponible dans l’environnement de production.

Nous avons ajouté plusieurs icônes d’informations pour les paramètres suivants :

* &quot;[!UICONTROL Peut modifier l’heure]&quot;case à cocher lors de la création ou de la modification d’une feuille de temps ou d’un profil de feuille de temps pour indiquer que lorsqu’elle est activée, les approbateurs peuvent également envoyer, rouvrir ou modifier la feuille de temps, sauf si votre administrateur restreint ces actions dans la variable [!UICONTROL Préférences de la feuille de temps] area of [!UICONTROL Configuration].
* &quot;[!UICONTROL Limitation de la modification de la feuille de temps aux propriétaires et aux administrateurs]&quot; dans la variable [!UICONTROL Préférences de la feuille de temps et de l’heure] area of [!UICONTROL Configuration] pour indiquer qu’en cas de désactivation, les utilisateurs suivants peuvent également modifier les feuilles de temps : les utilisateurs disposant d’un accès administratif aux feuilles de calcul temporelles et aux heures, les approbateurs de feuilles de temps sont autorisés à modifier l’heure et les gestionnaires des propriétaires de feuilles de temps.

Notez que la fonctionnalité de ces paramètres n’a pas été modifiée et que seules des icônes d’informations ont été ajoutées pour clarifier la fonction des paramètres.

+++

+++**Mise à jour de maintenance le 26 janvier 2023**

**Erreur de soumission d’une demande depuis [!DNL Outlook]**

_Intégrations_

Lorsque l’utilisateur tente de soumettre une demande comprenant des pièces jointes dans un e-mail [!DNL Outlook], une ou plusieurs des pièces jointes ne se chargent pas et le message d’erreur suivant apparaît :

&quot;[!UICONTROL L’erreur suivante s’est produite : Le fichier contenant l’identificateur xxxx n’existe pas.]&quot;

Cela se produit uniquement lorsqu’une affectation est effectuée pour la nouvelle demande, soit au moyen de la file d’attente des demandes, soit manuellement lors de la création de la demande.

**Nouvelle version du lecteur de vérification pour bureau**

_Vérification_

Pour résoudre un problème de blocage du lecteur de vérification pour bureau, nous en avons déployé une nouvelle version. Les utilisateurs ou utlisatrices qui disposent déjà du lecteur de vérification pour bureau recevont une notification automatique de cette mise à jour.

Les utilisateurs ou utilisatrices peuvent également afficher manuellement la dernière version. Pour plus d’informations, consultez [Installation du lecteur de vérification pour bureau](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=fr).

* Version précédente : 2.1.19
* Nouvelle version : 2.1.20

**L’utilisateur ne peut pas modifier ses propres paramètres utilisateur**

_Utilisateurs_

Lorsqu’un utilisateur ou une utilisatrice sous licence de Travail, Révision ou Demande tente de modifier ses propres paramètres utilisateur, la fenêtre contextuelle qui s’affiche est vide et l’utilisateur ou l’utilisatrice ne peut pas apporter de modifications. Pour quitter la fenêtre contextuelle, l’utilisateur ou l’utilisatrice doit actualiser la page.

+++

+++**Mise à jour de maintenance le 19 janvier 2023**

**Les filtres de colonne d’entrée peuvent désormais être partagés.**

_Tableaux_

Lors de la publication de la fonctionnalité Colonne d’entrée sur les tableaux, les filtres de configuration n’étaient visibles que par la personne qui les avait créés. Le créateur ou la créatrice des filtres peut maintenant les partager avec d’autres utilisateurs, utilisatrices ou équipes.

**Fonctionnalité Épingle disponible dans le menu [!UICONTROL Plus]**

_Navigation_

Les fonctionnalités suivantes sont désormais disponibles dans le menu [!UICONTROL Plus] pour les épingles, dans l’environnement de production :

* Renommer des épingles
* Réorganisation des épingles dans le menu [!UICONTROL Plus]
* Retrait d’une épingle du menu [!UICONTROL Plus] (en procédant de la sorte, la dernière épingle de la barre de navigation supérieure est déplacée vers le menu [!UICONTROL Plus])

+++

+++**Mise à jour de maintenance le 18 janvier 2023**

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

+++**Mise à jour de maintenance le 12 janvier 2023**

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
