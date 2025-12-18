---
title: Mises à jour de maintenance pour Workfront
description: Mises à jour de maintenance pour  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: db432f61d90c0900d7522c64c7feb990268b5542
workflow-type: tm+mt
source-wordcount: '3378'
ht-degree: 80%

---

# Mises à jour de maintenance pour [!DNL Workfront]

>[!NOTE]
>
>Pour plus d’informations sur les pannes de maintenance pour tous les produits Adobe, y compris Workfront, voir la [page de statut d’Adobe](https://status.adobe.com/fr/).

Cette page décrit les problèmes résolus par les mises à jour hebdomadaires de Workfront.

Ces mises à jour incluent également d’autres correctifs mineurs ou moins conséquents. L’assistance [!DNL Workfront] vous avertira lorsqu’un problème que vous avez soumis est résolu.

Pour connaître les mises à jour de maintenance antérieures à 2025, consultez les [Mises à jour de maintenance précédentes](#previous-maintenance-updates).

Les mises à jour de maintenance suivantes ont été effectuées en 2025.

## Mises à jour de décembre 2025

+++**Semaine des mises à jour de maintenance du 14 au 20 décembre 2025**

### Semaine des mises à jour de maintenance du 14 au 20 décembre 2025

#### Affectations

**Les affectations d’équipe ne sont pas enregistrées**

Lorsque l’utilisateur affecte une équipe à une tâche dans Workfront, l’affectation de l’équipe n’est pas enregistrée et l’équipe n’est pas avertie du travail.

#### Planifications

**Autorisations de planification révoquées pour un groupe**

Lorsque l’administrateur de groupes Workfront ajoute une exception de date à un planning et enregistre les modifications, les autorisations liées à ce planning sont supprimées du groupe et l’administrateur Workfront doit accorder l’accès au groupe.


#### Tâches

**Les modifications intégrées apportées à une tâche ne sont pas enregistrées**

Lorsque l’utilisateur apporte des modifications sur la ligne à une tâche dans l’expérience de tâche héritée et les enregistre, les modifications ne sont pas enregistrées.

#### Feuilles de temps

**feuilles de temps non générées**

Les feuilles de temps ne sont pas générées automatiquement comme prévu. Cela peut se produire même si les profils des feuilles de temps sont précis et que les feuilles de temps des autres semaines sont générées correctement.

#### Utilisateurs et utilisatrices

**Problèmes liés aux modifications apportées au profil d’épreuve**

Les problèmes suivants ont été signalés concernant la modification du profil d’épreuve d’un utilisateur :

* Lorsque l’utilisateur affecte un profil d’épreuve différent à un utilisateur et enregistre, la modification n’est pas enregistrée et l’utilisateur conserve le profil d’épreuve précédent.
* Un profil d’épreuve d’un utilisateur peut s’afficher comme un profil d’épreuve incorrect, même si le profil d’épreuve correct est affecté.
* Lorsque d’autres modifications sont apportées à un utilisateur, ses autorisations d’épreuve peuvent également changer.

**L’option de génération automatique d’épreuves est absente du profil utilisateur**

Lorsque l’utilisateur consulte un profil utilisateur, l’option « Générer automatiquement des épreuves lors du chargement de documents » n’est pas disponible. Cela peut se produire même si toutes les conditions préalables à l’option ont été remplies.

+++

+++**Semaine des mises à jour de maintenance du 7 au 13 décembre 2025**

### Semaine des mises à jour de maintenance du 7 au 13 décembre 2025

#### Demandes

**Impossible de charger le document à demander à GDrive**

Lorsque l’utilisateur crée une demande dans la nouvelle expérience de demande et tente de charger un document à partir de GDrive, la fenêtre de GDrive ne répond pas. L’utilisateur ne peut pas sélectionner de fichier ni fermer la fenêtre.


#### Utilisateurs et utilisatrices

**La modification en masse d’utilisateurs supprime les pools de ressources et les rapports directs**

Lorsque l’utilisateur modifie des utilisateurs en masse, clique dans le champ Pools de ressources et ne saisit pas de valeur, les pools de ressources de tous les utilisateurs modifiés sont supprimés.

La modification en masse peut également supprimer les rapports directs des utilisateurs modifiés.

**Erreur lors de l’ouverture de la page Utilisateurs**

Lorsque l’utilisateur tente d’ouvrir la page Utilisateurs depuis le menu principal, la page ne s’ouvre pas et le message suivant apparaît :

« Une erreur s’est produite et nous travaillons à résoudre le problème. Pour continuer votre travail, essayez d’actualiser cette page du navigateur. »

+++

+++**Semaine des mises à jour de maintenance du 30 novembre au 6 décembre 2025**

### Semaine des mises à jour de maintenance du 30 novembre au 6 décembre 2025

Les mises à jour de cette semaine incluent uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

## Mises à jour de novembre 2025

+++**Semaine des mises à jour de maintenance pour la planification Workfront du 16 au 22 novembre 2025**

### Semaine des mises à jour de maintenance pour la planification Workfront du 16 au 22 novembre 2025

#### Formulaires personnalisés

**Indicateur actif/inactif ajouté à la liste des formulaires personnalisés où un champ est utilisé**

Dans le concepteur de formulaires personnalisés, vous pouvez sélectionner un champ et cliquer sur **Afficher les Forms associés** pour afficher une liste de tous les autres formulaires dans lesquels le champ est utilisé. Vous voyez ainsi quels autres formulaires seront affectés si vous modifiez le champ.

Une amélioration de cette liste est un indicateur actif/inactif pour chaque formulaire. Vous pouvez voir en un coup d’œil si le champ est actuellement utilisé sur des formulaires actifs ou inactifs.

+++

+++**Semaine des mises à jour de maintenance pour la planification Workfront, du 9 au 15 novembre 2025**

### Semaine des mises à jour de maintenance pour la planification Workfront du 9 au 15 novembre 2025

#### Types d’enregistrements

**Les options Modifications et Paramètres ont été supprimées du menu Plus dans un type d’enregistrement**

Nous avons supprimé les options Modifier et Paramètres du menu Plus d’un type d’enregistrement global qui a été ajouté à un espace de travail secondaire à partir d’un type d’enregistrement global existant. Avant cette mise à jour, les menus étaient grisés et non fonctionnels.

+++

+++**Semaine des mises à jour de maintenance du 9 au 15 novembre 2025**

### Semaine des mises à jour de maintenance du 9 au 15 novembre 2025

#### Tâches

**L’ajout de prédécesseurs ne dépend plus des sous-paramètres Modifier des tâches dans le niveau d’accès**

Les utilisateurs peuvent ajouter des prédécesseurs aux tâches lorsque l’accès Modifier est activé pour les tâches dans leur niveau d’accès, quels que soient les sous-paramètres que vous avez sélectionnés. Cela est désormais cohérent avec la fonctionnalité d’API existante.

+++

+++**Mises à jour de maintenance, semaine du 2 au 8 novembre 2025**

### Mises à jour de maintenance, semaine du 2 au 8 novembre 2025

Les mises à jour de cette semaine incluent uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mises à jour de maintenance, semaine du 26 octobre au 1er novembre 2025**

### Mises à jour de maintenance, semaine du 26 octobre au 1er novembre 2025

#### Rapports

**Problèmes liés aux listes déroulantes dans les graphiques**

Les problèmes suivants ont été signalés concernant les listes déroulantes dans les graphiques :

* Lors de la consultation d’un rapport avec une colonne déroulante et la fonction Graphique, la liste déroulante de la fenêtre Graphique ne fonctionne pas.
* L’affectation de personnes à partir d’un rapport dans une liste déroulante n’est pas enregistrée.

#### Utilisateurs et utilisatrices

**Impossible d’utiliser les options avancées lors de la création d’utilisateurs et d’utilisatrices**

Lorsque l’équipe d’administration de Workfront crée un utilisateur ou une utilisatrice et tente d’utiliser l’option avancée, elle ne peut pas utiliser les options et le message suivant apparaît :

```
Cannot read properties of undefined (reading 'sections')

Cannot read properties of undefined (reading 'sections')

Error fetching object details
```

+++

## Mises à jour d’octobre 2025

+++**Mises à jour de maintenance, semaine du 19 au 25 octobre 2025**

### Mises à jour de maintenance, semaine du 19 au 25 octobre 2025

#### Formulaires personnalisés

**La logique d’affichage des champs n’est pas correctement suivie.**

Lorsqu’un utilisateur ou une utilisatrice remplit un formulaire personnalisé qui inclut une logique d’affichage (certains champs sont affichés ou non en fonction des valeurs d’autres champs), les champs ne sont pas affichés conformément à la logique de ces champs.

#### Épreuves

**Impossible de fermer la visionneuse de relecture**

Lorsqu’un utilisateur ou une utilisatrice consulte une épreuve dans la visionneuse de relecture et tente de fermer l’épreuve en cliquant sur le X dans le coin supérieur droit, elle ne se ferme pas.

+++

+++**Mises à jour de maintenance, semaine du 12 au 18 octobre 2025**

### Mise à jour de maintenance, semaine du 12 au 18 octobre 2025

Les mises à jour de cette semaine incluent uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mises à jour de maintenance, semaine du 5 au 11 octobre 2025**

### Mise à jour de maintenance, semaine du 5 au 11 octobre 2025

Les mises à jour de cette semaine incluent uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mises à jour de maintenance, semaine du 28 septembre au 4 octobre 2025**

### Mises à jour de maintenance, semaine du 28 septembre au 4 octobre 2025

#### Programmes

**Impossible d’enregistrer lors de la modification d’un programme**

Lorsqu’un utilisateur ou une utilisatrice modifie un programme et tente d’enregistrer les modifications, celles-ci ne sont pas enregistrées.

+++

## Mises à jour de septembre 2025

+++**Mises à jour de maintenance, semaine du 21 au 27 septembre 2025**

### Mises à jour de maintenance, semaine du 21 au 27 septembre 2025

#### Utilisateurs et utilisatrices

**Impossible de modifier les paramètres de notification d’une autre personne**

Lorsqu’une personne tente de modifier les paramètres de notification d’une autre personne, elle ne peut pas le faire et le message d’erreur suivant s’affiche :

« Vous ne disposez pas d’un accès suffisant pour modifier les données financières. »

+++

+++**Mises à jour de maintenance, semaine du 14 au 20 septembre 2025**

### Mises à jour de maintenance, semaine du 14 au 20 septembre 2025

Les mises à jour de cette semaine incluent uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mises à jour de maintenance, semaine du 7 au 13 septembre 2025**

### Mises à jour de maintenance, semaine du 7 au 13 septembre 2025

Les mises à jour de cette semaine incluent uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++


+++**Mises à jour de maintenance, semaine du 31 août au 6 septembre 2025**

### Mise à jour de maintenance, semaine du 31 août au 6 septembre 2025

#### API

**Nouveaux mécanismes de sécurisation pour éviter de surcharger les abonnements aux événements**

Les abonnements aux événements sont conçus pour assurer une diffusion fiable des événements à tous les utilisateurs et utilisatrices. Pour ce faire, des mesures de protection ont été mises en place pour éviter une production excessive d’événements par une seule personne, qui pourrait entraîner des problèmes de qualité de service pour tout le monde. Par conséquent, un utilisateur ou une utilisatrice qui produit trop d’événements à un taux élevé sur une courte période peut faire l’objet de mise en sandbox et de retards de diffusion d’événements.

#### Documents

**Les personnes ajoutées avec des fonctions d’approbation ne sont pas averties une fois l’approbation terminée.**

Lorsqu’une personne a approuvé un document et que d’autres personnes sont ajoutées avec des fonctions d’approbation, les personnes nouvellement ajoutées ne reçoivent pas de notifications in-app ou par e-mail de la demande d’approbation.

+++

## Mises à jour d’août 2025

+++**Mises à jour de maintenance, semaine du 24 au 30 août 2025**

### Mise à jour de maintenance, semaine du 24 au 30 août 2025

Les mises à jour de cette semaine incluent uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mises à jour de maintenance, semaine du 17 au 23 août 2025**

### Mise à jour de maintenance, semaine du 17 au 23 août 2025

#### Projets

**Erreur lors de l’ajout d’un projet à un programme**

Lorsqu’un utilisateur ou une utilisatrice tente d’ajouter un projet existant à un programme, le projet n’est pas ajouté et le message d’erreur suivant apparaît :

« Erreur lors du chargement du contenu secondaire... »

**Les projets exportés contiennent des heures effectives inexactes**

Lorsque l’utilisateur ou l’utilisatrice exporte un projet vers Excel, la colonne Heures effectives n’affiche pas les bonnes données.

+++

+++**Mises à jour de maintenance, semaine du 10 au 16 août 2025**

### Mise à jour de maintenance, semaine du 10 au 16 août 2025

Les mises à jour de cette semaine incluent uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mises à jour de maintenance, semaine du 3 au 9 août 2025**

### Mise à jour de maintenance, semaine du 3 au 9 août 2025

Les mises à jour de cette semaine incluent uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mises à jour de maintenance, semaine du 27 juillet au 2 août 2025**

### Mises à jour de maintenance, semaine du 27 juillet au 2 août 2025

#### Projets

**Un avertissement s’affiche désormais lorsque la chronologie n’a pas été recalculée.**

Une icône d’avertissement s’affiche désormais lorsque la chronologie du projet n’a pas été recalculée. Pointez sur cette icône pour afficher le message suivant :

« La chronologie du projet est incorrecte. Les personnes responsables du projet devront peut-être recalculer manuellement la chronologie. »

Parfois, les chronologies ne sont pas recalculées en raison de la complexité extrême du projet. Par exemple, un projet qui comporte plusieurs dépendances, un grand nombre de tâches, plusieurs projets transversaux antérieurs ou plusieurs indentations de tâches peut être affecté.

Auparavant, rien n’indiquait qu’une chronologie n’avait pas été recalculée.

#### Tâches

**La zone Approbations disparaît du volet de navigation de gauche.**

Lorsqu’un utilisateur ou une utilisatrice consulte une tâche, la zone Approbations peut disparaître du volet de navigation de gauche. La suppression et l’ajout de la zone Approbations dans le modèle de mise en page résolvent le problème, mais le problème peut se reproduire.

+++

## Mises à jour de juillet 2025

+++**Mises à jour de maintenance, semaine du 20 au 26 juillet 2025**

### Mises à jour de maintenance, semaine du 20 au 26 juillet 2025

#### Épreuves

**Impossible de taguer les utilisateurs et utilisatrices dans les commentaires de l’épreuve**

Lorsqu’une personne tente de taguer une autre personne dans un commentaire d’épreuve et commence à saisir son nom, la personne n’apparaît pas dans la liste et ne peut pas être sélectionnée pour être taguée.

+++

+++**Mises à jour de maintenance, semaine du 13 au 19 juillet 2025**

### Mises à jour de maintenance, semaine du 13 au 19 juillet

### Intégrations

**Problèmes d’intégration de Workfront pour Slack**

Les problèmes suivants liés à l’intégration de Workfront pour Slack ont été signalés :

* Les utilisateurs et utilisatrices ne sont pas avertis dans Slack lorsque des mises à jour sont effectuées dans Workfront.
* Les utilisateurs et utilisatrices ne peuvent pas se connecter à Workfront depuis Slack.
* Les autres commandes de l’intégration de Workfront pour Slack ne fonctionnent pas comme prévu.

+++

+++**Mises à jour de maintenance, semaine du 6 au 12 juillet 2025**

### Mises à jour de maintenance, semaine du 6 au 12 juillet

### Projets

**Impossible de déplacer le projet vers le programme spécifié**

Lorsqu’un utilisateur ou une utilisatrice tente de déplacer un projet vers un programme, le projet ne se déplace pas. Cela peut se produire même si l’utilisateur ou l’utilisatrice a reçu un message indiquant que le projet a bien été déplacé.

+++

## Mises à jour de juin 2025

+++**Mises à jour de maintenance, semaine du 22 au 27 juin 2025**

### Mise à jour de maintenance, semaine du 22 au 27 juin 2025

#### Épreuves

**Impossible d’ouvrir l’épreuve à partir du lien direct**

Lorsqu’une personne tente d’ouvrir une épreuve à partir d’un lien direct, celle-ci ne s’ouvre pas. Cela peut se produire même si la personne fait partie d’un workflow pour l’épreuve ou si elle est administratrice Workfront.

#### Rapports

**L’analyse en profondeur du graphique comprend des résultats inexacts.**

Lorsqu’une personne consulte un rapport de graphique et tente d’analyser en profondeur un groupe spécifique, les détails incluent les résultats qui ne se trouvent pas dans le groupe sélectionné.

Ce problème a été signalé dans les rapports regroupés par date.

+++

+++**Mises à jour de maintenance, semaine du 15 au 21 juin 2025**

### Mise à jour de maintenance, semaine du 15 au 21 juin 2025

Les mises à jour de cette semaine incluent uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mises à jour de maintenance, semaine du 8 au 14 juin 2025**

### Mise à jour de maintenance, semaine du 8 au 14 juin 2025

#### Planificateur de ressources

**Le bouton Exporter est désactivé.**

Lorsque l’utilisateur ou l’utilisatrice tente d’exporter à partir du planificateur de ressources, le bouton est désactivé (grisé) et l’export est impossible.

#### Feuilles de temps

**Les feuilles de temps ne sont pas générées correctement.**

Lorsque l’utilisateur ou l’utilisatrice tente de générer des feuilles de temps et que la génération est définie sur « Toutes les deux semaines », une seule semaine est générée.

+++

+++**Mises à jour de maintenance, semaine du 1er au 7 juin 2025**

### Mise à jour de maintenance, semaine du 1er au 7 juin 2025

### Recherche

**La recherche avancée ne renvoie pas les résultats attendus.**

Lorsqu’un utilisateur ou une utilisatrice utilise la recherche avancée, les résultats attendus ne sont pas renvoyés. Cela peut se produire même lorsqu’aucun filtre n’est appliqué à la recherche avancée.

+++

## Mises à jour de mai 2025

+++**Mises à jour de maintenance, semaine du 25 au 31 mai 2025**

### Mise à jour de maintenance, semaine du 25 au 31 mai 2025

Les mises à jour de cette semaine incluent uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mise à jour de maintenance le 22 mai 2025**

### Mise à jour de maintenance le 22 mai 2025

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mise à jour de maintenance le 15 mai 2025**

### Mise à jour de maintenance le 15 mai 2025

#### Rapports

**Erreur lors de l’affichage d’un rapport avec une vue Jalon**

Lorsque l’utilisateur ou l’utilisatrice tente d’afficher un rapport dont la vue Jalon est disponible pour activation, le rapport ne se charge pas et affiche une erreur.

+++

+++**Mise à jour de maintenance le 8 mai 2025**

### Mise à jour de maintenance le 8 mai 2025

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mise à jour de maintenance le 1er mai 2025**

### Mise à jour de maintenance le 1er mai 2025

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

## Mises à jour d’avril 2025

+++**Mise à jour de maintenance le 24 avril 2025**

### Mise à jour de maintenance le 24 avril 2025

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mise à jour de maintenance le 17 avril 2025**

### Mise à jour de maintenance le 17 avril 2025

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mise à jour de maintenance le 10 avril 2025**

### **Mise à jour de maintenance le 10 avril 2025**

#### Tableaux de bord

**Le tableau de bord personnalisé ne s’ouvre pas.**

Lorsque l’utilisateur ou l’utilisatrice consulte un objet et tente d’ouvrir un tableau de bord personnalisé joint à cet objet, le tableau de bord ne s’ouvre pas.

#### Rapports

**Les utilisateurs et utilisatrices de différents fuseaux horaires obtiennent des résultats de rapport différents.**

Les utilisateurs et utilisatrices de différents fuseaux horaires qui utilisent le sélecteur de date pour obtenir un rapport pour une certaine date obtiennent des résultats différents pour ce rapport.

+++

+++**Mise à jour de maintenance le 3 avril 2025**

### Mise à jour de maintenance le 3 avril 2025

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

## Mises à jour de mars 2025

+++**Mise à jour de maintenance le 27 mars 2025**

### Mise à jour de maintenance le 27 mars 2025

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mise à jour de maintenance le 20 mars 2025**

### Mise à jour de maintenance le 20 mars 2025

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mise à jour de maintenance le 13 mars 2025**

### Mise à jour de maintenance le 13 mars 2025

#### Rapports

**Le nombre d’éléments dans le graphique est inexact.**

Dans un rapport de tableau de bord, le fait de cliquer sur un résultat de graphique contenant plus de 15 éléments et choisir de n’afficher que 15 éléments fonctionne comme prévu. Cependant, si vous ouvrez le même rapport en dehors du tableau de bord et que vous cliquez sur le même résultat de graphique, tous les éléments s’affichent, mais seuls 15 d’entre eux apparaissent.

+++

+++**Mise à jour de maintenance le 6 mars 2025**

### Mise à jour de maintenance le 6 mars 2025

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

## Mises à jour de février 2025

+++**Mise à jour de maintenance le 27 février 2025**

### Mise à jour de maintenance le 27 février 2025

#### Groupes

**Impossible de partager le niveau d’accès d’administration**

Lors d’une tentative pour partager le niveau d’accès d’administration avec un groupe, la case à cocher pour chaque groupe ne répond pas et le groupe n’obtient pas le niveau d’accès attendu.

+++

+++**Mise à jour de maintenance le 20 février 2025**

### Mise à jour de maintenance le 20 février 2025

#### Notifications

**Retards des notifications in-app et par e-mail**

Lorsqu’un événement qui doit déclencher des notifications par e-mail ou in-app se produit, les notifications ne sont pas envoyées au moment de l’événement et peuvent prendre jusqu’à quelques heures.

#### Tâches

**Les heures consignées restent sur le projet précédent une fois déplacées.**

Une fois que les tâches ont été déplacées vers un nouveau projet, le total des heures du projet d’origine inclut les heures des tâches déplacées. Les tâches conservent toujours correctement les heures consignées dans le nouveau projet.

#### Feuilles de temps

**Nombre total d’heures incorrect**

Le calcul du nombre total d’heures des feuilles de temps affiche parfois une somme incorrecte.

+++

+++**Mise à jour de maintenance le 13 février 2025**

### Mise à jour de maintenance le 13 février 2025

#### Formulaires personnalisés

**Données personnalisées non affichées dans le panneau Résumé**

Lorsqu’un client ou une cliente consulte le panneau Résumé pour une tâche, les données personnalisées qui devraient apparaître dans le panneau Résumé sont absentes. Ce problème peut se produire même si le modèle de mise en page des tâches inclut les champs personnalisés.

#### Rapports

**Problèmes d’affichage des invites**

Lors de l’accès à un rapport d’invite avec un grand nombre d’invites, la boîte de dialogue d’invite ne permet pas de faire défiler l’écran pour accéder à toutes les invites ou au bouton Exécuter le rapport.

+++

+++**Mise à jour de maintenance le 6 février 2025**

### Mise à jour de maintenance le 6 février 2025

#### Listes

**Impossible de modifier la liste des tâches après le chargement de l’épreuve**

Lors du chargement d’une épreuve dans un projet, la liste des tâches de ce projet ne peut pas être modifiée en ligne tant que la page n’est pas actualisée ou que le chargement de l’épreuve n’est pas terminé.

+++

## Mises à jour de janvier 2025

+++**Mise à jour de maintenance le 30 janvier 2025**

### Mise à jour de maintenance le 30 janvier 2025

#### Page d’accueil

**Les approbations n’apparaissent pas dans le widget d’accueil.**

Les approbations soumises par une personne n’apparaissent pas dans son propre widget Mes approbations, même si elles sont filtrées pour être affichées spécifiquement.

#### Rapports

**Les filtres des rapports horaires incluent des dates incorrectes**

Lors du filtrage d’un rapport horaire pour n’afficher qu’une date spécifique, une date adjacente différente est en fait incluse dans le rapport. Ce problème semble lié aux paramètres de fuseau horaire.

+++

+++**Mise à jour de maintenance le vendredi 23 janvier 2025**

### Mise à jour de maintenance le vendredi 23 janvier 2025

#### Rapports

**Les champs de devise personnalisés provoquent une erreur de rapport**

Lorsqu’une vue de rapport contient plusieurs champs de devise personnalisés, le rapport renvoie une erreur.

#### Utilisateurs et utilisatrices

**La balise « Non enregistré » persiste après la connexion**

Même après une première connexion réussie, la balise « Non enregistré » ne disparaît pas comme prévu pour les nouveaux utilisateurs et utilisatrices.

+++

+++**Mise à jour de maintenance le vendredi 16 janvier 2025**

### Mise à jour de maintenance le vendredi 16 janvier 2025

#### Documents

**Erreur « Modifications non enregistrées » lors de l’ajout d’un formulaire à un document**

Lors de l’ajout d’un formulaire à un document, une erreur « Modifications non enregistrées » s’affiche. Elle ne peut pas être fermée et empêche toute interaction avec l’application.

#### Épreuves

**Le nom de l’épreuve n’apparaît pas sur l’onglet du navigateur.**

Lorsqu’une personne consulte une épreuve, le nom de l’épreuve n’est pas visible dans l’onglet du navigateur. À la place, l’onglet du navigateur affiche Workfront.

#### Demandes et problèmes

**Erreur lors des affectations d’utilisateurs et utilisatrices avancés**

Lorsqu’un utilisateur ou une utilisatrice tente d’effectuer une affectation avancée d’une personne à une demande ou à un problème, la personne n’est pas affectée et l’erreur suivante s’affiche :

« Une erreur s’est produite et nous travaillons à résoudre le problème. Pour continuer votre travail, essayez d’actualiser cette page du navigateur. »

L’actualisation de la page du navigateur ne fonctionne pas.

#### Demandes

**Impossible de créer des demandes dans les environnements de prévisualisation**

Lorsque vous tentez de créer une demande dans un environnement de sandbox de prévisualisation, une erreur indiquant que la file d’attente des demandes n’est plus disponible s’affiche et la demande ne peut pas être créée.

+++

## Mises à jour de maintenance précédentes

Les informations relatives aux mises à jour de maintenance précédentes sont disponibles ici :

* [Archive des mises à jour de maintenance de [!DNL Workfront] - 2024](2024-updates.md)
* [Archive des mises à jour de maintenance de [!DNL Workfront] - 2023](2023-updates.md)
* [Archive des mises à jour de maintenance d’[!DNL Workfront] - 2022](2022-updates.md)
* [Archive des mises à jour de maintenance de [!DNL Workfront] - 2021](2021-updates.md)
