---
title: Mises à jour de maintenance pour Workfront
description: Mises à jour de maintenance pour  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: eace4f6034ca11c6616e82b411c0dcfd936e5f9a
workflow-type: tm+mt
source-wordcount: '1270'
ht-degree: 33%

---

# Mises à jour de maintenance pour [!DNL Workfront]

>[!NOTE]
>
>Les mises à jour de cette page sont temporairement suspendues pendant que nous mettons en place un nouveau processus de gestion de son contenu.



<!--
>[!NOTE] 
>
>For information about maintenance outages for all Adobe products, including Workfront, see the [Adobe Status page](https://status.adobe.com/).

-->

Cette page décrit les problèmes résolus par les mises à jour hebdomadaires de Workfront.

Ces mises à jour incluent également d’autres correctifs mineurs ou moins importants. [!DNL Workfront] L’assistance vous avertira lorsqu’un problème que vous avez soumis sera résolu.

Pour connaître les mises à jour de maintenance antérieures à 2026, consultez les [Mises à jour de maintenance précédentes](#previous-maintenance-updates).

Les mises à jour de maintenance suivantes ont été effectuées en 2026.

## Mises à jour de février 2026

+++**Semaine de mise à jour de maintenance du 22 au 28 février 2026**

### Semaine de mise à jour de maintenance du 22 au 28 février 2026

#### Demandes

**Impossible de charger un document lors du remplissage d’une demande**

Lorsque l’utilisateur remplit une demande et tente de charger un document, le document n’est pas chargé et le message d’erreur suivant apparaît :

« Erreur de chargement : essayez un fichier plus petit ou joignez un fichier après la création. »

+++

+++**Semaine de mise à jour de maintenance du 15 au 21 février 2026**

### Semaine de mise à jour de maintenance du 15 au 21 février 2026

#### Formulaires personnalisés

**Les champs calculés n’affichent pas de données pour les utilisateurs non-administrateurs**

Lorsque l’utilisateur non-administrateur Workfront consulte un formulaire personnalisé avec des champs extraits des données d’une section réservée aux administrateurs du formulaire, ce champ n’affiche pas la valeur calculée. Si l’utilisateur exécute Recalculer les expressions, la valeur s’affiche, mais elle est perdue lors de l’actualisation.

Les administrateurs et administratrices de Workfront peuvent voir les valeurs de champ comme prévu.

**La logique d’affichage ne s’affiche pas correctement sur le formulaire de demande**

Lorsque l’utilisateur remplit un formulaire personnalisé lié à une demande, la logique d’affichage n’est pas suivie et certains champs peuvent ne pas s’afficher comme prévu.

#### Page d’accueil

**Les mentions des épreuves n’apparaissent pas dans le widget Mentions**

Lorsque l’utilisateur est mentionné dans un commentaire sur une épreuve, cette mention n’est pas incluse dans le widget Mentions de l’Accueil.

#### Connexion

**Workfront ne se charge pas après la connexion**

Lorsqu’un utilisateur se connecte à Workfront, Workfront ne se charge pas. Si l’utilisateur actualise la page, Workfront se charge comme prévu.

#### Rapports

Les champs Workfront Planning n’apparaissent pas dans le Report Builder des tableaux de bord de la zone de travail

Lorsque l’utilisateur utilise le créateur dans les tableaux de bord de la zone de travail et tente de référencer des champs dans Workfront Planning, ces champs ne s’affichent pas dans le créateur.

#### Demandes

**vue « All » n’affiche pas toutes les requêtes**

Lorsque l’utilisateur consulte la liste des demandes dans la nouvelle expérience de demande et que la vue est définie pour afficher toutes les demandes, seules certaines des demandes s’affichent.


+++

+++**Semaine de mise à jour de maintenance du 8 au 14 février 2026**

### Semaine de mise à jour de maintenance du 8 au 14 février 2026

#### Rapports

**La requête du lac de données ne renvoie pas les résultats attendus**

Lorsque le lac de données est interrogé, il ne renvoie pas tous les résultats attendus.

#### Demandes

**Le brouillon créé avec la requête entraîne des problèmes**

Lorsque l’utilisateur crée et envoie une nouvelle demande dans la nouvelle expérience de demande, un brouillon est également créé. Le brouillon n’affiche que la première lettre du nom de la requête envoyée et toute tentative d’ouverture génère une erreur « Échec de récupération ».

En outre, si la demande soumise est ensuite supprimée, elle semble être supprimée mais reste visible dans la zone des Demandes de Workfront. Si l’utilisateur tente de rouvrir la demande, un message l’informant que la demande n’existe pas s’affiche.

**Problèmes liés aux brouillons dans la nouvelle expérience de demande**

Les problèmes suivants ont été signalés concernant les brouillons dans la nouvelle expérience de demande :

* Les demandes créées en tant que brouillon, puis envoyées, n’affichent que la première lettre de l’objet dans la liste des demandes.
* Les brouillons supprimés ne sont pas supprimés de la liste des demandes, et entraînent l’erreur « Échec de la récupération du brouillon ».

+++

+++**Semaine de mise à jour de maintenance du 1 au 7 février 2026**

### Semaine de mise à jour de maintenance du 1 au 7 février 2026

#### Documents

**Le panneau Résumé est vide**

Lorsque l’utilisateur consulte une liste Documents et clique sur un document, le panneau Résumé s’ouvre, mais reste vide. L’utilisateur ne peut pas fermer le panneau Résumé .

Si l’utilisateur recharge la page, le panneau Résumé peut se remplir comme prévu. Cependant, si l’utilisateur clique sur un autre document, le panneau de résumé de ce document est vide.

#### Demandes

**« Aucun objet » s’affiche dans la liste des demandes**

Lorsque l’utilisateur consulte la liste des demandes dans la nouvelle expérience de demande, certaines des demandes affichent « Aucun objet » dans la colonne Objet.

Si l’utilisateur ouvre l’une de ces requêtes, il constate qu’elle a bien un objet.

**’erreur « Vous ne disposez pas d’un accès suffisant » lors de la copie de requêtes**

Lorsque l’utilisateur tente de copier une demande via la page de demande, la demande n’est pas copiée et le message d’erreur suivant apparaît :

« Vous ne disposez pas d’un accès suffisant pour modifier ce problème. »

**’erreur « Vous devez être un administrateur système » lors de la copie de requêtes**

Lorsque l’utilisateur copie une demande et tente de l’enregistrer, la demande n’est pas enregistrée et le message suivant apparaît :

« Vous devez être un administrateur système pour modifier cette valeur de paramètre de donnée personnalisée. »

#### Utilisateurs et utilisatrices

**Les utilisateurs ne sont pas correctement configurés sur le Adobe Admin Console**

Si une personne existe déjà dans une Adobe Admin Console et qu’elle est ensuite automatiquement configurée dans une console qui inclut Workfront, cette personne n’est pas correctement configurée dans la nouvelle console.

#### Équilibreur de charge de travail

**Les heures par utilisateur ne sont pas calculées correctement**

Lorsque l’utilisateur consulte les heures d’un utilisateur dans l’équilibreur de charge de travail , ces heures peuvent ne pas être calculées correctement. Par exemple, la vue Semaine peut afficher un calcul des heures, mais la vue 4 semaines affiche un nombre d&#39;heures différent pour cette semaine.

+++

## Mises à jour de janvier 2026

+++**Semaine de mise à jour de maintenance du 25 au 31 janvier 2026**

### Semaine de mise à jour de maintenance du 25 au 31 janvier 2026

#### Approbations

**Le widget Mes approbations affiche les approbations terminées.**

Lorsqu’une personne consulte son widget Mes approbations dans l’Accueil, le widget inclut les épreuves qui ont déjà été approuvées.

+++

+++**Semaine de mise à jour de maintenance du 18 au 24 janvier 2026**

### Semaine de mise à jour de maintenance du 18 au 24 janvier 2026

#### Demandes

**Problèmes liés aux brouillons dans la nouvelle expérience de demande**

Les problèmes suivants ont été signalés concernant les brouillons dans la nouvelle expérience de demande :

* Les demandes créées en tant que brouillon, puis envoyées, n’affichent que la première lettre de l’objet dans la liste des demandes.
* Les brouillons ignorés ne sont pas supprimés de la liste des requêtes,

#### Plannings

**Impossible de voir les exceptions des années précédentes**

Lorsque l’utilisateur consulte le calendrier des exceptions et tente de consulter les années précédentes, il ne peut pas consulter les années précédentes.

+++

+++**Semaine de mise à jour de maintenance du 11 au 17 janvier 2026**

### Semaine de mise à jour de maintenance du 11 au 17 janvier 2026

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance Workfront vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mises à jour de maintenance de Workfront Fusion, semaine du 4 au 10 janvier 2026**

### Mises à jour de maintenance, semaine du 4 au 10 janvier 2026

**Erreur d’en-tête manquant sur les modules AWS**

Les modules AWS échouent avec l’erreur suivante :

« En-tête obligatoire manquant pour cette requête »

+++

+++**Mises à jour de maintenance, semaine du 4 au 10 janvier 2026**

### Mises à jour de maintenance, semaine du 4 au 10 janvier 2026

#### Approbations

**Le widget Mes approbations affiche les approbations terminées.**

Lorsqu’une personne consulte son widget Mes approbations dans l’Accueil, le widget inclut les épreuves qui ont déjà été approuvées.

#### Épreuves

**Les modifications du statut des épreuves sont retardées.**

Lorsqu’une décision est prise concernant une épreuve, elle ne s’affiche pas dans la zone Documents d’un projet pendant un maximum de 24 heures. Cela peut prêter à confusion, car le statut indique toujours En attente ou un autre statut obsolète, même si une décision a été prise.

#### Demandes

**Les files d’attente des demandes apparaissent plusieurs fois.**

Lorsqu’une personne commence à créer une demande et qu’elle sélectionne une file d’attente des demandes, celle-ci apparaît plusieurs fois dans la liste déroulante.


+++


## Mises à jour de maintenance précédentes

Les informations relatives aux mises à jour de maintenance précédentes sont disponibles ici :

* [Archive des mises à jour de maintenance de [!DNL Workfront] - 2025](2025-updates.md)
* [Archive des mises à jour de maintenance de [!DNL Workfront] - 2024](2024-updates.md)
* [Archive des mises à jour de maintenance de [!DNL Workfront] - 2023](2023-updates.md)
* [Archive des mises à jour de maintenance d’[!DNL Workfront] - 2022](2022-updates.md)
* [Archive des mises à jour de maintenance de [!DNL Workfront] - 2021](2021-updates.md)
