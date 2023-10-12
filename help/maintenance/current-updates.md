---
title: Mises à jour de maintenance pour Workfront
description: Mises à jour de maintenance pour  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: e15a384697a60f4f6b909ebb44749cf554e6f9c4
workflow-type: tm+mt
source-wordcount: '6083'
ht-degree: 95%

---

# Mises à jour de maintenance pour [!DNL Workfront]

Les mises à jour de maintenance suivantes ont été effectuées en 2023.

>[!NOTE]
>
>Ces mises à jour incluent également d’autres correctifs mineurs ou moins conséquents. L’assistance [!DNL Workfront] vous avertira lorsqu’un problème que vous avez soumis est résolu.

Pour connaître les mises à jour de maintenance antérieures à 2023, consultez les [Mises à jour de maintenance précédentes](#previous-maintenance-updates).

## Mises à jour d’octobre 2023

+++**Mise à jour de maintenance le 12 octobre 2023**

**Workflows supprimés pour les comptes qui ne les utilisent pas**

_Panoramas_

Pour les comptes qui n’ont jamais créé de workflow dans l’application Panoramas, la zone Flux de travail a été supprimée du tableau de bord Panoramas. Les comptes qui utilisent des workflows y ont toujours accès.

**Les champs calculés ne conservent pas de valeur lorsque le problème est converti en tâche**

_Formulaires personnalisés_

Les champs calculés qui se référencent ne conservent pas leurs valeurs lorsqu’un problème est converti en tâche.

Lors de la conversion du problème en tâche, la valeur souhaitée s’affiche correctement dans la fenêtre d’édition. Cependant, une fois la conversion terminée, le champ calculé affiche un &quot;S/O&quot;.

**Erreur lors du changement de filtres dans [!UICONTROL Accueil]**

_Accueil_

Lorsqu’un utilisateur modifie les filtres sur [!UICONTROL Accueil], la variable [!UICONTROL Accueil] ne se charge pas et l’utilisateur voit l’erreur suivante :

« [!UICONTROL Une erreur s’est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d’actualiser cette page de navigateur.] »

+++

+++**Mise à jour de maintenance le 5 octobre 2023**

**Le chargement des panoramas se charge lentement**

_Panoramas_

Lorsqu’un utilisateur charge un panorama, celui-ci se charge extrêmement lentement. Cela peut se produire même si le panorama comporte un petit nombre de cartes.

Les cartes archivées, même si elles ne s’affichaient pas, affectaient le temps de chargement du panorama.

**Impossible de déplacer les cartes entre les colonnes**

_Panoramas_

Lorsqu’un utilisateur tente de déplacer une carte sur un panorama, celle-ci ne se déplace pas. Cela se produit dans les cas suivants :

* Glisser-déposer
* Option Déplacer sur la carte
* Modification de la carte

**Impossible de déplacer les cartes hors de la colonne d’ingestion**

_Panoramas_

L’utilisateur peut faire glisser une carte de la colonne d’entrée vers une autre colonne du panorama, mais les cartes suivantes ne peuvent pas être déplacées hors de la colonne d’entrée.

**Regrouper par affecte les performances du panorama**

_Panoramas_

Lorsque l’utilisateur tente de regrouper les cartes par des personnes désignées ou des balises, les performances du panorama sont très lentes.

**Les emails de rappel automatique ne sont pas envoyés**

_Notifications_

Les rappels automatiques par email ne sont pas envoyés. Cela a commencé le 14 septembre 2023.

+++

## Mises à jour de septembre 2023

+++**Mise à jour de maintenance le 28 septembre 2023**

**Impossible de supprimer le champ personnalisé**

_Formulaires personnalisés_

Lorsqu’une personne tente de supprimer un champ personnalisé, elle ne peut pas le supprimer et le message « [!UICONTROL Erreur de base de données en raison d’une violation de contrainte] » s’affiche.

**Les commentaires effectués dans une nouvelle expérience de commentaire ne sont pas visibles dans l’expérience héritée**

_Mises à jour_

Lorsqu’une personne fait un commentaire dans la nouvelle expérience de commentaire et que ce commentaire s’affiche dans la zone Commentaires de la nouvelle expérience, il se peut que le même commentaire ne s’affiche pas dans l’expérience de commentaire héritée. Cela peut entraîner l’absence de commentaires des personnes qui utilisent l’expérience héritée.

**Des éléments sont manquants sur la page Objet**

_Workfront_

Lorsqu’une personne accède à une section personnalisée d’un objet dans [!DNL Workfront], certains éléments peuvent manquer sur la page qui se charge. Ces éléments peuvent inclure :

* Le panneau de navigation de gauche
* Le nom de l’objet auquel la section personnalisée appartient
* Les champs et informations de l’en-tête

+++

+++**Mise à jour de maintenance le 21 septembre 2023**

**Impossible d’affecter une personne à un panorama sur un flux de travail**

_Panoramas_

Lorsqu’une personne tente d’affecter une autre personne à une tâche à partir d’un panorama qui fait partie d’un flux de travail en commençant à saisir son nom, cette dernière n’apparaît pas dans la liste déroulante des personnes disponibles. Cela se produit même lorsque la personne est active et est membre du panorama et du flux de travail.

La personne peut également remarquer que les personnes désactivées apparaissent dans la liste déroulante.

**Impossible de supprimer l’élément de liste de contrôle**

_Panoramas_

Lorsqu’une personne tente de supprimer un élément de liste de contrôle d’une carte sur un panorama, le bouton [!UICONTROL Supprimer] ne répond pas et l’élément n’est pas supprimé.

**Les formulaires personnalisés se chargent lentement**

_Formulaires personnalisés_

Lorsqu’une personne tente de charger un formulaire personnalisé, celui-ci se charge lentement.

**Impossible de déplacer le document vers un autre dossier**

_Documents_

Lorsqu’une personne déplace un document vers un autre dossier d’objets, l’opération est impossible.

**Erreur XML lors du téléchargement**

_Documents_

Lorsqu’une personne tente de télécharger un document, celui-ci ne se télécharge pas et une page s’affiche avec ce message suivi d’un texte XML.

« [!UICONTROL Le fichier XML ne semble pas être associé à des informations de style. L’arborescence du document se trouve ci-dessous.] »

**Impossible de télécharger des documents à partir des environnements Aperçu/Sandbox**

_Documents_

Lorsqu’une personne tente de télécharger un document à partir d’un environnement autre que la production, le document ne se télécharge pas et la personne voit l’erreur suivante :

« [!UICONTROL Oups ! Un problème est survenu. Contactez Workfront pour nous aider à comprendre l’erreur et y remédier.] »

**Les BAT apparaissent dénaturés ou recadrés**

_BAT_

Les problèmes suivants ont été signalés lors de la création d’un BAT à partir d’une URL.

* Le BAT semble désaturé ou délavé.
* Le BAT est recadré.

Cela peut rendre les décisions relatives aux BAT difficiles à prendre, car le BAT n’est pas représenté avec précision.

**La génération des BAT prend un temps excessif**

_BAT_

Lorsqu’une personne tente de générer un BAT, la génération prend un temps excessif. La génération des BAT peut prendre plusieurs jours.

+++

+++**Mise à jour de maintenance le 14 septembre 2023**

**Erreur « [!UICONTROL Aucune usine] » lors de l’ajout d’un document**

_Documents_

Lorsqu’une personne tente d’ajouter un document provenant d’une source externe, [!DNL Workfront] ne peut pas accéder à la source et la personne voit l’erreur suivante :

« [!UICONTROL L’erreur suivante s’est produite : aucune usine trouvée pour le type d’authentification null] »

**Erreur « Oups » sur les rapports de matrice**

_Rapports_

Lorsqu’une personne tente d’afficher un rapport de matrice, celui-ci ne se charge pas et le message d’erreur suivant apparaît :

« [!UICONTROL Oups ! Un problème est survenu. Contactez Workfront pour nous aider à comprendre l’erreur et y remédier.] »

Cela se produit lors du regroupement d’un rapport par périodes.

+++

+++**Mise à jour de maintenance le 11 septembre 2023**

**Les tâches personnelles ne s’affichent pas dans les feuilles de temps**

_Feuilles de temps_

Les tâches personnelles ne s’affichent plus par défaut sur la feuille de temps. Les tâches personnelles s’affichent sur la feuille de temps lorsqu’elles sont épinglées ou qu’elles comportent des heures consignées. Avant cette modification, les tâches personnelles s’affichaient par défaut sur les feuilles de temps.

+++

+++**Mise à jour de maintenance le 7 septembre 2023**

**Le projet est vide lorsqu’il est chargé à partir de la nouvelle expérience [!UICONTROL Accueil]**

_Projets_

Lorsqu’une personne clique sur un projet à partir de sa page [!UICONTROL Accueil] dans la nouvelle expérience d’accueil, le chargement de la page du projet échoue.

Cela se produit lorsque la personne s’est connectée en tant qu’autre utilisateur/utilisatrice, puis s’est déconnectée en tant qu’autre utilisateur/utilisatrice et est revenue à sa propre page [!UICONTROL Accueil].

+++

## Mises à jour d’août 2023

+++**Mise à jour de maintenance le 31 août 2023**

**Les filtres ne s’appliquent pas aux widgets dans la nouvelle expérience [!UICONTROL Accueil]**

_[!UICONTROL Accueil]_

Lorsqu’une personne applique un filtre à un widget dans la nouvelle expérience [!UICONTROL Accueil], le widget affiche les éléments qui doivent être exclus par le filtre.

Ce problème a été signalé dans l’environnement de sandbox personnalisé. Les mêmes widgets dans les environnements de prévisualisation et de production filtrent comme prévu.

**Erreurs lors du chargement des rapports de matrice**

_Rapports_

Lorsqu’une personne tente de charger un rapport de matrice en tant que graphique, l’un des événements suivants peut se produire :

* Certaines informations du rapport ne se chargent pas
* Le rapport renvoie l’erreur « [!UICONTROL Impossible de charger le contenu depuis le serveur] »

**Le planificateur ne se charge pas lorsque le filtre est appliqué**

_[!UICONTROL Planificateur de ressources]_

Lorsqu’une personne tente de charger le [!UICONTROL planificateur de ressources], celui-ci ne se charge pas et un message d’erreur s’affiche :

« [!UICONTROL L’erreur suivante s’est produite : un problème s’est produit lors de la connexion au service WorkPerDay] »

+++

+++**Mise à jour de maintenance le 24 août 2023**

**Impossible de sélectionner du texte dans des listes ou des puces**

_BAT_

Lorsqu’une personne consulte un BAT dans le lecteur de vérification et tente de sélectionner du texte qui se trouve dans une liste ou une puce, l’outil de sélection de texte est inefficace et le texte ne peut pas être sélectionné.

**La création d’une nouvelle version du BAT supprime toutes les versions du BAT**

_BAT_

Lorsqu’une personne crée un BAT à partir d’un document, le BAT est créé. Cependant, si une personne crée une autre version du BAT, les anciennes et nouvelles versions sont supprimées. Il existe une option [!UICONTROL Créer un BAT] sur le document d’origine. Les versions du BAT se trouvent dans la zone [!UICONTROL Corbeille] de la zone [!UICONTROL Relecture], dans [!DNL Workfront].

+++

+++**Mise à jour de maintenance le 17 août 2023**

**Impossible d’accéder au projet avec une URL qui utilise l’[!UICONTROL ID de référence]**

_Projets_

Lorsqu’une personne tente d’accéder à un projet à l’aide d’une URL qui inclut un numéro d’[!UICONTROL ID de référence], elle est redirigée vers une page contenant un message d’erreur. La navigation vers une tâche à l’aide d’un URI contenant un [!UICONTROL ID de référence] fonctionne comme prévu. »

**« Le paramètre [!UICONTROL Désactiver les notifications par e-mail du BAT] » s’affiche de manière incorrecte**

_BAT_

Lorsqu’une personne consulte les paramètres du BAT dans [!DNL Workfront], la case à cocher [!UICONTROL Désactiver les notifications par e-mail du BAT] n’affiche pas correctement le paramètre actuel. Lorsque la case est cochée, indiquant que les notifications par e-mail sont désactivées pour le BAT, les notifications sont en fait activées. Le contraire est également vrai.

**Impossible d’ajuster les annotations du BAT**

_BAT_

Lorsqu’une personne fait un commentaire dans le lecteur de vérification, ajoute une annotation au BAT, puis clique à l’extérieur, elle ne peut plus ajuster l’annotation.

+++

+++**Mise à jour de maintenance le 10 août 2023**

**Impossible de supprimer l’élément [!UICONTROL Tâches] dans la nouvelle expérience [!UICONTROL Accueil]**

_Page d’accueil_

Lorsqu’une personne accède à la nouvelle expérience [!UICONTROL Accueil] et tente de supprimer un élément du widget [!UICONTROL Tâches], l’élément ne se supprime pas et affiche l’erreur suivante :

« [!UICONTROL Un problème est survenu lors de la suppression de votre liste de tâches, veuillez réessayer ultérieurement.] »

Cette situation peut se produire lorsqu’il existe des heures consignées dans l’élément [!UICONTROL Tâches].

**Le projet épinglé n’affiche pas les informations de certaines colonnes**

_Projets_

Lorsqu’une personne accède à un projet épinglé à l’aide de l’épingle, les listes d’objets (comme la liste des tâches) peuvent afficher des colonnes vides. Par exemple, une colonne [!UICONTROL Affectations] peut n’afficher aucune affectation, même si des affectations ont été effectuées.

**Module de veille provoquant le blocage de scénarios**

_[!DNL Workfront Fusion]_

Dans un scénario, le module [!UICONTROL Outils] > [!UICONTROL Veille] peut entraîner le blocage de l’exécution d’un scénario. Ces exécutions indiquent le statut En cours dans l’[!UICONTROL historique du scénario] et ne se terminent pas.

+++

+++**Mise à jour de maintenance le 3 août 2023**

**Difficulté à localiser les éléments dans la colonne d’entrée**

_Panoramas_

La colonne d’entrée d’un panorama était triée par ordre de priorité défini sur les tâches et les problèmes, ce qui rendait difficile la localisation d’éléments spécifiques.

L’ordre par défaut est désormais le suivant :

Tâches :

* Ordre principal : nom du projet
* Ordre secondaire : structure de répartition du travail

Problèmes

* Ordre principal : nom du projet
* Ordre secondaire : numéro de référence

**Le projet ne résout pas correctement le problème**

_Projets/Problèmes_

Lorsqu’une personne change le statut d’un projet qui est l’objet de résolution d’un problème, le statut du problème est remplacé par un statut qui ne correspond pas à la même clé que le statut du projet.

**Erreur « Oups » sur les rapports de matrice**

_Rapports_

Lorsqu’une personne tente d’afficher un rapport de matrice, celui-ci ne se charge pas et le message d’erreur suivant apparaît :

« [!UICONTROL Oups ! Un problème est survenu. Contactez Workfront pour nous aider à comprendre l’erreur et y remédier.] »

Ceci a été signalé aux utilisateurs et utilisatrices des zones EMEA.

+++

## Mises à jour de juillet 2023

+++**Mise à jour de maintenance le 27 juillet 2023**

**Les balises et les éléments de liste de contrôle ne fonctionnaient pas correctement dans l’affichage du panorama des projets**

_Panoramas_

Les balises et les éléments de liste de contrôle ont été supprimés du panorama des projets, car ils ne font pas partie des tâches de Workfront et ne peuvent pas être partagés entre les utilisateurs et utilisatrices.

**« [!UICONTROL Activer à l’échelle du système] » et « [!UICONTROL Afficher à l’échelle du système] » constituent des fonctionnalités différentes**

_Filtres_

Si une personne partage un filtre et active l’option « [!UICONTROL Afficher à l’échelle du système] », le filtre est partagé avec chaque personne qui utilise le système. Cependant, si l’administration consulte ensuite ce filtre dans la [!UICONTROL Configuration], ce dernier affiche « [!UICONTROL false] » dans la colonne « [!UICONTROL Visible à l’échelle du système] ». Pour que ce filtre devienne la valeur système par défaut, l’administration doit activer l’option « [!UICONTROL Activer à l’échelle du système] » dans la [!UICONTROL Configuration]. Cela peut prêter à confusion en raison de la formulation similaire.

+++

+++**Mise à jour de maintenance le 20 juillet 2023**

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance [!DNL Workfront] vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mise à jour de maintenance le 13 juillet 2023**

**Le journal n’est pas recalculé**

_Projets/Tâches/Problèmes_

Lorsqu’un événement se produit qui doit déclencher un calcul du journal, celui-ci n’est pas recalculé. Ceci affecte les nouveaux calculs effectués lors des modifications et les nouveaux calculs planifiés. La précision de l’équilibreur de charge de travail peut également être affectée.

**Les validations de BAT verrouillés apparaissent toujours dans la liste de travail**

_BAT_

Les validations de BAT qui sont arrivées à expiration et qui sont verrouillées apparaissent toujours sur la liste de travail de l’accueil de l’approbateur ou de l’approbatrice, au lieu de disparaître de la liste lorsque la date limite est passée.

**Le rapport d’utilisation ne se charge pas**

_Rapports_

Lorsqu’un client ou une cliente tente d’afficher un rapport d’utilisation, il ou elle voit un indicateur de chargement en rotation, mais le rapport ne se charge pas. Le rapport a renvoyé une erreur 500, mais la personne ne voit aucune indication que le rapport a rencontré une erreur.

**La page Modifier l’utilisateur est vide**

<!--no article-->

_Utilisateurs et utilisatrices_

Lorsqu’une personne tente de modifier un autre utilisateur ou une autre utilisatrice, la page Modifier l’utilisateur est vide et rend la modification impossible.

+++

## Mises à jour de juin 2023

+++**Mise à jour de maintenance le 29 juin 2023**

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance [!DNL Workfront] vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mise à jour de maintenance le 22 juin 2023**

**Erreur [!UICONTROL « Oups ! »] lors de l’affichage du rapport de matrice**

_Rapports_

Lorsqu’une personne consulte un rapport de matrice, l’erreur suivante s’affiche :

« [!UICONTROL Oups ! Un problème est survenu. Contactez Workfront pour nous aider à comprendre l’erreur et y remédier.] »

Cela a été signalé lorsque le rapport est trié par date et que l’option « [!UICONTROL Afficher les semaines sans résultats] » est activée.

**Les dates ne s’affichent pas correctement dans les rapports de matrice**

_Rapports_

Lorsqu’un graphique ou rapport de matrice est regroupé par date, les dates proches des bords du regroupement peuvent apparaître dans le bon regroupement, dans le regroupement précédent/suivant ou dans les deux.

+++

+++**Mise à jour de maintenance le 15 juin 2023**

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance [!DNL Workfront] vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mise à jour de maintenance le 8 juin 2023**

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance [!DNL Workfront] vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++Mise à jour de maintenance d’**[!DNL Adobe Workfront Fusion]le 8 juin 2023**

[!DNL Fusion] a déployé un correctif qui empêche la suppression des connexions d’une personne lorsque celle-ci est supprimée ou désactivée dans [!UICONTROL Adobe Admin Console].

Les administrateurs et administratrices d’équipe [!DNL Fusion] peuvent toujours supprimer les connexions inutiles de la page [!UICONTROL Connexions] dans [!DNL Fusion].

+++

+++**Mise à jour de maintenance le 1 juin 2023**

**Aucun message d’erreur lors de la réorganisation de la tâche au** statut [!UICONTROL En attente d’approbation].

_Tâches_

Lorsqu’une personne tente de réorganiser une tâche dans une liste de tâches, et que la tâche a le statut [!UICONTROL En attente de validation], elle semble se déplacer dans la liste des tâches. Lors de l’actualisation, la personne voit que l’élément n’a pas été déplacé. L’élément ne peut pas être déplacé, car il se trouve au statut [!UICONTROL En attente de validation], mais aucun message n’indique à la personne que l’élément ne peut pas être déplacé, ce qui peut entraîner une confusion.

**Aucun message d’erreur lors du déplacement d’une tâche de prédécesseur sous une tâche dépendante**

_Tâches_

Lorsqu’une personne tente de réorganiser une tâche dans une liste de tâches, et que la tâche a le statut [!UICONTROL En attente de validation], elle semble se déplacer dans la liste des tâches. Lors de l’actualisation, la personne voit que l’élément n’a pas été déplacé. L’élément ne peut pas être déplacé, car une tâche de prédécesseur ne peut pas être déplacée sous une tâche dont elle est le prédécesseur, mais aucun message n’indique à l’utilisateur ou à l’utilisatrice que l’élément ne peut pas être déplacé, ce qui peut prêter à confusion.

+++

## Mises à jour de mai 2023

+++**Mise à jour de maintenance le 25 mai 2023**

Le panorama **[!UICONTROL Kanban] devient vide lors de la modification de cartes.**

_Agile_

Lorsqu’un utilisateur ou une utilisatrice apporte une modification à une carte sur le panorama [!UICONTROL Kanban], le panorama [!UICONTROL Kanban] devient vide au lieu d’être actualisé avec la modification. Si l’utilisateur ou l’utilisatrice actualise manuellement la page, le panorama [!UICONTROL Kanban] réapparaît, indiquant la modification correcte.

Les situations suivantes sont concernées :

* Modification d’une carte
* Déplacement d’une carte


+++

+++**Mise à jour de maintenance le 22 mai 2023**

**Impossible d’ajuster la taille du texte descriptif**

_Formulaires personnalisés_

Lorsque le créateur de formulaire personnalisé a été publié en version Beta, la fonctionnalité permettant d’ajuster la taille du texte descriptif n’était pas disponible. Ce problème a été corrigé et les utilisateurs et utilisatrices peuvent désormais ajuster la taille du texte descriptif.

+++

+++**Mise à jour de maintenance le 18 mai 2023**

**Le rapport n’est pas trié correctement lors du tri par champ personnalisé**

_Rapports_
Lorsqu’un utilisateur ou une utilisatrice exécute un rapport de tâche, le tri du rapport semble correct lors du chargement du rapport, mais une fois celui-ci terminé, la personne constate que le tri du rapport n’est pas correct.

Cela semble se produire si toutes les conditions suivantes sont réunies :

* le rapport est un rapport de tâches
* les rapports sont triés en fonction d’un champ personnalisé
* un groupement est appliqué au rapport

+++

+++**Mise à jour de maintenance le 11 mai 2023**

**Impossible de changer de version de BAT lors de sa visualisation**

_BAT_

Lorsqu’un utilisateur ou une utilisatrice consulte un BAT dans le [!UICONTROL Lecteur de vérification] et passe à une autre version, la liste déroulante des versions est désactivée et il est impossible de revenir à la version originale que la personne visualisait ou à une autre version du BAT.

La recherche **[!DNL Workfront]expire**

_Rechercher_

La recherche [!DNL Workfront] expire. La recherche peut renvoyer quelques résultats ou aucun.

Ce problème affecte également les fonctionnalités du module [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Recherche].

+++

+++Mise à jour de maintenance d’**[!DNL Adobe Workfront Fusion]le 11 mai 2023**

**Erreurs de délai d’expiration dans[!DNL Workfront Fusion]**

_Adobe Workfront Fusion_

Lorsqu’un scénario est en cours d’exécution, une erreur de délai d’expiration peut survenir. Les informations du module concerné par l’erreur n’atteignent pas leur destination.

La recherche **[!DNL Workfront]expire**

_Rechercher_

La recherche [!DNL Workfront] expire. La recherche peut renvoyer quelques résultats ou aucun.

Ce problème affecte également les fonctionnalités du module [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Recherche].

+++

+++**Mise à jour de maintenance le 9 mai 2023**

**Filtres enregistrés disponibles dans la colonne d’entrée du panorama**

_Panoramas_

Vous pouvez désormais utiliser les filtres de tâches et de problèmes existants de Workfront lors de la configuration de la colonne d’entrée d’un panorama. Toutefois, les filtres de colonnes d’entrée existants sont maintenant en lecture seule dans le panneau de configuration. Les filtres existants sont toujours appliqués à la colonne d’entrée, mais vous devez recréer les filtres si vous souhaitez les modifier.

+++

+++**Mise à jour de maintenance le 4 mai 2023**

**Impossible de sélectionner un modèle à partir des [!UICONTROL Modèles favoris]**

_Modèles_

Lorsqu’un utilisateur ou une utilisatrice tente de sélectionner un modèle dans le menu Actions (icône des trois points de suspension), la liste des modèles disparaît lors du déplacement de la souris vers la liste et il est imposible de sélectionner un modèle. Le problème est dû au fait que la barre de défilement se situe entre le menu et la liste des modèles : lors du déplacement de la souris vers la liste des modèles, le curseur agit sur la barre de défilement.

+++

## Mises à jour d’avril 2023

+++**Mise à jour de maintenance le 27 avril 2023**

**Impossible de changer de BAT dans la [!UICONTROL visionneuse de BAT]**

_BAT_

Lorsqu’un utilisateur ou une utilisatrice consulte un BAT dans le [!UICONTROL lecteur de vérification] et passe à un autre BAT, le bouton de changement de BAT ne répond plus. Il est impossible de revenir au BAT précédemment consulté ou à un autre BAT.

**Modifier les images jointes lors de la modification d’un commentaire**

_Mises à jour_

Vous pouvez désormais modifier l’image jointe à un commentaire lorsque vous modifiez ce dernier. Cette fonctionnalité est disponible dans la section Mises à jour pour les objectifs et les problèmes éventuels de Workfront lors de l’activation de l’expérience Beta des commentaires.

+++

+++Mise à jour de maintenance d’**[!DNL Adobe Workfront Fusion]le 25 avril 2023**

Les liens d’aide in-app de **[!DNL Fusion]ne mènent pas à des pages d’aide spécifiques**.

_[!DNL Workfront Fusion]_

Lorsqu’un utilisateur ou une utilisatrice consulte un BAT dans le [!UICONTROL lecteur de vérification] et passe à un autre BAT, le bouton de changement de BAT ne répond plus. Il est impossible de revenir au BAT précédemment consulté ou à un autre BAT.

+++

+++**Mise à jour de maintenance le 20 avril 2023**

**Problèmes liés aux champs de liste déroulante personnalisés**

_Formulaires personnalisés_

Les champs déroulants personnalisés activés en tant que champs à sélection multiple peuvent connaître les problèmes suivants :

* Le bouton « +[!UICONTROL Ajouter] » est absent lorsque le formulaire n’est pas en mode de modification.
* Les champs qui ne contiennent pas de valeur affichent l’option « --[!UICONTROL aucun libellé]-- ».

**Impossible d’utiliser l’outil Polyligne lors de l’ajout d’un commentaire sur un BAT**

_BAT_

Lorsqu’un utilisateur ou utilisatrice consulte un BAT dans le lecteur de vérification et tente d’ajouter un commentaire à l’aide de l’outil Polyligne, aucun commentaire n’est apporté au BAT.

**La zone Options de texte affiche « textAnnotations »**

_BAT_

Lorsqu’un utilisateur ou une utilisatrice consulte un BAT et souhaite apporter un commentaire, la personne ouvre l’outil Texte et le mot « textAnnotation » s’affiche en regard des options de l’outil. L’outil Texte fonctionne toujours normalement et « textAnnotation » disparaît après la publication du commentaire.

**Conserver les images sous format brouillon lors de l’abandon d’une mise à jour pour les objectifs et les problèmes liés à l’expérience bêta de commentaires**

>[!NOTE]
>
>Un aperçu de cette fonctionnalité a été présenté le 19 avril 2023 qui a été mise en production le 20 avril 2023.

_Mises à jour_

Désormais, lorsque vous quittez la page Mises à jour alors que vous composez un message auquel vous avez joint une image, le message et l’image sont conservés lorsque vous revenez en arrière. Avant cette mise à jour, le commentaire non envoyé était conservé, mais l’image était supprimée. Cette fonctionnalité est disponible dans la section Mises à jour pour les objectifs et les problèmes éventuels lors de l’activation de l’expérience bêta de commentaires.

**Mises à jour en temps réel et commentaires supprimés dans la section Mises à jour**

>[!NOTE]
>
>Un aperçu de cette fonctionnalité a été présenté le 19 avril 2023, laquelle a été mise en production le 20 avril 2023.

_Mises à jour_

Désormais, lorsqu’une personne publie un commentaire ou une réponse, ou supprime un commentaire de la zone Mises à jour, le nouveau commentaire ou une indication que le commentaire a été supprimé s’affiche en temps réel, sans délai. Cette fonctionnalité est disponible dans la section Mises à jour pour les objectifs et les problèmes éventuels lors de l’activation de l’expérience bêta de commentaires.

**Modification du niveau d’accès par le système sans enregistrement de la modification**

_Utilisateurs et utilisatrices_

Le système peut modifier le niveau d’accès d’un utilisateur ou d’une utilisatrice de manière imprévisible. Dans ce cas, aucune mise à jour n’est visible et la modification n’apparaît pas dans le journal d’audit.

+++

+++**Mise à jour de maintenance le 17 avril 2023**

**Afficher les nouveaux commentaires en dehors de la zone d’écran visible dans la section [!UICONTROL Mises à jour] des problèmes (nouvelle expérience de commentaires bêta) et [!UICONTROL Objectifs]**

_Mises à jour_

Nous avons ajouté une bannière de notification pour la section [!UICONTROL Mises à jour] afin d’informer les utilisateurs et utilisatrices de la publication de commentaires sur un élément, au cas où ceux-ci se trouveraient en dehors de la zone visible à l’écran. Cette mise à jour est actuellement disponible dans la section [!UICONTROL Mises à jour] pour les objectifs et les problèmes éventuels lorsque la nouvelle expérience bêta de commentaires a été activée pour résoudre les problèmes.

+++

+++**Mise à jour de maintenance le 13 avril 2023**

**Les filtres ne sont pas appliqués à la liste des demandes**

_Demandes_

Lorsqu’un utilisateur ou une utilisatrice affiche une liste de demandes qui comporte un filtre, celle-ci inclut les demandes que le filtre doit exclure.

**Impossible de sélectionner un [!UICONTROL Type d’heure par défaut] ou un [!UICONTROL Type d’heure disponible]**

_Utilisateurs et utilisatrices_

Lorsque l’administration modifie un utilisateur ou une utilisatrice et tente de sélectionner un [!UICONTROL Type d’heure par défaut] ou un [!UICONTROL Type d’heure disponible], les listes déroulantes de ces champs sont désactivées et le type d’heure ne peut pas être sélectionné.

+++

+++**Mise à jour de maintenance le 6 avril 2023**

**Les menus déroulants ne s’ouvrent pas lorsqu’un utilisateur ou une utilisatrice est ajouté à un BAT**

_BAT_

Lorsqu’un utilisateur ou une utilisatrice ajoute un autre utilisateur ou utilisatrice à un BAT dans le [!UICONTROL Lecteur de vérification], les menus déroulants « [!UICONTROL Rôle du BAT] » et « [!UICONTROL Alertes par e-mail] » ne s’ouvrent pas. L’utilisateur ou l’utilisatrice ne peut pas attribuer un rôle de BAT ou une alerte par e-mail. Cela peut se produire lors de l’ajout d’un utilisateur ou d’une utilisatrice par le biais d’un commentaire ou du partage du BAT avec l’utilisateur ou l’utilisatrice.

+++

## Mises à jour de mars 2023

+++**Mise à jour de maintenance le 30 mars 2023**

**Impossible de changer de version de BAT lors de sa visualisation**

_BAT_

Lorsqu’un utilisateur ou une utilisatrice consulte un BAT dans le [!UICONTROL Lecteur de vérification] et passe à une autre version, la liste déroulante des versions est désactivée et il est impossible de revenir à la version originale que la personne visualisait ou à une autre version du BAT.

**Erreur 504 lors de l’export des rapports**

_Rapports_

Lorsqu’un utilisateur ou une utilisatrice tente d’exporter un rapport contenant un grand nombre d’éléments, une erreur 504 s’affiche et il est impossible d’exporter le rapport.

**La mise à jour effectuée au nom d’un utilisateur ou d’une utilisatrice s’affiche comme provenant directement de l’utilisateur ou de l’utilisatrice**

_Mises à jour_

Lorsqu’une personne de l’administration est connectée en tant qu’utilisateur ou utilisatrice et qu’elle apporte un commentaire, celui-ci s’affiche comme provenant directement de l’utilisateur ou utilisatrice, et non de la personne de l’administration agissant au nom de l’utilisateur ou utilisatrice.

+++

+++**Mise à jour de maintenance le 23 mars 2023**

Le contenu du panneau **[!UICONTROL Résumé] est trop large pour le panneau**

_Documents_

Lorsqu’un utilisateur ou une utilisatrice consulte le panneau [!UICONTROL Résumé] d’un document, le contenu est trop large pour être affiché dans le panneau. Le panneau comporte désormais une barre de défilement horizontale qu’il faut faire défiler pour afficher le contenu du panneau [!UICONTROL Résumé]. Le problème est dû au fait que le nom de fichier du document ne s’ajuste pas. Ce problème est limité aux fichiers dont le nom comporte une extension de fichier HTML.

**Nouvelle version du [!UICONTROL lecteur de vérification pour bureau]**

_Vérification_

Pour résoudre un problème de commentaire du [!UICONTROL lecteur de vérification pour bureau], nous en avons déployé une nouvelle version.

Les utilisateurs ou utilisatrices qui disposent déjà du [!UICONTROL lecteur de vérification pour bureau] recevront une notification automatique de cette mise à jour.

Les utilisateurs ou utilisatrices peuvent également télécharger manuellement la dernière version. Pour plus d’informations, consultez [Installation [!UICONTROL du lecteur de vérification pour bureau]](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=fr).

* Version précédente : 2.1.22
* Nouvelle version : 2.1.23

+++

+++**Mise à jour de maintenance le 16 mars 2023**

**Éléments de liste de contrôle non copiés lors de la copie d’une carte**

_Panoramas_

Lors de la copie d’une carte ad hoc (les cartes connectées ne peuvent pas être copiées), les éléments de liste de contrôle ne sont pas copiés dans la nouvelle carte.

**Champ personnalisé manquant lorsque le problème est converti en projet**

_Projets_

Lorsqu’un utilisateur ou une utilisatrice convertit un problème en projet à l’aide d’un modèle, un champ personnalisé qui se trouvait sur le problème ne s’affiche pas sur le projet. Ce problème affecte uniquement les personnes hors administration.

**Les messages personnalisés ne s’affichent pas dans les e-mails de notification**

_BAT_

Lorsqu’un utilisateur ou une utilisatrice partage un BAT et ajoute un message personnalisé, ce dernier n’apparaît pas dans l’e-mail de notification envoyé au ou à la destinataire. L’objet est le nom du BAT et le message n’apparaît pas dans l’e-mail.

+++

+++**Mise à jour de maintenance le 9 mars 2023**

**Le niveau d’accès n’est pas attribué lors de la réactivation d’un utilisateur ou d’une utilisatrice**

_Utilisateurs ou utilisatrices_

Lorsqu’un utilisateur ou une autilisatrice en réactive un ou une autre et tente de lui attribuer un niveau d’accès dans la fenêtre [!UICONTROL Réactiver un utilisateur], le menu déroulant ne s’affiche pas lors de la saisie. Il est donc impossible de sélectionner un niveau d’accès. Si l’utilisateur ou l’utilisatrice saisit intégralement un niveau d’accès et l’enregistre, il n’est pas attribué à l’utilisateur réactivé ou à l’utilisatrice réactivée.

**Enregistrer le brouillon d’un commentaire dans la zone [!DNL Goals]**

_[!DNL Workfront Goals]_

Désormais, lorsque vous quittez la page [!UICONTROL Mises à jour] d’un objectif lors de la composition d’un message, le message est conservé lorsque vous revenez en arrière. Avant cette mise à jour, le commentaire non envoyé aurait été supprimé.

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

Lorsqu’un utilisateur ou une utilisatrice suit un lien vers un commentaire sur un objet dans Workfront, le flux de mise à jour se charge brièvement, puis l’utilisateur ou l’utilisatice est redirigé vers la zone [!UICONTROL Détails] de l’objet. Cela peut se produire si l’utilisateur ou l’utilisatrice clique sur le lien d’un e-mail ou le colle dans son navigateur.

Actuellement, seuls les objets Document sont touchés par ce problème.

**Le résumé d’impression ne se charge pas**

_[!UICONTROL Workfront Proof]_

Lorsqu’un utilisateur ou une utilisatrice tente de charger la page de résumé d’impression, celle-ci semble être en cours de chargement, mais ne se charge jamais.

+++

## Mises à jour de février 2023

+++**Mise à jour de maintenance du 23 février 2023**

**Le lien vers un commentaire redirige vers la page [!UICONTROL Détails]**

_Mises à jour_

Lorsqu’un utilisateur ou une utilisatrice suit un lien vers un commentaire sur un objet dans Workfront, le flux de mise à jour se charge brièvement, puis l’utilisateur ou l’utilisatice est redirigé vers la zone [!UICONTROL Détails] de l’objet. Cela peut se produire si l’utilisateur ou l’utilisatrice clique sur le lien d’un e-mail ou le colle dans son navigateur.

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

**La désactivation planifiée ne désactive pas l’utilisateur ou l’utilisatrice.**

_Utilisateurs_

Lorsque la désactivation d’un utilisateur ou d’une utilisatrice est planifiée et que la date et l’heure programmées sont passées, il ou elle n’est pas désactivé.

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

L’icône [!UICONTROL Panoramas] s’affiche maintenant dans le [!UICONTROL Menu principal] pour les utilisateurs et les utilisatrices qui ne disposent pas d’un modèle de disposition. Les panoramas sont également inclus par défaut dans le menu principal pour tous les nouveaux modèles de disposition créés. Les modèles existants n’ont pas été modifiés.

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

* La case « [!UICONTROL Peut modifier l’heure] » lors de la création ou de la modification d’une feuille de temps ou d’un profil de feuille de temps indique, lorsqu’elle est cochée, que les approbateurs et les approbatrices peuvent également envoyer, rouvrir ou modifier la feuille de temps, sauf si l’administration restreint ces actions dans les [!UICONTROL Préférences de la feuille de temps] de la section [!UICONTROL Configuration].
* L’option « [!UICONTROL Limiter la modification de la feuille de temps aux propriétaires et aux administrateurs] » dans la zone [!UICONTROL Préférences de la feuille de temps et d’heure] de la section [!UICONTROL Configuration] permet d’indiquer, lorsque cette case est décochée, que les utilisateurs suivants et les utilisatrices suivantes peuvent également modifier les feuilles de temps : les utilisateurs et les utilisatrices disposant d’un accès administratif aux feuilles de temps et d’heure, les approbateurs et les approbatrices de feuilles de temps autorisés à modifier l’heure et les gestionnaires des propriétaires de feuilles de temps.

Notez que le fonctionnement de ces paramètres n’a pas été modifié et que seules des icônes d’informations ont été ajoutées pour clarifier leur utilisation.

+++

+++**Mise à jour de maintenance du 26 janvier 2023**

**Erreur de soumission d’une demande depuis [!DNL Outlook]**

_Intégrations_

Lorsque l’utilisateur ou l’utilisatrice tente de soumettre une demande comprenant des pièces jointes dans un e-mail [!DNL Outlook], une ou plusieurs des pièces jointes ne se chargent pas et le message d’erreur suivant apparaît :

« [!UICONTROL L’erreur suivante s’est produite : Le fichier contenant l’identificateur xxxx n’existe pas.] »

Cela se produit uniquement lorsqu’une affectation est effectuée pour la nouvelle demande, soit au moyen de la file d’attente des demandes, soit manuellement lors de la création de la demande.

**Nouvelle version du lecteur de vérification pour bureau**

_Vérification_

Pour résoudre un problème de blocage du lecteur de vérification pour bureau, nous en avons déployé une nouvelle version. Les utilisateurs ou utilisatrices qui disposent déjà du lecteur de vérification pour bureau recevront une notification automatique de cette mise à jour.

Les utilisateurs ou utilisatrices peuvent également afficher manuellement la dernière version. Pour plus d’informations, consultez [Installation du lecteur de vérification pour bureau](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=fr).

* Version précédente : 2.1.19
* Nouvelle version : 2.1.20

**L’utilisateur ou l’utilisatrice ne peut pas modifier ses propres paramètres utilisateur**

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

Lorsqu’un utilisateur ou une utilisatrice consulte l’[!UICONTROL Équilibreur de charge de travail], il ou elle voit les heures enregistrées pour un utilisateur ou une utilisatrice qui ne sont associées à aucun projet, tâche ou problème, et qui ne sont pas non plus enregistrées en tant qu’heures [!UICONTROL Générales]. Ces heures peuvent s’afficher uniquement dans la vue 4 semaines ou 6 semaines.

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

Lorsqu’un utilisateur ou une utilisatrice crée ou modifie le champ calculé d’un formulaire personnalisé et inclut un champ personnalisé dans l’expression du champ calculé, l’expression est considérée comme non valide. Le bouton [!UICONTROL Enregistrer] est désactivé et l’utilisateur ou l’utilisatrice ne peut pas quitter le champ personnalisé. De plus, l’utilisateur ou l’utilisatrice voit le message suivant sous le champ :

« [!UICONTROL Oups ! Un problème est survenu. Contactez Workfront pour nous aider à comprendre l’erreur et y remédier.] »

La suppression du champ personnalisé de l’expression permet à l’utilisateur ou à l’utilisatrice d’enregistrer et de quitter le champ.

**Impossible de définir les niveaux d’accès**

_Utilisateurs_

Lorsqu’un utilisateur ou une utilisatrice tente de modifier le niveau d’accès d’un autre utilisateur ou d’une autre utilisatrice, les niveaux d’accès sont grisés et l’utilisateur ou l’utilisatrice ne peut pas les modifier. Le problème se produit également si l’utilisateur ou l’utilisatrice qui tente d’effectuer la modification est un administrateur ou une administratrice système.

+++

+++**Mise à jour de maintenance du 12 janvier 2023**

**Ctrl+F ou Cmd+F ne fonctionne pas comme prévu dans les champs de liste déroulante**

_Formulaires personnalisés_

Lorsqu’un utilisateur remplit un formulaire personnalisé et effectue une recherche dans une liste déroulante à l’aide de Ctrl+F ou Cmd+F, puis tente d’accéder à l’instance suivante de cette recherche, la liste déroulante revient en haut de la liste plutôt que d’accéder à l’instance suivante de la recherche. Cela se produit lorsqu’une liste déroulante est définie pour autoriser plusieurs sélections.

L’écran « **[!UICONTROL Modifier le rapport] » est vide**

_Rapports_

Lorsqu’un utilisateur ou une utilisatrice consulte un rapport et tente de le modifier, il ou elle est redirigé vers une page vide et ne peut pas le modifier.

**Les tâches mises en avant ne restent pas mises en avant**

_Tâches_

Lorsqu’un utilisateur ou une utilisatrice consulte une liste de tâches et met en avant une tâche, la tâche revient immédiatement à son état d’origine (mise en retrait).

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

Nous avons supprimé la restriction qui obligeait les utilisateurs et les utilisatrices devant être ajoutés à une équipe de projet à faire partie du groupe associé au projet. Vous pouvez désormais ajouter n’importe quel utilisateur actif ou utilisatrice active à une équipe de projet, quels que soient les groupes auxquels il ou elle appartient.

**Nouvelles icônes d’informations pour les feuilles de temps, les profils de feuille de temps et les préférences de feuille de temps**

>[!NOTE]
>
>Cette mise à jour est sortie dans l’environnement de prévisualisation le 3 novembre 2022 et passe désormais en production.

_Workfront_

Nous avons ajouté plusieurs icônes d’informations pour les paramètres suivants :

* La case « Peut modifier l’heure » lors de la création ou de la modification d’une feuille de temps ou d’un profil de feuille de temps indique, lorsqu’elle est cochée, que les approbateurs etles approbatrices peuvent également envoyer, rouvrir ou modifier la feuille de temps, sauf si votre administrateur ou administratrice restreint ces actions dans les « Préférences de la feuille de temps » de la section « Configuration ».
* « Limiter la modification de la feuille de temps aux propriétaires et aux administrateurs » dans la zone « Préférences de la feuille de temps et d’heure » de la section « Configuration » pour indiquer que, lorsque cette case est décochée, les utilisateurs et utilisatrices suivants peuvent également modifier les feuilles de temps : les utilisateurs et utilisatrices disposant d’un accès administratif aux feuilles de temps et d’heure, les approbateurs et les approbatrices de feuilles de temps autorisés à modifier l’heure et les gestionnaires des propriétaires de feuilles de temps.

Notez que le fonctionnement de ces paramètres n’a pas été modifié et que seules des icônes d’informations ont été ajoutées pour clarifier leur utilisation.

+++

## Mises à jour de maintenance précédentes

Les informations relatives aux mises à jour de maintenance précédentes sont disponibles ici :

* [Archive des mises à jour de maintenance d’[!DNL Workfront] - 2022](2022-updates.md)
* [Archive des mises à jour de maintenance de [!DNL Workfront] - 2021](2021-updates.md)
