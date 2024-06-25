---
title: Mises à jour de maintenance pour Workfront
description: Mises à jour de maintenance pour  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 7e617a611bf88f2133ba83746596f6336efa1593
workflow-type: tm+mt
source-wordcount: '4124'
ht-degree: 97%

---

# Mises à jour de maintenance pour [!DNL Workfront]

Les mises à jour de maintenance suivantes ont été effectuées en 2024.

>[!NOTE]
>
>Ces mises à jour incluent également d’autres correctifs mineurs ou moins conséquents. L’assistance [!DNL Workfront] vous avertira lorsqu’un problème que vous avez soumis est résolu.

Pour connaître les mises à jour de maintenance antérieures à 2024, consultez les [Mises à jour de maintenance précédentes](#previous-maintenance-updates).

## Mises à jour de juin 2024

+++**(Planifiée) Mise à jour de maintenance le vendredi 27 juin 2024**

### Mise à jour de maintenance (planifiée) pour le vendredi 27 juin 2024.

#### Rapports

**Le rapport ne se charge pas lorsque la devise par défaut est USD**

Lorsqu’un utilisateur tente d’afficher un rapport dont la devise par défaut est le dollar américain (USD), le rapport ne se charge pas.

#### Mises à jour

**Le lien copié ne se colle pas correctement**

Si un utilisateur copie un lien d’une mise à jour en cliquant avec le bouton droit de la souris et en sélectionnant &quot;[!UICONTROL Copier l’adresse du lien]&quot;, colle ensuite le lien dans une mise à jour ; le lien ne se colle pas correctement. Seule la première partie du lien est un lien et le reste de l’URL est ignoré.

Copie du lien à l’aide d’une autre méthode &quot;[!UICONTROL Copier l’adresse du lien]&quot; permet au lien de se coller comme prévu.

#### Utilisateurs

**Utilisateurs manquants lors d’affectations en bloc**

Lorsqu’une personne tente d’effectuer des affectations en masse et qu’une fonction est attribuée à la tâche, les personnes occupant cette fonction n’apparaissent pas dans la liste et la personne qui les affecte ne peut pas les sélectionner.

Ce comportement a également été signalé dans l’équilibreur de charge de travail.

+++

+++**Mise à jour de maintenance le vendredi 20 juin 2024**

### Mise à jour de maintenance le vendredi 20 juin 2024

#### Navigation

**Le bouton Retour ne revient pas à la page précédente**

Lorsqu’un utilisateur ou une utilisatrice de Workfront clique sur le bouton Retour de son navigateur, l’une des situations suivantes peut se produire.

* Le nom de l’onglet du navigateur change, mais la page ne change pas. Le fait de cliquer à nouveau sur le bouton Retour peut résoudre le problème.
* La personne est dirigée vers la page de destination de son navigateur.

#### Épreuves

**Impossible de fermer la visionneuse de BAT**

Lorsqu’un utilisateur ou une utilisatrice consulte une épreuve dans la visionneuse de relecture et tente de fermer l’épreuve en cliquant sur le X dans le coin supérieur droit, l’épreuve ne se ferme pas.

+++

+++**Mise à jour de maintenance le vendredi 13 juin 2024**

### **Mise à jour de maintenance le vendredi 13 juin 2024**

#### Groupes

**Impossible d’ajouter un sous-groupe**

Lorsqu’une personne tente d’ajouter un sous-groupe existant à un groupe, le bouton Enregistrer ne fonctionne pas et le sous-groupe n’est pas ajouté.

+++

+++ **Mise à jour de maintenance le 6 juin 2024**

### Mise à jour de maintenance le 6 juin 2024

#### Formulaires personnalisés dans mon groupe

**Limitation des champs natifs dans le créateur de formulaire**

Plusieurs champs natifs sont désormais pris en charge sur les formulaires personnalisés créés dans le créateur de formulaire. Auparavant, la limite était d’un champ natif par formulaire.

+++

## Mises à jour de mai 2024

+++ **Mise à jour de maintenance le 30 mai 2024**

### Mise à jour de maintenance le 30 mai 2024

#### Formulaires personnalisés dans mon groupe

Erreur lors de la modification des champs de texte descriptif

Lorsqu’une personne tente de modifier le texte descriptif sur un formulaire personnalisé, le texte n’est pas enregistré et l’erreur suivante s’affiche :

« La valeur de clé en double viole la contrainte unique. »

Ce problème a été signalé dans le créateur hérité de formulaires.

#### Mises à jour

**Copier et coller une mention ne notifie pas la personne mentionnée.**

Lorsqu’une personne copie un commentaire qui comprend une mention au format @, puis colle ce commentaire dans la zone Mises à jour d’un autre objet, la personne mentionnée n’est pas informée du commentaire collé.

+++

+++ **Mise à jour de maintenance le 23 mai 2024**

### Mise à jour de maintenance le 23 mai 2024

#### Rapports

Lorsqu’une personne consulte un rapport et clique sur le bouton Précédent du navigateur, l’un des événements suivants peut se produire :

* La personne reste sur la page Rapport.
* La personne est dirigée vers la page de destination du navigateur.
* La personne est dirigée vers la page de connexion.

Cela concerne le navigateur Chrome :

#### Mises à jour

**La personne taguée ne peut pas voir qui l’a taguée.**

Lorsqu’une personne est taguée dans une mise à jour, elle ne peut pas voir qui l’a taguée. Cela se produit lorsque le paramètre « Les personnes d’autres entreprises ne devraient pouvoir visualiser que les utilisateurs de... » est défini sur « Leur entreprise ».

**Mises à jour : taguer une personne avec @ dans le panneau Résumé ne fonctionne pas.**

Lorsqu’une personne tente de taguer une autre personne à l’aide de @ dans la zone Mises à jour d’un panneau Résumé, cliquer sur le nom de la personne dans la liste déroulante ne fonctionne pas. La deuxième tentative fonctionne toutefois comme prévu.

+++

+++**Mise à jour de maintenance le 16 mai 2024**

### Mise à jour de maintenance le 16 mai 2024

#### Configuration

**Les statuts des problèmes par défaut ne figurent pas dans certains types de problèmes dans la Configuration**

Lorsqu’une personne consulte les statuts des problèmes dans la Configuration, elle constate que les statuts par défaut (nouveaux, en cours et terminés) sont absents de certains types de problèmes. Les statuts par défaut ne proposent pas l’option de modifier le type de problème. La personne ne peut donc pas reconfigurer les statuts à afficher pour les types de problèmes concernés.

#### Utilisateurs

**Impossible de supprimer des utilisateurs et utilisatrices.**

Il est impossible de supprimer des utilisateurs et utilisatrices. Ce problème a été signalé dans les organisations qui ont migré vers Adobe Admin Console.

+++

+++**Mise à jour de maintenance le 9 mai 2024**

### Mise à jour de maintenance le 9 mai 2024

Cette mise à jour inclut uniquement des correctifs mineurs ou moins importants. L’assistance [!DNL Workfront] vous avertira lorsqu’un problème que vous avez soumis sera résolu.

+++

+++**Mise à jour de maintenance le 2 mai 2024**

### Mise à jour de maintenance le 2 mai 2024

#### Heure de connexion

**Impossible de modifier les heures sur les tâches ou les problèmes**

Lorsqu’un utilisateur ou une utilisatrice tente de modifier les heures sur une tâche ou un problème, les modifications ne sont pas enregistrées.

+++

## Mises à jour d’avril 2024

+++**Mise à jour de maintenance le 25 avril 2024**

### Mise à jour de maintenance le 25 avril 2024

#### Mises à jour

**Les listes numérotées ne sont pas numérotées correctement.**

Lorsqu’un utilisateur ou une utilisatrice envoie un commentaire contenant une liste numérotée, cette liste affiche une numérotation incorrecte dans la mise à jour.

Cela a été signalé dans la nouvelle expérience de commentaire.

**Le texte n’est pas conservé lorsque vous quittez le site et y revenez pour commenter.**

Lorsqu’une personne écrit un commentaire qui comprend une @mention, qu’elle quitte puis revient au commentaire avant de l’envoyer, tout le texte saisi après @mention est absent du brouillon du commentaire.

Cela a été signalé dans la nouvelle expérience de commentaire.

+++

+++**Mise à jour de maintenance le 18 avril 2024**

### Mise à jour de maintenance le 18 avril 2024

#### Agile

**Les cartes Kanban n’affichent pas les champs personnalisés.**

Lorsqu’un utilisateur ou une utilisatrice consulte un panorama Kanban configuré pour inclure des champs personnalisés, ces champs personnalisés peuvent ne pas s’afficher.

#### Calendriers

**Erreur lors de l’actualisation du calendrier**

Lorsqu’un utilisateur ou une utilisatrice affiche un calendrier et actualise la page, une erreur « Oups » s’affiche. Les données du calendrier s’affichent comme prévu, mais peuvent être masquées par le message d’erreur.

#### Formulaires personnalisés dans mon groupe

**Les champs de recherche externes ne renvoient pas de résultats.**

Lorsqu’un champ de recherche externe fait référence à un champ à sélection multiple pour lequel une seule valeur est sélectionnée, le champ ne renvoie pas la valeur.

Par exemple, si un champ de recherche externe fait référence à un champ à sélection multiple pour lequel les valeurs « rouge » et « bleu » sont sélectionnées, le champ fonctionne comme prévu. Si seule la valeur « rouge » du champ est sélectionnée, le champ de recherche externe ne renvoie aucune valeur.

#### Projets

**Impossible de convertir le problème en projet si l’épreuve web est jointe.**

Lorsqu’un problème est associé à une épreuve web (une épreuve d’URL utilisant un lien d’un fournisseur de documents externe tel que SharePoint) et qu’un utilisateur ou une utilisatrice tente de convertir ce problème en projet, la conversion échoue et le projet n’est pas créé. L’utilisateur ou l’utilisatrice voit l’erreur suivante :

« Un problème est survenu lors de la copie du fichier (GUID du fichier). Supprimez le fichier ou contactez l’assistance et réessayez. »

+++

+++**Mise à jour de maintenance le 11 avril 2024**

### Mise à jour de maintenance le 11 avril 2024

#### Recherche

**Impossible de modifier à partir de la recherche**

Lorsqu’une personne utilise la recherche avancée et tente de modifier ou de modifier en masse les résultats de la recherche, l’icône Modifier ne répond pas.

#### Mises à jour

**La prévisualisation de l’image dans les mises à jour est floue.**

Lorsqu’un utilisateur ou une utilisatrice affiche les mises à jour et clique sur la loupe d’une image pour la prévisualiser, la prévisualisation qui s’ouvre est extrêmement floue et pixellisée.

Si l’utilisateur ou l’utilisatrice télécharge l’image, celle-ci s’affiche à la résolution attendue.

**Message « [!UICONTROL Nous ne pouvons pas publier votre commentaire.] » lors de la réponse**

Lorsqu’un utilisateur ou une utilisatrice tente de répondre à un message dans la nouvelle expérience de commentaire, la réponse n’est pas enregistrée et le message suivant s’affiche :

« [!UICONTROL Nous ne pouvons pas publier votre commentaire maintenant. Patientez un instant, puis réessayez.] »

+++

+++**Mise à jour de maintenance le 4 avril 2024**

### Mise à jour de maintenance le 4 avril 2024

#### Recherche

**Impossible de modifier à partir de la recherche**

Lorsqu’une personne utilise la recherche avancée et tente de modifier ou de modifier en masse les résultats de la recherche, l’icône Modifier ne répond pas.

#### Mises à jour

**La prévisualisation de l’image dans les mises à jour est floue.**

Lorsqu’un utilisateur ou une utilisatrice affiche les mises à jour et clique sur la loupe d’une image pour la prévisualiser, la prévisualisation qui s’ouvre est extrêmement floue et pixellisée.

Si l’utilisateur ou l’utilisatrice télécharge l’image, celle-ci s’affiche à la résolution attendue.

**Message « [!UICONTROL Nous ne pouvons pas publier votre commentaire.] » lors de la réponse**

Lorsqu’un utilisateur ou une utilisatrice tente de répondre à un message dans la nouvelle expérience de commentaire, la réponse n’est pas enregistrée et le message suivant s’affiche :

« [!UICONTROL Nous ne pouvons pas publier votre commentaire maintenant. Patientez un instant, puis réessayez.] »

+++

+++**Mise à jour de maintenance le 4 avril 2024**

### Mise à jour de maintenance le 4 avril 2024

#### Intégrations

**Documents non joints lors de la création d’une requête à partir d’[!DNL Outlook]**

Lorsqu’un utilisateur ou une utilisatrice crée une requête à partir d’[!DNL Outlook], les documents joints à l’e-mail ne sont pas joints à la requête.

Ceci a été signalé pour les types de pièces jointes suivants :

XLS
PDF

#### Heure de connexion

**La personne ne peut pas consigner les heures pour le jour en cours.**

Lorsqu’une personne tente de consigner les heures dans la zone Mises à jour, le jour en cours est grisé et l’action est impossible.

#### Mises à jour

<!--no article-->

**Erreur lors de l’affichage des commentaires**

Lorsqu’une personne tente d’afficher des commentaires dans la nouvelle expérience de commentaire, elle ne peut pas voir les commentaires, mais voit plutôt l’erreur suivante :

« Un problème est survenu. Réessayez plus tard. »

L’expérience de commentaire héritée fonctionne comme prévu.

+++

## Mises à jour de mars 2024

+++**Mise à jour de maintenance le 28 mars 2024**

### Mise à jour de maintenance le 28 mars 2024

#### Intégrations

**Documents non joints lors de la création d’une requête à partir d’[!DNL Outlook]**

Lorsqu’un utilisateur ou une utilisatrice crée une requête à partir d’[!DNL Outlook], les documents joints à l’e-mail ne sont pas joints à la requête.

Ceci a été signalé pour les types de pièces jointes suivants :

XLS
PDF

#### Épreuves

**Les épreuves restent sur le widget Mes approbations.**

Une épreuve qui doit disparaître du widget Mes approbations reste sur le widget. Cela peut se produire lorsque plusieurs utilisateurs et utilisatrices prennent des décisions sur une épreuve en même temps, ou qu’un utilisateur ou une utilisatrice prend une décision et la modifie rapidement.

#### Gestion des ressources

**Incohérence dans les heures budgétées**

Les heures budgétées affichées dans l’une des zones suivantes peuvent ne pas correspondre à celles affichées dans une autre de ces zones :

* Business case
* Rapports
* Outil de budgétisation des ressources

#### Tâches

**L’info-bulle de la tâche antérieure n’affiche pas le nom de la tâche.**

Lorsqu’un utilisateur ou une utilisatrice consulte une liste de tâches et passe la souris sur l’icône d’une tâche antérieure pour obtenir davantage d’informations, l’info-bulle qui s’affiche n’affiche pas le nom de la tâche antérieure.

#### Mises à jour

**Les commentaires de document n’apparaissent pas dans les mises à jour de l’objet parent.**

Lorsqu’une personne fait un commentaire sur un document, ce commentaire n’apparaît pas immédiatement dans la zone Mises à jour de l’objet parent du document.

Le problème a été signalé dans la nouvelle expérience de commentaire. Les commentaires s’affichent dans l’expérience de commentaire héritée comme prévu.

**Taguer une personne ne fonctionne pas**

Lorsqu’une personne est balisée dans un commentaire, ce dernier n’est pas visible par la personne. De plus, la personne balisée n’est pas informée du commentaire, que ce soit par e-mail ou par le biais d’une notification in-app.

Ce problème a été signalé dans la nouvelle expérience de commentaire.

+++

+++**Mise à jour de maintenance de Workfront Fusion le 28 mars 2024**

### Mise à jour de maintenance de Workfront Fusion le 28 mars 2024

**RuntimeError avec réponse 200 du module Workfront**

Un module Workfront peut renvoyer une réponse `RuntimeError [200]`. La réponse 200 implique une réponse réussie, mais l’erreur indique que la requête a échoué.

Cela peut se produire si la réponse est extrêmement longue. Les données sont renvoyées à Fusion, mais ne peuvent pas être traitées par Fusion.

+++

+++**Mise à jour de maintenance le 21 mars 2024**

### Mise à jour de maintenance le 21 mars 2024

#### Mises à jour

**Espaces importants entre les lignes**

Lorsqu’un utilisateur ou une utilisatrice saisit une mise à jour avec plusieurs lignes à l’aide des touches Retour ou Entrée, ou colle plusieurs lignes dans une mise à jour, la mise à jour s’affiche comme prévu. Cependant, si un utilisateur ou une utilisatrice affiche ensuite cette mise à jour dans un rapport, il y a de grands espaces entre les lignes.

Cela a été signalé dans la nouvelle expérience de commentaire.

**Taguer une personne avec @ ne fonctionne pas**

Lorsqu’une personne en tague une autre avec le caractère @ dans un commentaire, elle n’est pas ajoutée à la zone des utilisateurs et utilisatrices tagués et ne reçoit pas de notification concernant le commentaire.

Ce correctif s’applique uniquement à la nouvelle expérience de commentaire.

+++

+++**Mise à jour de maintenance le 14 mars 2024**

### Mise à jour de maintenance le 14 mars 2024

#### Épreuves

**Les épreuves créées à partir de documents liés n’ont pas de modèle d’épreuve appliqué.**

Lorsqu’une personne crée une épreuve à partir d’un document lié, le modèle d’épreuve n’est pas correctement appliqué, et des informations peuvent manquer, comme le workflow, par exemple.

Cela s’applique également aux épreuves créées par le biais de l’API et de Workfront Fusion.

#### Utilisateurs

**Niveaux d’accès inférieurs non disponibles lors de la création d’un utilisateur ou d’une utilisatrice**

Lorsqu’un utilisateur ou une utilisatrice crée une autre personne, seul son premier niveau d’accès est disponible pour le nouvel utilisateur ou la nouvelle utilisatrice. Tous les niveaux d’accès avec des autorisations inférieures à celles de la personne à l’origine de la création doivent être disponibles pour être affectés au nouvel utilisateur ou à la nouvelle utilisatrice.

+++

+++**Mise à jour de maintenance le 7 mars 2024**

### Mise à jour de maintenance le 7 mars 2024

#### Panneaux

**Erreur 400 lors de l’ajout d’une tâche à un panorama**

Lorsqu’un utilisateur ou utilisatrice consulte un projet et tente d’ajouter une tâche à un panorama, la tâche n’est pas ajoutée et l’utilisateur ou l’utilisatrice voit s’afficher l’erreur suivante :

Erreur : « 400 : /boards-service/graphql non défini ».

#### Page d’accueil

**Erreur lors de la modification en ligne d’une tâche dans le widget Ma tâche**

Lorsqu’un utilisateur ou une utilisatrice tente de modifier en ligne une tâche dans le widget Mes tâches, l’erreur suivante s’affiche :

« Une erreur s’est produite et nous travaillons à résoudre le problème. Pour continuer votre travail, essayez d’actualiser cette page du navigateur. »


#### Équilibreur de charge de travail

**Le nombre d’heures prévues n’est pas mis à jour dans l’équilibreur de charge de travail.**

Lorsque le nombre d’heures prévues d’un projet est mis à jour, il n’est pas mis à jour dans l’équilibreur de charge de travail. Cela peut se produire même si la modification est reflétée correctement dans le projet.

+++

+++**Mise à jour de maintenance de Workfront Fusion le 7 mars 2024

**Workfront Proof > Le module de surveillance des épreuves expire.**

Les scénarios qui utilisent le module Workfront Proof > Module de surveillance des BAT peuvent se désactiver en raison de l’expiration du module de surveillance des BAT.

+++

## Mises à jour de février 2024

+++**Mise à jour de maintenance le 29 février 2024**

### Mise à jour de maintenance le 29 février 2024

#### Mises à jour

**Mises à jour : un écran vide s’affiche lorsque vous répondez à un utilisateur ou une utilisatrice d’une autre société**

Lorsqu’un utilisateur ou une utilisatrice tente de répondre à un commentaire d’un utilisateur ou d’une utilisatrice d’une autre société, l’écran devient vide.

Cela est dû au fait que la personne n’est pas autorisée à voir les utilisateurs et utilisatrices d’autres sociétés.

+++

+++**Mise à jour de maintenance le 22 février 2024**

### Mise à jour de maintenance le 22 février 2024

#### Page d’accueil

**[!UICONTROL Accueil] : l’[!UICONTROL espace de travail] et les épingles ne se chargent pas**

Lorsqu’un utilisateur ou une utilisatrice se connecte, les événements suivants peuvent se produire :

* Le nouvel [!UICONTROL espace de travail Accueil] de l’utilisateur ou de l’utilisatrice ne charge pas et affiche l’erreur « [!UICONTROL Nous ne pouvons pas charger vos informations d’espace de travail. Contactez Workfront pour nous aider à comprendre l’erreur et y remédier.] »
* Les épingles de l’utilisateur ou de l’utilisatrice ne se chargent pas et l’erreur « [!UICONTROL Vos épingles ne sont pas disponibles en raison d’une erreur système. Essayez d’actualiser votre navigateur pour résoudre le problème.] »

#### Utilisateurs

**L’administrateur ou l’administratrice de groupes ne peut pas définir ni modifier le niveau d’accès d’un utilisateur ou d’une utilisatrice.**

<!--no article-->

Lorsqu’un administrateur ou une administratrice de groupes tente de modifier le niveau d’accès d’un utilisateur ou d’une utilisatrice, l’un des événements suivants peut se produire :

* Le champ Niveau d’accès est désactivé.
* L’administrateur ou l’administratrice de groupes ne peut pas choisir un niveau d’accès inférieur.

#### Équilibreur de charge de travail

**Libellé pour les heures non travaillées**

L’équilibreur de charge de travail et le calendrier des congés affichent désormais « [!UICONTROL Heures non travaillées] » pendant le congé d’un utilisateur ou d’une utilisatrice. Auparavant, ils affichaient « [!UICONTROL Heures travaillées] » pour les heures non travaillées.

+++

+++**Mise à jour de maintenance le 15 février 2024**

### Mise à jour de maintenance le 15 février 2024

#### Problèmes

**Les champs d’heure enregistrent une heure incorrecte en cas de modification de problèmes en masse**.

Lorsqu’un utilisateur ou une utilisatrice modifie des problèmes en masse et sélectionne une date et une heure pour un champ de date et les enregistre, l’heure enregistrée dans ce champ dans le problème n’est pas l’heure sélectionnée par l’utilisateur ou l’utilisatrice. Au lieu de cela, l’heure semble être convertie au fuseau horaire UTC au moment de l’enregistrement par l’utilisateur ou l’utilisatrice.

#### Tâches

**L’affectation d’une personne à une ou plusieurs tâches est annulée**.

Une tâche peut automatiquement ne plus être affectée à une personne à laquelle elle était affectée. Cela peut se produire pour une ou plusieurs tâches. La fin de cette affectation ne s’affiche pas dans la zone Mises à jour système des tâches, mais dans la section Mise à jour des flux du menu de Configuration.

#### Mises à jour

**L’option Image désactivée est disponible lors de la modification d’un commentaire**.

Quand un administrateur ou une administratrice [!DNL Workfront] désactive l’option permettant d’ajouter des images aux commentaires, cette dernière n’est pas disponible lors de la création d’un commentaire. Cependant, si un utilisateur ou une utilisatrice modifie un commentaire existant, l’option d’image est disponible.

+++

+++**Mise à jour de maintenance le 8 février 2024**

### Mise à jour de maintenance le 8 février 2024

#### Panneaux

**Impossible de déplacer une carte dans une colonne à l’aide des options [!UICONTROL Déplacer]**

Lorsqu’un utilisateur ou une utilisatrice tente de déplacer une carte dans une colonne à l’aide des options [!UICONTROL Haut de la colonne] ou [!UICONTROL Bas de la colonne] du menu à trois points, la carte ne se déplace pas.

**Les cartes persistent lors d’un changement d’itération.**

Lorsqu’un utilisateur ou une utilisatrice consulte une itération sur un panorama, puis modifie l’itération, les cartes qui s’affichent pour la nouvelle itération sont celles d’une itération précédemment consultée par l’utilisateur ou l’utilisatrice.

#### Rapports

**La colonne « Aucune valeur » n’affiche aucun résultat**

Lorsqu’un rapport de graphique comporte un colonne « [!DNL No value] », la colonne n’affiche aucune donnée, même si elle doit en contenir.

#### Gestion des ressources

**Calculs financiers incorrects en raison de problèmes liés à la fonction**

Les heures et les calculs financiers peuvent être incorrects, affichant un coût de 0, même si les heures sont enregistrées dans une fonction avec un taux de dépenses.

Cela est dû au fait que les fonctions créent automatiquement des taux en double sans date de début ou de fin. Comme elles n’ont pas de date de début ou de fin, elles sont traitées comme une valeur de 0 lorsque les calculs financiers sont exécutés.

+++

+++**Mise à jour de maintenance le 1 février 2024**

### Mise à jour de maintenance le 1er février 2024

#### Connexion

**Les personnes utilisant la fonction SSO ne sont pas redirigées vers l’emplacement d’origine lors de la connexion**

Lorsqu’une personne se trouve sur une page de [!DNL Workfront] et se connecte avec l’option SSO, une fois la connexion terminée, elle est redirigée vers la page d’[!UICONTROL accueil] au lieu de la page sur laquelle elle se trouvait avant de se connecter.

#### Modèles

**Erreur lors de la copie de modèles**

Lorsqu’une personne tente de copier un modèle nouveau ou existant, celui-ci n’est pas copié et le message d’erreur suivant s’affiche :

« [!UICONTROL L’ID ne peut pas être nul] »

+++

## Mises à jour de janvier 2024

+++**Mise à jour de maintenance (correctif) le 30 janvier 2024**

### Mise à jour de maintenance (correctif) le 30 janvier 2024

#### Rapports

**Le champ d’API externe n’affiche pas toutes les valeurs disponibles dans les listes et les rapports**

Auparavant, les utilisateurs et utilisatrices pouvaient voir et modifier la valeur sélectionnée d’un champ de recherche externe dans les listes et dans les rapports, mais ne voyaient pas la liste déroulante avec les options provenant de l’API.

Désormais, lorsqu’un champ personnalisé de recherche externe est utilisé dans une liste ou un rapport, la liste déroulante contenant toutes les options de l’API externe est disponible.

+++

+++**Mise à jour de maintenance le 25 janvier 2024**

### Mise à jour de maintenance le 25 janvier 2024

#### Panneaux

**Les cartes ne se déplacent pas vers la colonne appropriée lorsque le statut est modifié**

Lorsque le statut de l’objet lié d’une carte connectée est modifié directement sur l’objet, la carte ne passe pas à la colonne appropriée. Si le statut de l’objet est modifié sur la carte ou si la carte est glissée vers la nouvelle colonne, la carte se comporte comme prévu.

#### Notifications

**Le marquage des notifications comme lues ne persiste pas**

Lorsqu’un utilisateur ou une utilisatrice marque ses notifications comme lues, puis accède à une autre page dans [!DNL Workfront], l’icône de notifications affiche toujours le nombre de notifications non lues qui existaient avant que la personne les marque comme lues et elles apparaissent toujours lorsque cette dernière clique sur l’icône. Cela se poursuit si l’utilisateur ou l’utilisatrice les marque comme lues et accède à une autre page ou revient à la page d’origine.

#### Mises à jour

**Problèmes de balisage dans l’expérience de commentaire héritée**

Lorsqu’une personne est identifiée dans un commentaire de l’expérience de commentaire héritée, les problèmes suivants se produisent :

* Seul son prénom apparaît dans le commentaire
* Son nom n’est pas marqué d’un symbole @
* Son nom n’est pas bleu
* Son nom ne s’affiche pas sous forme de lien vers son profil

La personne reçoit une notification par e-mail concernant la balise, comme prévu.

+++

+++**Mise à jour de maintenance le 18 janvier 2024**

### Mise à jour de maintenance le 18 janvier 2024

#### Panneaux

**Impossible de joindre un document à une carte**

Lorsqu’une personne tente de joindre un document à une carte connectée, elle peut sélectionner le document à joindre, mais ce dernier n’apparaît pas dans la zone de document de la carte et le document n’est pas joint à l’objet auquel la carte est connectée.

Ce fait a été signalé dans les cartes liées aux problèmes.

**La carte apparaît sur plusieurs sprints**.

Lorsqu’une personne consulte un sprint sur les panoramas, les cartes qui se trouvent dans différents sprints apparaissent sur le panorama. Ce problème est intermittent.

**La carte ne se ferme pas lors de l’utilisation de la vue Panoramas dans un projet**.

Lorsqu’un utilisateur ou une utilisatrice utilise la vue Panoramas sur une liste de tâches d’un projet et crée une carte, celle-ci ne se ferme pas et n’est pas enregistrée. Cela empêche l’utilisateur ou l’utilisatrice de revenir au projet.

Pour fermer la carte, l’utilisateur ou l’utilisatrice doit modifier l’URL afin de supprimer le mot « board » et tout ce qui se trouve à droite du mot « board ».

**Les cartes persistent lors d’un changement d’itération.**

Lorsqu’un utilisateur ou une utilisatrice consulte une itération sur un panorama, puis modifie l’itération, les cartes qui s’affichent pour la nouvelle itération sont celles d’une itération précédemment consultée par l’utilisateur ou l’utilisatrice.

**Erreur dans la section [!UICONTROL Commentaires] des cartes**

Lorsqu’un utilisateur ou une utilisatrice consulte une carte et se rend à la section [!UICONTROL Commentaires], les commentaires ne s’affichent pas et un message d’erreur apparaît :

&quot;[!UICONTROL Un problème est survenu. Veuillez réessayer plus tard.]&quot;

**Problèmes lors de l’affichage du statut de sous-tâche**

Les problèmes suivants ont été signalés concernant l’affichage du statut de sous-tâche sur une carte dans Panoramas :

* Le statut s’affiche sous la forme « Sélectionner le statut » même si la tâche a déjà un statut. Ce statut est visible lorsque vous affichez directement la tâche.
* Si l’utilisateur ou l’utilisatrice tente de sélectionner un statut, l’écran devient vide et doit être actualisé.

**« [!UICONTROL Vous n’avez aucun accès] » lors de l’affichage de commentaires sur une carte**.

Lorsqu’un utilisateur ou une utilisatrice tente d’afficher des commentaires sur une carte qui n’est pas connectée à un objet [!DNL Workfront], le message suivant s’affiche.

« [!UICONTROL Vous n’avez pas accès à l’affichage des commentaires sur cet objet.] »

Cela peut se produire même si l’utilisateur ou l’utilisatrice pouvait auparavant voir des commentaires sur la carte.

#### Formulaires personnalisés dans mon groupe

**Impossible d’ajouter ou de supprimer des formulaires personnalisés en bloc sur des tâches de modèle**

Si une personne tente d’ajouter ou de supprimer un formulaire personnalisé en bloc sur une tâche de modèle, ce dernier n’est pas ajouté ni supprimé et l’erreur suivante s’affiche :

[!UICONTROL Réessayons. Paramètre non valide : valeur templateID « XXXXXXXXXXXXXXXX »]

Si la personne localise le modèle avec le GUID spécifié, puis tente d’ajouter ou de supprimer des formulaires personnalisés sur le reste des tâches du modèle, l’erreur se produit avec un autre templateID.

Les formulaires personnalisés peuvent être ajoutés ou supprimés sur une seule tâche de modèle. Cette erreur s’applique uniquement à l’ajout ou à la suppression en bloc.

#### Portefeuilles

**La terminologie personnalisée ne s’applique pas à la page de groupe**.

Lorsqu’un utilisateur ou une utilisatrice définit une terminologie personnalisée au niveau du Portfolio, la terminologie ne s’applique pas à la page au niveau du groupe.

#### Configuration

**Impossible de masquer les statuts facultatifs**

Lorsqu’un utilisateur ou une utilisatrice tente de masquer les statuts facultatifs au niveau du système et du groupe, ces derniers ne sont pas masqués. Si la personne affiche le statut, l’option de masquage n’est pas activée, même si elle l’a activée puis a enregistré les modifications.

**Les statuts des problèmes par défaut ne figurent pas dans certains types de problèmes dans la Configuration**

Lorsqu’une personne consulte les statuts des problèmes dans la Configuration, elle constate que les statuts par défaut (nouveaux, en cours et terminés) sont absents de certains types de problèmes. Les statuts par défaut ne proposent pas l’option de modifier le type de problème. La personne ne peut donc pas reconfigurer les statuts à afficher pour les types de problèmes concernés.

#### Équipes

**Problèmes liés à la définition des statuts de l’équipe pour le bouton [!UICONTROL Terminé]**

Les problèmes suivants ont été signalés concernant les statuts pour le bouton [!UICONTROL Terminé] lors de l’édition ou de la création d’une équipe :

* Certains statuts peuvent ne pas figurer dans la zone du bouton Terminé dans la fenêtre [!UICONTROL Nouvelle équipe] ou dans la section [!UICONTROL Paramètres de l’équipe] d’une équipe existante.
* Si l’utilisateur ou l’utilisatrice tente d’enregistrer l’équipe, le message d’erreur « Vous devez sélectionner au moins un statut dans chaque catégorie. » peut s’afficher.

#### Modèles

**Erreur lorsqu’un modèle est joint à un projet**.

Lorsqu’une personne tente de joindre un modèle à un projet, l’erreur suivante est renvoyée :

« Oups ! Un problème est survenu. Contactez Workfront pour nous aider à comprendre l’erreur et y remédier. »

Cela se produit lorsque la personne ne dispose pas de l’autorisation Afficher pour un formulaire personnalisé associé au modèle.

#### Mises à jour

**Les commentaires ne sont pas transférés entre l’ancienne et la nouvelle expérience**.

Un commentaire effectué dans l’expérience de commentaire héritée peut ne pas être visible dans la nouvelle expérience de commentaire. L’inverse peut également se produire.

+++

+++**Mise à jour de maintenance le 11 janvier 2024**

### Mise à jour de maintenance le 11 janvier 2024

#### Panneaux

**Les cartes terminées ne se chargent pas correctement sur les panoramas dynamiques**

Auparavant, le seul moyen d’inclure le travail terminée sur un panorama dynamique était de charger les cartes en tant que cartes archivées. Sinon, les cartes terminées n’étaient pas du tout chargées sur le panorama. Des problèmes se produisaient alors lors de la recherche de cartes.

Désormais, lors de la création d’un panorama dynamique, les cartes terminées sont chargées par défaut sous forme de cartes archivées. Vous pouvez toutefois sélectionner Ne pas archiver les cartes terminées pour charger toutes les cartes terminées du panorama en tant que cartes visibles dans la colonne Terminé.

+++

## Mises à jour de maintenance précédentes

Les informations relatives aux mises à jour de maintenance précédentes sont disponibles ici :

* [Archive des mises à jour de maintenance de [!DNL Workfront] - 2023](2023-updates.md)
* [Archive des mises à jour de maintenance d’[!DNL Workfront] - 2022](2022-updates.md)
* [Archive des mises à jour de maintenance de [!DNL Workfront] - 2021](2021-updates.md)
