---
title: Mises à jour de maintenance de Workfront
description: Mises à jour de maintenance pour [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 38e86575a1c495bc2340899562d68e59cbce7b06
workflow-type: tm+mt
source-wordcount: '13831'
ht-degree: 3%

---

# [!DNL Workfront] Mises à jour de maintenance

Les mises à jour de maintenance suivantes ont été effectuées en 2022.

>[!NOTE]
>
>Ces mises à jour comprennent également d’autres correctifs mineurs ou moins importants. [!DNL Workfront] L’assistance vous avertira lorsqu’un problème que vous avez envoyé est corrigé.

<!--
* [July 2022](#updates-in-july-2022)
* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)
-->

Pour connaître les mises à jour de maintenance antérieures à 2022, voir [Mises à jour de maintenance précédentes](#previous-maintenance-updates)

## Mises à jour en octobre 2022

+++**Mise à jour de maintenance le 6 octobre 2022**

**Nouveau type de plan directeur**

*Plans directeurs*

Le type de plan directeur &quot;Tableau de bord&quot; a été ajouté au catalogue de plans directeurs. Auparavant, seuls les modèles de modèle de projet et de structure organisationnelle étaient disponibles.

**Chevauchement des éléments dans le panneau de gauche**

*Formulaires personnalisés dans mon groupe*

Lorsqu’un utilisateur travaille dans le créateur de formulaires et que le formulaire comporte plus de 100 champs, le message informant l’utilisateur de la limite de champs entraîne le chevauchement des éléments du panneau de gauche.

**Le sélecteur de date s’ouvre automatiquement lors de la mise au point**

*Navigation*

Désormais, lors de la navigation par le clavier, les sélecteurs de date ne sont plus automatiquement ouverts et activés lors de la réception de la sélection au clavier.

**L’affectation de plusieurs équipes entraîne l’affectation d’une seule équipe.**

*Équipes*

>[!NOTE]
>
>Ce problème existe uniquement dans l’environnement Aperçu .

Lorsqu’un utilisateur affecte plusieurs équipes à une tâche ou à un problème, une seule équipe s’affiche dans la liste des affectations. Ce problème affecte également la création de rapports. Les rapports indiquant les affectations d’équipe sont inexacts car une seule équipe apparaît comme affectée à la tâche ou au problème.

**&quot;[!UICONTROL Vos modifications récentes n’ont pas été enregistrées.]&quot;erreur lors de l’enregistrement automatique des modifications sur une feuille de temps**

*Feuilles de temps*

Lorsqu’un utilisateur tente de modifier une feuille de temps de manière à déclencher une enregistrement automatique, les modifications ne sont pas enregistrées et l’utilisateur voit le message suivant :

&quot;[!UICONTROL Vos modifications récentes n’ont pas été enregistrées. Actualisez la page à afficher.]&quot;

Cela a été signalé lors de la modification des éléments suivants :

* Heures
* Tâches

**Les notifications électroniques sont différées**

*Épreuve Workfront*

Lorsqu’un événement se produit dans [!DNL Workfront Proof] qui déclenche une notification par courrier électronique, l’utilisateur ne reçoit pas la notification immédiatement. La notification peut être différée de plusieurs heures.

+++

+++**Mise à jour de maintenance le 3 octobre 2022**

**Enregistrez manuellement votre feuille de temps lorsque les rôles de tâche précédents ont été modifiés.**

*Feuilles de temps*

Si un rôle de tâche pour lequel vous avez consigné une heure a changé et que la variable [!UICONTROL Affecter manuellement des rôles de tâche aux entrées d’heure] a été désactivé, vous devez enregistrer manuellement vos entrées de temps jusqu’à ce que les heures ne soient plus consignées pour le rôle de tâche qui a été modifié.

+++

## Mises à jour en septembre 2022

+++**Mise à jour de maintenance le 29 septembre 2022**

**L’utilisateur ne revient pas à la page précédente lors de la fermeture du BAT**

*Épreuves*

Lorsqu’un utilisateur consulte un BAT dans [!DNL Workfront] ferme le BAT, ils ne renvoient pas la page sur laquelle ils étaient avant d&#39;ouvrir le BAT. Ils sont redirigés à la place vers une autre page de [!DNL Workfront].

**Impossible d’ouvrir le BAT[!DNL Workfront]**

*Épreuves*

Lorsqu’un utilisateur consulte un document dans [!DNL Workfront] et tente d’ouvrir le BAT, le BAT ne s’ouvre pas et l’utilisateur est renvoyé au [!UICONTROL Détails du document] page.

**Les heures ne sont pas enregistrées lors de l’utilisation de [!UICONTROL Onglet] key**

*Feuilles de temps*

Lorsqu’un utilisateur remplit une feuille de temps et navigue entre les cellules avec la variable [!UICONTROL Onglet] clé, les heures ne sont pas enregistrées. Le [!UICONTROL Enregistrement automatique] ne s’affiche pas en bas de l’écran. Si l’utilisateur actualise la page, il peut voir que les heures n’ont pas été enregistrées.

**Pages vierges lors de l’affichage d’un BAT avec plusieurs pages**

*[!DNL Workfront Proof]*

Lorsqu’un utilisateur affiche un BAT avec plusieurs pages, il peut voir les miniatures des pages, mais les pages ne s’ouvrent pas dans la visionneuse principale.



+++

+++**Mise à jour de maintenance le 22 septembre 2022**

**Impossible de fermer la carte utilisateur dans le flux de mise à jour**

*Mises à jour*

Lorsqu’un utilisateur consulte les mises à jour et survole un nom, une carte contenant les détails sur l’utilisateur dont il s’ouvre et qui ne se ferme pas automatiquement. La page ne répond pas tant que la carte n’est pas fermée manuellement en cliquant sur le X dans le coin supérieur droit.

+++

+++**Mise à jour de maintenance le 15 septembre 2022**

**&quot;[!UICONTROL Quelqu&#39;un d&#39;autre a essayé d&#39;enregistrer ce projet.]&quot; erreur lors de la saisie des heures**

*Feuilles de temps*

Lorsqu’un utilisateur tente de consigner des heures sur une tâche dans sa feuille de temps, les heures ne sont pas automatiquement enregistrées et l’utilisateur voit l’erreur suivante :

&quot;[!UICONTROL Nous sommes désolés, mais votre enregistrement a échoué, une autre personne ayant tenté d&#39;enregistrer ce projet au même moment. Veuillez tenter d&#39;enregistrer à nouveau.]&quot;

**Impossible de fermer la carte utilisateur dans le flux de mise à jour**

*Mises à jour*

Lorsqu’un utilisateur consulte les mises à jour et survole un nom, une carte contenant les détails sur l’utilisateur dont il s’ouvre et qui ne se ferme pas automatiquement. La page ne répond pas tant que la carte n’est pas fermée manuellement en cliquant sur le X dans le coin supérieur droit.

**Le &quot;[!UICONTROL Affectation de rôle de tâche]&quot; a été renommé &quot;[!UICONTROL Attribution des rôles]&quot; lors de l’affectation de travail en bloc à l’aide de la fonction [!UICONTROL Équilibreur de charge de travail]**

*[!UICONTROL Équilbreur de charge de travail]*

Pour refléter la nouvelle fonctionnalité de possibilité d’affecter à la fois des tâches et des problèmes en bloc à partir du [!UICONTROL Travail non attribué] , nous avons renommé &quot;[!UICONTROL Affectation de rôle de tâche]&quot;.[!UICONTROL Attribution des rôles]&quot; dans la variable [!UICONTROL Équilibreur de charge de travail]. Le champ fait référence à des rôles de tâche qui ont été affectés à des tâches ou à des problèmes et il s’affiche lors de l’affectation d’utilisateurs à des éléments dans le [!UICONTROL Affectations en bloc] de la boîte.

+++

+++**[!DNL Workfront Scenario Planner]Mise à jour de maintenance le 15 septembre 2022**

**Le filtre partagé avec un groupe s’affiche désormais dans la variable [!DNL Scenario Planner]&#39;s  [!UICONTROL Importation de projets] Liste des membres de tous les sous-groupes**

*[!DNL Workfront Scenario Planner]*

Désormais, lorsque vous partagez un filtre de projet avec un groupe qui comporte des sous-groupes supplémentaires, le filtre est visible pour tous les membres de groupe et de sous-groupe qui affichent les projets dans la variable [!UICONTROL Importation de projets] d’un plan dans la [!DNL Scenario Planner].

+++

+++**Mise à jour de maintenance le 8 septembre 2022**

**Noms mis à jour restaurés pour les champs d’affectation de rôle et d’utilisateur**

*Affectations*

Les champs d’affectation temporairement renommés la semaine dernière ont été restaurés à leur nom d’origine :

* [!UICONTROL Utilisateurs de l’affectation]
* [!UICONTROL Rôles pour l’affectation]

**Erreur lors de la suppression du propriétaire du projet de l’en-tête**

*Projets*

Lorsqu’un utilisateur tente de supprimer une [!UICONTROL Propriétaire du projet] dans l’en-tête d’un projet, la variable [!UICONTROL Propriétaire du projet] n’est pas supprimé et l’utilisateur voit le message d’erreur suivant :

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Redimensionné [!UICONTROL Description] la zone retourne à la taille d’origine**

*Projets, tâches et problèmes*

Lorsqu’un utilisateur redimensionne la variable [!UICONTROL Description] dans la zone de détails d’un élément de travail pour l’agrandir, puis commencer à saisir dans la zone, la zone revient à sa taille d’origine. L’utilisateur peut toujours saisir dans la zone et le contenu est enregistré comme prévu.

**Sortie accidentelle lors de la création de tâches ou de problèmes**

*Tâches et événements*

Lorsqu’un utilisateur crée une tâche ou un problème dans un projet et clique en dehors de la fenêtre contextuelle de création, la fenêtre contextuelle se ferme sans avertissement et toutes les informations précédemment saisies sont perdues.

**Suppression de la possibilité d’envoyer un BAT par courrier électronique à une zone de dépôt**

*[!DNL Workfront Proof]*

Depuis jeudi 8 septembre 2022, nous avons supprimé la possibilité d’envoyer par courrier électronique un bon à tirer à une zone de dépôt dans l’instance autonome. [!DNL Workfront Proof] produit.

Vous pouvez toujours utiliser des zones de dépôt d’autres manières pour envoyer de nouveaux BAT et de nouvelles versions de BAT à votre compte sans avoir à vous connecter à votre compte. Voir [Zone de dépôt](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html) pour plus d’informations.

+++

+++**Mise à jour de maintenance le 6 septembre 2022**

**Dates prévues ajoutées à la liste des champs pour les en-têtes de projet personnalisables**

*Projets*

Nous avons ajouté la variable [!UICONTROL Date de début prévue] et [!UICONTROL Date d’achèvement prévue] à la liste des champs des en-têtes de projet personnalisables lors de l’utilisation d’un modèle de mise en page.

**Nouvelle limite avec un message de confirmation qui affiche le nombre d’éléments ajoutés à une feuille de temps**

*Feuilles de temps*

Lorsque vous sélectionnez plus de 50 éléments à ajouter à une feuille de temps, vous recevez désormais un message de confirmation qui affiche le nombre d’éléments à ajouter à la feuille de temps et vous donne la possibilité de modifier le cours et de ne pas ajouter tous les éléments. Tous les éléments ajoutés sont automatiquement épinglés dans la feuille de temps et doivent être supprimés manuellement des feuilles de temps actuelles et futures.

+++

+++**Mise à jour de maintenance le 2 septembre 2022**

Ajoutez la variable [!UICONTROL Intégrations] champ de l’en-tête personnalisé du projet

*Intégrations*

Vous pouvez maintenant ajouter la variable [!UICONTROL Intégrations] à l’en-tête personnalisé d’un projet lorsque vous utilisez un modèle de mise en page. Une fois ajouté, le champ affiche un lien vers un élément externe lié au projet situé dans [!DNL Salesforce] ou [!DNL Anaplan], selon votre intégration.

>[!NOTE]
>
>Cette mise à jour de maintenance a été publiée dans l’environnement Aperçu le 25 août 2022 et est maintenant en production.

+++

+++**Mise à jour de maintenance le 1er septembre 2022**

**Éléments terminés supprimés de la délégation**

*Délégations*

Désormais, seuls les éléments incomplets dont les dates correspondent à celles d’une délégation seront délégués à d’autres utilisateurs au démarrage de la délégation des tâches. Si des éléments ont été remplis avant le début de la délégation, ils ne seront pas délégués. Les éléments qui sont terminés pendant la période de délégation resteront sur la liste de travail de la zone d’accueil pour le délégué et la personne désignée pendant deux semaines avant d’être supprimés automatiquement, si la délégation ne s’est pas terminée au cours de ces semaines.

**Mises à jour des métadonnées pour le [!DNL Adobe Workfront] pour [!DNL Experience Manager Assets] et [!DNL Assets Essentials] intégrations**

*Intégrations*

Les métadonnées sont automatiquement transférées lorsque vous ajoutez une ressource à un dossier lié.

Auparavant, les métadonnées étaient diffusées uniquement lorsque vous ajoutiez une ressource à l’aide de la variable [!UICONTROL Ajouter] menu déroulant.

**Ne peut pas approuver ou rejeter des heures sur un problème**

*problèmes*

Lorsqu’un utilisateur tente d’approuver ou de rejeter des heures sur la variable [!UICONTROL Heures] de l’onglet d’un problème, la variable [!UICONTROL Approuver] et [!UICONTROL Rejeter] les boutons sont manquants.

**La conversion d’un problème en projet à l’aide d’un modèle affiche un message d’erreur incorrect.**

*problèmes*

Lors de la conversion d’un problème en projet à l’aide d’un modèle et d’une erreur survient, une page contenant le message &quot;[!UICONTROL Le projet n’existe plus]&quot; au lieu du message d’erreur correct qui explique la cause de la conversion ayant échoué.

**Impossible de créer le BAT pour les fichiers de plus de 1,5 Go**

*[!DNL Workfront Proof]*

Lors de la création d&#39;un BAT, si un utilisateur télécharge un fichier de plus de 1,5 Go, le nom de fichier devient rouge et le BAT ne peut pas être créé.

+++

## Mises à jour en août 2022

+++**Mise à jour de maintenance le 25 août 2022**

**Les liens de l’équilibreur de charge de travail s’affichent incorrectement dans les tableaux de bord**

*Tableaux de bord*

Les liens équilibreur de charge de travail partageable s’affichent incorrectement lorsqu’ils sont ajoutés à un tableau de bord en tant que page externe. Au lieu d&#39;utiliser la vue/les filtres uniques associés au lien, le tableau de bord utilise la vue/les filtres appliqués le plus récemment à l&#39;équilibreur de charge de travail.

**Ajoutez la variable [!UICONTROL Intégrations] champ de l’en-tête personnalisé du projet**

*Projets*

Vous pouvez maintenant ajouter la variable [!UICONTROL Intégrations] à l’en-tête personnalisé d’un projet lorsque vous utilisez un modèle de mise en page. Une fois ajouté, le champ affiche un lien vers un élément externe lié au projet situé dans [!DNL Salesforce] ou [!DNL Anaplan], selon votre intégration.

>[!NOTE]
>
>Actuellement, cette mise à jour de maintenance n’est disponible que dans l’environnement Aperçu . Il sera publié en production une semaine après la version de prévisualisation.

**Les données personnalisées ne sont pas conservées lors de la conversion d’un problème en projet vierge.**

*Projets*

Lorsqu’un utilisateur convertit un problème en projet vierge (sans modèle), les données des champs calculés ne sont pas transférées vers le nouveau projet.

**Erreur &quot;Mode de planification de la chronologie&quot; lors de la modification d’une date sur un projet**

*Projets*

Lorsqu’un utilisateur tente de modifier une date d’un projet dont la variable [!UICONTROL Mode Plan] défini sur [!UICONTROL Enregistrement manuel] > [!UICONTROL Planification de la chronologie], la date ne change pas et l’utilisateur voit une erreur.

&quot;[!UICONTROL Le mode Planification de la chronologie n’est disponible que lorsque la date de chronologie est chargée. Veuillez contacter [!DNL Workfront] donc nous pouvons comprendre ce qui s&#39;est mal passé et y remédier.]&quot;

**Cohérence lors de l’ouverture de l’équilibreur de charge de travail à l’aide de la vue Mois**

*Équilbreur de charge de travail*

Désormais, l’équilibreur de charge de travail affiche les éléments affectés des utilisateurs développés lors de leur affichage dans la [!UICONTROL Jour], [!UICONTROL Semaine]ou [!UICONTROL Mois] vues. Avant cette mise à jour, les éléments affectés s’affichaient développés pour le [!UICONTROL Jour] et [!UICONTROL Semaine] et réduits pour les [!UICONTROL Mois] vue.


+++

+++**Mise à jour de maintenance le 18 août 2022**

**&quot;[!UICONTROL Ajouter à l’itération]&quot; et &quot;[!UICONTROL Ajouter à la carte Kanban]&quot; options non disponibles lors des tâches de modification en ligne dans un rapport.**

*Rapports*

Lorsqu’un utilisateur consulte une liste de tâches dans un rapport et ouvre la variable [!UICONTROL Plus] (à trois points), le[!UICONTROL Ajouter à l’itération]&quot; et &quot;[!UICONTROL Ajouter à la carte Kanban]&quot; ne sont pas disponibles dans la liste déroulante. Si le rapport est affiché dans un tableau de bord, le[!UICONTROL Ajouter à l’itération]&quot; et &quot;[!UICONTROL Ajouter à la carte Kanban]&quot; sont disponibles dans la liste déroulante.

**Les rapports Matrice s’affichent incorrectement lors du défilement.**

*Rapports*

Lorsqu’un utilisateur consulte un rapport Matrice et le fait défiler, certains éléments visuels du rapport peuvent se chevaucher ou se dupliquer.

**[!UICONTROL Milestone] vue supprimée de la liste des projets de feuilles de temps**

*Feuilles de temps*

Le [!UICONTROL Milestone] La vue a été supprimée de la liste des projets de la feuille de temps lors de l’ajout d’un projet.

**Les hyperliens dans un BAT interactif ne sont pas principaux**

*[!DNL Workfront Proof]*

Lorsqu&#39;un utilisateur consulte un BAT interactif et clique sur un lien ou un bouton contenant un lien, il n&#39;est pas dirigé vers la page à laquelle le lien ou le bouton renvoie.

**Nouveaux champs de texte manquants de page BAT**

*[!DNL Workfront Proof]*

Sur le [!DNL New Proof] , de nombreux champs de texte ne s’affichent pas (libellés de champ, options de liste déroulante et noms de case à cocher inclus).

**Les utilisateurs ne reçoivent pas de notifications lorsqu’ils sont balisés dans un bon à tirer**

*[!DNL Workfront Proof]*

Lorsqu’un utilisateur est balisé dans un commentaire de BAT, il ne reçoit pas de notification par courrier électronique concernant le commentaire.

+++

+++**Mise à jour de maintenance le 12 août 2022**

**Nouveau champ d’en-tête personnalisable ajouté au début de l’en-tête**

*En-têtes*

Lorsque vous ajoutez un nouveau champ à un en-tête personnalisable, le champ est maintenant ajouté comme premier champ à gauche de l’en-tête, ou juste après la balise [!UICONTROL Rechercher] dans le modèle de mise en page. Avant cette modification, le champ était ajouté comme dernier champ de l’en-tête.

+++

+++**Mise à jour de maintenance le 11 août 2022**

**Impossible de modifier les formulaires personnalisés en raison d’une limite de caractères incorrecte sur les champs de texte descriptif.**

*Formulaires personnalisés dans mon groupe*

Lorsqu’un utilisateur tente de modifier un formulaire personnalisé et que ce formulaire personnalisé comporte une [!UICONTROL Texte descriptif] qui contient actuellement plus de 512 caractères, l’utilisateur ne peut pas enregistrer les modifications apportées au formulaire personnalisé et affiche l’erreur suivante :

&quot;Les champs suivants ne sont pas valides : (Champ) est trop long, max 512&quot;

Cela affecte [!UICONTROL Texte descriptif] des champs qui fonctionnaient bien auparavant, même s’ils comportaient plus de 512 caractères.

**Les données des champs masqués par un saut de section ne sont pas conservées lors de la conversion d’un problème en projet.**

*Formulaires personnalisés dans mon groupe*

Lorsqu’un utilisateur convertit un problème en projet et qu’il inclut un formulaire personnalisé avec des données dans un saut de section qui peuvent être masquées à l’aide de la logique d’affichage, les données de cette section ne sont pas transférées vers le nouveau projet.

**Les données des champs masqués par un saut de section ne sont pas conservées lors de la conversion d’une requête en projet.**

*Formulaires personnalisés dans mon groupe*

Lorsqu’un utilisateur convertit une requête en projet et que la requête inclut un formulaire personnalisé avec des données dans un saut de section qui peuvent être masquées à l’aide d’une logique d’affichage, les données de cette section ne sont pas transférées vers le nouveau projet.

**Impossible de modifier des formulaires personnalisés en raison d’un champ de texte descriptif**

*Formulaires personnalisés dans mon groupe*

Lorsqu’un utilisateur tente de modifier un formulaire personnalisé qui comprend un champ de texte descriptif, le libellé du champ n’est pas renseigné. L’utilisateur voit l’erreur &quot;[!UICONTROL Ce champ est obligatoire]&quot; sous le champ libellé et l’utilisateur ne peut pas modifier le formulaire personnalisé en raison de cette erreur.

**Impossible de supprimer les instructions d’un champ personnalisé dans le créateur de formulaires personnalisé**

*Formulaires personnalisés dans mon groupe*

Lorsqu’un utilisateur modifie un champ personnalisé et tente de supprimer du texte existant dans la variable [!UICONTROL Instructions] , le texte n’est pas supprimé lors de l’enregistrement du champ. L’utilisateur peut modifier du texte, mais ne peut pas le supprimer entièrement.

**Affectation d’équipe lors de la création d’une requête n’apparaît pas sur une nouvelle requête**

*Demandes*

Lorsqu’un utilisateur crée une requête et qu’il y affecte une équipe, puis envoie la requête, l’équipe n’est pas affectée à la requête créée. Cela affecte uniquement l’affectation de l’équipe. Les affectations d’utilisateurs fonctionnent comme prévu.

+++

+++**Mise à jour de maintenance le 4 août 2022**

Ces problèmes ont été résolus uniquement dans la nouvelle [!DNL Workfront] expérience.

Tous [!DNL Workfront Classic] Cette fonctionnalité a été supprimée le 14 juillet 2022.

**Erreur lors du changement de la date d’achèvement planifiée dans l’en-tête d’une tâche ou d’un problème**

*Tâches et problèmes*

Lorsqu’un utilisateur tente de modifier la variable [!UICONTROL Date d’achèvement prévue] dans l’en-tête d’une tâche ou d’un problème, la date ne change pas et l’utilisateur voit une erreur similaire à celle-ci :

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Mises à jour en juillet 2022

+++**Mise à jour de maintenance le 28 juillet 2022**

Ces problèmes ont été résolus uniquement dans la nouvelle [!DNL Workfront] expérience.

Tous [!DNL Workfront Classic] Cette fonctionnalité a été supprimée le 14 juillet 2022.

**Erreur lors de l’ouverture d’un élément à partir de [!UICONTROL Liste de travail à domicile]**

*[!UICONTROL Page d’accueil]*

Lorsqu’un utilisateur tente d’ouvrir un élément sur son [!UICONTROL Liste de travail à domicile], l’élément ne s’ouvre pas et l’utilisateur voit le message suivant :

&quot;[!UICONTROL Une erreur s’est produite et nous travaillons à résoudre le problème. Pour poursuivre votre travail, essayez d’actualiser cette page de navigateur.]&quot;

**Les tâches et les problèmes délégués à un utilisateur n’apparaissent pas dans la liste de tâches domestiques de l’utilisateur.**

*[!UICONTROL Page d’accueil]*

Lorsque l’utilisateur affiche les [!UICONTROL Liste de travail à domicile], les tâches ou problèmes délégués à l’utilisateur n’apparaissent pas dans la liste et l’utilisateur peut ne pas être au courant des délégations.

**Les rapports planifiés ne sont pas envoyés à tous les destinataires.**

*Rapports*

Lorsqu’un rapport planifié est envoyé, il n’est pas envoyé à tous les utilisateurs du[!UICONTROL Envoyer à]&quot;. Les utilisateurs omis sont aléatoires et peuvent varier chaque fois que le rapport est envoyé.

**[!UICONTROL Impossible de désélectionner les tâches lors de l’association d’un modèle]**

*Modèles*

Lorsqu’un utilisateur joint et personnalise un modèle, il est invité à désélectionner les tâches qu’il ne souhaite pas inclure. Toutefois, aucune des tâches ne s’affiche comme sélectionnée et l’utilisateur ne peut pas les désélectionner.

**Les champs &quot;Paramètres régionaux&quot; ont désormais des libellés plus spécifiques.**

*Terminologie*

Pour activer la fonction de[!UICONTROL Paramètres régionaux]&quot; plus clairs, nous avons mis à jour leurs libellés.

* Le &quot;[!UICONTROL Paramètres régionaux]&quot; sur le profil utilisateur est maintenant intitulé &quot;[!UICONTROL Paramètres régionaux des emails]&quot;
* Le &quot;[!UICONTROL Paramètres régionaux]&quot; dans le champ [!UICONTROL Configuration] >[!UICONTROL Système] >[!UICONTROL Informations sur le client] est maintenant étiquetée &quot;[!UICONTROL Paramètres régionaux de l’e-mail par défaut]&quot;

La fonctionnalité de ces champs n’a pas été modifiée.

**Problèmes lors de la création de feuilles de temps**

*Feuilles de temps*

Les problèmes suivants ont été signalés concernant la création de feuilles de temps :

* Lorsqu’un utilisateur tente de créer une feuille de temps pour un rôle, celle-ci n’est pas créée et l’utilisateur voit l’erreur &quot;[!UICONTROL Utilisateur avec les valeurs de clé Principales &#39;XXXXXXXXX&#39; introuvable.]&quot;
* Lorsqu’un utilisateur tente de créer une feuille de temps pour une équipe, la variable [!UICONTROL typeforward] n’est pas renseigné avec les équipes et la variable [!UICONTROL Créer une feuille de temps] est désactivé.


**Zones [!DNL Workfront Proof] ne pas mettre à jour lorsqu’un BAT est créé, déplacé ou archivé ;**

*[!DNL Workfront]Épreuve*

Actuellement, les délais d’indexation des bons à tirer sont retardés. Cela peut avoir une incidence sur l’expérience de l’utilisateur, notamment :

* Les tableaux de bord n’affichent pas le nombre correct de bons à tirer
* Les dossiers ne sont pas mis à jour lorsqu’un BAT est créé ou déplacé
* Les BAT archivés restent sur les principales listes de BAT.

+++

+++**Mise à jour de maintenance (correctif) le 26 juillet 2022**

Ces problèmes ont été résolus uniquement dans la nouvelle [!DNL Workfront] expérience.

Tous [!DNL Workfront Classic] Cette fonctionnalité a été supprimée le 14 juillet 2022.

**Les heures affichées sur la feuille de temps diffèrent de la liste Fiches horaires**

*Feuilles de temps*

Lorsqu’un utilisateur ouvre une feuille de temps pour l’afficher, les heures affichées sont différentes de celles qui s’affichent lorsque l’utilisateur consulte la même feuille de temps dans une liste de feuilles de temps.


**La requête convertie en projet avec modèle affiche le groupe de la file d’attente des demandes, et non le groupe du modèle.**

*Demandes*

Lorsqu’un utilisateur convertit une demande en projet à l’aide d’un modèle, le projet nouvellement créé est associé au groupe propriétaire de la file d’attente des demandes, et non au groupe affecté dans le modèle. Cela se produit même si, lors de la création du projet, le groupe associé au modèle est renseigné dans la variable [!UICONTROL Groupe] champ .

+++

+++**Mise à jour de maintenance le 21 juillet 2022**

Ces problèmes ont été résolus uniquement dans la nouvelle [!DNL Workfront] expérience.

Tous [!DNL Workfront Classic] Cette fonctionnalité a été supprimée le 14 juillet 2022.

**Le statut de rejet associé à une validation honore le workflow de validation**

**REMARQUE : Cette fonctionnalité a été publiée le 22 juillet 2022.**

*Approbations*

Si vous sélectionnez un état associé à un processus de validation comme état de rejet pour un chemin de validation, l’objet rejeté passe au statut sélectionné et il sera marqué comme &quot;&quot;[!UICONTROL En attente de validation]&quot;. Par exemple, si vous sélectionnez [!UICONTROL En attente] pour le statut de rejet et le [!UICONTROL En attente] status est associé à un processus de validation, l’objet rejeté est placé dans le statut &quot;[!UICONTROL En attente d’approbation]&quot;, nécessitant la validation.

Avant cette mise à jour, l’objet a ignoré le processus de validation du statut de rejet et a été placé dans la variable [!UICONTROL En attente] statut.

**Configuration d’une URL d’aide personnalisée**

*[!UICONTROL Menu principal]*

Si votre entreprise dispose d’un site d’aide interne personnalisé, vous pouvez configurer la variable [!UICONTROL Menu Principal] [!UICONTROL Aide] pour accéder à ce site. Cela s’avère utile si le site d’aide contient des informations sur la manière dont votre entreprise utilise [!DNL Workfront].
Cette URL personnalisée n’a aucune incidence sur le lien d’aide principal situé dans la zone supérieure de [!DNL Workfront], ou les liens d’aide contextuels dans [!DNL Workfront], qui permet aux utilisateurs d’ [!DNL Workfront] Site d’aide.

**Impossible de sélectionner le temps écoulé lors de la modification en ligne [!UICONTROL Durée de la tâche]**

*Tâches*

Lorsqu’un utilisateur consulte une liste de tâches et tente de modifier la variable [!UICONTROL Durée de la tâche], les unités de durée suivantes ne sont pas disponibles :

* [!UICONTROL Minutes écoulées]
* [!UICONTROL Heures écoulées]
* [!UICONTROL Jours écoulés]
* [!UICONTROL Semaines écoulées]
* [!UICONTROL Mois écoulés]

**[!UICONTROL Mes mises à jour] page vierge**

*Mises à jour*

Lorsqu’un utilisateur tente d’afficher sa [!UICONTROL Mes mises à jour] , la page ne se charge pas. L’utilisateur ne peut afficher que la variable [!DNL Workfront] en-tête de navigation.

**&quot;[!UICONTROL Autoriser uniquement l’authentification SAML 2.0]&quot; paramètre manquant lors de la copie d’un utilisateur**

*Utilisateurs*

Lorsqu’un administrateur de groupe copie un utilisateur et désélectionne le[!UICONTROL Envoyer un courrier électronique d’invitation à cette personne]&quot;, l’option &quot;O&quot;[!UICONTROL Autoriser uniquement l’authentification SAML 2.0]&quot; n’apparaît pas comme prévu. Cela peut se produire même si toutes les exigences d’accès et d’autorisation pour cette action sont remplies.

+++

+++**Mise à jour de maintenance le 14 juillet 2022**

Ces problèmes ont été résolus uniquement dans la nouvelle [!DNL Workfront] expérience.

Tous [!DNL Workfront Classic] Cette fonctionnalité a été supprimée le 14 juillet 2022.

**Erreur lors de la réinitialisation du mot de passe**

*Connexion*

Lorsqu’un utilisateur tente de réinitialiser son mot de passe, il ne peut pas le réinitialiser et un message s’affiche lui indiquant qu’il n’y a pas accès. L’utilisateur ne peut pas se connecter à Workfront.

**Impossible de demander plus d’accès à un rapport**

*Rapports*

Lorsqu’un utilisateur disposant d’un accès limité à un rapport tente de demander un accès plus étendu à un rapport, l’option de demande un accès plus étendu n’est pas disponible sous la variable [!UICONTROL actions de rapport] .

**Mise à jour du message de confirmation lors de la suppression d’un brouillon de requête**

*Demandes*

Lors de l’abandon d’une requête préliminaire, le message de confirmation qui s’affiche après avoir cliqué sur &quot;[!UICONTROL Ignorer le brouillon]&quot; affiche les éléments suivants :

* [!UICONTROL Le brouillon a été ignoré.] (il s’agit d’une notification vous informant que votre brouillon a été ignoré)
* [!UICONTROL Annuler] (il s’agit d’un lien sur lequel vous pouvez cliquer pour rétablir l’action de suppression du brouillon. Cela permet de conserver le brouillon au lieu de le supprimer.)

Avant cette modification, les options étaient les suivantes :

* [!UICONTROL Le brouillon sera ignoré]
* [!UICONTROL Annuler]

**Valeurs de date des champs d’entrée de journal incorrectes lorsqu’elles sont accessibles via l’API**

*Mises à jour*

Lorsqu’un utilisateur modifie une valeur de date sur un objet, puis que l’entrée de journal représentant ce changement de date est accessible via l’API, les valeurs de date pour [!UICONTROL oldDateVal] et [!UICONTROL newDateVal] renvoyés par l’API sont incorrects.

**Erreur lors de la tentative d’annulation d’un commentaire**

*Mises à jour*

Lorsqu’un utilisateur tente d’annuler un commentaire, celui-ci n’annule pas et l’utilisateur affiche l’erreur suivante :

[!UICONTROL Erreur 403 : Vous ne disposez pas d’un accès suffisant pour supprimer cette note /attask/api-internal/REMARQUE]

**Nouvelle limitation du nombre de caractères dans une mise à jour dans Aperçu**

*Mises à jour*

Pour améliorer les performances de la variable [!UICONTROL Mises à jour] , nous avons introduit une nouvelle limite au nombre de caractères que vous pouvez saisir dans une mise à jour ou une réponse à une mise à jour existante. La nouvelle limite est de 15 000 caractères. Cette mise à jour n’a pas modifié le nombre de caractères autorisés lors de l’utilisation de l’API. La limite de caractères de l’API pour les mises à jour est de 4 000.

**Erreur lors du téléchargement d’une pièce jointe depuis [!DNL Workfront] pour l’intégration d’Outlook**

*Intégrations Workfront*

Lorsqu’un utilisateur tente de télécharger une pièce jointe à l’aide de la variable [!DNL Workfront for Outlook] intégration, la pièce jointe ne charge pas et l’utilisateur voit le message suivant :

[!UICONTROL Certaines pièces jointes n’ont pas été chargées. Motif : Un problème s’est produit lors du téléchargement des pièces jointes.]

**Mise à jour de la notification par courrier électronique de BAT**

*[!DNL Workfront]Épreuve*

Ce mois-ci, dans le cadre d’un correctif au [!DNL Workfront] Environnement de production, nous avons corrigé un bogue dans le système de notification par courrier électronique du BAT. Cette modification n’a pas été communiquée dans la mise à jour de maintenance lors de sa publication. Nous avons ajouté les informations suivantes au [Mise à jour de maintenance le 2 juin 2022](#maintenance-update-on-june-2-2022) :

Suite à ces correctifs, l’adresse électronique utilisée pour envoyer les notifications de BAT a changé.

Auparavant, les adresses électroniques du BAT contenaient le sous-domaine de votre entreprise. Par exemple, notifications@[domaine d&#39;entreprise].my.workfront.com

Désormais, la configuration des adresses électroniques ne contient plus de sous-domaine d’organisation. Toutes les notifications par courrier électronique de BAT proviennent de l’adresse suivante : notification@my.workfront.com

Par conséquent, nous vous recommandons d’effectuer les actions suivantes si vous ne l’avez pas déjà fait :

* Mettez à jour vos filtres anti-spam pour accepter les emails de notification@my.workfront.com
* Mettre à jour vos listes autorisées pour accepter les emails de notification@my.workfront.com

**Les options utilisateur ne peuvent pas être modifiées après la configuration initiale dans les modèles de workflow.**

*[!DNL Workfront Proof]*

Lorsqu’un utilisateur ajoute un utilisateur à un modèle de workflow, il peut configurer des options. Cependant, une fois la configuration initiale terminée, l’utilisateur ne peut plus modifier les éléments suivants :

* &quot;[!UICONTROL Résoudre les commentaires et appliquer des actions]Capacité
* [!UICONTROL &quot;Partage du BAT par balisage]Capacité
* Rôle BAT ([!UICONTROL Réviseur], [!UICONTROL Approbateur], etc.)

**&quot;[!UICONTROL Éléments de travail de ce projet]&quot;le filtre a été restauré dans le projet [!UICONTROL Équilibreur de charge de travail]**

*[!UICONTROL Équilbreur de charge de travail]*

Nous avons restauré le filtre &quot;Éléments de travail de ce projet&quot; dans la variable [!UICONTROL Attribué] lorsque vous accédez à la zone [!UICONTROL Équilibreur de charge de travail] d’un projet.

Ce filtre est maintenant répertorié sous le[!UICONTROL Suggérée]&quot; des filtres pour la variable [!UICONTROL Travail attribué] zone d’un projet [!UICONTROL Équilibreur de charge de travail].

+++

## Mises à jour en juin 2022

+++**Mise à jour de maintenance le 30 juin 2022**

**Afficher le [!UICONTROL Équilibreur de charge de travail] pour une semaine**

*[!UICONTROL Équilbreur de charge de travail]*

En fonction des commentaires de nombreux clients, nous avons maintenant ajouté une option pour afficher la variable [!UICONTROL Équilibreur de charge de travail] pour une semaine. Avant cette mise à jour, vous pouvez afficher la variable [!UICONTROL Équilibreur de charge de travail] pendant 4, 6 et 12 semaines. Avec cette mise à jour, nous avons également défini l’option 12 semaines sur 3 mois.

**Le panneau Déléguer est désormais disponible dans l’équilibreur de charge de travail**

*[!UICONTROL Équilbreur de charge de travail]*

REMARQUE : Cette mise à jour existe uniquement dans l’environnement Aperçu . Les fonctionnalités associées à cette mise à jour seront disponibles dans Production avec la version 22.3.

Vous pouvez désormais afficher les délégués d’une tâche ou d’un problème à partir de l’équilibreur de charge de travail. Lors de l’affectation d’une tâche ou d’un problème à partir de l’équilibreur de charge de travail, vous pouvez afficher une liste des affectations ainsi qu’une liste des délégués pour la tâche ou le problème, s’ils sont actuellement délégués.

**Impossible d’ouvrir les informations de point de fin dans l’explorateur d’API**

*API*

Lorsqu’un utilisateur consulte la variable [!DNL API Explorer] et clique sur un point de terminaison , les informations du point de terminaison ne s’affichent pas.

**Problèmes liés à [!UICONTROL Détails] lors de l’utilisation du bouton [!UICONTROL Calendrier d’accueil]**

*Page d’accueil*

Lorsqu’un utilisateur utilise la variable [!UICONTROL Calendrier d’accueil] et clique sur une tâche, l’un des événements suivants peut se produire :

* Le [!UICONTROL Détails] s’affiche brièvement, puis disparaît. L’utilisateur ne peut pas accéder aux détails.
* Le [!UICONTROL Détails] n’apparaît pas. L’utilisateur ne peut pas accéder aux détails.
* Le [!UICONTROL Détails] s’affiche, mais n’est pas à l’emplacement approprié. L’utilisateur peut cliquer sur le bouton pour accéder aux détails.

+++

+++**Mise à jour de maintenance (correctif) le 24 juin 2022**

**Le sélecteur de date ne se ferme pas lors de la modification du formulaire personnalisé**

*Formulaires personnalisés*

Lorsqu’un utilisateur modifie un formulaire personnalisé et tente de modifier une date, le sélecteur de date ne se ferme pas lorsque la date est sélectionnée. L’utilisateur ne peut pas fermer le sélecteur de date en enregistrant, en annulant ou en cliquant hors du sélecteur de date.

Cela a été signalé dans les domaines suivants :

* [!UICONTROL Mises à jour] area
* [!UICONTROL Page d’accueil]

**L&#39;utilisateur ne peut pas se déplacer vers une autre étape d&#39;un BAT**

*Épreuves*

Lorsqu’un utilisateur consulte la variable [!UICONTROL Workflow de BAT] d’un BAT et de toute tentative de se faire glisser vers une autre étape du BAT, le nom de l’utilisateur revient à l’étape d’origine, et ils ne sont pas ajoutés à l’étape souhaitée.

+++

+++**Mise à jour de maintenance le 23 juin 2022**

**[!UICONTROL Impossible d’ajouter une nouvelle requête via le tableau de bord]**

*Tableaux de bord*

Lorsqu’un utilisateur consulte un tableau de bord sur un projet et tente d’ajouter une nouvelle requête en cliquant sur le [!UICONTROL +Nouvelle requête] , le bouton ne répond pas et l’utilisateur ne peut pas ajouter de nouvelle requête.

**Erreur lors de l’affichage d’éléments dans la liste de travail d’accueil**

*[!UICONTROL Page d’accueil]*

Lorsqu’un utilisateur consulte le rapport [!UICONTROL Liste de travail à domicile] et clique sur un élément dans la variable [!UICONTROL Validations que j’ai envoyées] , la page affiche l’erreur suivante :

&quot;[!UICONTROL Une erreur s&#39;est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d&#39;actualiser cette page de navigateur.]&quot;

Si l’utilisateur actualise la page, il clique sur n’importe quel élément de la variable [!UICONTROL Liste de tâches], l’erreur s’affiche. Le problème n’affecte plus uniquement les éléments de la variable [!UICONTROL Validations que j’ai envoyées] .

**La section personnalisée sur un objet inclut des résultats qui ne sont pas dans cet objet.**

*Objets*

Lorsqu’un utilisateur affiche une [!UICONTROL custom] sur un objet, la section personnalisée affiche les éléments qui ne font pas partie de cet objet. Cela a été signalé lorsque la section personnalisée est ajoutée directement à l’objet et lorsqu’une section personnalisée est ajoutée par le biais d’un modèle de mise en page.

**Les tâches sont déplacées vers un projet incorrect**

*Tâches*

Lorsqu’un utilisateur déplace des tâches du projet A vers le projet B, puis déplace d’autres tâches du projet A vers le projet C, les tâches initialement déplacées vers le projet B apparaissent sur le projet C.

**Certains boutons/icônes ne fonctionnent pas lors de l’accès à [!UICONTROL Équilibreur de charge de travail] à partir d’un lien partagé ou d’un tableau de bord**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsqu’un utilisateur accède à la variable [!UICONTROL Équilibreur de charge de travail] via un lien partagé ou un lien dans un tableau de bord et qui tente d&#39;utiliser l&#39;élément en haut de l&#39;écran, les éléments ne fonctionnent pas. Cela a été signalé pour les éléments suivants :

* [!UICONTROL Aujourd’hui]
* Flèches Précédent et Suivant
* [!UICONTROL Semaines]
* Icône Calendrier (sélecteur de date)

+++

+++**[!DNL Workfront]Mise à jour de la maintenance du planificateur de scénario le 23 juin 2022**

**Utilisateurs avec [!UICONTROL Gérer] les autorisations d’un plan peuvent le partager avec d’autres**

En tant qu’utilisateur avec [!UICONTROL Gérer] autorisations d’un plan dans la variable [!DNL Scenario Planner], vous pouvez désormais le partager avec d’autres utilisateurs. Avant cette mise à jour, seul le créateur du plan pouvait partager le plan avec d’autres utilisateurs.

+++

+++**Mise à jour de maintenance le 16 juin 2022**

**L’administrateur de groupe ne peut pas ajouter de membres au groupe.**

*Groupes*

Lorsqu’un administrateur de groupe tente d’ajouter un utilisateur à un groupe, la liste déroulante pour sélectionner l’utilisateur ne s’affiche pas. L’administrateur du groupe ne peut sélectionner aucun utilisateur et ne peut donc ajouter aucun utilisateur au groupe.

**Les trimestres personnalisés ne s’affichent pas lors de la définition d’un filtre**

*Filtres*

Lorsqu’un utilisateur crée un filtre et des filtres par champ de date, la liste déroulante des opérateurs disponibles pour le champ de date n’inclut aucun trimestre personnalisé récemment ajouté.

**Erreur &quot;Ouvre&quot; lors de la conversion d’un problème vers un projet via un modèle**

*Projets*

Lorsqu’un utilisateur tente de convertir un problème en projet via un modèle et qu’il dispose d’un formulaire personnalisé contenant une section réservée aux administrateurs, le problème n’est pas converti et l’utilisateur voit l’erreur suivante :

&quot;[!UICONTROL Réessayons. Oups ! Un problème est survenu. Veuillez contacter [!DNL Workfront] donc nous pouvons comprendre ce qui s&#39;est mal passé et y remédier.]&quot;

**Les demandes sont envoyées sans champs obligatoires renseignés**

*Demandes*

Lorsqu’un utilisateur crée une requête et ne remplit pas les champs requis, puis envoie la requête, celle-ci est envoyée sans données dans les champs requis. Le comportement attendu est que la demande ne soit pas envoyée et que l’utilisateur soit informé qu’il doit renseigner les champs requis avant de soumettre la demande.

**Les nouveaux trimestres personnalisés ne semblent pas être enregistrés**

*Configuration*

Lorsqu’un utilisateur ajoute un nouveau trimestre personnalisé à partir de la zone Configuration des projets et clique sur [!UICONTROL Enregistrer], il n’existe aucune indication visuelle de l’enregistrement. L’utilisateur ne voit pas de message de réussite, et la variable [!UICONTROL Enregistrer] toujours présente et principale. Cependant, si l’utilisateur actualise la page, il peut constater que les nouveaux trimestres apparaissent dans la liste des trimestres personnalisés.

Si l’utilisateur ajoute un nouveau trimestre, cliquez sur [!UICONTROL Enregistrer], ne reçoit aucune indication de l’enregistrement, ajoute un autre trimestre sans actualiser la page, puis clique [!UICONTROL Enregistrer] encore une fois, le deuxième trimestre ajouté peut ne pas être enregistré.

**[!UICONTROL Demandes de travail d’équipe] page vierge**

*Équipes*

REMARQUE : Ce problème existe uniquement dans l’environnement Aperçu .

Lorsqu’un utilisateur tente d’ouvrir la variable [!UICONTROL Requêtes de travail] sur une page d’équipe, la page est vierge. L’utilisateur peut voir la barre de navigation supérieure, mais pas le contenu de la page.

+++

+++**Mise à jour de maintenance le 9 juin 2022**

**Impossible de sélectionner les objets à filtrer [!UICONTROL Portfolio Optimizer] préférences**

*Portefeuilles*

Lorsqu’un utilisateur se trouve dans la variable [!UICONTROL Portfolio Optimizer] et affiche la variable [!UICONTROL Filtres de projet] dans le [!UICONTROL Préférences] , les cases à cocher en regard des objets sont absentes. L’utilisateur ne peut pas cocher ou décocher de cases, et par conséquent ne peut pas sélectionner d’objets à filtrer.

**Modification impossible [!UICONTROL Date de début planifiée] ou [!UICONTROL Date d’achèvement prévue] when[!UICONTROL Planifier à partir de]&quot; n’est pas coché**

*Projets*

Lorsqu’un utilisateur tente de modifier la variable [!UICONTROL Date de début planifiée] ou [!UICONTROL Date d’achèvement prévue] d’un projet et le[!UICONTROL Planifier à partir de]&quot; n’est pas cochée pour ce projet, la variable [!UICONTROL Date de début planifiée] et [!UICONTROL Date d’achèvement prévue] sont désactivées et l’utilisateur ne peut pas modifier ces dates.

**Impossible de modifier le niveau d’accès des utilisateurs**

*Utilisateurs*

Lorsqu’un utilisateur disposant d’un accès de planificateur qui inclut un accès d’administrateur de groupe (utilisateurs de groupe) tente de modifier des utilisateurs du groupe pour lequel il est administrateur, la variable [!UICONTROL Accès] Le champ level est désactivé et l&#39;utilisateur ne peut pas modifier le niveau d&#39;accès.

+++

+++**[!DNL Workfront Scenario Planner]Mise à jour de maintenance le 9 juin 2022**

**Panneau de gauche redimensionnable dans[!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

Vous pouvez désormais redimensionner le panneau de gauche d’un plan, dans la [!DNL Scenario Planner]. Cela permet l’affichage complet des noms d’initiative plus longs. Avant cette mise à jour, les noms d’initiative plus longs étaient tronqués.

+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 9 juin 2022**

**Données provenant de formulaires personnalisés non disponibles dans [!DNL Workfront Fusion] [!DNL Workfront] modules**

*[!DNL Workfront Fusion]*

Lorsqu’un utilisateur configure un [!DNL Workfront] module dans [!DNL Workfront Fusion]et tente de sélectionner les sorties pour le module, les champs des formulaires personnalisés ne sont pas visibles. Cela se produit lorsque le formulaire personnalisé a été créé pour un type de [!DNL Workfront] puis un autre type a été ajouté. [!DNL Workfront Fusion] affiche uniquement les champs de formulaires personnalisés créés à l’origine pour le type d’objet sélectionné.

**Impossible de faire défiler pour afficher toutes les exécutions de scénario**

*[!DNL Workfront Fusion]*

Lorsqu’un utilisateur consulte l’historique d’exécution d’un scénario et tente de faire défiler l’écran vers le bas pour afficher d’autres exécutions, les exécutions cessent de se charger et l’utilisateur ne peut pas les afficher. En outre, l’utilisateur ne peut pas faire défiler jusqu’aux exécutions les plus récentes.

+++

+++**Mise à jour de maintenance le 2 juin 2022**

**[!UICONTROL Portfolio Optimizer] affiche un score de 0 lors de l’utilisation d’une langue autre que l’anglais**

*Portefeuilles*

Lorsqu’un utilisateur utilise [!DNL Workfront] dans une autre langue que l’anglais et affiche la variable [!UICONTROL Portfolio Optimizer], le score s’affiche comme 0. Cela peut se produire même lorsque l’analyse de cas n’est pas terminée.

**Valeurs de champ calculé incorrectes lors de la création d’un projet à partir d’un modèle**

*Projets*

Lorsqu’un utilisateur crée un projet à partir d’un modèle qui inclut des champs calculés, les valeurs de champ qui apparaissent sur le nouveau projet sont incorrectes.

**Impossible de modifier [!UICONTROL Conditions] in [!UICONTROL Préférences du projet] area of [!UICONTROL Configuration]**

*[!UICONTROL Configuration]*

Lorsqu’un utilisateur tente de modifier [!UICONTROL Conditions] dans le [!UICONTROL Préférences du projet] area of [!UICONTROL Configuration], la page est vide.

**Nouvelle limitation du nombre de caractères dans une mise à jour dans Aperçu**

*[!UICONTROL Équilbreur de charge de travail]*

>[!NOTE]
>
>Cette mise à jour s’applique uniquement à l’environnement Aperçu .

Pour améliorer les performances de la zone Mises à jour , nous avons introduit une nouvelle limite au nombre de caractères que vous pouvez saisir dans une mise à jour ou dans une réponse à une mise à jour existante. La nouvelle limite est de 15 000 caractères. Cette mise à jour n’a pas modifié le nombre de caractères autorisés lors de l’utilisation de l’API. La limite de caractères de l’API pour les mises à jour est de 4 000. Mise à jour de la prise en charge des champs personnalisés de type Typehead dans les filtres de l’équilibreur de charge de travail

Nous prenons désormais en charge les filtres basés sur la variable [!UICONTROL Tirage anticipé] saisissez des champs personnalisés dans l’équilibreur de charge de travail. Avant ce correctif, le filtrage de ce type de champs personnalisés n’était pas possible dans l’équilibreur de charge de travail.

**Impossible de modifier les autorisations sur le rôle d’un utilisateur**

*[!DNL Workfront Proof]*

Lorsqu’un utilisateur tente de modifier le[!UICONTROL Résoudre les commentaires et appliquer des actions]&quot; ou &quot;[!UICONTROL Partage d’un BAT par balisage]&quot; autorisations sur le rôle d’un utilisateur dans [!DNL Workfront Proof], les modifications ne sont pas enregistrées. L’utilisateur reçoit une notification indiquant que le modèle a été mis à jour, mais si l’utilisateur ouvre à nouveau les autorisations de rôle, il peut constater que les modifications n’ont pas été enregistrées.

+++


## Mises à jour en mai 2022

+++**Mise à jour de maintenance le 26 mai 2022**

Ces problèmes ont été résolus uniquement dans la nouvelle [!DNL Workfront] expérience. [!DNL Adobe Workfront Classic] n’est plus prise en charge.

Tous [!DNL Workfront Classic] Cette fonctionnalité sera supprimée en juillet 2022. Effectuez une transition vers la nouvelle expérience dès que possible.

**Séparateurs de chemin de navigation mis à jour**

*[!DNL Workfront]*

REMARQUE : Cette mise à jour a été publiée le 24 mai 2022.

Nous avons mis à jour les séparateurs de chemin de navigation dans toutes les zones où des chemins de navigation sont disponibles. Désormais, les objets des chemins de navigation sont séparés par des barres verticales (|). Avant cette mise à jour, ils étaient séparés par des barres obliques (/).

**Impossible de modifier les formulaires personnalisés avec des sauts de section**

*Formulaires personnalisés*

Lorsqu’un utilisateur tente de modifier un formulaire personnalisé avec un saut de section, il ne peut pas le modifier et le message suivant s’affiche :

[!UICONTROL La sécurité du saut de section spécifiée ne peut pas être appliquée à tous les types d’objet]

**Problèmes lors de l’impression des tableaux de bord sur PDF**

*Tableaux de bord*

Les problèmes suivants ont été signalés lors de l’impression d’un tableau de bord sur un PDF : Le PDF n’imprime pas toutes les lignes du rapport. Lorsque des lignes sont manquantes, seul l’espace vide s’affiche.
Le PDF comprend des espaces vides entre les en-têtes de colonne et la première ligne du rapport.

**[!DNL Portfolio Optimizer]affiche un score de 0 lors de l’utilisation d’une langue autre que l’anglais**

*Portefeuilles*

Lorsqu’un utilisateur utilise [!DNL Workfront] dans une autre langue que l’anglais et affiche la variable [!UICONTROL Portfolio Optimizer], le score s’affiche comme 0. Cela peut se produire même lorsque l’analyse de cas n’est pas terminée.

**Certains formulaires personnalisés ne s’affichent pas lors de la modification d’un modèle**

*Modèles*

Lorsqu’un utilisateur tente de modifier les formulaires personnalisés sur un modèle en cliquant sur [!UICONTROL Modifier] dans l’en-tête du modèle, la variable [!UICONTROL Modifier le modèle] n’affiche que l’un des formulaires personnalisés associés au modèle.

**Le lien partagé avec l’équilibreur de charge de travail affiche incorrectement le travail attribué.**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsqu’un utilisateur affiche la variable [!UICONTROL Équilibreur de charge de travail] à l’aide d’un lien partagé, la variable [!DNL Workload Balancer] inclut [!UICONTROL Travail attribué] dans le [!UICONTROL Travail non attribué] . [!UICONTROL Travail attribué] ne comporte pas de section distincte. Lorsque l’utilisateur affiche la variable [!UICONTROL Équilibreur de charge de travail] sans utiliser le lien partagé, [!UICONTROL Travail attribué] s’affiche comme prévu.

+++

+++**Mise à jour de la maintenance le 19 mai 2022**

**Impossible de créer un BAT à partir d’un[!DNL PowerPoint]**

*[!DNL Workfront Proof]*

Lorsqu’un utilisateur tente de créer un BAT à partir d’un [!DNL PowerPoint] qui inclut un graphique, la création du BAT échoue.

**Impossible de créer un BAT à partir d’un [!UICONTROL Word] document**

*[!DNL Workfront Proof]*

Lorsqu’un utilisateur tente de créer un BAT à partir d’un [!DNL Word] qui comprend un graphique, la création du BAT échoue.

**Impossible d’ajouter un message personnalisé lors du partage d’un BAT**

*[!DNL Workfront Proof]*

Lorsqu’un utilisateur consulte un BAT, ouvre la variable [!UICONTROL Partager le BAT] et sélectionne la variable [!UICONTROL Ajout d’un message personnalisé] , l’utilisateur ne peut pas saisir dans la zone de texte qui s’ouvre. Lorsque l’utilisateur tente de saisir du texte dans cette zone, la zone disparaît immédiatement.

**Impossible de fermer le BAT**

*[!DNL Workfront Proof]*

Lorsqu’un utilisateur consulte un BAT et tente de le fermer, le X pour fermer le BAT est absent du coin supérieur droit du BAT.

**Impossible d’ajouter ou de supprimer un administrateur de groupe**

*Groupes*

Si un utilisateur consulte une [!UICONTROL Groupe] et tente d’ajouter ou de supprimer un administrateur de groupe à l’aide de la méthode [!UICONTROL Administrateurs de groupe] dans l’en-tête, les modifications ne sont pas enregistrées et l’utilisateur voit l’erreur suivante :

[!UICONTROL Erreur Oups ! Un problème est survenu. Veuillez contacter [!DNL Workfront] donc nous pouvons comprendre ce qui s&#39;est mal passé et y remédier.]

**Blocs de la barre de défilement horizontale en fin de liste**

*Projets*

Lorsqu’un utilisateur consulte une liste à l’aide d’une vue qui s’étend hors du côté de l’écran, la barre de défilement horizontale bloque l’affichage du dernier élément de la liste par l’utilisateur.

**&quot;[!UICONTROL Erreur inattendue]&quot; lors de la conversion d’un problème en projet à l’aide d’un modèle ;**

*Listes*

Lorsqu’un utilisateur tente de convertir un problème en projet à l’aide d’un modèle, le problème n’est pas converti et l’utilisateur voit le message suivant :

[!UICONTROL Une erreur inattendue s&#39;est produite]

**Le [!UICONTROL État] dans une vue de feuille de temps est désormais en lecture seule.**

*Feuilles de temps*

Nous avons modifié la variable [!UICONTROL État] dans une vue de feuille de temps pour être en lecture seule. Avant cette modification, les utilisateurs pouvaient modifier en ligne l’état d’une feuille de temps qui leur permettait de remplacer la décision des approbateurs de la feuille de temps.

+++

+++**Mise à jour de la maintenance le 12 mai 2022**

**[!UICONTROL Enregistrer] n’arrête pas le chargement lors de la modification d’un projet.**

*Projets*

Lorsqu’un utilisateur modifie un projet et tente d’enregistrer, il remarque que la variable [!UICONTROL Enregistrer] affiche le mot &quot;[!UICONTROL Chargement].&quot; Si l’utilisateur clique sur ce bouton pour enregistrer les modifications apportées au projet, le bouton ne répond pas et les modifications ne sont pas enregistrées.

**Les libellés de champ ne s’affichent pas lors de l’affichage d’un objet dans [!UICONTROL Accueil]**

*Page d’accueil*

Lorsqu’un utilisateur sélectionne un objet parmi les [!UICONTROL Liste de travail à domicile], la zone située à droite de la propriété [!UICONTROL Liste de travail à domicile] qui affiche l’objet n’inclut pas de libellés de champ. Les valeurs de champ sont présentes.

**Le filtre rapide ne se concentre pas automatiquement sur la barre de recherche**

*Listes*

Lorsqu’un utilisateur se trouve dans une liste et clique sur la loupe pour accélérer le filtrage, puis commence à saisir, le texte n’apparaît pas. En effet, l’accent est toujours mis sur l’icône de loupe plutôt que de la transférer vers la barre de recherche.

Cliquer sur la barre de recherche transfère la cible d’action et permet à l’utilisateur de saisir le texte de sa recherche.

**Utilisateurs ne pouvant pas insérer de champs de modification en ligne dans un rapport**

*Rapports*

Lorsqu’un utilisateur tente de modifier un champ d’un rapport et que ce champ est extrait d’un formulaire personnalisé, il ne peut pas le modifier. Cela se produit lorsque le formulaire personnalisé a été créé à l’origine pour un type d’objet autre que l’objet auquel il est associé.

**Libellé et texte de bouton non visible lors de la création d’un BAT**

*[!DNL Workfront Proof]*

REMARQUE : Ce problème existe uniquement dans l’environnement Aperçu .

Lorsqu’un utilisateur tente de créer un BAT, le texte n’est pas visible pour les options ou les boutons. Par conséquent, l’utilisateur ne sait pas ce que représentent chaque option ou bouton et ne peut pas configurer le BAT.

+++

+++**Mise à jour de maintenance le 5 mai 2022**

**Impossible d’ajouter un nouvel enregistrement de facturation**

*Projets*

Lorsqu’un utilisateur se trouve dans la variable [!UICONTROL Enregistrements de facturation] d’un projet et utilise la variable [!UICONTROL Nouvel enregistrement de facturation] Si l’utilisateur tente d’ajouter un nouvel enregistrement de facturation, les champs d’un nouvel enregistrement de facturation ne s’affichent pas et l’enregistrement de facturation ne peut pas être créé.

**Erreur lors de l’attribution en bloc dans [!UICONTROL Équilibreur de charge de travail]**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsqu’un utilisateur tente d’effectuer des affectations dans la variable [!DNL Workload Balancer] d’un projet, l’utilisateur est redirigé vers une page avec le message suivant :

&quot;[!UICONTROL Une erreur s&#39;est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d&#39;actualiser cette page de navigateur.]&quot;

L’utilisateur ne peut pas quitter cette page tant qu’il n’a pas actualisé la page.

**Mise à jour de la navigation pour ouvrir le [!UICONTROL Résumé] pour les tâches et les problèmes dans la [!UICONTROL Équilibreur de charge de travail]**

*[!UICONTROL Équilbreur de charge de travail]*

Maintenant, il vous suffit de cliquer sur une tâche ou une barre de problèmes dans la [!UICONTROL Équilibreur de charge de travail] ouvre le panneau Résumé. Avant cette mise à jour, vous deviez cliquer sur le bouton [!UICONTROL Résumé ouvert] dans la barre d’outils, puis cliquez sur la tâche ou le problème. Cela avait prouvé une expérience déroutante qui est maintenant corrigée. Vous pouvez également cliquer sur le bouton [!UICONTROL Plus] en regard du nom de la tâche ou du problème, puis cliquez sur [!UICONTROL Résumé ouvert].

**L’administrateur de groupe ne peut pas afficher les détails des utilisateurs du groupe.**

*Utilisateurs*

Lorsqu’un utilisateur est affecté à un niveau d’accès qui comprend la variable [!UICONTROL Administration des utilisateurs (utilisateurs de groupe)] le paramètre d’accès tente d’afficher les détails d’un utilisateur dans son groupe. l’erreur suivante s’affiche :

&quot;[!UICONTROL Réessayons. Oups ! Un problème est survenu. Veuillez contacter [!DNL Workfront] donc nous pouvons comprendre ce qui s&#39;est mal passé et y remédier.]&quot;

**Impossible de supprimer l’état du groupe personnalisé**

*Groupes*

Lorsqu’un utilisateur tente de supprimer un état de groupe personnalisé de la variable [!UICONTROL Groupe] , la page reste vide et l’état n’est pas supprimé.

**Les paramètres d’alerte par e-mail sont incohérents entre la zone Contacts et les Détails de l’utilisateur**

*[!DNL Workfront Proof]*

Paramètres des alertes par e-mail affichés dans la [!UICONTROL Contacts] area of [!DNL Workfront Proof] pour un utilisateur donné sont différents du paramètre d’alerte par e-mail défini dans la variable [!UICONTROL Détails de l’utilisateur].

**Impossible d’utiliser l’outil Texte lors de l’ajout d’un commentaire sur un BAT**

*[!DNL Workfront Proof]*

Lorsqu’un utilisateur fait un commentaire sur un BAT et tente d’ouvrir la variable [!UICONTROL Texte] , l’outil ne s’ouvre pas et l’utilisateur voit le message suivant :

&quot;[!UICONTROL Les données textuelles de cette page sont toujours en cours de téléchargement. Veuillez attendre.]&quot;

**Les emails de BAT seront envoyés à l’Principal email de l’utilisateur.**

*[!DNL Workfront Proof]*

Nous ajustons la façon dont les notifications électroniques de BAT sont envoyées. Désormais, les notifications sont envoyées à l’adresse email Principale de l’utilisateur plutôt qu’à l’adresse email d’alias générée par le système.

Pour plus d’informations sur la raison pour laquelle le système génère des emails d’alias, voir Synchronisation des utilisateurs entre les Adobes . [!DNL Workfront] et [!DNL Workfront Proof].

+++

## Mises à jour en avril 2022

+++**Mise à jour de maintenance le 28 avril 2022**

**Impossible de faire défiler jusqu’à [!UICONTROL Enregistrer] lors de la modification d’une feuille de temps**

*Feuilles de temps*

Lorsqu’un utilisateur modifie une feuille de temps, il ne peut pas faire suffisamment défiler la fenêtre de modification pour afficher la variable [!UICONTROL Enregistrer] et ne peut donc pas modifier la feuille de temps.

**La signature électronique vérifie désormais l’ID de fédération**

*Épreuves*

Lors de la signature électronique d’un BAT, le système vérifie désormais l’ID de fédération, si l’authentification unique est configurée dans [!DNL Workfront Proof], en plus de votre adresse électronique dans [!DNL Workfront].

Auparavant, le système vérifiait uniquement votre adresse électronique dans Workfront.

+++

+++**Mise à jour de maintenance (correctif) le 25 avril 2022**

**[!UICONTROL Équilibreur de charge de travail] ne charge pas**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsqu’un utilisateur tente d’ouvrir la variable [!UICONTROL Équilibreur de charge de travail], la charge de navigation de l’en-tête et de gauche, mais le contenu de l’équilibreur de charge de travail ne charge pas. L’utilisateur voit des carrés gris clignotants au lieu de données. Parfois, une partie du contenu se charge, mais l’utilisateur voit toujours des carrés gris clignotants où se trouvent les données manquantes.

+++

+++**Mise à jour de maintenance le 21 avril 2022**

**L’ajout d’une tâche entraîne le saut de page vers le bas**

*Tâches*

Lorsqu’un utilisateur ajoute une tâche en dessous d’une tâche existante dans une liste, la page passe en bas de la liste. Bien que la nouvelle tâche soit au bon endroit, l’utilisateur doit faire défiler la page vers le haut pour la localiser.

**Les utilisateurs ajoutés à un BAT ne peuvent pas accéder à l’élément de travail du BAT dans[!DNL Workfront]**

*Épreuves*

Si un utilisateur est ajouté à une étape dans le workflow d’un BAT, il n’est pas ajouté au partage de document et n’obtient pas d’autorisations sur l’élément de travail du BAT dans [!DNL Workfront]. Lorsque l’utilisateur se trouve dans [!DNL Workfront] et tente d’ouvrir l’élément de travail auquel le BAT est joint, le message suivant s’affiche :

&quot;[!UICONTROL Vous ne disposez pas d’un accès suffisant pour afficher cet objet.]&quot;

Ce problème est spécifique aux bons à tirer déjà créés et aux utilisateurs ajoutés après coup. L’ajout d’utilisateurs au workflow avant la création du BAT fonctionne comme prévu.

**Impossible d’envoyer le courrier électronique de réinitialisation de mot de passe à partir de[!DNL Workfront]**

*Utilisateurs*

Lorsqu’un utilisateur tente d’envoyer un courrier électronique de réinitialisation de mot de passe à partir d’une liste d’utilisateurs dans [!DNL Workfront], l’option permettant d’envoyer l’email n’est pas disponible.

**Le bouton affiche &quot;[!UICONTROL Problème de début]&quot; plutôt que &quot;[!UICONTROL Lancer la requête]&quot;**

*Demandes*

Lorsqu’un utilisateur consulte une requête attribuée à son équipe, il voit un &quot;[!UICONTROL Problème de début]&quot; dans l’en-tête plutôt qu’un &quot;[!UICONTROL Lancer la requête]&quot;.

**&quot;[!UICONTROL Annuler le commentaire]L’option supprime les utilisateurs balisés**

*Mises à jour*

Lorsqu’un utilisateur marque un autre utilisateur dans un commentaire, publie le commentaire, puis sélectionne le[!UICONTROL Annuler le commentaire]&quot;, le commentaire s’affiche normalement dans une zone de mise à jour, mais l’utilisateur balisé ne se trouve pas dans la balise [!UICONTROL Utilisateurs balisés] de la boîte.

**Impossible de faire défiler lors de l’utilisation de [!UICONTROL Milestone] affichage dans un rapport**

*Rapports*

Lorsqu’un utilisateur consulte un rapport et sélectionne la variable [!UICONTROL Milestone] vue, la page affiche la vue Milestone mais ne fait plus défiler et l’utilisateur ne peut pas afficher les jalons qui seraient plus bas dans la page.

**Monnaie incorrecte lorsque le rapport s’affiche dans le tableau de bord**

*Rapports*

Lorsqu’un utilisateur affiche un rapport dans un tableau de bord, la devise utilisée dans le rapport est incorrecte. Lorsque l’utilisateur affiche le rapport en dehors du tableau de bord, la devise est correcte.

**Le filtre Terminé n’affiche pas l’élément de travail Terminé**&#x200B; s

*[!UICONTROL Page d’accueil]*

Lorsqu’un utilisateur affiche les [!UICONTROL Liste de travail à domicile] avec le [!UICONTROL Terminé] filtre les tâches sélectionnées et terminées ne s’affichent pas dans la liste. Lorsque la variable [!UICONTROL Tous] est sélectionné, les éléments terminés sont inclus dans la liste, ce qui indique que les éléments terminés existent.

**[!DNL Workfront]ne charge pas**

*[!DNL Workfront]*

Lorsqu’un utilisateur tente de se connecter [!DNL Workfront], la page semble être bloquée dans une boucle de redirections ou d’actualisations et ne se charge pas.

+++

+++**Mise à jour de maintenance le 14 avril 2022**

**Impossible d’ajouter une tâche à partir d’un rapport sur une section personnalisée d’une tâche**

*Tâches*

Lorsqu’un utilisateur consulte une section personnalisée sur une tâche et que la section contient un rapport de tâche, il ne peut pas ajouter de tâche à partir de ce rapport. Le [!UICONTROL Ajouter une tâche] surligne le rapport, mais n’ouvre pas de fenêtre permettant à l’utilisateur d’ajouter une tâche.

**Bouton Terminé au mauvais emplacement lors de la modification d’une vue**

*Vues*

Lorsqu’un utilisateur modifie une vue, la variable [!UICONTROL Terminé] s’affiche plus haut à l’écran et peut chevaucher du texte.

L’utilisateur peut modifier la vue comme d’habitude. La fonctionnalité n’est pas affectée.

**Impossible de faire défiler lors de l’utilisation de [!UICONTROL Milestone] affichage dans un rapport**

*Rapports*

Lorsqu’un utilisateur consulte un rapport et sélectionne la variable [!UICONTROL Milestone] vue, la page affiche la vue Milestone mais ne fait plus défiler et l’utilisateur ne peut pas afficher les jalons qui seraient plus bas dans la page.

**Écran vierge lors de l’affichage des mises à jour**

*Mises à jour*

Lorsqu’un utilisateur consulte les mises à jour et fait défiler l’écran pour afficher les mises à jour plus bas, l’écran devient vide et l’utilisateur ne peut pas voir les mises à jour.

**Erreur lors de l’affectation groupée d’un utilisateur à une tâche qui n’est pas affectée au rôle de l’utilisateur**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsqu’un utilisateur dans la variable [!UICONTROL Équilibreur de charge de travail] tente d’affecter des tâches à un utilisateur dont le rôle de tâche ne correspond pas au rôle de tâche affecté aux tâches. L’utilisateur voit s’afficher un message indiquant que la tâche sera affectée à l’aide du rôle de tâche Principal de l’utilisateur affecté. Cependant, lorsque l’utilisateur clique sur &quot;[!UICONTROL Attribuer],&quot; les tâches ne sont pas affectées et l’utilisateur voit l’erreur suivante :

&quot;[!UICONTROL Erreur. Le serveur a rencontré une erreur inconnue.]&quot;

+++

+++**Mise à jour de maintenance le 7 avril 2022**

**Les utilisateurs ajoutés aux bons à tirer ont des rôles incorrects**

*Épreuves*

Lorsqu’un utilisateur ajoute un autre utilisateur à un BAT, son rôle sur le BAT est défini comme &quot;[!UICONTROL Lecture seule]&quot; malgré le rôle de BAT réel de l’utilisateur.

**Impossible d’envoyer un courrier électronique de réinitialisation de mot de passe à l’utilisateur**

*Utilisateurs*

Lorsqu’un utilisateur tente d’envoyer un mot de passe réinitialisé à un autre utilisateur, il constate que la variable [!UICONTROL Envoyer un e-mail de mot de passe oublié] n’est pas disponible dans la variable [!UICONTROL Plus] .

**[!UICONTROL Mettre à jour tout] envoie des mises à jour aux profils utilisateur au lieu d’un projet ;**

*Mises à jour*

Lorsqu’un utilisateur consulte la variable [!UICONTROL Personnes] d’un projet et sélectionne la variable [!UICONTROL Mettre à jour tout] , puis saisit une mise à jour. la mise à jour n’est pas publiée sur le projet lui-même. Il est plutôt publié sur les profils utilisateur individuels de chaque utilisateur du projet.

**Trop de pages lors de l’impression de mises à jour**

*Mises à jour*

Lorsqu’un utilisateur consulte un flux de mise à jour qui serait constitué de plusieurs pages imprimées et tente d’imprimer la page, l’écran d’impression indique que le nombre de pages est bien supérieur au nombre réel de pages nécessaires à l’impression des mises à jour. Si l’utilisateur tente ensuite d’imprimer sur PDF, la création du PDF échoue.

**Les utilisateurs ne peuvent pas voir la liste complète des entités partagées avec un rapport lorsque la variable[!UICONTROL Visible à l’échelle du système]&quot; paramètre activé**

*Rapports*

Lors du partage de rapports avec plusieurs entités s’affichant dans la variable [!UICONTROL Accès aux rapports] , les utilisateurs ne peuvent pas faire défiler la liste jusqu’au bas de la liste pour afficher l’intégralité de la liste lorsque l’événement[!UICONTROL Visible à l’échelle du système]&quot; activé.

**Monnaie incorrecte utilisée dans les rapports**

*Rapports*

Si un utilisateur définit la devise d’un projet sur différente de la devise par défaut, puis affiche un rapport sur ce projet, la devise apparaît comme devise par défaut au lieu de la devise du projet.

**Les informations sur les dernières vues ne sont pas mises à jour dans [!UICONTROL Utilisation du rapport] rapports**

*Rapports*

Lorsqu’un utilisateur consulte un rapport qui affiche des informations sur la dernière fois que le rapport a été consulté, ces informations peuvent être vides ou être d’anciennes données. Ce problème affecte les champs, notamment :

* [!UICONTROL Affiché en dernier par]
* [!UICONTROL Dernières données consultées]
* [!UICONTROL X dernières visionneuses]
* [!UICONTROL Affichages ce mois / trimestre / année]

**Tâches terminées s’affichant dans [!UICONTROL Liste de travail à domicile]**

*[!UICONTROL Page d’accueil]*

Lorsqu’un utilisateur consulte le rapport [!UICONTROL Liste de travail à domicile], ils voient Tâches terminées dans la liste, même si l’option d’affichage Tâches terminées n’est pas sélectionnée.

**Bouton Planification non visible pour planifier l’actualisation de l’environnement de test**

*Environnement de test*

Le [!UICONTROL Planification] le bouton utilisé pour planifier une actualisation de l’environnement de test n’est pas visible dans la bannière supérieure de l’environnement de test.

**Les modifications apportées à un champ calculé affectent tous les champs calculés d’un formulaire.**

*Formulaires personnalisés*

Lorsqu’un utilisateur se trouve dans le créateur de formulaires personnalisés et modifie la valeur d’un formulaire calculé, tous les champs calculés du formulaire affichent la nouvelle valeur. Cela peut avoir une incidence sur les champs calculés nouveaux ou existants.

**Couleurs scintillant sur le créateur de formulaires personnalisé**

*Formulaires personnalisés*

Lorsqu’un utilisateur utilise des champs calculés sur le créateur de formulaires personnalisé, les couleurs des champs et des expressions scintillent.

**[!UICONTROL Ne peut pas refuser une validation]**

*Approbations*

Lorsqu’un utilisateur tente de refuser une approbation, la variable [!UICONTROL Rejeter] ne répond pas et la validation n’est pas rejetée.

**[!UICONTROL Projets] La section Tous les projets est définie par défaut malgré la sélection précédente.**

*Projets*

Lorsqu’un utilisateur accède à une page Projets via un onglet qui a été épinglé dans le cadre du modèle de mise en page, la page utilise par défaut la variable [!UICONTROL Tous les projets] de la navigation de gauche. Cela se produit même lorsque l’utilisateur choisit une autre zone du volet de navigation de gauche, puis quitte la page Projets et revient.

+++


## Mises à jour en mars 2022

+++**Mise à jour de la maintenance le 31 mars 2022**

**Fuseaux horaires non cohérents entre [!DNL Workfront] et[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Si le profil d’un utilisateur est défini sur un fuseau horaire spécifique dans [!DNL Workfront], le fuseau horaire de l’utilisateur dans [!DNL Workfront Proof] est défini sur un autre fuseau horaire.

**Le lien d’envoi d’un document demandé conduit à une page vierge.**

*Documents*

Lorsqu’un utilisateur reçoit une demande d’envoi de document et clique sur le lien vers l’objet dans lequel le document a été demandé, le lien mène à une page vierge. Cela peut se produire lorsque vous cliquez sur un lien dans un email ou dans une notification in-app.

**Le groupe n’est pas correctement attribué lors de la conversion d’un problème en projet**

Groupes

Lorsqu’un utilisateur convertit un problème en projet à l’aide d’un modèle, la fonctionnalité est la suivante :

* Si un groupe est affecté au modèle, ce groupe s’affiche dans la fenêtre de conversion des problèmes en tant que groupe pour le nouveau projet.
* Si aucun groupe n’est affecté au modèle, le groupe par défaut de l’utilisateur qui convertit le problème s’affiche dans la fenêtre de conversion des problèmes en tant que groupe pour le nouveau projet.
* Si le modèle ne comporte aucun groupe, le nouveau projet doit hériter du groupe du projet du problème.

**Impossible de joindre un formulaire personnalisé avec plusieurs objets à la file d’attente de demande**

Demandes

Lorsqu’un utilisateur tente d’ajouter un formulaire personnalisé contenant plusieurs objets à la page de détails d’une file d’attente, le formulaire contenant plusieurs objets n’apparaît pas dans la liste déroulante des formulaires disponibles et l’utilisateur ne peut pas le sélectionner pour l’ajouter aux détails de la file d’attente.

**Les utilisateurs ne peuvent pas se voir attribuer un rôle de tâche secondaire sur [!UICONTROL Équilibreur de charge de travail]**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsqu’un utilisateur tente d’affecter un autre utilisateur à une tâche sur l’événement [!UICONTROL Équilibreur de charge de travail]et que la tâche est affectée à un rôle de tâche autre que le rôle de tâche Principal de l’utilisateur affecté, l’utilisateur est affecté à la tâche par son rôle de tâche Principal, et le message suivant s’affiche :

&quot;\&lt;name> ne correspond pas au rôle de \&lt;task role=&quot;&quot; assignment=&quot;&quot;>. 1 élément de travail actuellement attribué au rôle &lt;\Affectation de rôle de tâche\> sera affecté à \&lt;name> dans le rôle de \&lt;primary job=&quot;&quot; role=&quot;&quot;>.&quot;

Cela se produit même si l’utilisateur possède le rôle de tâche de l’affectation de rôle Tâche comme rôle de tâche secondaire.

**Problème avec le Scrum Board &quot;Afficher plus d’éléments de travail&quot; b**&#x200B; ar

*Agile*

Lorsqu’un utilisateur clique sur la variable [!UICONTROL Afficher d’autres tâches] sur un panorama, puis faites défiler l’écran pour afficher les nouveaux éléments, la variable [!UICONTROL Afficher d’autres tâches] La barre d’outils s’accroche au panorama de défilement et se déplace avec celui-ci lorsque vous le faites défiler. Cela peut rendre les cartes difficiles à lire.

**Les points rouges apparaissent sur les champs obligatoires des formulaires personnalisés**

Formulaires personnalisés

Lorsqu’un utilisateur affiche un champ obligatoire sur un formulaire personnalisé, il voit deux points rouges sous l’astérisque qui indiquent que le champ est obligatoire.

**Menu déroulant du temps coupé en invites**

*Rapports*

Lorsqu’un utilisateur remplit les invites d’un rapport et rencontre un sélecteur de date, le sélecteur d’heure au bas du sélecteur de date n’affiche pas les heures au-delà de 2, et l’utilisateur ne peut sélectionner aucune valeur d’heure en dehors de 1 ou 2.

+++

+++**Mise à jour de maintenance (correctif) le 29 mars 2022**

**Impossible de modifier ou d’enregistrer les calculs dans le créateur de formulaires personnalisés**

*Formulaires personnalisés dans mon groupe*

Si un utilisateur saisit manuellement un calcul dans un champ de calcul du créateur de formulaires personnalisés et enregistre le formulaire, le calcul n’est pas enregistré. Si l’utilisateur ouvre à nouveau le formulaire personnalisé, ce champ est vide.

Si un utilisateur saisit un calcul dans un champ de calcul du créateur de formulaires personnalisés à l’aide des listes déroulantes et enregistre le formulaire, cette valeur est enregistrée. Cependant, si l’utilisateur rouvre le formulaire personnalisé, il ne peut pas modifier ce champ ni supprimer la valeur, manuellement ou dans la liste déroulante.

REMARQUE : Ce problème entraînait l’ajout de fonctionnalités supplémentaires. Désormais, lorsque vous commencez à saisir du texte dans un champ calculé, les expressions ou calculs possibles s’affichent dans une liste déroulante ci-dessous, de la même manière que dans l’éditeur de calcul. Cliquez sur un élément dans la liste déroulante pour l’ajouter au champ calculé.

+++

+++**Mise à jour de maintenance le 24 mars 2022**

**Fuseaux horaires non cohérents entre [!DNL Workfront] et[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Si le profil d’un utilisateur est défini sur un fuseau horaire spécifique dans [!DNL Workfront], le fuseau horaire de l’utilisateur dans [!DNL Workfront Proof] est défini sur un autre fuseau horaire.

**Erreur de champ obligatoire pour les champs personnalisés remplis lors de l’ajout d’un modèle**

*Projets*

Lors de l’association d’un modèle avec les champs personnalisés requis à un projet pour lequel le champ existe déjà et est rempli, les utilisateurs voient l’erreur suivante : &quot;[!UICONTROL Il existe des champs incomplets. Saisissez les valeurs des champs requis avant de pouvoir continuer.]&quot; Cliquer sur &quot;[!UICONTROL Emmenez-moi là-bas]&quot; leur permet de voir que les champs sont remplis et qu’ils peuvent joindre le modèle avec succès.

**Le [!UICONTROL Équilibreur de charge de travail] clignote lorsque vous basculez d’une date à l’autre**

*[!UICONTROL Équilbreur de charge de travail]*

Les heures de l’utilisateur répertoriées en premier dans la variable [!UICONTROL Équilibreur de charge de travail] ne s’affiche pas lorsque vous mettez à jour la chronologie. L’utilisateur et ses heures s’affichent avec toutes les zones grises qui clignotent. Cela se produit si vous avancez et régressez sur la chronologie.

La mise à jour du filtre semble réinitialiser l’affichage. Toutefois, si vous déplacez vers l’arrière et vers l’avant sur la chronologie, le flash d’affichage n’est plus affiché et les heures d’utilisateur ne le sont plus.

**La terminologie personnalisée est incohérente**

*Modèles de mise en page*

Les utilisateurs signalent que lorsque la variable [!DNL Workfront] Si l’administrateur personnalise la terminologie de certains objets à l’aide d’un modèle de mise en page, le nouveau nom d’objet s’affiche de manière incohérente dans l’interface.

Par exemple, sur la page [!UICONTROL Projets] , vous pouvez toujours voir le titre de la page affiché sous la forme &quot;[!UICONTROL Projets]&quot;, même si la variable [!DNL Workfront] administrator a modifié le nom de &quot;[!UICONTROL Projets]&quot; à autre chose.

Cela entraîne une confusion pour les utilisateurs finaux.

+++

+++**Mise à jour de la maintenance le 17 mars 2022**

**Les miniatures et les images principales sont vides lors de l’affichage de fichiers multi-pages à l’aide de [!DNL Safari] browser**

*[!DNL Workfront Proof]*

Lorsqu’un utilisateur tente d’afficher un fichier comportant plusieurs pages dans la variable [!DNL Safari] , les images de la page miniature sont vides. Il arrive que l’image principale soit également vide.

**Liste d’utilisateurs incorrecte lors d’affectations en bloc dans [!UICONTROL Équilibreur de charge de travail]**

*[!UICONTROL Équilbreur de charge de travail]*

Lorsqu’un utilisateur effectue une attribution en bloc dans la variable [!UICONTROL Équilibreur de charge de travail] et sélectionne un projet et un rôle de tâche. La liste des utilisateurs disponibles est incorrecte. Il peut afficher les utilisateurs sans les autorisations de rôle ou de projet, et les utilisateurs avec les autorisations de rôle et de projet n’apparaissent pas dans la liste.

**[!UICONTROL Le tri ne fonctionne pas dans les rapports]**

*Rapports*

Lorsqu’un utilisateur clique sur une colonne pour la trier, le tri semble fonctionner, mais les résultats reviennent instantanément au tri d’origine tel qu’il s’affichait avant de cliquer sur la colonne. Le tri sur n’importe quelle colonne n’est pas conservé.

**Sélectionner &quot;[!UICONTROL Rien]&quot; rétablit le [!UICONTROL Rapport par défaut] groupement**

*Rapports*

Lorsqu’un rapport comporte un groupement intégré et que l’utilisateur tente de sélectionner &quot;[!UICONTROL Rien]&quot; dans la variable [!UICONTROL Regroupement] menu déroulant, le rapport s’affiche sous peu sans aucun regroupement, puis revient au [!UICONTROL Rapport par défaut] regroupement.

**Supprimé &quot;[!UICONTROL Accès aux plans directeurs]Onglet des préférences de plan directeur**

*Plans directeurs*

REMARQUE : Ce problème existe uniquement dans l’environnement Aperçu .

Le [!UICONTROL Accès aux plans directeurs] a été supprimé de la fenêtre modale Préférences de plan directeur . Aucune fonctionnalité n’a été supprimée des préférences de plan directeur.

+++

+++**Mise à jour de maintenance (correctif) le 14 mars 2022**

**Impossible de faire défiler la liste des utilisateurs lors d’une affectation sur le panorama Kanban**

*Agile*

Lorsqu’un utilisateur affiche une [!DNL Kanban] tableau et tente d’effectuer une affectation. La liste des utilisateurs qui s’affiche lorsqu’ils tapent n’arrête pas de remonter vers le haut lorsqu’ils font défiler la page vers le bas. L’utilisateur ne peut pas sélectionner un utilisateur qui ne se trouve pas en haut de la liste et ne peut pas enregistrer la modification d’affectation.

**[!UICONTROL Milestone] L’affichage dans le rapport du projet provoque une erreur**

*Rapports*

Lors de l’affichage d’un rapport de projet à l’aide de la variable [!UICONTROL Milestone] Vue, les utilisateurs reçoivent un &quot;[!UICONTROL APIModel INTERNAL ne prend pas en charge namedQuery TILE:milestone-view (UIVW)]&quot;.

**La terminologie personnalisée est incohérente**

*Modèles de mise en page*

Les utilisateurs signalent que lorsque la variable [!DNL Workfront] Si l’administrateur personnalise la terminologie de certains objets à l’aide d’un modèle de mise en page, le nouveau nom d’objet s’affiche de manière incohérente dans l’interface.

Par exemple, sur la page [!UICONTROL Projets] , vous pouvez toujours voir le titre de la page affiché sous la forme &quot;[!UICONTROL Projets]&quot;, même si la variable [!DNL Workfront] administrator a modifié le nom de &quot;[!UICONTROL Projets]&quot; à autre chose.

Cela entraîne une confusion pour les utilisateurs finaux.

**Impossible de mettre à jour les calculs pour les champs calculés existants**

*Formulaires personnalisés*

Les utilisateurs ne peuvent pas mettre à jour/modifier les calculs dans les champs calculés. Si le champ a été créé et enregistré sans calcul, à chaque tentative d’ajout d’une expression et d’enregistrement/application, le créateur revient à la zone vierge.

Si vous créez un champ calculé avec une certaine expression et que vous l’enregistrez, chaque fois que vous essayez de modifier le calcul, il revient à sa valeur précédente.

**[!UICONTROL Paramètre non valide] erreur lors de la réinitialisation des mots de passe**

*Connexion*

Les utilisateurs ne peuvent pas réinitialiser leurs mots de passe dans aucun environnement. Lorsqu’ils saisissent leur email et tentent de poursuivre, une erreur s’affiche.

[!UICONTROL Erreur : Paramètre non valide : Valeur du paramètre de recherche &quot;domain&quot;].

+++

+++**Mise à jour de maintenance le 10 mars 2022**

**Problèmes de connexion à l’environnement de prévisualisation**

*Connexion*

Les problèmes suivants liés à la connexion à l’environnement Aperçu ont été signalés.

Lorsqu’un utilisateur tente de se connecter à l’environnement Aperçu, un message s’affiche pour l’informer qu’il a ajouté un ID ou un mot de passe incorrect.

Lorsqu’un utilisateur tente de réinitialiser son mot de passe, l’erreur &quot;[!UICONTROL ?Plusieurs utilisateurs ont été trouvés avec l&#39;adresse email <example@example.com>?]&quot;

**Les formulaires personnalisés se chargent lentement dans [!UICONTROL Détails du projet] area**

*Projets*

Lorsqu’un utilisateur tente d’afficher le rapport [!UICONTROL Détails du projet] , tous les formulaires personnalisés associés au projet ne sont chargés qu’après un délai de 15 secondes ou plus. Le [!UICONTROL Ajouter des formulaires personnalisés] est également affectée par ce délai.

**Valeurs de champ de formulaire personnalisées non enregistrées dans le panneau de résumé du document**

*Documents*

Lorsqu’un utilisateur met à jour des champs de formulaire personnalisés dans le panneau de résumé du document et qu’un ou plusieurs d’entre eux sont des champs de saisie anticipée, enregistre les modifications et quitte le panneau de résumé, les mises à jour ne sont pas enregistrées. Cela ne se produit que lorsqu’un champ de saisie anticipée est modifié, bien que tous les champs soient affectés.

**Données non conservées lors de la conversion de modèles en raison des niveaux d’accès de partage de modèles**

*Projets*

Lorsqu’un utilisateur disposant de l’accès Affichage sur un modèle partagé tente de convertir un problème en projet, toutes les données des sections de formulaire personnalisées qui nécessitent [!UICONTROL Contribution] ou un accès supérieur à la vue n’est pas transféré vers le projet créé.

**Erreur lors du téléchargement d’une nouvelle version de document**

*Documents*

Lorsqu’un utilisateur tente de charger une nouvelle version d’un document à partir de la liste de documents, le document n’est pas téléchargé et l’utilisateur voit l’erreur suivante :

[!UICONTROL Erreur Impossible d’appeler &quot;com.attask.boz.Document.getCurrentVersion()&quot; car &quot;document&quot; est nul]

**Impossible de modifier les taux de facturation**

*Projets*

Lorsqu’un utilisateur tente de modifier un taux de facturation sur la variable [!UICONTROL Taux de facturation] d’un projet, en cliquant sur l’onglet [!UICONTROL Modifier] ouvre le bouton [!UICONTROL Modifier] brièvement, mais elle se ferme avant que l’utilisateur puisse modifier le taux de facturation. Le fait de cliquer de nouveau sur le bouton n’ouvre pas la fenêtre d’édition.

**Le lien public du document mène à une page vierge.**

*Documents*

Lorsqu’un utilisateur tente d’ouvrir un document à l’aide d’un lien public, le lien mène à une page vierge. Cela se produit lorsque le lien est ouvert dans une fenêtre où une principale [!DNL Workfront] La session est ouverte.

**Ignore l’erreur lors de l’ajout d’une tâche ou d’un problème à la liste**

*Tâches et problèmes*

Lorsqu’un utilisateur qui n’est pas administrateur tente d’ajouter une tâche ou un problème à une liste et renseigne des champs personnalisés, la tâche ou le problème n’est pas créé et l’utilisateur voit l’erreur suivante :

[!UICONTROL Erreur Oups ! Un problème est survenu. Veuillez contacter [!DNL Workfront] donc nous pouvons comprendre ce qui s&#39;est mal passé et y remédier.]

**Le fait de laisser une mise à jour après une modification de l’état rétablit l’état précédent de l’objet.**

Projets, tâches et problèmes

Si vous modifiez l’état d’un projet, d’une tâche ou d’un problème, puis commencez immédiatement à saisir une mise à jour sans actualiser la page, la zone de mise à jour affiche l’état précédent. Si la mise à jour est publiée, l’objet revient au statut précédent.

**Les utilisateurs ajoutés aux bons à tirer ont des rôles incorrects**

*Épreuves*

Lorsqu’un utilisateur ajoute un autre utilisateur à un BAT, son rôle sur le BAT est défini comme &quot;[!UICONTROL Lecture seule]&quot; malgré le rôle de BAT réel de l’utilisateur.

Solution : Définissez le rôle de BAT de l’utilisateur dans son profil sur autre chose, puis réinitialisez-le au rôle approprié.

**Le formulaire personnalisé ne se charge pas lors de la conversion d’un problème en projet à l’aide d’un modèle**

*Formulaires personnalisés dans mon groupe*

Lorsqu’un utilisateur tente de convertir un problème en projet à l’aide d’un modèle, un ou plusieurs des formulaires personnalisés associés au modèle peuvent ne pas se charger. Lorsque l’utilisateur configure le modèle pour le nouveau projet, au lieu des formulaires personnalisés, le message suivant s’affiche :

&quot;[!UICONTROL Un problème s’est produit, impossible de charger le formulaire].&quot;

**L’utilisateur ne peut pas ajouter de problème en ligne avec le champ déroulant personnalisé qui s’affiche dans la vue**

*Listes*

Lorsqu’un utilisateur ajoute un problème en ligne et qu’une vue personnalisée avec des champs déroulants personnalisés est appliquée à la liste, une erreur se produit lorsqu’il remplit uniquement le champ déroulant. L’utilisateur a accès à la modification d’un formulaire personnalisé et est le propriétaire du projet avec les droits de gestion du projet.

[!UICONTROL Erreur : Oups ! Un problème est survenu. Veuillez contacter [!DNL Workfront] alors nous pouvons comprendre ce qui s&#39;est mal passé et y remédier !]

**Les autorisations d’ajout de tâches à un projet ne sont pas requises pour déplacer ou copier une tâche vers le projet.**

*Tâches*

Vous pouvez désormais déplacer ou copier une tâche vers une autre tâche d’un projet sans disposer des autorisations nécessaires pour ajouter des tâches au projet de destination. Vous devez disposer des autorisations nécessaires pour ajouter des tâches à au moins l’une des tâches du projet de destination. Avant cette mise à jour, vous deviez disposer des autorisations nécessaires pour ajouter des tâches au projet afin de déplacer ou de copier une tâche dans le projet ou dans l’une de ses tâches.  Cette mise à jour est désormais disponible dans l’environnement Production. Il a été disponible dans l’environnement Aperçu à partir de la mise à jour de maintenance du 24 mars 2022.

REMARQUE : Cette mise à jour sera disponible dans l’environnement de production lors de la copie ou du déplacement de problèmes après la version de production 22.2. Pour plus d’informations sur la version actuelle, voir workfront.com/release.

**Le menu déroulant d’invite est coupé.**

*Rapports*

Lorsque vous utilisez une invite dans un rapport, les menus déroulants qui permettent de sélectionner les critères de filtrage du rapport sont coupés. Par conséquent, les critères situés au bas du menu déroulant de sélection ne s’affichent pas.

**L’élément de travail revient au statut précédent lorsqu’une mise à jour est effectuée**

*Mises à jour*

Lorsqu’un utilisateur modifie l’état d’un élément de travail dans l’en-tête, celui-ci n’est pas mis à jour dans la variable [!UICONTROL Mettre à jour] zone. Si l’utilisateur effectue ensuite une mise à jour, la liste déroulante affiche toujours l’état précédent. Lorsque la mise à jour est enregistrée, ce statut précédent, incorrect, remplace l’état défini dans l’en-tête .

+++

+++**Mise à jour de maintenance le 3 mars 2022**

**Impossible d’ajouter le document à partir de[!DNL Google Drive]**

*Documents*

Lorsqu’un utilisateur tente d’ajouter un document à partir de [!DNL Google Drive], la sélection ne répond pas et l’utilisateur ne peut pas sélectionner les documents à ajouter.

**Les utilisateurs balisés ne sont pas ajoutés pour mettre à jour le thread**

*Mises à jour*

Lorsqu’un utilisateur est balisé dans une mise à jour, il n’apparaît pas dans le[!UICONTROL À]&quot; de la mise à jour ou de ses réponses.

**L’utilisateur BAT dispose de deux comptes de vérification distincts.**

*[!DNL Workfront Proof]*

Adresse électronique d’un utilisateur dans [!DNL Workfront Proof] peut se trouver dans deux comptes distincts avec des identifiants distincts, ce qui donne à l’utilisateur deux comptes. Cela peut rendre difficile la localisation du compte correct.

**Erreur de perte de contenu affichée dans les en-têtes de rapport**

*Rapports*

Lorsqu’un utilisateur consulte un rapport, l’erreur suivante s’affiche dans l’en-tête du rapport :

&quot;[!UICONTROL Réessayons. Oups ! Un problème est survenu. Veuillez contacter [!DNL Workfront] donc nous pouvons comprendre ce qui s&#39;est mal passé et y remédier.]&quot;

Si l’utilisateur consulte un tableau de bord, l’erreur peut s’afficher dans l’en-tête de tous les rapports du tableau de bord.

**Les données des champs d’édition uniquement de formulaire personnalisé ne sont pas conservées lors de la conversion de problèmes en projets.**

*Projets*

Lorsqu’un utilisateur non-administrateur tente de convertir un problème en projet à l’aide d’un modèle et que le problème contient des données dans des champs qui ne peuvent être modifiés que par un administrateur, les données de ces champs ne sont pas transférées vers le nouveau projet.

Lorsqu’un administrateur convertit le problème, les données sont transférées vers le nouveau projet comme prévu.

**[!DNL XLS]et [!DNL XLSX] limite de taille de fichier temporairement réduite à 100 Mo pour les bons à tirer**

*Relecture*

Pour résoudre un problème de sécurité, nous avons temporairement limité la taille maximale de fichier pour [!DNL XLS] et [!DNL XLSX] fichiers à 100 Mo lors de la création d’un BAT.

REMARQUE : Cette mise à jour a eu lieu dans l’environnement Aperçu le 24 février et sera dans l’environnement de production le 3 mars.

**Mise à jour de la recherche Workfront**

Rechercher

Un déploiement échelonné a commencé cette semaine pour mettre à jour l’infrastructure de la [!DNL Workfront] Fonction de recherche. La mise à jour rendra les améliorations futures de la recherche plus simples et plus fiables. Grâce à ces modifications, des éléments ont été ajoutés à la variable [!DNL Workfront] sera indexé plus rapidement et renverra donc les résultats de recherche plus tôt.

Le déploiement par étapes se poursuit pendant 2 semaines.

**Barres d’outils mises à jour pour les rapports dans les tableaux de bord**

Rapports

Les rapports des tableaux de bord affichent désormais une nouvelle barre d’outils. Cette barre d’outils fait partie des mises à jour apportées aux listes et aux rapports qui se produisent dans l’ensemble du [!DNL Workfront].

+++


## Mises à jour en février 2022

+++**Mise à jour de maintenance (correctif) le 24 février 2022**

**Données non conservées lors de la conversion de problèmes en projets si le champ est masqué sur le modèle**

*Projets*

Lorsqu’un utilisateur convertit un problème en modèle et que ce dernier inclut un formulaire personnalisé qui affiche ou masque des champs en fonction des valeurs d’autres champs, les données des champs masqués sur le modèle (sans données) au moment de la conversion ne sont pas transférées dans le nouveau projet.

**Impossible d’exporter le planificateur de ressources par rôle**

*Planification des ressources*

Lorsqu’un utilisateur tente d’exporter la variable [!DNL Resource Planner] lors de l’utilisation de la variable [!UICONTROL Afficher par rôle] , l&#39;export ne réussit pas et l&#39;utilisateur reçoit un email avec le message suivant :

Une erreur s’est produite lors de l’exportation de votre [!DNL Resource Planner] data.

**Le bouton Copier la requête ne fonctionne pas**

*Demandes*

Lorsqu’un utilisateur tente de copier une requête, la variable [!UICONTROL Copier la requête] ne fonctionne pas si l’utilisateur ne dispose pas de l’accès Affichage à la rubrique de la file d’attente.

+++

+++**Mise à jour de maintenance le 24 février 2022**

**Les données de formulaire personnalisées disparaissent lorsque d’autres champs de formulaire sont remplis**

*Formulaires personnalisés dans mon groupe*

Lorsqu’un utilisateur remplit un formulaire personnalisé dans le cadre de la conversion d’un problème en projet, le remplissage d’un champ personnalisé peut provoquer la disparition des données d’un autre champ personnalisé. Si l’utilisateur saisit à nouveau les données manquantes, lorsqu’il tente de créer le projet, le message d’erreur suivant s’affiche :

&quot;[!UICONTROL Vous devez être un administrateur système pour modifier cette valeur de paramètre de donnée personnalisée]&quot;

**&quot;[!UICONTROL Ce processus de validation peut être utilisé par...]Champ manquant**

*Approbations*

Lorsqu’un utilisateur crée ou modifie un processus d’approbation dans [!UICONTROL Configuration] , le[!UICONTROL Ce processus de validation peut être utilisé par...]&quot; est manquant. Cela peut se produire lors de la création d’un processus d’approbation ou de la modification d’un processus existant.

**L’administrateur système ne peut pas réaffecter les utilisateurs lors de la suppression d’un groupe.**

*Groupes*

Lorsqu’un administrateur système supprime un groupe, il aura uniquement la possibilité de réaffecter les utilisateurs de ce groupe aux groupes pour lesquels l’administrateur système est administrateur de groupe. D’autres groupes n’apparaissent pas dans la liste déroulante et l’administrateur ne peut pas les sélectionner.

**Erreur de type &quot;Whoa&quot; lors de la conversion d’un problème en projet**

*Projets*

Lorsqu’un utilisateur tente de convertir un problème en projet à l’aide d’un modèle et ajoute ou supprime des formulaires personnalisés du modèle, le problème n’est pas converti et l’utilisateur voit le message suivant :

[!UICONTROL Oups ! Un problème est survenu. Veuillez contacter [!DNL Workfront] donc nous pouvons comprendre ce qui s&#39;est mal passé et y remédier.]

**Impossible d’ouvrir le BAT ; actualisations de page**

*Épreuves*

Lorsqu’un utilisateur tente d’ouvrir un BAT, le BAT ne peut pas s’ouvrir. La page s’actualise éventuellement.

**[!DNL XLS]et [!DNL XLSX] limite de taille de fichier temporairement réduite à 100 Mo pour les bons à tirer**

*Relecture*

Pour résoudre un problème de sécurité, nous avons temporairement limité la taille maximale de fichier pour [!DNL XLS] et [!DNL XLSX] fichiers à 100 Mo lors de la création d’un BAT.

REMARQUE : Cette mise à jour sera effectuée dans l’environnement Aperçu le 24 février et dans l’environnement Production le 3 mars.

**Les autorisations d’ajout de tâches ou de problèmes à un projet ne sont pas requises pour déplacer ou copier une tâche ou un problème dans le projet.**

*Projets*

Vous pouvez désormais déplacer ou copier une tâche ou un problème vers une autre tâche d’un projet sans disposer des autorisations nécessaires pour ajouter des tâches ou des problèmes au projet de destination. Vous devez disposer des autorisations nécessaires pour ajouter des tâches ou des problèmes à au moins l’une des tâches du projet de destination. Avant cette mise à jour, vous deviez disposer des autorisations nécessaires pour ajouter des tâches ou des problèmes au projet afin de déplacer ou de copier une tâche ou un problème dans le projet ou dans l’une de ses tâches. Cette mise à jour n’est disponible que dans l’environnement Aperçu .

REMARQUE : Cette mise à jour sera disponible dans l’environnement de production lors de la gestion ou du déplacement des tâches le 10 mars. Cette mise à jour sera disponible dans l’environnement de production lors de la copie ou du déplacement de problèmes avec la version de production 22.2. Pour plus d’informations sur la version actuelle, voir workfront.com/release.

**Mise à jour de la recherche Workfront**

*Rechercher*

Un déploiement échelonné a commencé cette semaine pour mettre à jour l’infrastructure de la [!DNL Workfront] Fonction de recherche. La mise à jour rendra les améliorations futures de la recherche plus simples et plus fiables. Grâce à ces modifications, des éléments ont été ajoutés à la variable [!DNL Workfront] sera indexé plus rapidement et renverra donc les résultats de recherche plus tôt.

Le déploiement par étapes se poursuit pendant 2 semaines.

+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 18 février 2022**

**Validation du type de valeur de champ ajoutée à [!DNL Anaplan] propriétés d’éléments de liste**

*[!DNL Adobe Workfront Fusion]*

Correction d’un problème en raison duquel les utilisateurs pouvaient placer un type de données incorrect dans les champs pour les propriétés d’élément de liste. La validation du type de propriété autorise [!DNL Fusion] pour vous assurer que le type de données correct est envoyé à Anaplan, en éliminant les erreurs dues à des types de données incorrects.

+++

+++**Mise à jour de maintenance le 17 février 2022**

**Erreur lors de la suppression du prédécesseur de l’onglet Prédécesseurs**

*Tâches*

Lorsqu’un utilisateur tente de supprimer un prédécesseur de la fonction [!UICONTROL Prédécesseurs] sur une tâche, la tâche ne supprime pas et l’utilisateur voit l’erreur suivante :

[!UICONTROL Tâche avec la ou les valeurs de clé Principale &quot;&quot; introuvable]

**Erreur de page blanche lors de l’ouverture de la page des utilisateurs**

*Utilisateurs*

Lorsqu’un utilisateur tente d’ouvrir la variable [!UICONTROL Utilisateurs] , la page ne s’ouvre pas et l’utilisateur voit l’erreur suivante :

[!UICONTROL Oups ! Un problème est survenu. Veuillez contacter [!DNL Workfront] donc nous pouvons comprendre ce qui s&#39;est mal passé et y remédier.]

**Chevauchement d’éléments dans l’en-tête d’un rapport sur un tableau de bord**

*Tableaux de bord*

Lorsqu’un utilisateur affiche un rapport dans un tableau de bord, il voit que l’icône de regroupement et le libellé chevauchent les liens vers [!UICONTROL Détails] et [!UICONTROL Résumé].

**Problèmes liés à[!UICONTROL Plus]Menu &quot; pour les documents et les bons à tirer**

*Documents*

Lorsqu’un utilisateur sélectionne un document ou un BAT sur un [!DNL Workfront Classic] liste de documents, puis clique sur &quot;[!UICONTROL Plus],&quot; l’un des problèmes suivants peut leur être posé : Le bouton ne répond pas Toutes les options situées sous le bouton sont intitulées &quot;[!UICONTROL objet]&quot; et ne peuvent pas être utilisés.

**Erreur &quot;Vous devez être un administrateur système&quot; lors de la création d’un projet**

*Projets*

Lorsqu’un utilisateur qui n’est pas un administrateur tente de créer un projet et joint un formulaire personnalisé dont une section est réservée aux administrateurs, il ne peut pas créer le projet et le message d’erreur suivant s’affiche :

&quot;Vous devez être un administrateur système pour modifier cette valeur de paramètre de donnée personnalisée&quot;

**Les données de la section réservée aux administrateurs du formulaire personnalisé ne sont pas conservées lors de la conversion de problèmes en projets**

*Projets*

Lorsqu’un utilisateur convertit un problème en projet à l’aide d’un modèle comportant un formulaire personnalisé avec une section réservée aux administrateurs, aucune donnée de la section réservée aux administrateurs n’est transférée au nouveau projet. Cela se produit même si un administrateur convertit le problème.

+++

+++**Mise à jour de maintenance le 10 février 2022**

**&quot;[!UICONTROL Vous devez être un administrateur système.]&quot;erreur lors de la création d’un projet**

*Projets*

Lorsqu’un utilisateur qui n’est pas un administrateur tente de créer un projet et joint un formulaire personnalisé dont une section est réservée aux administrateurs, il ne peut pas créer le projet et le message d’erreur suivant s’affiche :

&quot;[!UICONTROL Vous devez être un administrateur système pour modifier cette valeur de paramètre de donnée personnalisée]&quot;

**Les utilisateurs qui ont été désactivés et réactivés n’apparaissent pas dans [!UICONTROL Profiler les contacts]**

*[!DNL Workfront Proof]*

Lorsqu’un utilisateur affiche sa liste de contacts dans [!DNL Workfront Proof], les utilisateurs qui ont été désactivés et réactivés n’apparaissent pas dans la liste.

**Message &quot;Une erreur s’est produite lors de la conversion d’un problème en projet à l’aide d’un modèle&quot;**

*Projets*

Lorsqu’un utilisateur qui n’est pas administrateur tente de convertir un problème en projet à l’aide d’un modèle, les champs de formulaire personnalisés visibles uniquement aux administrateurs affichent le message suivant :

&quot;[!UICONTROL Un problème s’est produit, impossible de charger le formulaire]&quot;

**Erreur &quot;Impossible de charger le contenu de la page&quot; lors de l’affichage des préférences du projet**

*Configuration*

Lorsqu’un utilisateur administrateur tente d’afficher des projets, des tâches ou des problèmes sous [!UICONTROL Préférences du projet] dans le [!UICONTROL Configuration] , la page ne se charge pas et l’utilisateur voit l’erreur suivante :

&quot;[!UICONTROL Impossible de charger le contenu de la page. Essayez d&#39;actualiser la page.]&quot;

+++

+++**Mise à jour de maintenance le 3 février 2022**

**[!UICONTROL BizContext] lors de la connexion**

*Connexion*

Lorsqu’un utilisateur tente de se connecter à [!DNL Workfront], la connexion échoue et le message suivant s’affiche :

&quot;[!UICONTROL Réessayons. Erreur de base de données : Échec de la validation BizContext !]&quot;

Cela a été signalé dans l’environnement Aperçu .

**Le flux de mise à jour du problème disparaît si le problème est en attente d’approbation**

*Mises à jour*

Lorsqu’un utilisateur clique dans la variable [!UICONTROL Nouvelle mise à jour] dans le flux de mise à jour d’un problème en attente d’approbation, l’intégralité du flux de mise à jour disparaît.

**Erreur lors du téléchargement d’une nouvelle version d’un document**

*Documents*

Lorsqu’un utilisateur tente de charger une nouvelle version d’un document, la nouvelle version ne charge pas et l’utilisateur voit l’une des erreurs suivantes :

* [!UICONTROL documentID ne peut pas être nul]
* [!UICONTROL Erreur : Paramètre non valide : valeur documentID &quot;undefined&quot;]

**Le lien public du document mène à une page vierge.**

*Documents*

Lorsqu’un utilisateur tente d’ouvrir un document à l’aide d’un lien public, le lien mène à une page vierge. Cela se produit lorsque le lien est ouvert dans une fenêtre où une principale [!DNL Workfront] La session est ouverte.

**Les contrôles de liste ne fonctionnent pas sur les rapports dans les tableaux de bord**

*Tableaux de bord*

Lorsqu’un utilisateur consulte un rapport dans un tableau de bord et tente de modifier le filtre, le regroupement ou la vue du rapport, le filtre, le regroupement ou la vue ne change pas.

**&quot;[!UICONTROL Vous devez être un administrateur système.]&quot;erreur lors de la création d’un projet**

*Projets*

Lorsqu’un utilisateur qui n’est pas un administrateur tente de créer un projet et joint un formulaire personnalisé dont une section est réservée aux administrateurs, il ne peut pas créer le projet et le message d’erreur suivant s’affiche :

&quot;[!UICONTROL Vous devez être un administrateur système pour modifier cette valeur de paramètre de donnée personnalisée]&quot;

**Données personnalisées non conservées lors de la conversion d’un problème en projet**

*Projets*

Lorsqu’un utilisateur convertit un problème en projet à l’aide d’un modèle, les données d’un formulaire personnalisé sur le problème ne sont pas transférées vers le formulaire personnalisé comparable sur le projet. Cela se produit pour les données qui se trouvent dans des champs personnalisés qui peuvent être masqués en fonction des valeurs d’autres champs personnalisés.

**Erreur lors de la conversion d’un problème en projet**

*Projets*

Lorsqu’un utilisateur tente de convertir un problème en projet, celui-ci n’est pas converti et le message d’erreur suivant s’affiche :

&quot;[!UICONTROL Une erreur inattendue s’est produite]&quot;

+++


## Mises à jour en janvier 2022

+++**Mise à jour de maintenance le 27 janvier 2022**

**Données personnalisées non conservées lors de la conversion d’un problème en projet**

*Projets*

Lorsqu’un utilisateur convertit un problème en projet à l’aide d’un modèle, les données d’un formulaire personnalisé sur le problème ne sont pas transférées vers le formulaire personnalisé comparable sur le projet. Cela se produit pour les données qui se trouvent dans des champs personnalisés qui peuvent être masqués en fonction des valeurs d’autres champs personnalisés.

**La liste des utilisateurs sur la carte agile n’est pas alphabétique**

*Agile*

Lorsqu’un utilisateur affiche la liste des utilisateurs sur un panorama agile, les utilisateurs ne sont pas affichés dans l’ordre alphabétique. Au lieu de cela, les utilisateurs qui ont le plus d’affectations sont répertoriés en premier.

**Mise à jour des liens pour copier et déplacer des problèmes**

*problèmes*

Dans l’environnement Aperçu, les liens permettant de copier et de déplacer des problèmes ont été mis à jour vers &quot;[!UICONTROL Copier vers]&quot; et &quot;[!UICONTROL Déplacer vers]&quot; à la fois sur la page de problèmes et dans une liste de problèmes.

**Ajoutez jusqu’à 45 adresses IP à votre [!DNL Workfront] liste autorisée**

*Configuration*

La limite pour les adresses IP ajoutées à votre [!DNL Workfront] La liste autorisée est passée de 30 à 45.

+++

+++**Mise à jour de maintenance le 20 janvier 2022**

**&quot;[!UICONTROL Paramètre non valide]&quot; erreur lors de la création d’un projet à partir d’un modèle**

*Projets*

Lorsqu’un utilisateur tente de créer un projet à partir d’un modèle et supprime un formulaire personnalisé du modèle lors de la création du projet, le projet n’est pas créé et l’utilisateur voit un &quot;[!UICONTROL Paramètre non valide]&quot; message d’erreur qui mentionne un champ obligatoire sur le formulaire personnalisé supprimé.

**La liste des utilisateurs ne se charge pas dans [!DNL Safari] browser**

*Utilisateurs*

Lorsqu’un utilisateur accède à la variable [!UICONTROL Utilisateurs] , l’en-tête s’affiche, mais la liste des utilisateurs ne se charge pas.

**Faire glisser des tâches dans une liste entraîne le déplacement de la tâche vers un emplacement incorrect**

*Listes*

Lorsqu’un utilisateur tente de déplacer une tâche dans une liste en la faisant glisser, la ligne bleue qui indique où la tâche sera déplacée se déplace beaucoup plus lentement que le curseur. Lorsque l’utilisateur relâche la tâche, elle se déplace à l’endroit où se trouve la ligne bleue, même si le curseur pointe vers un autre emplacement de la liste.

+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 14 janvier 2022**

**Certains champs mappés sont réinitialisés lors de la sélection de [!UICONTROL nouveau champ à mapper]**

*[!DNL Workfront Fusion]*

Lorsqu’au moins un champ de la variable [!DNL Workfront] [!UICONTROL Créer] ou [!UICONTROL Mettre à jour] Le mappage est activé pour les modules et un utilisateur sélectionne un nouveau champ à mapper, les champs précédemment mappés pour lesquels le mappage est activé perdent les valeurs de mappage.

+++

+++**Mise à jour de maintenance le 13 janvier 2022**

**Impossible d’ajouter un lien hypertexte à un commentaire dans le panneau Résumé**

*Tâches*

Lorsqu’un utilisateur fait un commentaire dans le panneau de résumé d’une tâche et tente d’ajouter un lien hypertexte au commentaire, la fenêtre de lien hypertexte s’ouvre, mais dès que l’utilisateur clique dans la fenêtre, elle se ferme et l’utilisateur ne peut pas ajouter de lien hypertexte. Si un utilisateur accède à la fenêtre par onglets, il peut saisir ou coller un lien dans le champ, mais l’hyperlien n’est pas enregistré. Dans les deux cas, la tâche est désélectionnée.

**La page Modifier l’équipe ne se ferme pas**

*Équipes*

Lorsqu’un utilisateur tente de modifier une équipe, la variable [!DNL Edit team] ne se ferme pas. L’utilisateur ne peut pas fermer la page en cliquant sur l’un des boutons, en cliquant sur le X ou en quittant la page.

**Les notifications électroniques et in-app ne sont pas envoyées**

*Notifications*

Lorsqu’un événement devant déclencher une notification se produit, la notification n’est pas envoyée. Cela peut se produire pour les notifications par e-mail ou in-app, et même si d’autres notifications sont envoyées.

**[!UICONTROL Mon travail] la liste apparaît vide**

*[!UICONTROL Mon travail]*

Lorsqu’un utilisateur affiche les [!UICONTROL Mon travail] et le modèle de mise en page de leur [!UICONTROL Mon travail] list inclut une valeur numérique, telle que [!UICONTROL Pourcentage terminé], la variable [!UICONTROL Mon travail] ne s’affiche pas.

**[!UICONTROL Pourcentage terminé] et [!UICONTROL Heures terminées] ne peut pas être modifié sur Agile Board**

*Agile*

Lorsqu’un utilisateur sélectionne[!UICONTROL Afficher d’autres tâches]&quot; sur l’Agile Board, puis tente de modifier la variable [!UICONTROL Pourcentage terminé] ou [!UICONTROL Heures terminées] sur l’une des tâches nouvellement chargées, ils ne peuvent pas modifier le pourcentage d’achèvement ou les heures de fin. Le [!UICONTROL Pourcentage terminé] est également gris, ce qui indique qu’il est inactif.

+++

+++**Mise à jour de maintenance le 6 janvier 2022**

**&quot;[!UICONTROL Paramètre non valide]&quot;erreur lors de l’association de modèles ou de formulaires personnalisés à des projets**

*Projets*

Lorsqu’un utilisateur tente de joindre un formulaire personnalisé ou un modèle à un projet existant, puis remplit les champs requis du formulaire ou du modèle personnalisé et enregistre les modifications dans le projet, les modifications ne sont pas enregistrées et l’utilisateur voit un &quot;[!UICONTROL Paramètre non valide]&quot; en haut de la page des détails du projet.

**Les commentaires de BAT ne s’affichent pas dans les mises à jour du document.**

*Épreuves*

Lorsqu’un utilisateur affiche un BAT dans la variable [!UICONTROL Documents] , les commentaires effectués sur le BAT lui-même ne s’affichent pas dans la variable [!UICONTROL mises à jour] du document.

**[!UICONTROL Équilbreur de charge de travail]: &quot;[!UICONTROL ?[objet]?]&quot; s’affiche dans les informations de surallocation.**

*[!UICONTROL Équilbreur de charge de travail]*

Si un utilisateur affiche la valeur surallouée dans la variable [!UICONTROL Équilibreur de charge de travail] en raison d’une tâche qui chevauche le temps de pause de l’utilisateur, et qu’un autre utilisateur voit sa surallocation, le[!UICONTROL Capacité]&quot;la zone des informations de suraffectation affiche &quot;[!UICONTROL ?[objet]?]&quot; plutôt que la capacité réelle de l’utilisateur.

+++

## Mises à jour de maintenance précédentes

Des informations relatives aux mises à jour de maintenance précédentes sont disponibles ici :

* [[!DNL Workfront] Archive des mises à jour de maintenance - 2021](2021-updates.md)
