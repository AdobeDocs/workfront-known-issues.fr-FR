---
title: Mises à jour de maintenance pour Workfront
description: Mises à jour de maintenance pour  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: e399c45c2bb5782d8d25add9b097cce18205f994
workflow-type: tm+mt
source-wordcount: '2205'
ht-degree: 95%

---

# Mises à jour de maintenance pour [!DNL Workfront]

Les mises à jour de maintenance suivantes ont été effectuées en 2024.

>[!NOTE]
>
>Ces mises à jour incluent également d’autres correctifs mineurs ou moins conséquents. L’assistance [!DNL Workfront] vous avertira lorsqu’un problème que vous avez soumis est résolu.

Pour connaître les mises à jour de maintenance antérieures à 2023, consultez les [Mises à jour de maintenance précédentes](#previous-maintenance-updates).

## Mises à jour de mars 2024

+++**Mise à jour de maintenance le vendredi 14 mars 2024**

### Mise à jour de maintenance le 14 mars 2024

#### Épreuves

**Les BAT créés à partir de documents liés n’ont pas de modèle de BAT appliqué**

Lorsqu’une personne crée une épreuve à partir d’un document lié, le modèle d’épreuve n’est pas correctement appliqué, et des informations peuvent manquer, comme le workflow, par exemple.

Cela s’applique également aux épreuves créées par le biais de l’API et de Workfront Fusion.

#### Utilisateurs

**Niveaux d’accès inférieurs non disponibles lors de la création d’un utilisateur**

Lorsqu’un utilisateur ou une utilisatrice crée une autre personne, seul son premier niveau d’accès est disponible pour le nouvel utilisateur ou la nouvelle utilisatrice. Tous les niveaux d’accès avec des autorisations inférieures à celles de la personne à l’origine de la création doivent être disponibles pour être affectés au nouvel utilisateur ou à la nouvelle utilisatrice.

+++

+++**Mise à jour de maintenance le vendredi 7 mars 2024**

### Mise à jour de maintenance le 7 mars 2024

#### Panneaux

**Erreur 400 lors de l’ajout d’une tâche à un panorama**

Lorsqu’un utilisateur ou utilisatrice consulte un projet et tente d’ajouter une tâche à un panorama, la tâche n’est pas ajoutée et l’utilisateur ou l’utilisatrice voit s’afficher l’erreur suivante :

Erreur : &quot;400 : undefined /Panneaux-service/graphql&quot;

#### Page d’accueil

**Erreur lors de la modification en ligne d’une tâche dans le widget Ma tâche**

Lorsqu’un utilisateur tente de modifier en ligne une tâche dans le widget Mes tâches, l’erreur suivante s’affiche :

&quot;Une erreur s&#39;est produite et nous travaillons à résoudre le problème. Pour continuer votre travail, essayez d’actualiser cette page du navigateur. »


#### Équilibreur de charge de travail

**Les heures planifiées ne sont pas mises à jour dans l’équilibreur de charge**

Lorsque le nombre d’heures prévues d’un projet est mis à jour, il n’est pas mis à jour dans l’équilibreur de charge de travail. Cela peut se produire même si la modification est reflétée correctement dans le projet.

+++

Mise à jour de maintenance de la fusion Workfront le 7 mars 2024

**Bon à tirer Workfront > délai d’expiration du module BAT**

Les scénarios qui utilisent le module Workfront Proof > Module de surveillance des BAT peuvent se désactiver en raison de l’expiration du module de surveillance des BAT.

+++

## Mises à jour de février 2024

+++**Mise à jour de maintenance du vendredi 29 février 2024**

### Mise à jour de maintenance du vendredi 29 février 2024

#### Mises à jour

**Mises à jour : un écran vide s’affiche lorsque vous répondez à un utilisateur ou une utilisatrice d’une autre société**

Lorsqu’un utilisateur ou une utilisatrice tente de répondre à un commentaire d’un utilisateur ou d’une utilisatrice d’une autre société, l’écran devient vide.

Cela est dû au fait que la personne n’est pas autorisée à voir les utilisateurs et utilisatrices d’autres sociétés.

+++

+++**Mise à jour de maintenance du vendredi 22 février 2024**

### Mise à jour de maintenance du vendredi 22 février 2024

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

+++**Mise à jour de maintenance du vendredi 15 février 2024**

### Mise à jour de maintenance du vendredi 15 février 2024

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

+++**Mise à jour de maintenance du vendredi 8 février 2024**

### Mise à jour de maintenance du 8 février 2024

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

+++**Mise à jour de maintenance du vendredi 1 février 2024**

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

+++**Mise à jour de maintenance (correctif) le mercredi 30 janvier 2024**

### Mise à jour de maintenance (correctif) le 30 janvier 2024

#### Rapports

**Le champ d’API externe n’affiche pas toutes les valeurs disponibles dans les listes et les rapports**

Auparavant, les utilisateurs et utilisatrices pouvaient voir et modifier la valeur sélectionnée d’un champ de recherche externe dans les listes et dans les rapports, mais ne voyaient pas la liste déroulante avec les options provenant de l’API.

Désormais, lorsqu’un champ personnalisé de recherche externe est utilisé dans une liste ou un rapport, la liste déroulante contenant toutes les options de l’API externe est disponible.

+++

+++**Mise à jour de maintenance du vendredi 25 janvier 2024**

### Mise à jour de maintenance du vendredi 25 janvier 2024

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

+++**Mise à jour de maintenance du vendredi 18 janvier 2024**

### Mise à jour de maintenance du vendredi 18 janvier 2024

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

+++**Mise à jour de maintenance du vendredi 11 janvier 2024**

### Mise à jour de maintenance du vendredi 11 janvier 2024

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
