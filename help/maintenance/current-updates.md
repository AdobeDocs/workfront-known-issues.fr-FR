---
title: Mises à jour de maintenance pour Workfront
description: Mises à jour de maintenance pour  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 17e60b281dc05073247083257121d8809a271722
workflow-type: tm+mt
source-wordcount: '1332'
ht-degree: 81%

---

# Mises à jour de maintenance pour [!DNL Workfront]

Les mises à jour de maintenance suivantes ont été effectuées en 2024.

>[!NOTE]
>
>Ces mises à jour incluent également d’autres correctifs mineurs ou moins conséquents. L’assistance [!DNL Workfront] vous avertira lorsqu’un problème que vous avez soumis est résolu.

Pour connaître les mises à jour de maintenance antérieures à 2023, consultez les [Mises à jour de maintenance précédentes](#previous-maintenance-updates).

## Mises à jour de février 2024

+++**Mise à jour de maintenance du vendredi 1 février 2024**

### Mise à jour de maintenance (planifiée) le 1er février 2024

#### Connexion

**Les utilisateurs utilisant la fonction SSO ne sont pas redirigés vers l’emplacement d’origine lors de la connexion**

Lorsqu’un utilisateur se trouve sur une page de [!DNL Workfront] et se connecte avec SSO, une fois la connexion terminée, ils sont redirigés vers [!UICONTROL Accueil] au lieu de la page sur laquelle ils se trouvaient avant de se connecter.

#### Modèles

**Erreur lors de la copie de modèles**

Lorsqu’un utilisateur tente de copier un modèle nouveau ou existant, le modèle ne le copie pas et l’utilisateur voit l’erreur suivante :

&quot;[!UICONTROL ID ne peut pas être nul]&quot;

+++

## Mises à jour de janvier 2024

+++**Mise à jour de maintenance (correctif) le mercredi 30 janvier 2024**

### Mise à jour de maintenance (correctif) le 30 janvier 2024

#### Rapports

**Le champ API externe n’affiche pas toutes les valeurs disponibles dans les listes et les rapports.**

Auparavant, les utilisateurs pouvaient voir la valeur sélectionnée (et la modifier) pour un champ de recherche externe dans les listes et les rapports, mais ne voyaient pas la liste déroulante avec les options provenant de l’API.

Désormais, lorsqu’un champ personnalisé de recherche externe est utilisé dans une liste ou un rapport, la liste déroulante contenant toutes les options de l’API externe est disponible.

+++

+++**Mise à jour de maintenance du vendredi 25 janvier 2024**

### Mise à jour de maintenance du vendredi 25 janvier 2024

#### Panneaux

**Les cartes ne se déplacent pas vers la colonne appropriée lorsque l’état est modifié**

Lorsque le statut de l’objet lié d’une carte connectée est modifié directement sur l’objet, la carte ne passe pas à la colonne appropriée. Si le statut de l’objet est modifié sur la carte ou si la carte est glissée vers la nouvelle colonne, la carte se comporte comme prévu.

#### Notifications

**Le marquage des notifications comme indiqué ne persiste pas**

Lorsqu’un utilisateur ou une utilisatrice marque ses notifications comme lues, puis accède à une autre page dans [!DNL Workfront], l’icône de notifications affiche toujours le nombre de notifications non lues qui existaient avant que la personne les marque comme lues et elles apparaissent toujours lorsque cette dernière clique sur l’icône. Cela se poursuit si l’utilisateur ou l’utilisatrice les marque comme lues et accède à une autre page ou revient à la page d’origine.

#### Mises à jour

**Problèmes liés au balisage dans les commentaires hérités**

Lorsqu’un utilisateur est balisé dans un commentaire dans l’expérience de commentaire héritée, les problèmes suivants se produisent :

* Seul le prénom de l’utilisateur est présent dans le commentaire
* Le nom de l’utilisateur n’est pas marqué d’un symbole @
* Le nom de l’utilisateur n’est pas bleu
* Le nom de l’utilisateur n’est pas un lien vers son profil.

L’utilisateur reçoit une notification par courrier électronique concernant la balise, comme prévu.

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
