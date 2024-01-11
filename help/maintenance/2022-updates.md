---
title: Mises à jour de maintenance Workfront en 2022
description: Mises à jour de maintenance 2022 pour [!DNL Adobe Workfront]
exl-id: 78ea4e31-143f-4a70-bb9a-060b5a8e097e
feature: Get Started with Workfront
source-git-commit: 8dc177a194ae32bcb135910badc7fdb2c42e530d
workflow-type: tm+mt
source-wordcount: '16797'
ht-degree: 99%

---

# [!DNL Workfront] Mises à jour de maintenance en 2022

Les mises à jour de maintenance suivantes ont été effectuées en 2022.

>[!NOTE]
>
>Ces mises à jour incluent également d’autres correctifs mineurs ou moins conséquents. L’assistance [!DNL Workfront]vous avertira lorsqu’un problème que vous avez soumis est résolu.

<!--
* [July 2022](#updates-in-july-2022)
* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)
-->

Pour connaître les mises à jour de maintenance antérieures à 2022, consultez les [Mises à jour de maintenance précédentes](#previous-maintenance-updates)

## Mises à jour de décembre 2022

+++**Mise à jour de maintenance le 15 décembre 2022**

**Mises à jour de l’accessibilité dans les listes**

*Listes*

Les fonctionnalités d’accessibilité suivantes sont désormais disponibles dans les listes :

* Les cases à cocher des listes sont désormais dotées d’un indicateur de sélection visible lorsque vous les sélectionnez avec la touche tabulation. Cela facilite la visualisation de la navigation au clavier des éléments d’une liste.
* Tous les boutons des barres d’outils de liste ont désormais des états de survol et de sélection cohérents, avec un arrière-plan gris affiché lors du survol et un arrière-plan gris et un contour bleu affichés lors de la sélection.
* Auparavant, lors de l’ouverture d’un menu déroulant dans une liste avec la touche Espace, le menu s’ouvrait et la page défilait également légèrement vers le bas, ce qui n’était pas prévu. Désormais, la page ne défile plus lorsque vous appuyez sur Espace dans une liste déroulante, ce qui est le comportement prévu.
* Lorsque vous affichez une liste avec la case à cocher de rangée sélectionnée, vous pouvez désormais passer d’un élément modifiable à un autre à l’aide de la touche Tabulation, puis appuyer sur la touche Espace pour passer en mode édition et commencer à modifier cette cellule dans la rangée. Auparavant, il était impossible de naviguer entre ces éléments à l’aide du clavier, l’utilisation d’une souris était nécessaire. Le passage en mode édition est désormais possible avec la souris et le clavier.

**Erreur « [!UICONTROL Oups] » lors de la création d’un projet à partir d’un modèle**

*Projets*

Lorsque l’utilisateur tente de créer un projet à partir d’un modèle, le projet n’est pas créé et l’erreur suivante apparaît :

« [!UICONTROL Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.] »

**Le graphique combiné affiche les mêmes données en double**

*Rapports*

Lorsque l’utilisateur consulte un graphique combiné, celui-ci affiche un ensemble de valeurs en double au lieu de comparer deux ensembles de valeurs. Les ensembles de valeurs corrects se trouvent dans les détails du rapport.

**Infobulles ajoutées pour les cellules d’heures grisées dans les feuilles de temps**

*Feuilles de temps*

Nous avons ajouté des infobulles pour expliquer pourquoi une cellule d’heure peut être grisée dans une feuille de temps. Par exemple, cela peut être dû à la fermeture de la feuille de temps ou à la fin du projet.

**Les utilisateurs désactivés sont sélectionnables en tant qu’approbateurs de la feuille de temps**

*Feuilles de temps*

Lorsque l’utilisateur crée une feuille de temps et tente d’affecter un approbateur, la liste déroulante inclut les utilisateurs désactivés. Si un utilisateur désactivé est sélectionné, la feuille de temps n’est pas enregistrée et le message suivant apparaît :

« [!UICONTROL Erreur. Désolé, mais seuls les utilisateurs disposant d’une licence Plan peuvent approuver ou refuser les feuilles de temps. Contactez votre administrateur système.] »

L’utilisateur désactivé ne pouvant pas être affecté, il faut sélectionner un utilisateur activé. La feuille de temps fonctionne donc comme prévu, mais la présence d’utilisateurs désactivés dans la liste peut prêter à confusion ou gêner l’utilisateur.

**Impossible de saisir des heures sur la feuille de temps**

*Feuilles de temps*

Lorsqu’un utilisateur tente d’ajouter des heures à une feuille de temps, les cases « heure » dans les lignes de temps du projet ou de la tâche sont grisées et l’utilisateur ne peut saisir d’heures dans ces cases. Seule la partie « Heure générale » peut être complétée.

+++

+++**Mise à jour de maintenance le 8 décembre 2022**

**Sélection intelligente des utilisateurs lors de l’ajout d’approbateurs à un chemin d’approbation**

*Approbations*

Nous avons amélioré l’affichage des utilisateurs lorsque vous les ajoutez au champ [!UICONTROL Approbateurs] d’une nouvelle validation.

Désormais, lorsque vous ajoutez un utilisateur aux [!UICONTROL Approbateurs] d’une validation au niveau du système ou à usage unique, leur rôle principal et leur e-mail s’affichent en plus de leur nom et de leur avatar. Cela permet de distinguer plusieurs utilisateurs portant des noms similaires ou identiques.

**Le statut du projet ne correspond pas aux préférences du groupe**

*Projets*

Lorsqu’un utilisateur crée un projet à partir d’un modèle, le nouveau projet ne prend pas le statut défini dans les préférences du groupe. Si un projet est créé sans modèle, le statut reflète les préférences du groupe comme prévu.

**Impossible d’ajouter une sous-tâche**

*Tâches*

Lorsqu’un utilisateur tente d’ajouter une sous-tâche à l’aide du bouton « [!UICONTROL +Nouveau] », aucune option n’apparaît dans la fenêtre [!UICONTROL Nouvelle tâche] et le message suivant apparaît :

« [!UICONTROL Impossible de lire les propriétés de l’objet non défini (lecture des « validations »)] »

**Erreurs lors de la fermeture ou de l’enregistrement des feuilles de temps**

*Feuilles de temps*

Lorsqu’un utilisateur tente d’ajouter du temps à une feuille de temps ou de la fermer, cette dernière ne s’enregistre pas et les erreurs suivantes apparaissent :

* Erreur de base de données en raison d’une déclaration SQL non valide.
* Vos dernières modifications n’ont pas été enregistrées. Actualisez la page pour les voir.

+++

+++**Mise à jour de maintenance (correctif) le 1er décembre 2022**

**Les erreurs de modification en ligne par l’utilisateur ne provoquent pas de messages d’erreur**

*Listes*

Lorsqu’un utilisateur édite un objet en ligne et qu’il génère une erreur qui doit créer un message d’erreur, aucun message d’erreur ne s’affiche. L’erreur elle-même n’est pas enregistrée dans Workfront. Par conséquent, les données ne sont pas affectées, mais l’absence de message d’erreur peut prêter à confusion.

Les situations suivantes sont concernées :

* Prédécesseurs : Une boucle précédente est créée, par exemple en affectant une tâche à elle-même.
* Dates : Une date impossible est définie, par exemple une date de fin antérieure à la date de début ou postérieure à la date d’achèvement du projet.

**L’option « Déplacer vers » n’est pas disponible dans les rapports d’événement**

*Rapports*

Lorsqu’un utilisateur consulte un rapport d’événement et tente de déplacer un événement, l’option « Déplacer vers » n’est pas disponible sous le menu Plus (à trois points).


**Impossible de fermer la carte d’utilisateur dans le flux de mise à jour**

*Mises à jour*

Lorsque l’utilisateur consulte les mises à jour et survole un nom, une carte contenant des informations sur l’utilisateur correspondant s’ouvre et ne se ferme pas automatiquement. La page ne répond plus tant que la carte n’est pas fermée manuellement en cliquant sur le X du coin supérieur droit.


+++

+++**Mise à jour de maintenance le 1 décembre 2022**

**L’ordre de la tâche dans la liste d’attente Kanban est égal à 0.**

*Agile*

Lorsqu’un utilisateur consulte la liste d’attente d’une équipe Kanban, une ou plusieurs tâches affichent un ordre de backlog de 0.

**Un message « [!UICONTROL Expression personnalisée non valide] » apparaît lorsqu’un champ calculé fait référence à un « [!UICONTROL propriétaire] »**

*Formulaires personnalisés*

Lorsque l’utilisateur ajoute un champ calculé à un formulaire personnalisé au niveau du problème et tente de faire référence à un « [!UICONTROL propriétaire] » (par exemple `ownerID`), le champ n’est pas enregistré et le message suivant apparaît :

« [!UICONTROL Cette expression client n’est pas valide, veuillez réessayer.] »

Cela se produit même lorsque l’expression est valide.

**Impossible d’accéder aux éléments de l’intégration [!DNL Workfront for Jira]**

*Intégrations*

Les éléments suivants ne sont actuellement pas accessibles dans l’intégration [!DNL Workfront for Jira] pour [!DNL Jira Cloud] :

* La page de [!UICONTROL configuration]
* Le bouton « [!UICONTROL Ouvrir Workfront] » sur un événement [!DNL Jira]

**L’ajout d’un message personnalisé cause un problème dans la visionneuse d’épreuves**

*BAT*

Lorsque l’utilisateur partage une épreuve et tente d’ajouter un message personnalisé, voici ce qui se passe :

* La visionneuse d’épreuves effectue un zoom avant sur l’épreuve.
* Les zones du volet de navigation de gauche ne réagissent plus.

**Les utilisateurs désactivés sont sélectionnables en tant qu’approbateurs de la feuille de temps**

*Feuilles de temps*

Lorsque l’utilisateur crée une feuille de temps et tente d’affecter un approbateur, la liste déroulante inclut les utilisateurs désactivés. Si un utilisateur désactivé est sélectionné, la feuille de temps n’est pas enregistrée et le message suivant apparaît :

« [!UICONTROL Erreur. Désolé, mais seuls les utilisateurs disposant d’une licence Plan peuvent approuver ou refuser les feuilles de temps. Contactez votre administrateur système.] »

L’utilisateur désactivé ne pouvant pas être affecté, il faut sélectionner un utilisateur activé. La feuille de temps fonctionne donc comme prévu, mais la présence d’utilisateurs désactivés dans la liste peut prêter à confusion ou gêner l’utilisateur.

**La feuille de temps n’est pas générée**

*Feuilles de temps*

Les feuilles de temps ne sont pas générées contrairement aux paramètres du profil des feuilles de temps. Étant donné que la feuille de temps n’est jamais générée, l’utilisateur ne peut pas saisir de temps et elle n’est pas visible sur les listes.

+++

## Mises à jour de novembre 2022

+++**Mise à jour de maintenance le 17 novembre 2022**

**Les documents sont envoyés dans la [!UICONTROL Corbeille] s’ils sont désélectionnés lorsqu’une tâche ou un problème est déplacé**

*Documents*

Lorsque vous désélectionnez l’option [!UICONTROL Documents] pendant le déplacement d’une tâche ou d’un problème, les documents associés à la tâche ou au problème seront désormais envoyés dans la [!UICONTROL Corbeille] pendant 30 jours. Un administrateur peut les restaurer si nécessaire. Si l’option Documents est désélectionnée pendant le déplacement, un message d’avertissement s’affichera à ce propos dans la fenêtre [!UICONTROL Déplacer la tâche] ou [!UICONTROL Déplacer le problème]. Avant cette amélioration, les documents étaient supprimés définitivement.

**Le masquage d’un élément ne masque pas le bon élément**

*Modèles de disposition*

Lorsque l’utilisateur affiche ou masque un élément, c’est un autre élément du modèle de mise en page qui est affiché ou masqué.


+++

+++**Mise à jour de maintenance le 10 novembre 2022**

**La modification en masse de tâches modifie les affectations de tâches**

*Tâches*

Lorsqu’un utilisateur modifie en masse un champ pour un ensemble de tâches, les affectations de la première tâche sont appliquées à toutes les tâches. Cela supprime les affectations précédentes.

**Impossible d’ouvrir un BAT interactif**

*Épreuve Workfront*

Lorsque l’utilisateur tente d’ouvrir un BAT interactif, celui-ci ne s’ouvre pas et le message suivant apparaît :

« [!UICONTROL BAT non chargé (501) Réessayer] »

+++

+++**Mise à jour de maintenance (correctif) le 4 novembre 2022**

**Problèmes avec des tâches ajoutées à une itération**

*Agile*

Les problèmes suivants ont été signalés concernant des événements ajoutés à une itération :

* Certaines sous-tâches d’une tâche ajoutée à une itération n’apparaissent pas sur la page [!UICONTROL Itération].
* Lorsqu’un utilisateur tente d’ajouter une tâche manquante à l’itération, la tâche n’est pas ajoutée et l’utilisateur voit le message suivant :

  « [!UICONTROL L’erreur suivante s’est produite : aucun des éléments suivants n’a pu être déplacé parce qu’ils ne sont pas affectés à une équipe Agile ou ne sont pas des éléments Agile.] »

**Les tâches affectées au moyen de la modification en bloc n’apparaissent pas dans la liste d’attente de l’équipe.**

*Agile*

Lorsqu’un utilisateur affecte des tâches à une équipe de Scrum en utilisant la modification en bloc, ces tâches n’apparaissent pas dans la liste d’attente de l’équipe.

Les équipes de Kanban ne sont pas affectées par ce problème.

**La zone de texte « [!UICONTROL Nouveaux destinataires du BAT] » est trop petite**

*BAT*

Lorsqu’un utilisateur consulte une épreuve et tente de la partager à partir de l’onglet [!UICONTROL Partage], la zone de texte « [!UICONTROL Nouveaux destinataires de l’épreuve] » est trop petite. L’utilisateur peut saisir un nom, mais en raison de la petite taille de la zone de texte, le texte est, mais en raison de la petite taille de la boîte, le texte est illisible.

**Les informations sur l’utilisation des rapports ne sont pas mises à jour**

*Rapports*

Lorsqu’un utilisateur affiche un rapport, les informations relatives à la dernière consultation, telles que date de dernière consultation et Affiché en dernier par, ne sont pas mises à jour. Cela signifie que toutes les informations d’utilisation peuvent être incorrectes.

Ce comportement a été signalé lorsque l’utilisateur accède au rapport des façons suivantes :

* Recherche
* Épingles
* Favoris
* Récents

L’accès aux rapports via un tableau de bord met à jour les informations relatives à la dernière consultation.

**[!DNL Workfront] : erreur 500 lors de la modification d’un [!DNL Workfront]objet**+

*[!DNL Workfront]*

Lorsqu’un utilisateur tente d’apporter des modifications à un objet [!DNL Workfront], les modifications ne sont pas enregistrées et l’utilisateur voit l’erreur suivante :

« [!UICONTROL 500 : Erreur de base de données en raison d’une déclaration SQL non valide.] »

Les situations suivantes sont concernées :

* Modification du statut d’un objet
* Recalcul des chronologies
* Ajout d’un modèle
* Heure de connexion

+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 3 novembre 2022**

**Erreur concernant [!UICONTROL apiKey] dans le module [!DNL Workfront] > [!UICONTROL Événements Espion]**

*[!DNL Workfront Fusion]*

Lorsqu’un utilisateur tente d’ajouter un webhook dans le module [!DNL Workfront] > [!UICONTROL Événements Espion], il reçoit l’erreur suivante :

« [!UICONTROL L’apiKey fourni était vide ou est considéré comme non valide.] »

+++

+++**Mise à jour de maintenance le 3 novembre 2022**

**Renommez les sections « Planifier » et « Planification » pour les équipes et les projets dans le modèle de disposition.**

*Modèles de disposition*

Les onglets « Planifier » et « Planification » disponibles pouvant être ajoutés dans un modèle de disposition au panneau de gauche d’une équipe ou d’un projet ont été renommés « Équilibreur de charge de travail ».

**Erreurs lors de l’accès aux paramètres de notification par e-mail**

*Notifications*

>[!NOTE]
>
>Ce problème existe dans les environnements de production et de prévisualisation.

Lorsque l’utilisateur tente de modifier les paramètres de notification par e-mail, l’une des erreurs suivantes survient parfois :

* « [!UICONTROL Réessayons. Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.] »

* « [!UICONTROL Échec de la récupération des notifications par e-mail] »

Les zones suivantes sont concernées :

* [!UICONTROL Configuration] > [!UICONTROL Notifications par e-mail]
* [!UICONTROL Utilisateur] > [!UICONTROL Modifier l’utilisateur]
* [!UICONTROL Groupes]

**Nouvelles icônes d’informations pour les feuilles de temps, les profils de feuille de temps et les préférences de la feuille de temps**

*Workfront*

>[!NOTE]
>
>Cette mise à jour a été publiée uniquement dans l’environnement de Prévisualisation. Elle sera publiée en production avec la version 23.1.

Nous avons ajouté plusieurs icônes d’informations pour les paramètres suivants :

* La case « Peut modifier l’heure » lors de la création ou de la modification d’une feuille de temps ou d’un profil de feuille de temps indique, lorsqu’elle est cochée, que les approbateurs etles approbatrices peuvent également envoyer, rouvrir ou modifier la feuille de temps, sauf si votre administrateur ou administratrice restreint ces actions dans les « Préférences de la feuille de temps » de la section « Configuration ».
* « Limiter la modification de la feuille de temps aux propriétaires et aux administrateurs » dans la zone « Préférences de la feuille de temps et d’heure » de la section « Configuration » pour indiquer que, lorsque cette case est décochée, les utilisateurs et utilisatrices suivants peuvent également modifier les feuilles de temps : les utilisateurs et utilisatrices disposant d’un accès administratif aux feuilles de temps et d’heure, les approbateurs et les approbatrices de feuilles de temps autorisés à modifier l’heure et les gestionnaires des propriétaires de feuilles de temps.

Notez que la fonctionnalité de ces paramètres n’a pas été modifiée et que seules des icônes d’informations ont été ajoutées pour clarifier la fonction des paramètres.

+++

## Mises à jour d’octobre 2022

+++**Mise à jour de maintenance le 27 octobre 2022**

La fonction **[!UICONTROL HEURE] dans les champs calculés utilise le format UTC.**

*Formulaires personnalisés*

Lorsqu’un champ calculé inclut la fonction [!UICONTROL HEURE], celle-ci renvoie des valeurs en fonction du fuseau horaire UTC plutôt que du fuseau horaire attendu. Par conséquent, tous les calculs basés sur la fonction HEURE sont incorrects.

Le **[!UICONTROL filtre rapide] ne renvoie aucun résultat lors de la recherche d’équipes**.

*Listes*

Lorsqu’un utilisateur tente d’utiliser le [!UICONTROL filtre rapide] sur une liste pour rechercher une équipe, la saisie du nom de l’équipe ne renvoie aucun résultat, même si l’équipe est visible dans la liste (par exemple dans le champ [!UICONTROL Affecté à]). La recherche du mot « [!UICONTROL équipe] » ne renvoie également aucun résultat.

**Impossible de réépingler une page après l’avoir désépinglée**

*Navigation*

>[!NOTE]
>
>Ce problème a été corrigé dans la prévisualisation le 13 octobre 2022. Il a été corrigé en production le 27 octobre 2022.

Lorsqu’un utilisateur sélectionne l’option « [!UICONTROL Supprimer l’épingle] », qu’il est notifié de la suppression et qu’il essaie de la remplacer en cliquant sur « [!UICONTROL Annuler] » dans le message, l’épingle n’est pas remplacée dans le panneau de navigation supérieur et n’est pas non plus ajoutée à la liste des épingles dans la liste « [!UICONTROL Plus d’épingles] » (menu sous forme de trois points dans la zone [!UICONTROL Épingles] ).

Si un utilisateur tente de réépingler la page en accédant à la page et en l’épinglant, l’épingle n’est pas créée et l’utilisateur ne peut pas épingler la page.

**Tous les utilisateurs répertoriés dans [!UICONTROL Équilibreur de charge de travail] lors de l’utilisation d’un lien partageable dans le [!DNL Safari] navigateur**

*[!UICONTROL Équilibreur de charge de travail]*

Lorsqu’un utilisateur suit un lien partageable vers l’[!UICONTROL Équilibreur de charge de travail] lors de l’utilisation d’un navigateur [!DNL Safari], il voit tous les utilisateurs plutôt que seulement les membres de l’équipe répertoriés.

+++

+++**Mise à jour de maintenance le 20 octobre 2022**

**Erreur lors de l’affectation en bloc d’une équipe**

*Affectations*

Lorsqu’un utilisateur modifie en bloc des tâches ou des événements et affecte une équipe après avoir affecté une personne, les affectations ne sont pas enregistrées et l’utilisateur voit l’erreur suivante :

« [!UICONTROL Réessayons. L’erreur suivante s’est produite : teamAssignments doit être une liste d’objets ou une liste d’identifiants] ».

Erreur **« [!UICONTROL Échec de chargement du fichier] »**

*Documents*

Lorsqu’un utilisateur tente de charger un fichier dans la zone [!UICONTROL Documents], le fichier ne charge pas et l’utilisateur voit l’erreur « [!UICONTROL Échec de chargement du fichier] ».

Ceci a été signalé lors de la tentative de chargement de fichiers MP4.

**Le nombre d’événements figurant dans le panneau de navigation gauche de la tâche n’est pas correct**

*Événements*

Lorsqu’un utilisateur consulte une tâche, le nombre affiché dans la section [!UICONTROL Événements] du panneau de navigation gauche ne représente pas exactement le nombre réel d’événements associés à la tâche.


Icône **[!UICONTROL Prédécesseur] manquante dans l’en-tête de la tâche**

*Tâches*

Lorsqu’un utilisateur consulte une tâche, l’icône du prédécesseur de la tâche est manquante dans l’en-tête.

+++

+++**Mise à jour de maintenance le 13 octobre 2022**

**Impossible de réépingler une page après l’avoir désépinglée**

*Navigation*

>[!NOTE]
>
>Ce problème sera corrigé dans la prévisualisation le 13 octobre 2022. Il sera corrigé en production le 27 octobre 2022.

Lorsqu’un utilisateur sélectionne l’option « [!UICONTROL Supprimer l’épingle] », qu’il est notifié de la suppression et qu’il essaie de la remplacer en cliquant sur « [!UICONTROL Annuler] » dans le message, l’épingle n’est pas remplacée dans le panneau de navigation supérieur et n’est pas non plus ajoutée à la liste des épingles dans la liste « [!UICONTROL Plus d’épingles] » (menu sous forme de trois points dans la zone [!UICONTROL Épingles] ).

Si un utilisateur tente de réépingler la page en accédant à la page et en l’épinglant, l’épingle n’est pas créée et l’utilisateur ne peut pas épingler la page.

**Impossible de nommer ou d’enregistrer les filtres nouvellement créés**

*[!UICONTROL Planificateur de ressources]*

Lorsqu’un utilisateur tente de nommer un nouveau filtre dans le [!UICONTROL Planificateur de ressources], le champ du nom reste vide. De plus, si l’utilisateur a appuyé sur la barre d’espace, le bouton [!UICONTROL Enregistrer] se désactive.

**Impossible de modifier le nom ou le pourcentage d’avancement d’une tâche ou d’un événement**

*Tâches et événements*

Les utilisateurs ayant un accès de type [!UICONTROL Contributeur] à une tâche ou à un événement ne peuvent pas modifier le nom de la tâche ou de l’événement dans l’en-tête. De plus, les utilisateurs ayant un accès de type [!UICONTROL Contributeur] ne peuvent pas modifier le pourcentage d’avancement d’une tâche ou d’un événement.

**Les demandeurs et les réviseurs sont comptabilisés dans le nombre de licences d’une organisation**

*[!DNL Workfront Proof]*

Lorsque l’utilisateur est ajouté à une épreuve en tant que réviseur ou demandeur, il obtient un profil d’autorisations de niveau « [!UICONTROL Visiteur] », qui n’utilise normalement pas de licence [!DNL Workfront Proof]. Toutefois, lorsque l’utilisateur est ajouté, le nombre de licences [!DNL Workfront Proof] utilisées augmente.

+++

+++**Mise à jour de maintenance le 11 octobre 2022**

**Impossible de réépingler une page après l’avoir désépinglée**

*Navigation*

>[!NOTE]
>
>Ce problème a été corrigé dans la prévisualisation le 13 octobre 2022. Il sera corrigé en production le 27 octobre 2022.

Lorsqu’un utilisateur sélectionne l’option « [!UICONTROL Supprimer l’épingle] », qu’il est notifié de la suppression et qu’il essaie de la remplacer en cliquant sur « [!UICONTROL Annuler] » dans le message, l’épingle n’est pas remplacée dans le panneau de navigation supérieur et n’est pas non plus ajoutée à la liste des épingles dans la liste « [!UICONTROL Plus d’épingles] » (menu sous forme de trois points dans la zone [!UICONTROL Épingles] ).

Si un utilisateur tente de réépingler la page en accédant à la page et en l’épinglant, l’épingle n’est pas créée et l’utilisateur ne peut pas épingler la page.

+++

+++**Mise à jour de maintenance le 6 octobre 2022**

**Nouveau type de blueprint**

*Blueprints*

Le type de blueprint « Tableau de bord » a été ajouté au catalogue de blueprints. Auparavant, seuls les blueprints Modèle de projet et structure organisationnelle étaient disponibles.

**Chevauchement des éléments dans le panneau de gauche**

*Formulaires personnalisés*

Lorsque l’utilisateur travaille dans le créateur de formulaires et que le formulaire contient plus de 100 champs, le message informant l’utilisateur de la limite de champs entraîne le chevauchement des éléments du panneau de gauche.

**Le sélecteur de date ne s’ouvre plus automatiquement, que ce soit avec le clavier ou la souris**

*Navigation*

Lorsqu’un utilisateur navigue avec le clavier et l’utilise pour saisir une date, les sélecteurs de date ne s’ouvrent pas automatiquement. L’utilisateur doit donc cliquer sur l’icône du sélecteur de date et appuyer sur Entrée pour ouvrir le sélecteur de date. Lorsqu’un utilisateur navigue avec la souris et l’utilise pour saisir une date, les sélecteurs de date ne s’ouvrent pas automatiquement. L’utilisateur doit donc cliquer sur l’icône du sélecteur de date pour l’ouvrir.

Cette modification a été effectuée afin de mieux se conformer aux modèles standard de l’expérience utilisateur du sélecteur de date et de créer une expérience plus accessible pour les utilisateurs qui privilégient le clavier ou qui utilisent un lecteur d’écran.

**Lors de l’affectation de plusieurs équipes, une seule équipe est affectée**

*Équipes*

>[!NOTE]
>
>Ce problème est uniquement présent dans l’environnement de prévisualisation.

Lorsqu’un utilisateur affecte plusieurs équipes à une tâche ou à un événement, une seule équipe s’affiche dans la liste des affectations. Ce problème affecte également la création de rapports. Les rapports indiquant les affectations d’équipe sont inexacts, car une seule équipe apparaît comme affectée à la tâche ou à l’événement.

**Erreur « [!UICONTROL Les derniers changements n’ont pas été enregistrés] » lors de l’enregistrement automatique des modifications sur une feuille de temps**

*Feuilles de temps*

Lorsque l’utilisateur tente d’apporter une modification à une feuille de temps qui déclencherait son enregistrement automatique, la modification n’est pas enregistrée et le message suivant apparaît :

« [!UICONTROL Vos modifications récentes n’ont pas été enregistrées. Actualisez la page que vous souhaitez afficher.] »

Ce problème a été signalé lors de la modification des éléments suivants :

* Heures
* Tâches

**Retard des notifications par e-mail**

*Épreuve Workfront*

Lorsqu’un événement se produit dans [!DNL Workfront Proof] et déclenche l’envoi d’une notification par e-mail, l’utilisateur ne reçoit pas immédiatement la notification. Il peut la recevoir plusieurs heures plus tard.

+++

+++**Mise à jour de maintenance le 3 octobre 2022**

**Enregistrement manuel de votre feuille de temps lorsque les rôles précédents d’une tâche ont été modifiés**

*Feuilles de temps*

Si un rôle de tâche pour lequel vous avez saisi une heure a changé et que le paramètre [!UICONTROL Affecter manuellement des rôles aux entrées d’heure] a été désactivé, vous devez enregistrer manuellement vos entrées de temps jusqu’à ce que les heures ne soient plus saisies pour le rôle de tâche qui a été modifié.

+++

## Mises à jour de septembre 2022

+++**Mise à jour de maintenance le 29 septembre 2022**

**L’utilisateur ne revient pas à la page précédente lors de la fermeture de l’épreuve**

*Épreuves*

Lorsqu’un utilisateur consulte une épreuve dans [!DNL Workfront] et la ferme, il ne revient pas à la page sur laquelle il était avant d’ouvrir l’épreuve. Au lieu de cela, il est redirigé vers une autre page de [!DNL Workfront].

**Impossible d’ouvrir l’épreuve dans [!DNL Workfront]**

*Épreuves*

Lorsqu’un utilisateur consulte un document dans [!DNL Workfront] et tente d’ouvrir l’épreuve, l’épreuve ne s’ouvre pas et l’utilisateur est renvoyé à la page des [!UICONTROL Détails du document].

**Les heures ne sont pas enregistrées lors de l’utilisation de la touche de [!UICONTROL tabulation]**

*Feuilles de temps*

Lorsque l’utilisateur remplit une feuille de temps et navigue entre les cellules à l’aide de la touche de [!UICONTROL tabulation], les heures ne sont pas enregistrées. La notification d’[!UICONTROL enregistrement automatique] n’apparaît pas en bas de l’écran, et si l’utilisateur actualise la page, il constate que les heures n’ont pas été enregistrées.

**Pages vierges lors de l’affichage d’une épreuve avec plusieurs pages**

*[!DNL Workfront Proof]*

Lorsqu’un utilisateur affiche une épreuve avec plusieurs pages, il peut voir les miniatures des pages, mais les pages ne s’ouvrent pas dans la visionneuse principale.



+++

+++**Mise à jour de maintenance le 22 septembre 2022**

**Impossible de fermer la carte d’utilisateur dans le flux de mise à jour**

*Mises à jour*

Lorsque l’utilisateur consulte les mises à jour et survole un nom, une carte contenant des informations sur l’utilisateur correspondant s’ouvre et ne se ferme pas automatiquement. La page ne répond plus tant que la carte n’est pas fermée manuellement en cliquant sur le X du coin supérieur droit.

+++

+++**Mise à jour de maintenance le 15 septembre 2022**

**« [!UICONTROL Une autre personne a tenté d’enregistrer ce projet] » lors de la saisie des heures**

*Feuilles de temps*

Lorsque l’utilisateur tente de consigner des heures pour une tâche sur sa feuille de temps, les heures ne s’ajoutent pas et le message d’erreur suivant apparaît :

«[!UICONTROL  Votre enregistrement a échoué, car une autre personne a tenté d’enregistrer ce projet au même moment. Veuillez réessayer de l’enregistrer plus tard.] »

**Impossible de fermer la carte d’utilisateur dans le flux de mise à jour**

*Mises à jour*

Lorsque l’utilisateur consulte les mises à jour et survole un nom, une carte contenant des informations sur l’utilisateur correspondant s’ouvre et ne se ferme pas automatiquement. La page ne répond plus tant que la carte n’est pas fermée manuellement en cliquant sur le X du coin supérieur droit.

**Le champ « [!UICONTROL Affectation de rôle de tâche] » est devenu « [!UICONTROL Affectation de rôle] » lors de l’affectation de tâches en bloc avec l’[!UICONTROL équilibreur de charge de travail]**

*[!UICONTROL Équilbreur de charge de travail]*

Pour signifier que la nouvelle fonctionnalité est capable d’affecter à la fois des tâches et des événements en bloc depuis la zone [!UICONTROL Tâches non affectées], nous avons renommé le champ « [!UICONTROL Affectation de rôle de tâche] », qui devient « [!UICONTROL Affectation de rôle] » dans l’[!UICONTROL équilibreur de charge de travail]. Le champ fait référence à des fonctions affectées à des tâches ou à des événements. Il s’affiche lors de l’affectation d’utilisateurs à des éléments dans la zone [!UICONTROL Affectations en bloc].

+++

+++**[!DNL Workfront Scenario Planner]Mise à jour de maintenance le 15 septembre 2022**

**Le filtre partagé avec un groupe s’affiche désormais dans la liste [!UICONTROL Importer des projets] de [!DNL Scenario Planner] chez tous les membres de tous les sous-groupes**

*[!DNL Workfront Scenario Planner]*

Désormais, lorsque vous partagez un filtre de projet avec un groupe qui comporte d’autres sous-groupes, le filtre est visible pour tous les membres de groupe et de sous-groupe qui consultent les projets dans la zone [!UICONTROL Importer des projets] d’un plan dans le [!DNL Scenario Planner].

+++

+++**Mise à jour de maintenance le 8 septembre 2022**

**Annulation de la mise à jour des noms de champs d’affectation de rôle et d’utilisateur**

*Affectations*

Les champs d’affectation temporairement renommés la semaine dernière ont retrouvé leur nom d’origine :

* [!UICONTROL Utilisateurs de l’affectation]
* [!UICONTROL Rôles pour l’affectation]

**Erreur lors de la suppression du Propriétaire du projet dans l’en-tête**

*Projets*

Lorsque l’utilisateur tente de supprimer un [!UICONTROL Propriétaire de projet] dans l’en-tête d’un [!UICONTROL projet], il n’y parvient pas et le message d’erreur suivant apparaît :

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**La zone [!UICONTROL Description] reprend sa taille d’origine une fois redimensionnée**

*Projets, tâches et événements*

Lorsque l’utilisateur redimensionne la zone [!UICONTROL Description] dans la zone de détails d’un élément de travail et l’agrandit, puis commence à saisir du texte dans la zone, celle-ci revient à sa taille d’origine. La saisie est toujours possible dans la zone, et le contenu est enregistré comme prévu

**La fenêtre se ferme accidentellement lors de la création de tâches ou d’événements**

*Tâches et événements*

Lorsque l’utilisateur crée une tâche ou un événement dans un projet et clique en dehors du pop-up de création, celui-ci se ferme sans avertissement et toutes les informations déjà saisies sont perdues.

**Suppression de la possibilité d’envoyer une épreuve par e-mail vers une zone de dépôt**

*[!DNL Workfront Proof]*

Depuis jeudi 8 septembre 2022, il n’est plus possible d’envoyer une épreuve par e-mail vers une zone de dépôt dans le produit [!DNL Workfront Proof] autonome.

Vous pouvez toujours utiliser des zones de dépôt d’autres manières pour soumettre de nouvelles épreuves et de nouvelles versions d’épreuve vers votre compte sans devoir vous y connecter. Consultez la [Zone de dépôt](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html?lang=fr) pour en savoir plus.

+++

+++**Mise à jour de maintenance le 6 septembre 2022**

**Dates prévues ajoutées à la liste de champs pour les en-têtes de projet personnalisables**

*Projets*

La [!UICONTROL Date de début prévue] et la [!UICONTROL Date d’achèvement prévue] ont été ajoutées à la liste de champs pour les en-têtes de projet personnalisables lorsqu’un modèle de mise en page est utilisé.

**Nouvelle limite accompagnée d’un message de confirmation qui indique le nombre d’éléments ajoutés à une feuille de temps**

*Feuilles de temps*

Lorsque vous sélectionnez plus de 50 éléments à ajouter à une feuille de temps, vous recevez désormais un message de confirmation qui indique le nombre d’éléments à ajouter à la feuille de temps et vous donne la possibilité de changer d’avis et de ne pas ajouter tous les éléments. Tous les éléments ajoutés sont automatiquement épinglés dans la feuille de temps et doivent être supprimés manuellement des feuilles de temps actuelles et futures.

+++

+++**Mise à jour de maintenance le 2 septembre 2022**

Ajout du champ [!UICONTROL Intégrations] à l’en-tête personnalisé du projet

*Intégrations*

Vous pouvez maintenant ajouter le champ [!UICONTROL Intégrations] à l’en-tête personnalisé d’un projet lorsque vous utilisez un modèle de mise en page. Une fois ajouté, ce champ affiche un lien menant à un élément externe lié au projet, situé dans [!DNL Salesforce] ou [!DNL Anaplan] en fonction de votre intégration.

>[!NOTE]
>
>Cette mise à jour de maintenance est sortie dans l’environnement de prévisualisation le 25 août 2022 et passe désormais en production.

+++

+++**Mise à jour de maintenance le 1 septembre 2022**

**Éléments terminés supprimés de la délégation**

*Délégations*

Désormais, seuls les éléments incomplets dont les dates correspondent à celles d’une délégation seront délégués à d’autres utilisateurs au début de la délégation des tâches. Les éléments été terminés avant le début de la délégation ne seront pas délégués. Les éléments terminés pendant la période de délégation resteront deux semaines sur la Liste de travail de la zone d’Accueil du délégué et de la personne affectée avant d’être supprimés automatiquement si la délégation ne se termine pas au cours de ces deux semaines.

**Mises à jour des métadonnées pour les intégrations [!DNL Adobe Workfront] de [!DNL Experience Manager Assets] et [!DNL Assets Essentials]**

*Intégrations*

Les métadonnées sont automatiquement introduites lorsque vous ajoutez une ressource à un dossier lié.

Auparavant, les métadonnées étaient uniquement introduites lorsque vous ajoutiez une ressource à l’aide du menu [!UICONTROL Ajouter nouveau].

**Impossible d’approuver ou de rejeter des heures dans un événement**

*Événements*

Lorsque l’utilisateur tente d’approuver ou de rejeter des heures dans l’onglet [!UICONTROL Heures] d’un événement, les boutons [!UICONTROL Approuver] et [!UICONTROL Rejeter] n’apparaissent pas.

**Un message d’erreur incorrect apparaît lorsqu’un événement est converti en projet à l’aide d’un modèle**

*Événements*

Lorsqu’une erreur survient lors de la conversion d’un événement en projet à l’aide d’un modèle, une page contenant le message « [!UICONTROL Le projet n’existe plus] » s’affiche à la place du message d’erreur correct, qui explique la raison de l’échec de la conversion.

**Impossible de créer une épreuve pour les fichiers de plus de 1,5 Go**

*[!DNL Workfront Proof]*

Si l’utilisateur télécharge un fichier de plus de 1,5 Go pour la création d’une épreuve, le nom du fichier s’affiche en rouge et il est impossible de créer l’épreuve.

+++

## Mises à jour d’août 2022

+++**Mise à jour de maintenance le 25 août 2022**

**Les liens de l’équilibreur de charge de travail ne s’affichent pas correctement dans les tableaux de bord**

*Tableaux de bord*

Les liens de l’équilibreur de charge de travail dont le partage est autorisé ne s’affichent pas correctement lorsqu’ils sont ajoutés à un tableau de bord en tant que page externe. Au lieu d’utiliser la vue/les filtres uniques associés au lien, le tableau de bord utilise la dernière vue/les derniers filtres appliqués à l’équilibreur de charge de travail.

**Ajout du champ [!UICONTROL Intégrations] à l’en-tête personnalisé du projet**

*Projets*

Vous pouvez maintenant ajouter le champ [!UICONTROL Intégrations] à l’en-tête personnalisé d’un projet lorsque vous utilisez un modèle de mise en page. Une fois ajouté, ce champ affiche un lien menant à un élément externe lié au projet, situé dans [!DNL Salesforce] ou [!DNL Anaplan] en fonction de votre intégration.

>[!NOTE]
>
>Cette mise à jour de maintenance n’est actuellement disponible que dans l’environnement de prévisualisation. Elle passera en production une semaine après sa sortie en prévisualisation.

**Les données personnalisées ne sont pas conservées lors de la conversion d’un événement en projet vierge**

*Projets*

Lorsque l’utilisateur convertit un événement en projet vierge (sans modèle), les données des champs calculés ne sont pas transférées vers le nouveau projet.

**Erreur de type « Mode Planification de la chronologie » lorsqu’une date est modifiée dans un projet**

*Projets*

Lorsque l’utilisateur tente de modifier une date dans un projet pour lequel le [!UICONTROL mode de planification] est défini sur [!UICONTROL Enregistrer manuellement] > [!UICONTROL Planification de la chronologie], la date ne change pas et un message d’erreur apparaît.

« [!UICONTROL Le mode Planification de la chronologie n’est disponible que lorsque timelineDate est chargée. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.] »

**Cohérence lors de l’ouverture de l’équilibreur de charge de travail en vue Mois**

*Équilbreur de charge de travail*

L’équilibreur de charge de travail développe désormais l’affichage des éléments affectés aux utilisateurs en vue [!UICONTROL Jour], [!UICONTROL Semaine] ou [!UICONTROL Mois]. Avant cette mise à jour, les éléments affectés étaient développés dans les vues [!UICONTROL Jour] et [!UICONTROL Semaine] et réduits dans la vue [!UICONTROL Mois].


+++

+++**Mise à jour de maintenance le 18 août 2022**

**Les options « [!UICONTROL Ajouter à l’itération] » et « [!UICONTROL Ajouter au tableau kanban] » ne sont pas disponibles lors de la modification sur la ligne d’un rapport**

*Rapports*

Lorsque l’utilisateur consulte une liste de tâches dans un rapport et ouvre le menu [!UICONTROL Plus] (trois points), les options « [!UICONTROL Ajouter à l’itération] » et « [!UICONTROL Ajouter au tableau kanban] » ne sont pas sélectionnables dans la liste déroulante. Si le rapport est consulté dans un tableau de bord, les options « [!UICONTROL Ajouter à l’itération] » et « [!UICONTROL Ajouter au tableau kanban] » sont sélectionnables dans la liste déroulante.

**Rapports de la matrice ne s’affichent pas correctement lors du défilement**

*Rapports*

Lorsque l’utilisateur consulte un rapport de la matrice et le fait défiler, certains éléments visuels du rapport peuvent se chevaucher ou se dupliquer.

Suppression de la vue **[!UICONTROL Jalon] de la liste des projets de feuilles de temps**

*Feuilles de temps*

La vue [!UICONTROL Jalon] a été supprimée de la liste des projets de la feuille de temps lors de l’ajout d’un projet.

**Les liens hypertextes d’une épreuve interactive sont inactifs**

*[!DNL Workfront Proof]*

Lorsque l’utilisateur consulte une épreuve interactive et clique sur un lien ou un bouton contenant un lien, il n’est pas redirigé vers la page à laquelle le lien ou le bouton renvoie.

**Pas de champs de texte sur la page Nouvelle épreuve**

*[!DNL Workfront Proof]*

De nombreux champs de texte n’apparaissent pas sur la page [!DNL New Proof] (notamment les libellés des champs, les options des listes déroulantes et les noms des cases à cocher).

**Les utilisateurs ne reçoivent pas de notifications lorsqu’ils sont identifiés dans une épreuve**

*[!DNL Workfront Proof]*

Lorsque l’utilisateur est identifié dans un commentaire d’épreuve, il ne reçoit aucune notification par e-mail concernant ce commentaire.

+++

+++**Mise à jour de maintenance le 12 août 2022**

**Nouveau champ d’en-tête personnalisable ajouté au début de l’en-tête**

*En-têtes*

Lorsque vous ajoutez un nouveau champ à un en-tête personnalisable, le champ est maintenant ajouté en tant que premier champ à gauche de l’en-tête, ou juste après la zone [!UICONTROL Rechercher] dans le modèle de mise en page. Avant cette modification, le champ était ajouté en tant que dernier champ de l’en-tête.

+++

+++**Mise à jour de maintenance le 11 août 2022**

**Impossible de modifier les formulaires personnalisés en raison d’une limite de caractères incorrecte appliquée aux champs de texte descriptif**

*Formulaires personnalisés*

Lorsque l’utilisateur tente de modifier un formulaire personnalisé qui comporte un champ de [!UICONTROL texte descriptif] contenant alors plus de 512 caractères, il est impossible d’enregistrer les modifications apportées au formulaire, et le message d’erreur suivant apparaît :

« Les champs suivants ne sont pas valides : (champ) est trop long, 512 caractères max. »

Cela concerne les champs de [!UICONTROL texte descriptif] qui ne posaient auparavant pas de problème, même s’ils comportaient plus de 512 caractères.

**Les données des champs masquées par un saut de section ne sont pas conservées lors de la conversion d’un événement en projet**

*Formulaires personnalisés*

Lorsque l’utilisateur convertit un événement en projet et qu’il inclut un formulaire personnalisé avec des données dans un saut de section pouvant être masquées par la logique de rendu, les données de cette section ne sont pas conservées dans le nouveau projet.

**Les données des champs masquées par un saut de section ne sont pas conservées lors de la conversion d’une demande en projet**

*Formulaires personnalisés*

Lorsque l’utilisateur convertit une demande en projet et qu’elle inclut un formulaire personnalisé avec des données dans un saut de section pouvant être masquées par la logique de rendu, les données de cette section ne sont pas conservées dans le nouveau projet.

**Impossible de modifier les formulaires personnalisés en raison du champ de texte descriptif**

*Formulaires personnalisés*

Lorsque l’utilisateur tente de modifier un formulaire personnalisé qui comprend un champ de texte descriptif, le libellé du champ n’est pas renseigné. L’erreur « [!UICONTROL Ce champ est obligatoire] » apparaît sous le champ du libellé et empêche toute modification du formulaire personnalisé.

**Impossible de supprimer les instructions d’un champ personnalisé dans le créateur de formulaires personnalisés**

*Formulaires personnalisés*

Lorsque l’utilisateur modifie un champ personnalisé et tente de supprimer le texte existant dans la zone [!UICONTROL Instructions], le texte n’est pas supprimé lorsque le champ est enregistré. L’utilisateur peut modifier le texte sans le supprimer entièrement.

**L’affectation d’équipes lors de la création d’une demande n’apparaît pas sur la nouvelle demande**

*Demandes*

Lorsque l’utilisateur crée une demande et qu’il y affecte une équipe, puis soumet la demande, l’équipe n’est pas affectée à la demande créée. Seule l’affectation d’équipes est concernée par ce problème. La fonction d’affectation d’utilisateurs fonctionne comme prévu.

+++

+++**Mise à jour de maintenance le 4 août 2022**

Ces problèmes ont uniquement été résolus dans la nouvelle expérience [!DNL Workfront].

Toutes les fonctionnalités de [!DNL Workfront Classic] ont été supprimées le 14 juillet 2022.

**Erreur lors de la modification de la Date d’achèvement prévue dans l’en-tête d’une tâche ou d’un événement**

*Tâches et événements*

Lorsque l’utilisateur tente de modifier la [!UICONTROL Date d’achèvement prévue] dans l’en-tête d’une tâche ou d’un événement, la date ne change pas et une erreur telle que celle-ci se produit :

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Mises à jour de juillet 2022

+++**Mise à jour de maintenance le 28 juillet 2022**

Ces problèmes ont uniquement été résolus dans la nouvelle expérience [!DNL Workfront].

Toutes les fonctionnalités de [!DNL Workfront Classic] ont été supprimées le 14 juillet 2022.

**Erreur lors de l’ouverture d’un élément à partir de la [!UICONTROL Liste de travail de l’accueil]**

*[!UICONTROL Page d’accueil]*

Lorsque l’utilisateur tente d’ouvrir un élément de sa [!UICONTROL Liste de travail de l’accueil], l’élément ne s’ouvre pas et le message suivant apparaît :

« [!UICONTROL Une erreur s’est produite et nous travaillons à résoudre le problème. Pour continuer votre travail, essayez d’actualiser cette page de navigateur. ]»

**Les tâches et les événements délégués à l’utilisateur n’apparaissent pas dans sa Liste de travail de l’accueil**

*[!UICONTROL Page d’accueil]*

Lorsque l’utilisateur consulte sa [!UICONTROL Liste de travail de l’accueil], les tâches ou événements qui lui ont été délégué(e)s n’apparaissent pas et il n’est parfois pas informé de ces délégations.

**Les rapports planifiés ne sont pas envoyés à tous les destinataires**

*Rapports*

Lorsqu’un rapport planifié est envoyé, il n’est pas envoyé à tous les utilisateurs dans la section « [!UICONTROL Envoyer à] ». Les utilisateurs omis sont aléatoires et peuvent varier à chaque envoi du rapport.

**[!UICONTROL Impossible de désélectionner les tâches lorsqu’un modèle est joint]**

*Modèles*

Lorsque l’utilisateur joint et personnalise un modèle, il est invité à désélectionner les tâches qu’il ne souhaite pas inclure. Toutefois, aucune des tâches ne s’affiche comme étant sélectionnée et il est impossible de les désélectionner.

**Les libellés des champs « Paramètres régionaux » sont désormais plus précis**

*Terminologie*

Nous avons mis à jour les libellés des champs « [!UICONTROL Paramètres régionaux] » pour clarifier leur fonction.

* Le champ « [!UICONTROL Paramètres régionaux] » du profil utilisateur est maintenant intitulé « [!UICONTROL Paramètres régionaux des e-mails] »
* Le champ « [!UICONTROL Paramètres régionaux] » de la zone [!UICONTROL Configuration] > [!UICONTROL Système] > [!UICONTROL Informations de clients] est désormais intitulé « [!UICONTROL Paramètres régionaux des e-mails par défaut] »

La fonction de ces champs n’a pas changé.

**Problèmes lors de la création des feuilles de temps**

*Feuilles de temps*

Les problèmes suivants ont été signalés lors de la création des feuilles de temps :

* Lorsque l’utilisateur tente de créer une feuille de temps pour un rôle, celle-ci n’est pas créée et le message d’erreur « [!UICONTROL Utilisateur avec valeur(s) de clé primaire “XXXXXXXXXXX” introuvable]. » apparaît.
* Lorsque l’utilisateur tente de créer une feuille de temps pour une équipe, le champ de [!UICONTROL saisie semi-automatique] n’est pas renseigné avec les équipes et le bouton [!UICONTROL Créer une feuille de temps] n’est pas sélectionnable.


**Certaines zones de [!DNL Workfront Proof] ne se mettent pas à jour lorsqu’une épreuve est créée, déplacée ou archivée**

*[!DNL Workfront] Épreuve*

L’indexation sur Proof prend actuellement plus de temps que prévu. Cela peut avoir diverses conséquences sur l’expérience utilisateur, notamment :

* Les tableaux de bord n’affichent pas le nombre correct d’épreuves
* Les dossiers ne sont pas mis à jour lorsqu’une épreuve est créée ou déplacée
* Les épreuves archivées restent dans les listes d’épreuves actives

+++

+++**Mise à jour de maintenance (correctif) le 26 juillet 2022**

Ces problèmes ont uniquement été résolus dans la nouvelle expérience [!DNL Workfront].

Toutes les fonctionnalités de [!DNL Workfront Classic] ont été supprimées le 14 juillet 2022.

**Les heures indiquées sur la feuille de temps diffèrent de celles sur la liste Feuilles de temps**

*Feuilles de temps*

Lorsque l’utilisateur ouvre une feuille de temps pour la consulter, les heures indiquées diffèrent de celles affichées lorsque l’utilisateur consulte la même feuille de temps dans une liste Feuilles de temps.


**Les demandes converties en projets avec un modèle indiquent le groupe de la file d’attente des demandes, et non le groupe du modèle**

*Demandes*

Lorsque l’utilisateur convertit une demande en projet à l’aide d’un modèle, le projet nouvellement créé est associé au groupe propriétaire de la file d’attente des demandes, et non pas au groupe affecté dans le modèle. Cela se produit même si, lors de la création du projet, le groupe associé au modèle est renseigné dans le champ [!UICONTROL Groupe].

+++

+++**Mise à jour de maintenance le 21 juillet 2022**

Ces problèmes ont uniquement été résolus dans la nouvelle expérience [!DNL Workfront].

Toutes les fonctionnalités de [!DNL Workfront Classic] ont été supprimées le 14 juillet 2022.

**Le statut Rejeté associé à une approbation suit le workflow d’approbation²**

**REMARQUE : cette fonctionnalité est sortie le 22 juillet 2022.**

*Approbations*

Si vous sélectionnez un statut associé à un processus d’approbation, comme le statut Rejeté pour un chemin d’approbation, l’objet rejeté passe au statut sélectionné et est marqué comme « [!UICONTROL En attente d’approbation] ». Par exemple, si vous sélectionnez [!UICONTROL En attente] pour le statut Rejeté alors que le statut [!UICONTROL En attente] est associé à un processus d’approbation, le statut de l’objet rejeté devient « [!UICONTROL En attente d’approbation] » et une approbation est nécessaire.

Avant cette mise à jour, l’objet ignorait le processus d’approbation du statut Rejeté et son statut était défini sur [!UICONTROL En attente].

**Configuration d’une URL d’aide personnalisée**

*[!UICONTROL Menu principal]*

Si votre organisation possède un site d’aide interne personnalisé, vous pouvez configurer l’icône d’[!UICONTROL Aide] du [!UICONTROL Menu principal] de manière à renvoyer vers ce site. Ce renvoi est utile si le site d’aide contient des informations sur la manière dont votre organisation utilise [!DNL Workfront].
Cette URL personnalisée n’a aucune incidence sur le lien d’aide principal situé en haut de [!DNL Workfront], ni sur les liens d’aide contextuelle dans [!DNL Workfront] qui renvoient les utilisateurs sur le site d’aide de [!DNL Workfront].

**Impossible de sélectionner le Temps écoulé en modifiant la [!UICONTROL Durée de la tâche sur la ligne]**

*Tâches*

Lorsque l’utilisateur consulte une liste de tâches et tente de modifier la [!UICONTROL Durée de la tâche], les unités de durée écoulée suivantes ne sont pas sélectionnables :

* [!UICONTROL Minutes écoulées]
* [!UICONTROL Heures écoulées]
* [!UICONTROL Jours écoulés]
* [!UICONTROL Semaines écoulées]
* [!UICONTROL Mois écoulés]

La page **[!UICONTROL Mes mises à jour] est vierge**

*Mises à jour*

Lorsque l’utilisateur tente d’afficher sa page [!UICONTROL Mes mises à jour], elle ne se charge pas. Seul l’en-tête de navigation [!DNL Workfront] apparaît.

**Aucun paramètre « [!UICONTROL Autoriser uniquement l’authentification SAML 2.0] » lors de la copie d’un utilisateur**

*Utilisateurs*

Lorsque l’administrateur de groupes copie un utilisateur et désélectionne l’option « [!UICONTROL Envoyer une invitation par e-mail à cette personne] », la case à cocher « [!UICONTROL Autoriser uniquement l’authentification SAML 2.0] » n’apparaît pas comme prévu. Cela peut se produire même si toutes les exigences d’accès et d’autorisation pour cette action sont remplies.

+++

+++**Mise à jour de maintenance le 14 juillet 2022**

Ces problèmes ont uniquement été résolus dans la nouvelle expérience [!DNL Workfront].

Toutes les fonctionnalités de [!DNL Workfront Classic] ont été supprimées le 14 juillet 2022.

**Erreur lors de la réinitialisation du mot de passe**

*Connexion*

Lorsque l’utilisateur tente de réinitialiser son mot de passe, il n’y parvient pas et un message lui indiquant qu’il n’a pas accès apparaît. L’utilisateur ne peut pas se connecter à Workfront.

**Impossible de demander un accès plus étendu à un rapport**

*Rapports*

Lorsque l’utilisateur à l’accès limité à un rapport tente de demander un accès plus étendu à un rapport, l’option correspondante n’est pas sélectionnable dans le menu [!UICONTROL Actions liées aux rapports].

**Mise à jour du message de confirmation lors de la suppression d’un brouillon de demande**

*Demandes*

Lors de l’abandon d’un brouillon de demande, le message de confirmation qui s’affiche après avoir cliqué sur « [!UICONTROL Ignorer le brouillon] » indique ceci :

* [!UICONTROL Le brouillon a été ignoré] (il s’agit d’une notification vous informant que votre brouillon a été ignoré)
* [!UICONTROL Annuler] (il s’agit d’un lien sur lequel vous pouvez cliquer pour annuler la suppression du brouillon. Le brouillon ne sera pas supprimé, mais conservé.)

Avant cette modification, les options disponibles étaient les suivantes :

* [!UICONTROL Le brouillon sera ignoré]
* [!UICONTROL Annuler]

**Valeurs de date des champs d’Entrée du journal incorrectes lorsqu’elles sont consultées avec l’API**

*Mises à jour*

Lorsque l’utilisateur modifie une valeur de date sur un objet, puis qu’il consulte l’Entrée du journal représentant ce changement de date avec l’API, les valeurs de date pour [!UICONTROL oldDateVal] et [!UICONTROL newDateVal] renvoyés par l’API sont incorrectes.

**Erreur lors de la tentative d’annulation d’un commentaire**

*Mises à jour*

Lorsque l’utilisateur tente d’annuler un commentaire, celui-ci n’est pas annulé et le message d’erreur suivant apparaît :

[!UICONTROL Erreur 403 : Vous ne disposez pas d’un accès suffisant pour supprimer ce commentaire /attask/api-internal/NOTE]

**Nouvelle limitation du nombre de caractères d’une mise à jour dans la Prévisualisation**

*Mises à jour*

Pour améliorer les performances de la zone [!UICONTROL Mises à jour], une nouvelle limite de nombre de caractères saisis dans une mise à jour ou une réponse à une mise à jour existante a été ajoutée. La nouvelle limite est de 15 000 caractères. Cette mise à jour n’a pas modifié le nombre de caractères autorisés avec l’API. La limite de caractères des mises à jour avec l’API est de 4 000.

**Erreur lors du chargement d’une pièce jointe depuis [!DNL Workfront] pour l’intégration Outlook**

*Intégrations Workfront*

Lorsque l’utilisateur tente de charger une pièce jointe avec l’intégration [!DNL Workfront for Outlook], la pièce jointe ne se charge pas et le message suivant apparaît :

[!UICONTROL Certaines pièces jointes n’ont pas été chargées. Cause : un problème est survenu au moment du chargement des pièces jointes.]

**Mise à jour des notifications par e-mail liées aux épreuves**

*[!DNL Workfront] Épreuve*

Un correctif déployé ce mois-ci destiné à l’environnement d’Exploitation de [!DNL Workfront] corrige également un bug concernant le système d’envoi de notifications par e-mail en lien avec les épreuves. Cette modification n’a pas été recensée dans la mise à jour de maintenance lors de sa publication. Nous avons ajouté les informations suivantes à la [Mise à jour de maintenance le 2 juin 2022](#maintenance-update-on-june-2-2022) :

Suite à ces correctifs, l’adresse e-mail utilisée pour envoyer les notifications liées aux épreuves a changé.

Auparavant, les adresses e-mail d’épreuves contenaient le sous-domaine de votre organisation. Par exemple, notifications@[domaine de l’entreprise].my.workfront.com

Désormais, les adresses e-mail d’épreuves ne contiennent plus le sous-domaine de l’organisation. Toutes les notifications par e-mail liées aux épreuves proviennent de l’adresse suivante : notification@my.workfront.com

Par conséquent, nous vous recommandons d’effectuer les actions suivantes si vous ne l’avez pas déjà fait :

* Mettez à jour vos filtres antispam pour accepter les e-mails de notification@my.workfront.com
* Mettez à jour vos listes autorisées pour accepter les e-mails de notification@my.workfront.com

**Impossible de modifier les options de l’utilisateur après la configuration initiale dans les modèles de workflow**

*[!DNL Workfront Proof]*

Lorsque l’utilisateur ajoute un utilisateur à un Modèle de workflow, il peut configurer des options. Cependant, une fois la configuration initiale terminée, l’utilisateur ne peut plus modifier les éléments suivants :

* la capacité « [!UICONTROL Résoudre les commentaires et appliquer les mesures] »
* la capacité « [!UICONTROL Partager l’épreuve en identifiant un ou des utilisateurs] »
* le rôle dans l’épreuve ([!UICONTROL Réviseur], [!UICONTROL Approbateur], etc.)

**Le filtre « [!UICONTROL Tâches de ce projet] » a été rétabli dans l’[!UICONTROL équilibreur de charge de travail]** du projet

*[!UICONTROL Équilbreur de charge de travail]*

Le filtre « Tâches de ce projet » a été rétabli dans la zone [!UICONTROL Affecté] lorsque vous accédez à l’[!UICONTROL équilibreur de charge de travail] depuis un projet.

Ce filtre se trouve désormais dans la section « [!UICONTROL Suggestions] » des filtres de la zone [!UICONTROL Tâches affectées] de l’[!UICONTROL équilibreur de charge de travail] d’un projet.

+++

## Mises à jour de juin 2022

+++**Mise à jour de maintenance le 30 juin 2022**

**Afficher l’[!UICONTROL équilibreur de charge de travail] pendant une semaine**

*[!UICONTROL Équilbreur de charge de travail]*

Au vu des commentaires de nombreux clients, une option permettant d’afficher l’[!UICONTROL équilibreur de charge de travail] pendant une semaine a été ajoutée. Avant cette mise à jour, l’[!UICONTROL équilibreur de charge de travail] pouvait être affiché pendant 4, 6 ou 12 semaines. Cette mise à jour modifie également l’option de 12 semaines, qui passe à 3 mois.

**Le panneau Délégué est désormais disponible dans l’équilibreur de charge de travail**

*[!UICONTROL Équilbreur de charge de travail]*

REMARQUE : cette mise à jour est uniquement valable pour l’environnement de prévisualisation. Les fonctionnalités associées à cette mise à jour seront mises en production avec la version 22.3.

Vous pouvez désormais afficher les délégués d’une tâche ou d’un événement dans l’équilibreur de charge de travail. Lors de l’affectation d’une tâche ou d’un événement à partir de l’équilibreur de charge de travail, vous pouvez consulter la liste des affectations ainsi que celle des délégués pour la tâche ou l’événement, s’ils sont actuellement délégués.

**Impossible d’ouvrir les informations de point d’entrée dans l’API Explorer**

*API*

Lorsque l’utilisateur consulte l’[!DNL API Explorer] et clique sur un point d’entrée, les informations de celui-ci ne s’affichent pas.

**Problèmes liés au bouton [!UICONTROL Détails] lors de l’utilisation du [!UICONTROL Calendrier de l’accueil]**

*Page d’accueil*

Lorsque l’utilisateur utilise le [!UICONTROL Calendrier de l’accueil] et clique sur une tâche, l’un des événements suivants peut se produire :

* Le bouton [!UICONTROL Détails] apparaît brièvement, puis disparaît. L’utilisateur ne peut pas accéder aux détails.
* Le bouton [!UICONTROL Détails] n’apparaît pas. L’utilisateur ne peut pas accéder aux détails.
* Le bouton [!UICONTROL Détails] apparaît, mais n’est pas à l’emplacement correct. L’utilisateur peut cliquer sur le bouton pour accéder aux détails.

+++

+++**Mise à jour de maintenance (correctif) le 24 juin 2022**

**Le sélecteur de date ne se ferme pas lorsque le formulaire personnalisé est modifié**

*Formulaires personnalisés*

Lorsque l’utilisateur modifie un formulaire personnalisé et tente de changer une date, le sélecteur de date ne se ferme pas lorsque la date est sélectionnée. L’utilisateur ne peut pas fermer le sélecteur de date en enregistrant, en annulant ou en cliquant hors du sélecteur de date.

Les zones suivantes sont concernées :

* Zone des [!UICONTROL Mises à jour]
* [!UICONTROL Page d’accueil]

**L’utilisateur ne peut pas se déplacer vers une autre étape d’une épreuve**

*Épreuves*

Lorsque l’utilisateur consulte le [!UICONTROL workflow d’une épreuve] et tente de glisser son propre nom vers une autre étape de l’épreuve, son nom revient à l’étape d’origine et n’est pas ajouté à l’étape souhaitée.

+++

+++**Mise à jour de maintenance le 23 juin 2022**

**[!UICONTROL Impossible d’ajouter une nouvelle demande depuis le tableau de bord]**

*Tableaux de bord*

Lorsque l’utilisateur consulte le tableau de bord d’un projet et tente d’ajouter une nouvelle demande en cliquant sur le bouton [!UICONTROL +Nouvelle demande], le bouton ne répond pas et l’ajout d’une nouvelle demande est impossible.

**Erreur lors de l’affichage d’éléments dans la Liste de travail de l’accueil**

*[!UICONTROL Page d’accueil]*

Lorsque l’utilisateur consulte sa [!UICONTROL Liste de travail de l’accueil] et clique sur un élément de la section [!UICONTROL Mes approbations soumises], la page affiche le message d’erreur suivant :

« [!UICONTROL Une erreur s’est produite et nous travaillons à résoudre le problème. Pour continuer votre travail, essayez d’actualiser cette page de navigateur.] »

Si l’utilisateur actualise la page, puis clique sur n’importe quel élément de la [!UICONTROL Liste de travail], le message d’erreur apparaît. Le problème ne concerne plus uniquement les éléments de la section [!UICONTROL Mes approbations soumises].

**La section personnalisée d’un objet inclut des résultats qui ne sont pas dans cet objet**

*Objets*

Lorsque l’utilisateur consulte une section [!UICONTROL personnalisée] d’un objet, cette section affiche des éléments qui ne font pas partie de cet objet. Ce problème a été signalé lorsque la section personnalisée est ajoutée directement à l’objet, et lorsqu’une section personnalisée est ajoutée au moyen d’un modèle de mise en page.

**Les tâches ne sont pas déplacées vers le bon projet**

*Tâches*

Lorsque l’utilisateur déplace des tâches du projet A vers le projet B, puis déplace d’autres tâches du projet A vers le projet C, les tâches initialement déplacées vers le projet B apparaissent dans le projet C.

**Certains boutons et icônes ne fonctionnent pas lors de l’accès à l’[!UICONTROL équilibreur de charge de travail] depuis un lien partagé ou un tableau de bord**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsque l’utilisateur accède à l’[!UICONTROL équilibreur de charge de travail] depuis un lien partagé ou un lien dans un tableau de bord et tente d’utiliser l’un des éléments en haut de l’écran, les éléments ne fonctionnent pas. Les éléments suivants sont concernés :

* [!UICONTROL Aujourd’hui]
* Flèches Précédent et Suivant
* [!UICONTROL Semaines]
* Icône du calendrier (sélecteur de date)

+++

+++Mise à jour de maintenance pour le Planificateur de scénario **[!DNL Workfront]le 23 juin 2022**

**Les utilisateurs disposant d’autorisations de niveau [!UICONTROL Gérer] pour un plan peuvent le partager avec d’autres personnes**

Les utilisateurs disposant d’autorisations de niveau [!UICONTROL Gérer] pour un plan dans le [!DNL Scenario Planner]peuvent désormais le partager avec d’autres utilisateurs. Avant cette mise à jour, seul le créateur du plan pouvait partager son plan avec d’autres utilisateurs.

+++

+++**Mise à jour de maintenance le 16 juin 2022**

**L’administrateur de groupes ne peut pas ajouter de membres au groupe**

*Groupes*

Lorsque l’administrateur de groupes tente d’ajouter un utilisateur à un groupe, la liste déroulante pour sélectionner l’utilisateur ne s’affiche pas. L’administrateur de groupes ne peut sélectionner aucun utilisateur et ne peut donc en ajouter aucun au groupe.

**Les trimestres personnalisés ne s’affichent pas lors de l’application d’un filtre**

*Filtres*

Lorsque l’utilisateur crée un filtre et applique un filtre de champ de date, la liste déroulante des opérateurs disponibles pour le champ de date n’inclut aucun trimestre personnalisé récemment ajouté.

**Erreur de type « Oups » lors de la conversion d’un événement en projet dans un modèle**

*Projets*

Lorsque l’utilisateur tente de convertir un événement en projet dans un modèle et que l’événement inclut un formulaire personnalisé contenant une section réservée aux administrateurs, l’événement n’est pas converti et le message d’erreur suivant apparaît :

« [!UICONTROL Réessayons. Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.] »

**Les demandes sont soumises avec des champs obligatoires vides**

*Demandes*

Lorsque l’utilisateur crée une demande et ne remplit pas les champs obligatoires, puis soumet la demande, celle-ci est soumise alors que les champs obligatoires sont vides. La demande ne devrait pas être soumise, et l’utilisateur devrait être prévenu qu’il doit renseigner les champs obligatoires avant de soumettre la demande.

**Les nouveaux trimestres personnalisés ne semblent pas s’enregistrer**

*Configuration*

Lorsque l’utilisateur ajoute un nouveau trimestre personnalisé à partir de la zone des Projets de la Configuration et clique sur [!UICONTROL Enregistrer], aucune indication visuelle de l’enregistrement n’apparaît. Aucun message d’enregistrement effectué n’apparaît et le bouton [!UICONTROL Enregistrer] reste affiché et sélectionnable. Cependant, si l’utilisateur actualise la page, les nouveaux trimestres apparaissent dans la liste des trimestres personnalisés.

Si l’utilisateur ajoute un nouveau trimestre, clique sur [!UICONTROL Enregistrer], ne voit aucune preuve de l’enregistrement, ajoute un autre trimestre sans actualiser la page, puis clique de nouveau sur [!UICONTROL Enregistrer], le deuxième trimestre ajouté peut ne pas être enregistré.

La page **[!UICONTROL Demandes de tâches d’équipe] est vierge**

*Équipes*

REMARQUE : ce problème est uniquement présent dans l’environnement de prévisualisation.

Lorsque l’utilisateur tente d’ouvrir la zone [!UICONTROL Demandes de travail] sur une page d’équipe, la page est vierge. La barre de navigation supérieure apparaît, mais pas le contenu de la page.

+++

+++**Mise à jour de maintenance le 9 juin 2022**

**Impossible de sélectionner les objets à filtrer dans les préférences de l’[!UICONTROL optimisateur de portfolio]**

*Portefeuilles*

Lorsque l’utilisateur consulte l’onglet [!UICONTROL Filtres de projet] dans les [!UICONTROL Préférences] de l’[!UICONTROL optimisateur de portfolio], les cases à cocher devant se trouver près des objets ont disparu. L’utilisateur ne peut pas interagir avec les cases, et par conséquent ne peut pas sélectionner d’objets à filtrer.

**Impossible de modifier la [!UICONTROL Date de début prévue] ou la [!UICONTROL Date d’achèvement prévue] lorsque la case « [!UICONTROL Planifier à partir de] » n’est pas cochée**

*Projets*

Lorsque l’utilisateur tente de modifier la [!UICONTROL Date de début prévue] ou la [!UICONTROL Date d’achèvement prévue] d’un projet et que l’option « [!UICONTROL Planifier à partir de] » n’est pas cochée pour ce projet, les zones de la [!UICONTROL Date de début prévue] et de la [!UICONTROL Date d’achèvement prévue] sont désactivées et l’utilisateur ne peut pas modifier ces dates.

**Impossible de modifier le niveau d’accès des utilisateurs**

*Utilisateurs*

Lorsque l’utilisateur disposant d’un accès de niveau Planificateur qui inclut un accès de niveau Administrateur d’utilisateurs (Groupe d’utilisateurs) tente de modifier des utilisateurs du groupe dont il est administrateur, le champ [!UICONTROL Niveau d’accès] est désactivé et l’utilisateur ne peut pas modifier le niveau d’accès.

+++

+++**[!DNL Workfront Scenario Planner]Mise à jour de maintenance le 9 juin 2022**

**Panneau de gauche redimensionnable dans [!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

Vous pouvez désormais redimensionner le panneau de gauche d’un plan dans le [!DNL Scenario Planner]. Ainsi, les noms d’initiative plus longs peuvent s’afficher entièrement. Avant cette mise à jour, les noms d’initiative plus longs étaient tronqués.

+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 9 juin 2022**

**Certaines données provenant de formulaires personnalisés ne sont pas disponibles dans les [!DNL Workfront Fusion] [!DNL Workfront] modules**

*[!DNL Workfront Fusion]*

Lorsque l’utilisateur configure un module [!DNL Workfront] dans [!DNL Workfront Fusion] et tente de sélectionner des sorties pour le module, les champs des formulaires personnalisés ne sont pas visibles. Cela se produit lorsque le formulaire personnalisé a été créé pour un type d’objet [!DNL Workfront] et qu’un autre type y a ensuite été ajouté. [!DNL Workfront Fusion] affiche uniquement les champs de formulaires personnalisés initialement créés pour le type d’objet sélectionné.

**Impossible de faire défiler la page pour afficher toutes les exécutions de scénario**

*[!DNL Workfront Fusion]*

Lorsque l’utilisateur consulte l’historique d’exécution d’un scénario et tente de faire défiler l’écran vers le bas pour afficher davantage d’exécutions, les exécutions ne se chargent plus et l’utilisateur ne peut pas les consulter. Il ne peut pas non plus remonter jusqu’aux exécutions les plus récentes.

+++

+++**Mise à jour de maintenance le 2 juin 2022**

L’**[!UICONTROL optimisateur de portfolio] indique un score de 0 lors de l’utilisation d’une langue autre que l’anglais**

*Portefeuilles*

Lorsque l’utilisateur définit une langue autre que l’anglais pour [!DNL Workfront] et ouvre l’[!UICONTROL optimisateur de portfolio], le score indiqué est de 0. Ce problème peut survenir même lorsque l’analyse de rentabilité n’est pas terminée.

**Les valeurs des champs calculés ne sont pas correctes lors de la création d’un projet à partir d’un modèle**

*Projets*

Lorsque l’utilisateur crée un projet à partir d’un modèle qui inclut des champs calculés, les valeurs des champs qui apparaissent sur le nouveau projet sont incorrectes.

**Impossible de modifier les [!UICONTROL Conditions] dans les [!UICONTROL Préférences du projet] de la [!UICONTROL Configuration]**

*[!UICONTROL Configuration]*

Lorsque l’utilisateur tente de modifier les [!UICONTROL Conditions] dans les [!UICONTROL Préférences du projet] de la [!UICONTROL Configuration], la page est vierge.

**Nouvelle limitation du nombre de caractères d’une mise à jour dans la Prévisualisation**

*[!UICONTROL Équilbreur de charge de travail]*

>[!NOTE]
>
>Cette mise à jour est uniquement valable pour l’environnement de prévisualisation.

Pour améliorer les performances de la zone Mises à jour, une nouvelle limite de nombre de caractères saisis dans une mise à jour ou une réponse à une mise à jour existante a été ajoutée. La nouvelle limite est de 15 000 caractères. Cette mise à jour n’a pas modifié le nombre de caractères autorisés avec l’API. La limite de caractères des mises à jour avec l’API est de 4 000. Mises à jour Prise en charge des champs personnalisés de saisie semi-automatique dans les filtres de l’équilibreur de charge de travail

Les filtres basés sur les champs personnalisés de [!UICONTROL saisie semi-automatique] sont désormais compatibles avec l’équilibreur de charge de travail. Avant ce correctif, le filtrage de ce type de champs personnalisés n’était pas possible dans l’équilibreur de charge de travail.

**Impossible de modifier les autorisations du rôle d’un utilisateur**

*[!DNL Workfront Proof]*

Lorsque l’utilisateur tente de modifier les autorisations « [!UICONTROL Résoudre les commentaires et appliquer les mesures] » ou « [!UICONTROL Partager l’épreuve en identifiant un ou des utilisateurs] » du rôle d’un utilisateur dans [!DNL Workfront Proof], les modifications ne s’enregistrent pas. L’utilisateur reçoit une notification indiquant que le modèle a été mis à jour, mais s’il ouvre à nouveau les autorisations de rôle, il constate que les modifications n’ont pas été enregistrées.

+++


## Mises à jour de mai 2022

+++**Mise à jour de maintenance le 26 mai 2022**

Ces problèmes ont uniquement été résolus dans la nouvelle expérience [!DNL Workfront]. [!DNL Adobe Workfront Classic] n’est plus pris en charge.

Toutes les fonctionnalités [!DNL Workfront Classic] disparaîtront au mois de juillet 2022. Passez à la nouvelle expérience dès que possible.

**Mise à jour des séparateurs de chemin de navigation**

*[!DNL Workfront]*

REMARQUE : cette mise à jour a été publiée le 24 mai 2022.

Les séparateurs de chemin de navigation ont été mis à jour dans toutes les zones où ils sont disponibles. Désormais, les objets des chemins de navigation sont séparés par des barres verticales (|). Avant cette mise à jour, ils étaient séparés par des barres obliques (/).

**Impossible d’ajouter des sauts de section aux formulaires personnalisés**

*Formulaires personnalisés*

Lorsque l’utilisateur tente de modifier un formulaire personnalisé comprenant un saut de section, il n’y parvient pas et le message suivant s’affiche :

[!UICONTROL La sécurité du saut de section spécifiée ne peut pas être appliquée à tous les types d’objet]

**Problèmes lors de l’impression des tableaux de bord au format PDF**

*Tableaux de bord*

Les problèmes suivants ont été signalés lors de l’impression d’un tableau de bord au format PDF : Toutes les lignes du rapport ne figurent pas sur le PDF imprimé. À l’endroit des lignes sont manquantes, seuls des espaces vides apparaissent.
Le PDF inclut des espaces vides entre les en-têtes de colonne et la première ligne du rapport.

**[!DNL Portfolio Optimizer] indique un score de 0 lors de l’utilisation d’une langue autre que l’anglais**

*Portefeuilles*

Lorsque l’utilisateur définit une langue autre que l’anglais pour [!DNL Workfront] et ouvre l’[!UICONTROL optimisateur de portfolio], le score indiqué est de 0. Ce problème peut survenir même lorsque l’analyse de rentabilité n’est pas terminée.

**Certains formulaires personnalisés ne s’affichent pas lorsqu’un modèle est modifié**

*Modèles*

Lorsque l’utilisateur tente de modifier les formulaires personnalisés d’un modèle en cliquant sur [!UICONTROL Modifier] dans l’en-tête du modèle, la fenêtre [!UICONTROL Modifier le modèle] n’affiche que l’un des formulaires personnalisés joints au modèle.

**Le lien partagé avec l’équilibreur de charge de travail n’indique pas correctement les tâches affectées**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsque l’utilisateur consulte l’[!UICONTROL équilibreur de charge de travail] depuis un lien partagé, l’[!DNL Workload Balancer] inclut les [!UICONTROL Tâches affectées] dans la section [!UICONTROL Tâches non affectées]. Les [!UICONTROL Tâches affectées] ne comportent pas de section distincte. Lorsque l’utilisateur consulte l’[!UICONTROL équilibreur de charge de travail] sans utiliser le lien partagé, les [!UICONTROL Tâches affectées] apparaissent normalement.

+++

+++**Mise à jour de maintenance le 19 mai 2022**

**Impossible de créer une épreuve à partir d’un [!DNL PowerPoint]**

*[!DNL Workfront Proof]*

Lorsque l’utilisateur tente de créer une épreuve à partir d’un [!DNL PowerPoint] qui comprend un graphique, la création de l’épreuve échoue.

**Impossible de créer une épreuve à partir d’un document [!UICONTROL Word]**

*[!DNL Workfront Proof]*

Lorsque l’utilisateur tente de créer une épreuve à partir d’un document [!DNL Word] qui comprend un graphique, la création de l’épreuve échoue.

**Impossible d’ajouter un message personnalisé lors du partage d’une épreuve**

*[!DNL Workfront Proof]*

Lorsque l’utilisateur consulte une épreuve, ouvre la zone [!UICONTROL Partager l’épreuve] et sélectionne le bouton [!UICONTROL Ajouter un message personnalisé], il ne parvient pas à saisir du texte dans la zone qui s’ouvre. Lorsque l’utilisateur tente de saisir du texte dans cette zone, celle-ci disparaît aussitôt.

**Impossible de fermer l’épreuve**

*[!DNL Workfront Proof]*

Lorsque l’utilisateur consulte une épreuve et tente de la fermer, le X servant à fermer l’épreuve a disparu du coin supérieur droit de l’épreuve.

**Impossible d’ajouter ou de supprimer un administrateur de groupes**

*Groupes*

Si l’utilisateur consulte une page de [!UICONTROL Groupe] et tente d’ajouter ou de supprimer un administrateur de groupes depuis la zone [!UICONTROL Administrateurs de groupes] de l’en-tête, les modifications ne s’enregistrent pas et le message d’erreur suivant apparaît :

[!UICONTROL Erreur : Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.]

**La barre de défilement horizontale masque les éléments en fin de liste**

*Projets*

Lorsque l’utilisateur consulte une liste dans une vue qui continue hors de l’écran, la barre de défilement horizontale masque le dernier élément de la liste.

**« [!UICONTROL Erreur inattendue] » lors de la conversion d’un événement en projet dans un modèle**

*Listes*

Lorsque l’utilisateur tente de convertir un événement en projet avec un modèle, l’événement n’est pas converti et le message suivant apparaît :

[!UICONTROL Une erreur inattendue s’est produite]

**Le champ [!UICONTROL Statut] dans une vue de feuille de temps est désormais en lecture seule**

*Feuilles de temps*

Le champ [!UICONTROL Statut] dans une vue de feuille de temps est désormais en lecture seule. Avant cette modification, les utilisateurs pouvaient modifier sur la ligne le statut d’une feuille de temps et remplacer la décision des approbateurs de la feuille de temps.

+++

+++**Mise à jour de maintenance le 12 mai 2022**

Le bouton **[!UICONTROL Enregistrer] charge sans cesse lorsqu’un projet est modifié**

*Projets*

Lorsque l’utilisateur modifie un projet et tente de l’enregistrer, le bouton [!UICONTROL Enregistrer] indique le mot « [!UICONTROL Chargement] ». Si l’utilisateur clique sur ce bouton pour enregistrer les modifications apportées au projet, le bouton ne répond pas et les modifications ne sont pas enregistrées.

**Les libellés des champs disparaissent lors de l’affichage d’un objet dans l’[!UICONTROL Accueil]**

*Page d’accueil*

Lorsque l’utilisateur sélectionne un objet dans sa [!UICONTROL Liste de travail de l’accueil], la zone située à droite de la [!UICONTROL Liste de travail de l’accueil] qui affiche l’objet n’inclut pas les libellés des champs. Les valeurs des champs sont bien affichées.

**La barre de recherche n’est pas automatiquement sélectionnée lors de l’utilisation d’un filtre rapide**

*Listes*

Lorsque l’utilisateur se trouve dans une liste et clique sur la loupe pour utiliser un filtre rapide, puis commence à saisir son texte, celui-ci n’apparaît pas. En effet, l’icône de loupe est toujours sélectionnée au lieu de la barre de recherche.

Cliquer sur la barre de recherche permet de la sélectionner, et l’utilisateur peut saisir le texte de sa recherche.

**Certains utilisateurs ne peuvent pas insérer de champs de modification sur la ligne dans un rapport**

*Rapports*

Lorsque l’utilisateur tente de modifier un champ dans un rapport et que ce champ est extrait d’un formulaire personnalisé, il ne peut pas le modifier. Ce problème se produit lorsque le formulaire personnalisé a été initialement créé pour un type d’objet autre que celui auquel il est associé.

**Le libellé et le texte du bouton n’apparaissent pas lors de la création d’une épreuve**

*[!DNL Workfront Proof]*

REMARQUE : ce problème est uniquement présent dans l’environnement de prévisualisation.

Lorsque l’utilisateur tente de créer une épreuve, le texte des options ou des boutons ne s’affiche pas. Par conséquent, l’utilisateur ne sait pas ce que représentent les options ou les boutons et ne peut pas configurer l’épreuve.

+++

+++**Mise à jour de maintenance le 5 mai 2022**

**Impossible d’ajouter un nouvel enregistrement de facturation**

*Projets*

Lorsque l’utilisateur se trouve dans la zone [!UICONTROL Enregistrements de facturation] d’un projet dans la vue [!UICONTROL Nouvel enregistrement de facturation] et tente d’ajouter un nouvel enregistrement de facturation, les champs du nouvel enregistrement de facturation ne s’affichent pas et l’enregistrement de facturation ne peut pas être créé.

**Erreur lors de l’affectation en bloc dans l’[!UICONTROL équilibreur de charge de travail]**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsque l’utilisateur tente une affectation dans l’[!DNL Workload Balancer] d’un projet, il est redirigé vers une page affichant le message suivant :

« [!UICONTROL Une erreur s’est produite et nous travaillons à résoudre le problème. Pour continuer votre travail, essayez d’actualiser cette page de navigateur.] »

L’utilisateur ne peut pas quitter cette page tant qu’il ne l’actualise pas.

**Mise à jour de la navigation pour ouvrir le panneau [!UICONTROL Résumé] pour les tâches et les événements dans l’[!UICONTROL équilibreur de charge de travail]**

*[!UICONTROL Équilbreur de charge de travail]*

Il vous suffit désormais de cliquer sur une barre de tâches ou d’événements dans l’[!UICONTROL équilibreur de charge de travail] pour ouvrir le panneau Résumé. Avant cette mise à jour, vous deviez cliquer sur l’icône [!UICONTROL Ouvrir le résumé] dans la barre d’outils, puis cliquer sur la tâche ou l’événement. Cette manipulation confuse est désormais corrigée. Vous pouvez aussi cliquer sur le menu [!UICONTROL Plus] près du nom de la tâche ou de l’événement, puis cliquer sur [!UICONTROL Ouvrir le résumé].

**L’administrateur de groupes ne peut pas afficher les détails des utilisateurs du groupe**

*Utilisateurs*

Lorsque l’utilisateur affecté à un niveau d’accès qui inclut l’accès de niveau [!UICONTROL Administrateur d’utilisateurs (Groupe d’utilisateurs)] tente d’afficher les détails d’un utilisateur dans son groupe, le message d’erreur suivant apparaît :

« [!UICONTROL Réessayons. Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.] »

**Impossible de supprimer le statut de groupe personnalisé**

*Groupes*

Lorsque l’utilisateur tente de supprimer un statut de groupe personnalisé depuis la page [!UICONTROL Groupe], la page devient vierge et le statut n’est pas supprimé.

**Les paramètres de notification par e-mail de la zone Contacts diffèrent de ceux dans les Détails de l’utilisateur**

*[!DNL Workfront Proof]*

Les paramètres de notification par e-mail indiqués dans la zone [!UICONTROL Contacts] de [!DNL Workfront Proof] pour un utilisateur spécifique diffèrent de ceux définis dans les [!UICONTROL Détails de l’utilisateur] en question.

**Impossible d’utiliser l’outil Texte lors de l’ajout d’un commentaire sur une épreuve**

*[!DNL Workfront Proof]*

Lorsque l’utilisateur commente une épreuve et tente d’ouvrir l’outil [!UICONTROL Texte], l’outil ne s’ouvre pas et le message suivant apparaît :

« [!UICONTROL Les données de texte de cette page sont toujours en cours de téléchargement. Veuillez patienter.] »

**Les e-mails concernant les épreuves seront envoyés à l’adresse e-mail principale de l’utilisateur**

*[!DNL Workfront Proof]*

Les paramètres d’envoi des notifications par e-mail changent. Désormais, les notifications sont envoyées à l’adresse e-mail principale de l’utilisateur et non plus à l’adresse e-mail d’alias générée par le système.

Pour plus d’informations sur la raison pour laquelle le système génère des adresses e-mail d’alias, consultez la rubrique Synchronisation des utilisateurs entre Adobe [!DNL Workfront] et [!DNL Workfront Proof].

+++

## Mises à jour d’avril 2022

+++**Mise à jour de maintenance le 28 avril 2022**

**Impossible d’atteindre le bouton [!UICONTROL Enregistrer] lors de la modification d’une feuille de temps**

*Feuilles de temps*

Lorsque l’utilisateur modifie une feuille de temps, il ne peut pas faire défiler la fenêtre de modification jusqu’à afficher le bouton [!UICONTROL Enregistrer] et ne peut donc pas modifier la feuille de temps.

**La signature électronique entraîne désormais la vérification de l’ID de fédération**

*Épreuves*

Lors de la signature électronique d’une épreuve, le système vérifie désormais l’ID de fédération si le SSO est activé dans [!DNL Workfront Proof]en plus de votre adresse e-mail dans [!DNL Workfront].

Auparavant, le système vérifiait uniquement votre adresse e-mail dans Workfront.

+++

+++**Mise à jour de maintenance (correctif) le 25 avril 2022**

L’**[!UICONTROL équilibreur de charge de travail] ne se charge pas**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsque l’utilisateur tente d’ouvrir l’[!UICONTROL équilibreur de charge de travail], l’en-tête et le panneau de gauche se chargent, mais pas le contenu de l’équilibreur de charge de travail. Des carrés gris clignotants remplacent les données. Parfois, une partie du contenu se charge, mais des carrés gris clignotent toujours là où devraient se trouver les données manquantes.

+++

+++**Mise à jour de maintenance le 21 avril 2022**

**L’ajout d’une tâche décale la page vers le bas**

*Tâches*

Lorsque l’utilisateur ajoute une tâche sous une tâche existante dans une liste, la page est décalée en bas de la liste. Bien que la nouvelle tâche se trouve au bon endroit, l’utilisateur doit faire défiler la page vers le haut pour la retrouver.

**Les utilisateurs ajoutés à une épreuve ne peuvent pas accéder à l’élément de travail de l’épreuve dans [!DNL Workfront]**

*Épreuves*

Si l’utilisateur est ajouté à une étape du workflow d’une épreuve, il n’est pas ajouté au partage de document et n’obtient aucune autorisation concernant l’élément de travail de l’épreuve dans [!DNL Workfront]. Lorsque l’utilisateur tente d’ouvrir l’élément de travail auquel l’épreuve est jointe dans[!DNL Workfront], le message suivant apparaît :

« [!UICONTROL Vous ne disposez pas d’un accès suffisant pour afficher ce (l’objet)] »

Ce problème concerne les épreuves déjà créées et les utilisateurs ajoutés après la création. L’ajout d’utilisateurs au workflow avant la création de l’épreuve fonctionne comme prévu.

**Impossible d’envoyer l’e-mail de réinitialisation de mot de passe à partir de [!DNL Workfront]**

*Utilisateurs*

Lorsque l’utilisateur tente d’envoyer un e-mail de réinitialisation de mot de passe à partir d’une liste d’utilisateurs dans [!DNL Workfront], l’option permettant d’envoyer l’e-mail n’est pas sélectionnable.

**Le bouton indique « [!UICONTROL Démarrer l’événement] » au lieu de « [!UICONTROL Démarrer la demande] »**

*Demandes*

Lorsque l’utilisateur consulte une demande affectée à son équipe, le bouton qui apparaît dans l’en-tête indique « [!UICONTROL Démarrer l’événement] » au lieu de « [!UICONTROL Démarrer la demande] ».

**L’option « [!UICONTROL Annuler le commentaire] » supprime les utilisateurs identifiés**

*Mises à jour*

Lorsque l’utilisateur identifie un autre utilisateur dans un commentaire, publie le commentaire, puis sélectionne l’option « [!UICONTROL Annuler le commentaire] », le commentaire s’affiche dans une zone de mise à jour comme prévu, mais l’utilisateur identifié ne se trouve pas dans la zone [!UICONTROL Utilisateurs identifiés].

**Impossible de faire défiler l’écran dans la vue [!UICONTROL Jalon] d’un rapport**

*Rapports*

Lorsque l’utilisateur consulte un rapport et sélectionne la vue [!UICONTROL Jalon], la page passe en vue Jalon, mais il est impossible de la faire défiler et l’utilisateur ne peut pas afficher les jalons plus bas dans la page.

**La devise est incorrecte lorsque le rapport s’affiche dans le tableau de bord**

*Rapports*

Lorsque l’utilisateur consulte un rapport dans un tableau de bord, la devise du rapport est incorrecte. Lorsque l’utilisateur affiche le rapport en dehors du tableau de bord, la devise est correcte.

**Le filtre Terminé n’affiche pas les éléments de travail terminés**&#x200B;

*[!UICONTROL Page d’accueil]*

Lorsque l’utilisateur consulte sa [!UICONTROL Liste de travail de l’accueil] avec le filtre [!UICONTROL Terminé] activé, les éléments de travail terminés ne s’affichent pas dans la liste. Lorsque le filtre [!UICONTROL Tous] est activé, les éléments terminés sont inclus dans la liste, ce qui prouve leur existence.

**[!DNL Workfront]ne se charge pas**

*[!DNL Workfront]*

Lorsque l’utilisateur tente de se connecter à [!DNL Workfront], la page semble être bloquée dans une boucle de redirections ou d’actualisations et ne se charge pas.

+++

+++**Mise à jour de maintenance le 14 avril 2022**

**Impossible d’ajouter une tâche à partir d’un rapport sur une section personnalisée d’une tâche**

*Tâches*

Lorsque l’utilisateur consulte une section personnalisée d’une tâche et que la section contient un rapport de tâche, il ne peut pas ajouter de tâche à partir de ce rapport. Le bouton [!UICONTROL Ajouter une tâche] met en surbrillance le rapport, mais n’ouvre pas de fenêtre permettant à l’utilisateur d’ajouter une tâche.

**Le bouton Terminé se trouve au mauvais emplacement lors de la modification d’une vue**

*Vues*

Lorsque l’utilisateur modifie une vue, le bouton [!UICONTROL Terminé] s’affiche plus haut à l’écran et peut chevaucher du texte.

L’utilisateur peut modifier la vue normalement. La fonctionnalité reste la même.

**Impossible de faire défiler l’écran dans la vue [!UICONTROL Jalon] d’un rapport**

*Rapports*

Lorsque l’utilisateur consulte un rapport et sélectionne la vue [!UICONTROL Jalon], la page passe en vue Jalon, mais il est impossible de la faire défiler et l’utilisateur ne peut pas afficher les jalons plus bas dans la page.

**Écran vierge lors de l’affichage des mises à jour**

*Mises à jour*

Lorsque l’utilisateur consulte les mises à jour et fait défiler l’écran vers le bas pour afficher d’autres mises à jour, l’écran devient vide et les mises à jour n’apparaissent pas.

**Erreur lors de l’affectation en bloc d’un utilisateur à une tâche non affectée au rôle de l’utilisateur**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsque l’utilisateur de l’[!UICONTROL équilibreur de charge de travail] tente d’affecter des tâches à un utilisateur dont la fonction ne correspond pas à celle affectée aux tâches, un message indiquant que la tâche sera affectée à l’aide de la fonction principale de l’utilisateur affecté s’affiche. Cependant, lorsque l’utilisateur clique sur « [!UICONTROL Affecter] », les tâches ne sont pas affectées et le message d’erreur suivant apparaît :

« [!UICONTROL Erreur. Le serveur a rencontré une erreur inconnue.] »

+++

+++**Mise à jour de maintenance le 7 avril 2022**

**Les utilisateurs ajoutés aux épreuves ont des rôles incorrects**

*Épreuves*

Lorsque l’utilisateur ajoute un autre utilisateur à une épreuve, son rôle dans l’épreuve est défini comme en « [!UICONTROL Lecture seule] » malgré le véritable rôle d’épreuve de l’utilisateur.

**Impossible d’envoyer l’e-mail de réinitialisation de mot de passe à l’utilisateur**

*Utilisateurs*

Lorsque l’utilisateur tente d’envoyer une réinitialisation de mot de passe à un autre utilisateur, l’option [!UICONTROL Envoyer un e-mail Mot de passe oublié] n’est pas sélectionnable dans le menu [!UICONTROL Plus].

**[!UICONTROL Tout mettre à jour] envoie les mises à jour aux profils d’utilisateurs plutôt que sur les projets**

*Mises à jour*

Lorsque l’utilisateur consulte la zone [!UICONTROL Personnes] d’un projet et sélectionne l’option [!UICONTROL Tout mettre à jour], puis saisit une mise à jour, celle-ci n’est pas publiée sur le projet lui-même. Au lieu de cela, elle est publiée sur les profils d’utilisateurs de chacun des utilisateurs appartenant au projet.

**Nombre de pages excessif lors de l’impression des mises à jour**

*Mises à jour*

Lorsque l’utilisateur consulte un flux de mise à jour qui s’imprimerait en plusieurs pages et tente d’imprimer la page, l’écran d’impression indique que le nombre de pages à imprimer est largement supérieur au nombre réel de pages à imprimer. Si l’utilisateur tente ensuite d’imprimer au format PDF, la création du PDF échoue.

**Les utilisateurs ne voient pas la liste complète des entités partagées avec un rapport lorsque le paramètre « [!UICONTROL Visible à l’échelle du système] » est activé**

*Rapports*

Lors du partage de rapports avec plusieurs entités indiquées dans la zone [!UICONTROL Accès aux rapports], les utilisateurs ne peuvent pas faire défiler la page jusqu’au bas de la liste pour consulter la liste complète lorsque le paramètre « [!UICONTROL Visible à l’échelle du système] » est activé.

**Devise incorrecte utilisée dans les rapports**

*Rapports*

Si la devise définie par l’utilisateur pour un projet diffère de la devise par défaut et qu’ensuite l’utilisateur consulte un rapport pour ce projet, la devise qui apparaît est celle par défaut et non pas celle du projet.

**Les dernières informations consultées ne se mettent pas à jour dans les rapports [!UICONTROL Utilisation des rapports]**

*Rapports*

Lorsque l’utilisateur consulte un rapport qui affiche des informations portant sur la dernière consultation du rapport, ces informations peuvent être absentes ou constituer d’anciennes données. Ce problème concerne notamment les champs :

* [!UICONTROL Affiché en dernier par]
* [!UICONTROL Dernières données consultées]
* [!UICONTROL X auteurs des dernières vues]
* [!UICONTROL Vue le mois/le trimestre/l’année en cours]

**Les tâches terminées apparaissent dans la [!UICONTROL Liste de travail de l’accueil]**

*[!UICONTROL Page d’accueil]*

Lorsque l’utilisateur consulte sa [!UICONTROL Liste de travail de l’accueil], les tâches terminées apparaissent dans cette liste même si l’option d’affichage des tâches terminées n’est pas sélectionnée.

**Le bouton de Planification pour planifier l’actualisation du sandbox n’apparaît pas**

*Environnement sandbox*

Le bouton de [!UICONTROL Planification] servant à planifier l’actualisation du sandbox n’apparaît pas dans la bannière supérieure de l’environnement sandbox.

**Les modifications apportées à un champ calculé modifient tous les champs calculés d’un formulaire.**

*Formulaires personnalisés*

Lorsque l’utilisateur se trouve dans le créateur de formulaires personnalisés et modifie la valeur d’un formulaire calculé, tous les champs calculés du formulaire affichent la nouvelle valeur. Cela peut concerner les nouveaux champs calculés ou ceux déjà existants.

**Les couleurs du créateur de formulaires personnalisé scintillent**

*Formulaires personnalisés*

Lorsque l’utilisateur travaille sur des champs calculés dans le créateur de formulaires personnalisés, les couleurs des champs et des expressions scintillent.

**[!UICONTROL Impossible de refuser une approbation]**

*Approbations*

Lorsque l’utilisateur tente de refuser une approbation, le bouton [!UICONTROL Refuser] ne répond pas et l’approbation n’est pas refusée.

L’onglet **[!UICONTROL Projets] affiche par défaut la section Tous les projets malgré la sélection précédente**

*Projets*

Lorsque l’utilisateur accède à la page des Projets depuis un onglet épinglé en tant que partie intégrante du modèle de mise en page, la page affiche par défaut la zone [!UICONTROL Tous les projets] dans le panneau de navigation de gauche. Cela se produit même lorsque l’utilisateur choisit une autre zone du panneau de navigation de gauche, quitte la page des Projets puis y revient.

+++


## Mises à jour de mars 2022

+++**Mise à jour de maintenance le 31 mars 2022**

**Les fuseaux horaires de [!DNL Workfront] et de [!DNL Workfront Proof]** ne sont pas cohérents

*[!DNL Workfront Proof]*

Si le profil de l’utilisateur est défini sur un fuseau horaire spécifique dans [!DNL Workfront], le fuseau horaire de l’utilisateur défini dans [!DNL Workfront Proof] est différent.

**Le lien permettant de soumettre un document demandé mène à une page vierge**

*Documents*

Lorsque l’utilisateur reçoit une demande de soumission de documents et clique sur le lien menant vers l’objet où le document a été demandé, une page vierge s’affiche. Cela peut se produire en cliquant sur un lien dans un e-mail ou dans une notification in-app.

**Le groupe n’est pas correctement affecté lors de la conversion d’un événement en projet**

Groupes

Voici ce qui se produit lorsque l’utilisateur convertit un événement en projet à l’aide d’un modèle :

* Si un groupe est affecté au modèle, ce groupe s’affiche dans la fenêtre de conversion de l’événement en tant que groupe pour le nouveau projet.
* Si aucun groupe n’est affecté au modèle, le groupe par défaut de l’utilisateur qui convertit l’événement s’affiche dans la fenêtre de conversion de l’événement en tant que groupe pour le nouveau projet.
* Si le modèle ne comporte aucun groupe, le nouveau projet doit hériter du groupe du projet de l’événement.

**Impossible de joindre un formulaire personnalisé interobjet à la file d’attente des demandes**

Demandes

Lorsque l’utilisateur tente d’ajouter un formulaire personnalisé interobjets à la page de détails d’une file d’attente, le formulaire interobjets n’apparaît pas dans la liste déroulante des formulaires disponibles et l’utilisateur ne peut pas le sélectionner pour l’ajouter aux détails de la file d’attente.

**Impossible d’affecter une fonction secondaire aux utilisateurs dans l’[!UICONTROL équilibreur de charge de travail]**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsque l’utilisateur tente d’affecter un autre utilisateur à une tâche dans l’[!UICONTROL équilibreur de charge de travail] et que la tâche est affectée à une fonction autre que la fonction principale de l’utilisateur affecté, l’utilisateur est affecté à la tâche d’après sa fonction principale, et le message suivant s’affiche :

« &lt;Nom> ne convient pas au rôle de l’affectation &lt;Affectation de rôle de tâche>. 1 élément de travail actuellement affecté au rôle &lt;Affectation de rôle de tâche> sera affecté à &lt;Nom> en tant que &lt;Fonction principale>. »

Cela se produit même si l’utilisateur possède la fonction de l’affectation de rôle de tâche en tant que fonction secondaire.

**Problème de la barre « Afficher plus d’éléments de travail » du scrum board**&#x200B;

*Agile*

Lorsque l’utilisateur clique sur la barre [!UICONTROL Afficher plus d’éléments de travail] d’un scrum board puis fait défiler l’écran pour consulter les nouveaux éléments, la barre [!UICONTROL Afficher plus d’éléments de travail] reste affichée sur le scrum board et se déplace avec celui-ci en suivant le défilement de la page. Cela peut rendre les cartes difficiles à lire.

**Des points rouges apparaissent sur les champs obligatoires des formulaires personnalisés**

Formulaires personnalisés

Lorsque l’utilisateur affiche un champ obligatoire d’un formulaire personnalisé, deux points rouges apparaissent sous l’astérisque indiquant que le champ est obligatoire.

**Le menu déroulant du temps est tronqué dans les invites**

*Rapports*

Lorsque l’utilisateur remplit les invites d’un rapport et rencontre un sélecteur de date, le sélecteur d’heure en bas du sélecteur de date n’indique pas les heures au-delà du chiffre 2 et les seules valeurs que peut sélectionner l’utilisateur sont 1 ou 2.

+++

+++**Mise à jour de maintenance (correctif) le 29 mars 2022**

**Impossible de modifier ou d’enregistrer les calculs dans le créateur de formulaires personnalisés**

*Formulaires personnalisés*

Si l’utilisateur saisit manuellement un calcul dans un champ de calcul du créateur de formulaires personnalisés et enregistre le formulaire, le calcul n’est pas enregistré. Si l’utilisateur ouvre à nouveau le formulaire personnalisé, ce champ est vide.

Si l’utilisateur saisit un calcul dans un champ de calcul du créateur de formulaires personnalisés à l’aide des menus déroulants et enregistre le formulaire, cette valeur est enregistrée. Cependant, si l’utilisateur ouvre de nouveau le formulaire personnalisé, ce champ ne peut pas être modifié et la valeur ne peut pas être supprimée, que ce soit manuellement ou depuis la liste déroulante.

REMARQUE : ce correctif concernait également des fonctionnalités supplémentaires. Désormais, lorsque vous commencez à saisir du texte dans un champ calculé, les expressions ou calculs possibles s’affichent dans une liste déroulante juste en dessous, de la même manière que dans l’éditeur de calcul. Cliquez sur un élément dans la liste déroulante pour l’ajouter au champ calculé.

+++

+++**Mise à jour de maintenance le 24 mars 2022**

**Les fuseaux horaires de [!DNL Workfront] et de [!DNL Workfront Proof]** ne sont pas cohérents

*[!DNL Workfront Proof]*

Si le profil de l’utilisateur est défini sur un fuseau horaire spécifique dans [!DNL Workfront], le fuseau horaire de l’utilisateur défini dans [!DNL Workfront Proof] est différent.

**Erreur de champ obligatoire pour les champs personnalisés remplis lorsqu’un modèle est joint**

*Projets*

Lorsqu’un modèle avec des champs personnalisés obligatoires est joint à un projet dans lequel le champ rempli existe déjà, l’erreur suivante se produit : « [!UICONTROL Certains champs sont incomplets. Saisissez les valeurs des champs obligatoires pour continuer.] » Cliquer sur « [!UICONTROL Y accéder] » permet de constater que les champs sont remplis et que le modèle peut être joint.

**L’[!UICONTROL équilibreur de charge de travail] clignote en passant d’une date à l’autre**

*[!UICONTROL Équilbreur de charge de travail]*

Les heures de l’utilisateur répertoriées en premier dans l’[!UICONTROL équilibreur de charge de travail] ne s’affichent pas lorsque la chronologie est mise à jour. L’utilisateur et ses heures sont remplacés par des carrés gris clignotants. Cela se produit lorsque l’utilisateur avance et recule sur la chronologie.

Mettre à jour le filtre semble réinitialiser l’affichage. Toutefois, si l’utilisateur avance et recule sur la chronologie, les carrés clignotants réapparaissent et les heures de l’utilisateur disparaissent.

**La terminologie personnalisée est incohérente**

*Modèles de mise en page*

Les utilisateurs signalent que lorsque l’administrateur [!DNL Workfront] personnalise la terminologie de certains objets à l’aide d’un modèle de mise en page, le nouveau nom d’objet s’affiche de manière incohérente dans l’interface.

Par exemple, sur la page [!UICONTROL Projets], le titre de la page indique toujours « [!UICONTROL Projets] » même si l’administrateur [!DNL Workfront] a modifié le nom des « [!UICONTROL Projets] ».

Cela perturbe les utilisateurs finaux.

+++

+++**Mise à jour de maintenance le 17 mars 2022**

**Les miniatures et les images principales des fichiers à plusieurs pages sont vides dans le [!DNL Safari] navigateur**

*[!DNL Workfront Proof]*

Lorsque l’utilisateur tente de consulter un fichier à plusieurs pages dans le navigateur [!DNL Safari], les images de la page des miniatures sont vides. De la même manière, l’image principale est parfois vide.

**Liste d’utilisateurs incorrecte lors d’affectations en bloc dans l’[!UICONTROL équilibreur de charge de travail]**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsque l’utilisateur affecte en bloc des éléments dans l’[!UICONTROL équilibreur de charge de travail] et sélectionne un projet et un rôle de tâche, la liste des utilisateurs disponibles est incorrecte. Elle peut afficher des utilisateurs sans fonction ni autorisation de projet, et les utilisateurs disposant des fonctions et des autorisations de projet n’apparaissent pas toujours dans la liste.

**[!UICONTROL Le tri ne fonctionne pas dans les rapports]**

*Rapports*

Lorsque l’utilisateur clique sur une colonne pour la trier, le tri semble fonctionner, mais les résultats reviennent instantanément dans l’ordre d’origine avant que l’utilisateur ne clique sur la colonne. Aucun tri n’est conservé sur aucune colonne.

**Sélectionner « [!UICONTROL Rien] » rétablit le regroupement [!UICONTROL Rapport par défaut]**

*Rapports*

Lorsque l’utilisateur tente de sélectionner « [!UICONTROL Rien] » dans le menu déroulant [!UICONTROL Regroupement] d’un rapport comportant un groupement intégré, le rapport s’affiche sans aucun regroupement pendant quelques instants, puis repasse au regroupement [!UICONTROL Rapport par défaut].

**Suppression de l’onglet « [!UICONTROL Accès aux blueprints] » depuis les préférences des blueprints**

*Plans directeurs*

REMARQUE : ce problème est uniquement présent dans l’environnement de prévisualisation.

L’onglet [!UICONTROL Accès aux blueprints] a été supprimé de la fenêtre modale Préférences de blueprint. Aucune fonctionnalité n’a été supprimée des préférences de blueprints.

+++

+++**Mise à jour de maintenance (correctif) le 14 mars 2022**

**Impossible de faire défiler la liste des utilisateurs lors d’une affectation dans le tableau kanban**

*Agile*

Lorsque l’utilisateur consulte un tableau [!DNL Kanban] et tente une affectation, la liste d’utilisateurs qui apparaît lorsqu’il saisit du texte revient sans cesse vers le haut lorsqu’il la fait défiler vers le bas. L’utilisateur ne parvient pas à sélectionner un utilisateur qui ne se trouve pas près du haut de la liste et ne peut pas enregistrer la modification de l’affectation.

La vue **[!UICONTROL Jalon] du rapport du projet provoque l’apparition d’une erreur**

*Rapports*

Lors de l’affichage d’un rapport de projet dans la vue [!UICONTROL Jalon], l’erreur « [!UICONTROL L’APIModel INTERNAL ne prend pas en charge la VIGNETTE namedQuery TILE:milestone-view (UIVW)] » apparaît.

**La terminologie personnalisée est incohérente**

*Modèles de mise en page*

Les utilisateurs signalent que lorsque l’administrateur [!DNL Workfront] personnalise la terminologie de certains objets à l’aide d’un modèle de mise en page, le nouveau nom d’objet s’affiche de manière incohérente dans l’interface.

Par exemple, sur la page [!UICONTROL Projets], le titre de la page indique toujours « [!UICONTROL Projets] » même si l’administrateur [!DNL Workfront] a modifié le nom des « [!UICONTROL Projets] ».

Cela perturbe les utilisateurs finaux.

**Impossible de mettre à jour les calculs des champs calculés existants**

*Formulaires personnalisés*

Les utilisateurs ne peuvent pas mettre à jour ni modifier les calculs des champs calculés. Si le champ a été créé et enregistré sans calcul, le créateur se vide à chaque tentative d’ajout d’une expression et d’enregistrement ou d’application de cette expression.

Si un champ calculé est créé avec une certaine expression puis enregistré, il reviendra à sa valeur précédente chaque fois que l’utilisateur tente de modifier le calcul.

Erreur **[!UICONTROL Paramètre non valide] lors de la réinitialisation des mots de passe**

*Connexion*

Les utilisateurs ne peuvent pas réinitialiser leurs mots de passe dans aucun environnement. Lorsqu’ils saisissent leur adresse e-mail et tentent de continuer le processus, un message d’erreur apparaît.

[!UICONTROL Erreur : paramètre non valide : valeur du paramètre de recherche « domaine »].

+++

+++**Mise à jour de maintenance le 10 mars 2022**

**Problèmes de connexion à l’environnement de prévisualisation**

*Connexion*

Les problèmes suivants liés à la connexion à l’environnement de prévisualisation ont été signalés.

Lorsque l’utilisateur tente de se connecter à l’environnement de prévisualisation, un message l’informant que l’ID ou le mot de passe saisi est incorrect apparaît.

Lorsque l’utilisateur tente de réinitialiser son mot de passe, le message d’erreur « [!UICONTROL Plusieurs utilisateurs correspondent à cette adresse e-mail <example@example.com>] » apparaît.

**Les formulaires personnalisés se chargent lentement dans la zone [!UICONTROL Détails du projet]**

*Projets*

Lorsque l’utilisateur tente d’accéder à la zone [!UICONTROL Détails du projet], tous les formulaires personnalisés joints au projet prennent 15 secondes ou plus à se charger. L’option [!UICONTROL Ajouter des formulaires personnalisés] est également concernée par ce retard.

**Les valeurs de champ de formulaire personnalisés ne s’enregistrent pas dans le panneau de résumé du document**

*Documents*

Lorsque l’utilisateur met à jour des champs de formulaire personnalisés dans le panneau de résumé du document et qu’un ou plusieurs d’entre eux sont des champs de saisie semi-automatique, enregistre les modifications et quitte le panneau de résumé, les mises à jour ne sont pas enregistrées. Cela ne se produit que lorsqu’un champ de saisie semi-automatique est modifié, même si tous les champs sont concernés.

**Les données ne sont pas conservées lors de la conversion de modèles en raison des niveaux d’accès de partage de modèles**

*Projets*

Lorsque l’utilisateur disposant d’un accès en lecture seule à un modèle partagé tente de convertir un événement en projet, aucune des données des sections de formulaire personnalisées qui nécessitent un accès de niveau [!UICONTROL Contributeur] ou supérieur n’est transférée vers le projet créé.

**Erreur lors du chargement d’une nouvelle version du document**

*Documents*

Lorsque l’utilisateur tente de charger une nouvelle version d’un document depuis la liste de documents, le document n’est pas chargé et le message d’erreur suivant apparaît :

[!UICONTROL Erreur : Impossible d’appeler « com.attask.boz.Document.getCurrentVersion() », car « document » est nul]

**Impossible de modifier les taux de facturation**

*Projets*

Lorsque l’utilisateur tente de modifier un taux de facturation dans l’onglet [!UICONTROL Taux de facturation] d’un projet, cliquer sur le bouton [!UICONTROL Modifier] ouvre brièvement la fenêtre de [!UICONTROL Modification], mais elle se ferme avant que l’utilisateur puisse modifier le taux de facturation. Cliquer une nouvelle fois sur le bouton ne rouvre pas la fenêtre de modification.

**Le lien public du document mène à une page vierge**

*Documents*

Lorsque l’utilisateur tente d’ouvrir un document à l’aide d’un lien public, le lien mène à une page vierge. Cela se produit lorsque le lien est ouvert dans une fenêtre où une session [!DNL Workfront] active est ouverte.

**Erreur de type « Oups » lors de l’ajout d’une tâche ou d’un événement à la liste**

*Tâches et événements*

Lorsque l’utilisateur non-administrateur tente d’ajouter une tâche ou un événement à une liste et renseigne des champs personnalisés, la tâche ou l’événement n’est pas créé et le message d’erreur suivant apparaît :

[!UICONTROL Erreur : Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.]

**Conserver une mise à jour après un changement de statut rétablit l’état précédent de l’objet**

Projets, tâches et événements

Modifier le statut d’un projet, d’une tâche ou d’un événement, puis commencer immédiatement à saisir une mise à jour sans actualiser la page entraîne l’affichage du statut précédent dans la zone de mise à jour. Si la mise à jour est publiée, l’objet revient au statut précédent.

**Les utilisateurs ajoutés aux épreuves ont des rôles incorrects**

*Épreuves*

Lorsque l’utilisateur ajoute un autre utilisateur à une épreuve, son rôle dans l’épreuve est défini comme en « [!UICONTROL Lecture seule] » malgré le véritable rôle d’épreuve de l’utilisateur.

Solution : Changez le rôle de l’utilisateur sur l’épreuve indiqué dans son profil puis repassez-le au rôle approprié.

**Le formulaire personnalisé ne se charge pas lors de la conversion d’un événement en projet à l’aide d’un modèle**

*Formulaires personnalisés*

Lorsque l’utilisateur tente de convertir un événement en projet à l’aide d’un modèle, un ou plusieurs des formulaires personnalisés joints au modèle peuvent ne pas se charger. Lorsque l’utilisateur configure le modèle pour le nouveau projet, au lieu des formulaires personnalisés, le message suivant apparaît :

« [!UICONTROL Un problème est survenu, impossible de charger le formulaire]. »

**L’utilisateur ne peut pas ajouter d’événement sur la ligne avec le champ déroulant personnalisé qui s’affiche dans la vue**

*Listes*

Lorsque l’utilisateur ajoute un événement sur la ligne et qu’une vue personnalisée avec des champs déroulants personnalisés est appliquée à la liste, une erreur se produit lorsqu’il remplit uniquement le champ déroulant. L’utilisateur est autorisé à modifier les formulaires personnalisés et est le propriétaire du projet disposant de droits de gestion sur le projet.

[!UICONTROL Erreur : Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.]

**Les autorisations d’ajout de tâches à un projet ne sont pas obligatoires pour déplacer ou copier une tâche dans le projet**

*Tâches*

Vous pouvez désormais déplacer ou copier une tâche vers une autre tâche d’un projet sans disposer des autorisations nécessaires pour ajouter des tâches au projet de destination. Vous devez disposer des autorisations nécessaires pour ajouter des tâches à au moins l’une des tâches du projet de destination. Avant cette mise à jour, vous deviez disposer des autorisations nécessaires pour ajouter des tâches au projet afin de déplacer ou de copier une tâche dans le projet ou dans l’une de ses tâches.  Cette mise à jour est désormais disponible dans l’environnement d’Exploitation. Elle est sortie dans l’environnement de Prévisualisation en même temps que la mise à jour de maintenance du 24 mars 2022.

REMARQUE : cette mise à jour sera disponible dans l’environnement d’Exploitation lors de la copie ou du déplacement d’événements après la sortie de la version d’Exploitation 22.2. Pour plus d’informations sur la version actuelle, consultez workfront.com/release.

**Le menu déroulant de l’invite est tronqué**

*Rapports*

Lorsqu’une invite est utilisée dans un rapport, les menus déroulants qui permettent de sélectionner les critères de filtrage du rapport sont tronqués. Par conséquent, les critères situés en bas du menu déroulant de sélection n’apparaissent pas.

**L’élément de travail revient à son statut précédent lorsqu’une mise à jour est effectuée**

*Mises à jour*

Lorsque l’utilisateur modifie le statut d’un élément de travail dans l’en-tête, celui-ci n’est pas mis à jour dans la zone [!UICONTROL Mise à jour]. Si l’utilisateur effectue ensuite une mise à jour, la liste déroulante affiche toujours le statut précédent. Lorsque la mise à jour est enregistrée, le statut incorrect précédent remplace le statut défini dans l’en-tête.

+++

+++**Mise à jour de maintenance le 3 mars 2022**

**Impossible d’ajouter de document à partir de [!DNL Google Drive]**

*Documents*

Lorsque l’utilisateur tente d’ajouter un document à partir de [!DNL Google Drive], les options ne répondent pas et aucune sélection n’est possible.

**Les utilisateurs identifiés ne sont pas ajoutés au fil de mise à jour**

*Mises à jour*

Lorsque l’utilisateur est identifié dans une mise à jour, il n’apparaît pas dans la zone « [!UICONTROL À] » de la mise à jour ou de ses réponses.

**L’utilisateur de l’épreuve dispose de deux comptes de relecture distincts**

*[!DNL Workfront Proof]*

L’adresse électronique d’un utilisateur dans [!DNL Workfront Proof] peut appartenir à deux comptes distincts avec des ID distincts. L’utilisateur possède alors deux comptes. Identifier le compte correct est alors compliqué.

**Erreur de type « Oups » dans les en-têtes de rapports**

*Rapports*

Lorsque l’utilisateur consulte un rapport, le message d’erreur suivant apparaît dans l’en-tête du rapport :

« [!UICONTROL Réessayons. Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.] »

Si l’utilisateur consulte un tableau de bord, l’erreur peut apparaître dans l’en-tête de tous les rapports du tableau de bord.

**Dans les formulaires personnalisés, les données des champs dont la modification est uniquement possible par les administrateurs ne sont pas conservées lors de la conversion d’événements en projets**

*Projets*

Lorsque l’utilisateur non-administrateur tente de convertir un événement en projet à l’aide d’un modèle et que l’événement contient des données dans des champs dont la modification est uniquement possible par les administrateurs, les données de ces champs ne sont pas transférées vers le nouveau projet.

Lorsque l’administrateur convertit l’événement, les données sont transférées vers le nouveau projet comme prévu.

La limite de taille de fichier pour **[!DNL XLS] et [!DNL XLSX] est temporairement réduite à 100 Mo pour les épreuves**

*Relecture*

Dans le but de résoudre un problème de sécurité, nous avons temporairement limité la taille maximale des fichiers pour [!DNL XLS] et [!DNL XLSX] à 100 Mo lors de la création d’une épreuve.

REMARQUE : cette mise à jour est sortie dans l’environnement de Prévisualisation le 24 février et sera disponible dans l’environnement d’Exploitation le 3 mars.

**Mise à jour de la recherche Workfront**

Rechercher

Le déploiement échelonné de la mise à jour de l’infrastructure de la fonctionnalité de recherche de [!DNL Workfront] a commencé cette semaine. Cette mise à jour rendra les futures améliorations de la recherche plus simples et plus fiables. Avec ces modifications, les éléments ajoutés à [!DNL Workfront] seront indexés plus rapidement et se retrouveront donc plus rapidement dans les résultats de recherche.

Le déploiement échelonné se poursuivra pendant 2 semaines.

**Mise à jour des barres d’outils pour les rapports dans les tableaux de bord**

Rapports

Les rapports dans les tableaux de bord possèdent désormais une nouvelle barre d’outils. Cette barre d’outils fait partie des mises à jour des listes et des rapports publiées dans tout [!DNL Workfront].

+++


## Mises à jour de février 2022

+++**Mise à jour de maintenance (correctif) le 24 février 2022**

**Les données ne sont pas conservées lors de la conversion d’événements en projets si le champ est masqué dans le modèle**

*Projets*

Lorsque l’utilisateur convertit un événement en modèle et que ce dernier inclut un formulaire personnalisé qui affiche ou masque des champs en fonction des valeurs d’autres champs, aucune des données des champs masqués dans le modèle (sans données) au moment de la conversion n’est transférée dans le nouveau projet.

**Impossible d’exporter le planificateur de ressources en fonction des rôles**

*Planification des ressources*

Lorsque l’utilisateur tente d’exporter le [!DNL Resource Planner] avec l’option [!UICONTROL Afficher par rôle] activée, l’exportation échoue et l’utilisateur reçoit un e-mail contenant le message suivant :

Une erreur s’est produite lors de l’exportation de vos données [!DNL Resource Planner].

**Le bouton Copier la demande ne fonctionne pas**

*Demandes*

Lorsque l’utilisateur tente de copier une demande, le bouton [!UICONTROL Copier la demande] ne fonctionne pas si l’utilisateur ne dispose pas d’un accès en lecture seule à la rubrique de file d’attente.

+++

+++**Mise à jour de maintenance le 24 février 2022**

**Les données des formulaires personnalisés disparaissent lorsque d’autres champs des formulaires sont remplis**

*Formulaires personnalisés*

Lorsque l’utilisateur remplit un formulaire personnalisé en vue de la conversion d’un événement en projet, le remplissage d’un champ personnalisé peut provoquer la disparition des données d’un autre champ personnalisé. Si l’utilisateur saisit à nouveau les données manquantes, le message d’erreur suivant s’affiche lorsqu’il tente de créer le projet :

« [!UICONTROL Vous devez être un administrateur système pour modifier cette valeur de paramètre de donnée personnalisée] »

**Aucun champ « [!UICONTROL Ce processus d’approbation peut être utilisé par…] »**

*Approbations*

Lorsque l’utilisateur crée ou modifie un processus d’approbation dans la zone [!UICONTROL Configuration], le champ « [!UICONTROL Ce processus d’approbation peut être utilisé par…] » n’apparaît pas. Cela peut se produire lors de la création d’un processus d’approbation ou de la modification d’un processus existant.

**L’administrateur système ne peut pas réaffecter les utilisateurs lors de la suppression d’un groupe**

*Groupes*

Lorsque l’administrateur système supprime un groupe, il pourra uniquement réaffecter les utilisateurs de ce groupe aux groupes dont il est l’administrateur. Les autres groupes n’apparaissent pas dans la liste déroulante et l’administrateur ne peut pas les sélectionner.

**Erreur de type « Oups » lors de la conversion d’un événement en projet**

*Projets*

Lorsque l’utilisateur tente de convertir un événement en projet avec un modèle et ajoute ou supprime des formulaires personnalisés du modèle, l’événement n’est pas converti et le message suivant apparaît :

[!UICONTROL Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.]

**Impossible d’ouvrir l’épreuve, et la page s’actualise**

*Épreuves*

Lorsque l’utilisateur tente d’ouvrir une épreuve, celle-ci ne s’ouvre pas. La page finit par s’actualiser.

La limite de taille de fichier pour **[!DNL XLS] et [!DNL XLSX] est temporairement réduite à 100 Mo pour les épreuves**

*Relecture*

Dans le but de résoudre un problème de sécurité, nous avons temporairement limité la taille maximale des fichiers pour [!DNL XLS] et [!DNL XLSX] à 100 Mo lors de la création d’une épreuve.

REMARQUE : cette mise à jour sortira dans l’environnement de Prévisualisation le 24 février et sera disponible dans l’environnement d’Exploitation le 3 mars.

**Les autorisations d’ajout de tâches ou d’événements à un projet ne sont pas obligatoires pour déplacer ou copier une tâche ou un événement dans le projet**

*Projets*

Vous pouvez désormais déplacer ou copier une tâche ou un événement vers une autre tâche d’un projet sans disposer des autorisations nécessaires pour ajouter des tâches ou des événements au projet de destination. Vous devez disposer des autorisations nécessaires pour ajouter des tâches ou des événements à au moins l’une des tâches du projet de destination. Avant cette mise à jour, vous deviez disposer des autorisations nécessaires pour ajouter des tâches ou des événements au projet afin de déplacer ou de copier une tâche ou un événement dans le projet ou dans l’une de ses tâches. Cette mise à jour n’est actuellement disponible que dans l’environnement de Prévisualisation.

REMARQUE : cette mise à jour sera disponible dans l’environnement d’Exploitation lors de la copie ou du déplacement de tâches à partir du 10 mars. Cette mise à jour sera disponible dans l’environnement d’Exploitation lors de la copie ou du déplacement d’événements au moment de la sortie de la version d’Exploitation 22.2. Pour plus d’informations sur la version actuelle, consultez workfront.com/release.

**Mise à jour de la recherche Workfront**

*Rechercher*

Le déploiement échelonné de la mise à jour de l’infrastructure de la fonctionnalité de recherche de [!DNL Workfront] a commencé cette semaine. Cette mise à jour rendra les futures améliorations de la recherche plus simples et plus fiables. Avec ces modifications, les éléments ajoutés à [!DNL Workfront] seront indexés plus rapidement et se retrouveront donc plus rapidement dans les résultats de recherche.

Le déploiement échelonné se poursuivra pendant 2 semaines.

+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 18 février 2022**

**Validation du type de valeur de champ ajoutée aux propriétés d’éléments de liste [!DNL Anaplan]**

*[!DNL Adobe Workfront Fusion]*

Correction d’un problème qui permettait aux utilisateurs d’insérer un type de données incorrect dans les champs des propriétés d’éléments de liste. La validation du type de propriété autorise [!DNL Fusion] à vérifier que le type de données correct est envoyé à Anaplan et élimine les erreurs dues à des types de données incorrects.

+++

+++**Mise à jour de maintenance le 17 février 2022**

**Erreur lors de la suppression du prédécesseur depuis l’onglet Prédécesseurs**

*Tâches*

Lorsque l’utilisateur tente de supprimer un prédécesseur depuis l’onglet [!UICONTROL Prédécesseurs] d’une tâche, la tâche n’est pas supprimée et le message d’erreur suivant apparaît :

[!UICONTROL Tâche avec valeur(s) de clé primaire &quot;&quot; introuvable]

**Erreur de type « Oups » lors de l’ouverture de la page Utilisateurs**

*Utilisateurs*

Lorsque l’utilisateur tente d’ouvrir la page [!UICONTROL Utilisateurs], celle-ci ne se charge pas et le message d’erreur suivant apparaît :

[!UICONTROL Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.]

**Des éléments de l’en-tête des rapports de tableaux de bord se chevauchent**

*Tableaux de bord*

Lorsque l’utilisateur consulte un rapport dans un tableau de bord, l’icône et le libellé des regroupements chevauchent les liens menant vers les [!UICONTROL Détails] et le [!UICONTROL Résumé].

**Problèmes liés au menu « [!UICONTROL Plus] » des documents et des épreuves**

*Documents*

Lorsque l’utilisateur sélectionne un document ou une épreuve dans une liste de documents [!DNL Workfront Classic] puis clique sur « [!UICONTROL Plus] », l’un des problèmes suivants peut survenir : 
Le bouton ne répond pas 
Toutes les options apparaissant sous le bouton sont intitulées « [!UICONTROL Objet de l’objet] » et ne peuvent pas être sélectionnées.

**Erreur « Vous devez être un administrateur système » lors de la création d’un projet**

*Projets*

Lorsque l’utilisateur non-administrateur tente de créer un projet et joint un formulaire personnalisé dont une section est réservée aux administrateurs, il ne peut pas créer le projet et le message d’erreur suivant apparaît :

« Vous devez être un administrateur système pour modifier cette valeur de paramètre de donnée personnalisée »

**Dans les formulaires personnalisés, les données des sections réservées aux administrateurs ne sont pas conservées lors de la conversion d’événements en projets**

*Projets*

Lorsque l’utilisateur convertit un événement en projet à l’aide d’un modèle comportant un formulaire personnalisé avec une section réservée aux administrateurs, aucune donnée de la section réservée aux administrateurs n’est transférée vers le nouveau projet. Cela se produit même si l’administrateur convertit l’événement.

+++

+++**Mise à jour de maintenance le 10 février 2022**

**Erreur « [!UICONTROL Vous devez être un administrateur système] » lors de la création d’un projet**

*Projets*

Lorsque l’utilisateur non-administrateur tente de créer un projet et joint un formulaire personnalisé dont une section est réservée aux administrateurs, il ne peut pas créer le projet et le message d’erreur suivant apparaît :

« [!UICONTROL Vous devez être un administrateur système pour modifier cette valeur de paramètre de donnée personnalisée] »

**Les utilisateurs désactivés puis réactivés n’apparaissent pas dans les [!UICONTROL Contacts de l’épreuve]**

*[!DNL Workfront Proof]*

Lorsque l’utilisateur consulte sa liste de contacts dans [!DNL Workfront Proof], les utilisateurs désactivés puis réactivés n’apparaissent pas dans la liste.

**Message « Un problème est survenu » lors de la conversion d’un événement en projet à l’aide d’un modèle**

*Projets*

Lorsque l’utilisateur non-administrateur tente de convertir un événement en projet à l’aide d’un modèle, les champs de formulaire personnalisés visibles uniquement par les administrateurs indiquent le message suivant :

« [!UICONTROL Un problème est survenu, impossible de charger le formulaire] »

**Erreur « Impossible de charger le contenu de la page » lors de l’affichage des préférences du projet**

*Configuration*

Lorsque l’utilisateur au statut d’administrateur tente d’afficher des projets, des tâches ou des événements depuis les [!UICONTROL Préférences du projet] dans la zone [!UICONTROL Configuration], la page ne se charge pas et le message d’erreur suivant apparaît :

« [!UICONTROL Impossible de charger le contenu de la page. Essayez d’actualiser la page.] »

+++

+++**Mise à jour de maintenance le 3 février 2022**

Erreur **[!UICONTROL BizContext] lors de la connexion**

*Connexion*

Lorsque l’utilisateur tente de se connecter à [!DNL Workfront], la connexion échoue et le message suivant apparaît :

« [!UICONTROL Réessayons. Erreur de base de données : échec de l’engagement BizContext] »

Ce problème a été signalé dans l’environnement de Prévisualisation.

**Le flux de mise à jour de l’événement disparaît si l’événement est en attente d’approbation**

*Mises à jour*

Lorsque l’utilisateur clique sur la zone [!UICONTROL Nouvelle mise à jour] du flux de mise à jour d’un événement en attente d’approbation, l’intégralité du flux de mise à jour disparaît.

**Erreur lors du chargement d’une nouvelle version d’un document**

*Documents*

Lorsque l’utilisateur tente de charger une nouvelle version d’un document, la nouvelle version ne se charge pas et l’un des messages d’erreur suivants apparaît :

* [!UICONTROL documentID ne peut pas être nul]
* [!UICONTROL Erreur : paramètre non valide : la valeur de documentID est « non définie »]

**Le lien public du document mène à une page vierge**

*Documents*

Lorsque l’utilisateur tente d’ouvrir un document à l’aide d’un lien public, le lien mène à une page vierge. Cela se produit lorsque le lien est ouvert dans une fenêtre où une session [!DNL Workfront] active est ouverte.

**Les contrôles de listes ne fonctionnent pas sur les rapports dans les tableaux de bord**

*Tableaux de bord*

Lorsque l’utilisateur consulte un rapport dans un tableau de bord et tente de modifier le filtre, le regroupement ou la vue du rapport, le filtre, le regroupement ou la vue ne change pas.

**Erreur « [!UICONTROL Vous devez être un administrateur système] » lors de la création d’un projet**

*Projets*

Lorsque l’utilisateur non-administrateur tente de créer un projet et joint un formulaire personnalisé dont une section est réservée aux administrateurs, il ne peut pas créer le projet et le message d’erreur suivant apparaît :

« [!UICONTROL Vous devez être un administrateur système pour modifier cette valeur de paramètre de donnée personnalisée] »

**Les données personnalisées ne sont pas conservées lors de la conversion d’un événement en projet**

*Projets*

Lorsque l’utilisateur convertit un événement en projet à l’aide d’un modèle, les données d’un formulaire personnalisé dans l’événement ne sont pas transférées vers le formulaire personnalisé similaire dans le projet. Cela concerne les données dans des champs personnalisés pouvant être masquées en fonction des valeurs d’autres champs personnalisés.

**Erreur lors de la conversion d’un événement en projet**

*Projets*

Lorsque l’utilisateur tente de convertir un événement en projet, l’événement n’est pas converti et le message d’erreur suivant apparaît :

« [!UICONTROL Une erreur inattendue s’est produite] »

+++


## Mises à jour de janvier 2022

+++**Mise à jour de maintenance le 27 janvier 2022**

**Les données personnalisées ne sont pas conservées lors de la conversion d’un événement en projet**

*Projets*

Lorsque l’utilisateur convertit un événement en projet à l’aide d’un modèle, les données d’un formulaire personnalisé dans l’événement ne sont pas transférées vers le formulaire personnalisé similaire dans le projet. Cela concerne les données dans des champs personnalisés pouvant être masquées en fonction des valeurs d’autres champs personnalisés.

**La liste des utilisateurs sur le tableau agile n’est pas dans l’ordre alphabétique**

*Agile*

Lorsque l’utilisateur affiche la liste des utilisateurs d’un tableau agile, les utilisateurs ne sont pas affichés dans l’ordre alphabétique. Au lieu de cela, les utilisateurs qui ont le plus grand nombre d’affectations apparaissent en premier.

**Mise à jour des liens pour copier et déplacer les événements**

*Événements*

Dans l’environnement de Prévisualisation, les liens permettant de copier et de déplacer les événements ont été mis à jour et sont passés à « [!UICONTROL Copier vers] » et « [!UICONTROL Déplacer vers] », à la fois sur la page de l’événement et dans la liste des événements.

**Ajoutez jusqu’à 45 adresses IP à votre liste autorisée [!DNL Workfront]**

*Configuration*

La limite du nombre d’adresses IP ajoutées à votre liste autorisée [!DNL Workfront] est passée de 30 à 45.

+++

+++**Mise à jour de maintenance le 20 janvier 2022**

**Erreur « [!UICONTROL Paramètre non valide] » lors de la création d’un projet à partir d’un modèle**

*Projets*

Lorsque l’utilisateur tente de créer un projet à partir d’un modèle et supprime un formulaire personnalisé du modèle lors de la création du projet, le projet n’est pas créé et un message d’erreur « [!UICONTROL Paramètre non valide] » apparaît, qui mentionne un champ obligatoire du formulaire personnalisé supprimé.

**La liste des utilisateurs ne se charge pas dans le [!DNL Safari] navigateur**

*Utilisateurs*

Lorsque l’utilisateur accède à la zone [!UICONTROL Utilisateurs], l’en-tête s’affiche, mais la liste des utilisateurs ne se charge pas.

**Faire glisser des tâches dans une liste est lent et entraîne le déplacement de la tâche vers un emplacement incorrect**

*Listes*

Lorsque l’utilisateur tente de déplacer une tâche dans une liste en la faisant glisser, la ligne bleue qui indique où la tâche sera déplacée se déplace beaucoup plus lentement que le curseur. Lorsque l’utilisateur relâche la tâche, elle se déplace à l’endroit où se trouve la ligne bleue, même si le curseur indique un autre emplacement dans la liste.

+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 14 janvier 2022**

**Certains champs mappés sont réinitialisés lors de la sélection d’un [!UICONTROL nouveau champ à mapper]**

*[!DNL Workfront Fusion]*

Lorsque le mappage est activé pour au moins un champ du module [!UICONTROL Créer] ou [!UICONTROL Mettre à jour] de [!DNL Workfront] et qu’un utilisateur sélectionne un autre champ à mapper, les champs précédemment mappés pour lesquels le mappage est activé perdent leurs valeurs de mappage.

+++

+++**Mise à jour de maintenance le 13 janvier 2022**

**Impossible d’ajouter un lien hypertexte à un commentaire dans le panneau Résumé**

*Tâches*

Lorsque l’utilisateur ajoute un commentaire dans le panneau de résumé d’une tâche et tente de joindre un lien hypertexte au commentaire, la fenêtre du lien hypertexte s’ouvre, mais dès que l’utilisateur clique dans la fenêtre, elle se ferme et l’utilisateur ne peut pas ajouter de lien hypertexte. Si l’utilisateur accède à la fenêtre avec la touche de tabulation, il peut saisir ou coller un lien hypertexte dans le champ, mais il n’est pas enregistré. Dans les deux cas, la tâche est désélectionnée.

**La page Modifier l’équipe ne se ferme pas**

*Équipes*

Lorsque l’utilisateur tente de modifier une équipe, la page [!DNL Edit team] ne se ferme pas. L’utilisateur ne peut pas fermer la page en cliquant sur l’un des boutons, en cliquant sur le X ni en tentant d’accéder à une autre page.

**Les notifications par e-mail et in-app ne s’envoient pas**

*Notifications*

Lorsqu’un événement devant déclencher une notification se produit, la notification n’est pas envoyée. Cela peut concerner les notifications par e-mail ou in-app même si d’autres notifications sont envoyées.

La liste **[!UICONTROL Mes tâches] apparaît vide**

*[!UICONTROL Mes tâches]*

Lorsque l’utilisateur affiche sa liste [!UICONTROL Mes tâches] et que le modèle de mise en page de sa liste [!UICONTROL Mes tâches] inclut une valeur numérique comme un [!UICONTROL Pourcentage terminé], la liste [!UICONTROL Mes tâches] ne s’affiche pas.

Le **[!UICONTROL Pourcentage terminé] et les [!UICONTROL Heures terminées] ne sont pas modifiables dans le tableau Agile**

*Agile*

Lorsque l’utilisateur sélectionne « [!UICONTROL Afficher plus d’éléments de travail] » dans le tableau Agile puis tente de modifier le [!UICONTROL Pourcentage terminé] ou les [!UICONTROL Heures terminées] pour l’un des éléments de travail nouvellement chargés, il n’y parvient pas. Le bouton [!UICONTROL Pourcentage terminé] reste également gris, indiquant qu’il est inactif.

+++

+++**Mise à jour de maintenance le 6 janvier 2022**

**Erreur « [!UICONTROL Paramètre non valide] » lorsque des modèles ou des formulaires personnalisés sont joints à des projets**

*Projets*

Lorsque l’utilisateur tente de joindre un formulaire personnalisé ou un modèle à un projet existant, puis remplit les champs obligatoires du formulaire personnalisé ou du modèle et enregistre les modifications dans le projet, les modifications ne sont pas enregistrées et un message d’erreur « [!UICONTROL Paramètre non valide] » apparaît en haut de la page des détails du projet.

**Les commentaires de l’épreuve ne s’affichent pas dans les mises à jour du document**

*Épreuves*

Lorsque l’utilisateur consulte une épreuve dans la zone [!UICONTROL Documents], les commentaires ajoutés sur l’épreuve ne s’affichent pas dans la zone des [!UICONTROL mises à jour] du document.

**[!UICONTROL Équilbreur de charge de travail] : « [!UICONTROL ?[Objet d’objet] ?] » s’affiche dans les informations de suraffectation**

*[!UICONTROL Équilbreur de charge de travail]*

Si l’utilisateur est indiqué comme suraffecté dans l’[!UICONTROL équilibreur de charge de travail] en raison d’une tâche qui empiète sur son temps de pause et qu’un autre utilisateur consulte sa suraffectation, la zone « [!UICONTROL Capacité] » des informations de suraffectation indique « [!UICONTROL ?[Objet d’objet] ?] » plutôt que la capacité réelle de l’utilisateur.

+++

## Mises à jour de maintenance précédentes

Les informations relatives aux mises à jour de maintenance précédentes sont disponibles ici :

* [[!DNL Workfront] Archive des mises à jour de maintenance - 2021](2021-updates.md)
