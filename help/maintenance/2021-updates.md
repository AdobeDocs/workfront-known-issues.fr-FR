---
title: Mises à jour de maintenance pour Workfront en 2021
description: Historique des mises à jour de maintenance pour  [!DNL Adobe Workfront] en 2021
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
source-git-commit: 7fa90198186a7b0f392683d432a7da0424943da2
workflow-type: ht
source-wordcount: '10019'
ht-degree: 100%

---

# Mises à jour de maintenance pour [!DNL Workfront] en 2021

Les mises à jour de maintenance suivantes ont été effectuées en 2021 :

## Mises à jour de décembre 2021

+++**Mise à jour de maintenance le 23 décembre 2021**

**Les nouvelles tâches renvoient par défaut une contrainte de tâche incorrecte**

_Tâches_

Lorsque l’utilisateur crée une tâche à l’aide du bouton &quot;[!UICONTROL Nouvelle tâche]&quot; alors que l’option [!UICONTROL Date de début par défaut de la nouvelle tâche] est définie sur &quot;[!UICONTROL Aujourd’hui]&quot;, la contrainte de tâche de la tâche créée est définie sur &quot;[!UICONTROL Dès que possible]&quot; plutôt que sur &quot;[!UICONTROL Ne pas démarrer avant]&quot;. Cela peut également se produire lors de l’utilisation de modèles de projet.

**L’ouverture d’un planning dans la zone des [!UICONTROL Groupes] fait apparaître une page vierge**

_Configuration_

Lorsque l’utilisateur consulte des groupes dans la zone [!UICONTROL Configuration] et tente d’ouvrir, de modifier ou de copier un planning, le planning ne s’ouvre pas et une page vierge s’affiche.

**Les modifications ne s’affichent pas lors de la réorganisation du panneau de navigation de gauche**

_Navigation_

Lorsque l’utilisateur tente de réorganiser le panneau de navigation de gauche en faisant glisser un élément, cet élément retourne à son emplacement précédent lorsque l’utilisateur le lâche. Si l’utilisateur actualise la page, le panneau de gauche affiche le nouvel ordre.

**Le lien permettant de soumettre un document demandé mène à une page vierge.**

_Documents_

Lorsque l’utilisateur reçoit une demande de soumission de documents et clique sur le lien menant vers l’objet où le document a été demandé, une page vierge s’affiche. Cela peut se produire en cliquant sur un lien dans un e-mail ou dans une notification in-app.

L’**[!UICONTROL équilibreur de charge de travail] indique qu’aucune heure n’est affectée**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur consulte l’[!UICONTROL équilibreur de charge de travail] avec le paramètre &quot;[!UICONTROL Afficher les dates prévues]&quot; activé, toutes les futures dates indiquent 0 heure affectée.

**Les épreuves disparaissent des dossiers par intermittence**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur est connecté et [!DNL Workfront Proof]consulte un dossier, celui-ci semble vide. Si l’utilisateur revient plus tard consulter les informations, les épreuves sont visibles.

+++

+++**Mise à jour de maintenance le 16 décembre 2021**

**Cliquer sur l’annonce dans la liste de notifications mène à une page vierge**

_Notifications_

Lorsque l’utilisateur ouvre sa liste de notifications depuis l’icône [!UICONTROL Notifications], puis clique sur une annonce, une page vierge apparaît et l’annonce ne s’affiche pas.

**Le panneau de résumé indique &quot;[!UICONTROL Aucune sélection]&quot; lorsque la tâche est sélectionnée**

_Tâches_

Lorsque l’utilisateur ouvre un résumé du document dans la zone [!UICONTROL Documents] d’un projet, puis passe à la liste des tâches, sélectionne une tâche et tente d’ouvrir le résumé de la tâche, le résumé de la tâche ne s’affiche pas et le message suivant apparaît :

[!UICONTROL Aucune sélection. Sélectionnez un document dans la liste pour afficher les détails.]

Le message mentionne des documents même si l’utilisateur figure dans la liste des tâches.

La zone **[!UICONTROL Tâches non affectées] ne se charge pas**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur crée un filtre dans l’[!UICONTROL Équilibreur de charge de travail] à l’aide du champ [!UICONTROL Affectation : ID de rôle], la zone [!UICONTROL Tâches non affectées] ne se charge pas.

**Joindre un modèle avec l’option &quot;[!UICONTROL Personnaliser et joindre]&quot; efface les valeurs de champ personnalisées**

_Projets_

Si l’utilisateur joint un modèle à un projet avec l’option &quot;[!UICONTROL Personnaliser et joindre]&quot; et qu’un formulaire personnalisé est déjà joint au projet, les valeurs des champs personnalisés ne sont pas transférées et doivent être saisies une nouvelle fois manuellement. Cela se produit même lorsque le formulaire personnalisé inclus au modèle est identique.

+++

+++**Mise à jour de maintenance (correctif) le 10 décembre 2021**

Erreur **[!UICONTROL Oups] lorsqu’un modèle est joint à un projet existant**

_Projets_

Lorsque l’utilisateur tente de joindre un modèle à un projet existant, le modèle n’est pas joint et le message d’erreur suivant apparaît :

&quot;[!UICONTROL Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.]&quot;

+++

+++**Mise à jour de maintenance le 9 décembre 2021**


**Le panneau de navigation de gauche réduit se développe au moment du chargement de la page**

_Navigation_

Lorsque l’utilisateur réduit le panneau navigation de gauche puis actualise la page, le panneau de navigation de gauche redevient développé sur la page actualisée. Le panneau de navigation de gauche redevient également développé si l’utilisateur ouvre une page dans un nouvel onglet.

L’**[!UICONTROL équilibreur de charge de travail] indique qu’aucune heure n’est affectée**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur consulte l’[!UICONTROL équilibreur de charge de travail] avec le paramètre &quot;[!UICONTROL Afficher les dates prévues]&quot; activé, toutes les futures dates indiquent 0 heure affectée.

+++

+++**Mise à jour de maintenance le 8 décembre 2021**

**L’approbation se réinitialise lors de la mise à jour**

_Approbations_

Lorsque l’utilisateur prend une décision à propos d’une approbation avec l’en-tête de l’objet puis met immédiatement à jour l’objet, les icônes d’approbation réapparaissent dans l’en-tête et la décision d’approbation n’est pas enregistrée.

**[!UICONTROL Impossible de modifier sur la ligne une affectation dans un rapport]**

_Rapports_

Lorsque l’utilisateur tente de modifier sur la ligne une affectation dans un rapport, la valeur du champ ne change pas et la modification n’est pas enregistrée.


+++

+++**Mise à jour de maintenance le 2 décembre 2021**

**Barre oblique supplémentaire ajoutée lors de la saisie manuelle de l’URL**

_Demandes_

Lorsque l’utilisateur remplit une demande et commence la saisie manuelle d’une URL, une barre oblique supplémentaire est ajoutée au début de l’URL. Cette barre oblique ne peut pas être supprimée.

**Impossible de retirer les sections personnalisées du panneau de navigation de gauche**

_Navigation_

Lorsque l’utilisateur tente de retirer une section personnalisée du panneau de navigation de gauche en cliquant sur le X près de cette section, elle n’est pas supprimée.

**Les Tâches non affectées ne se chargent pas**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur crée un filtre dans l’[!UICONTROL Équilibreur de charge de travail] à l’aide du champ [!UICONTROL Affectation : ID de rôle], la zone [!UICONTROL Tâches non affectées] ne se charge pas.

**Des pages ne se chargent pas dans certains navigateurs**

_[!DNL Workfront]_

Lorsque l’utilisateur travaille sur les pages [!DNL Workfront], elles ne se chargent pas et le message d’erreur suivant apparaît :

&quot;[!UICONTROL Une erreur s’est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d’actualiser cette page de navigateur.]&quot;

Cela a été signalé dans

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Cette erreur se produit de manière aléatoire et peut affecter n’importe quelle zone de [!DNL Workfront].

+++


## Mises à jour de novembre 2021

+++**Mise à jour de maintenance le 18 novembre 2021**

Erreur &quot;[!UICONTROL ClientID ou clientSecret non valide]&quot; sur **[!DNL Workfront]pour [!DNL Jira] au moment de la connexion**

_Intégrations Workfront_

Des utilisateurs ont été déconnectés du [!DNL Jira] pour l’intégration Workfront. L’utilisateur ne peut pas se connecter à l’intégration [!DNL Workfront for Jira] et le message d’erreur suivant apparaît :

&quot;[!UICONTROL ClientID ou clientSecret non valide]&quot;

**Le formulaire personnalisé joint à la demande ne se met pas à jour lorsqu’une nouvelle rubrique de file d’attente est sélectionnée**

_Demandes_

Lorsque l’utilisateur crée une demande et sélectionne une rubrique de file d’attente qui joint automatiquement un formulaire personnalisé à la demande, puis sélectionne une autre rubrique de file d’attente, le formulaire personnalisé de la première rubrique de file d’attente reste joint à la demande.

**Les icônes ne s’affichent pas correctement**

_[!DNL Workfront]_

Les images des icônes ne s’affichent pas correctement. Cela a été signalé dans de nombreuses zones de [!UICONTROL Workfront].

**Les tâches ne sont pas exportées au format PDF lorsque l’option &quot;Autres tailles&quot; est sélectionnée.**

_Tâches_

Si l’utilisateur tente d’exporter une liste de tâches au format PDF et sélectionne l’option &quot;[!UICONTROL Autres tailles]&quot;, il peut sélectionner une taille et cliquer sur [!UICONTROL Exporter], mais la liste n’est pas exportée. Aucun message d’erreur et aucune indication que l’exportation a échoué ne s’affiche.

**L’indicateur d’image ne s’affiche pas dans les notifications par e-mail**

_Notifications_

Lorsque l’utilisateur ajoute une image à une mise à jour et qu’un e-mail de notification est envoyé au destinataire de la mise à jour, l’e-mail n’inclut aucun indicateur de la présence d’une image dans la mise à jour.

**Des pages ne se chargent pas dans certains navigateurs**

_[!DNL Workfront]_

Lorsque l’utilisateur travaille sur les pages [!DNL Workfront], elles ne se chargent pas et le message d’erreur suivant apparaît :

&quot;[!UICONTROL Une erreur s’est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d’actualiser cette page de navigateur.]&quot;

Cela a été signalé dans

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Cette erreur se produit de manière aléatoire et peut affecter n’importe quelle zone de Workfront.

+++

+++**Mise à jour de maintenance le 11 novembre 2021**

**Problème au niveau des intégrations de documents, page vierge dans la fenêtre contextuelle de chargement du document[!DNL Google Drive*]*

_Documents_

Lorsque l’utilisateur tente d’ajouter un nouveau document provenant de [!DNL Google Drive] à [!DNL Workfront] en utilisant [!UICONTROL Ajouter nouveau] > [!UICONTROL Depuis [!DNL Google Drive]], l’écran contextuel de chargement reste vierge.

**Impossible d’utiliser plusieurs filtres dans l’équilibreur de charge de travail**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur tente d’utiliser plusieurs filtres dans l’[!UICONTROL équilibreur de charge de travail], il rencontre les problèmes suivants :

* Si l’utilisateur sélectionne deux filtres, seul le filtre inférieur est appliqué.
* Si l’utilisateur sélectionne plus de deux filtres, aucun résultat ne s’affiche.

**L’en-tête du document &quot;[!UICONTROL Dossiers du projet]&quot; est absent de la zone des documents du projet**

_Projets_

Lorsque l’utilisateur consulte les documents du projet dans un projet, l’en-tête &quot;[!UICONTROL Dossiers du projet]&quot; est absent du panneau de navigation de gauche. La flèche de la liste déroulante apparaît toujours, et l’utilisateur peut sélectionner un dossier.

**Les colonnes du tableau kanban sont trop larges et ne peuvent pas être modifiées.**

_Agile_

Lorsque l’utilisateur consulte un tableau kanban à plusieurs colonnes, celles-ci sont trop larges et il doit faire défiler l’écran pour afficher ou déplacer les cartes dans les colonnes les plus à droite. La largeur des colonnes ne peut pas être modifiée ; par conséquent, l’utilisateur ne peut pas réduire les colonnes afin qu’elles soient toutes visibles à l’écran en même temps.

**Interface améliorée pour la création d’une nouvelle équipe**

_Équipes_

La création d’équipes est désormais plus intuitive, avec de nouveaux repères visuels. Lorsque l’icône [!UICONTROL Changer d’équipe] est sélectionnée sur n’importe quelle page d’équipe, le lien [!UICONTROL Créer une nouvelle équipe] comporte une icône indiquant &quot;[!UICONTROL nouvelle]&quot; et le lien est séparé du reste de la liste afin de ne pas être confondu avec un nom d’équipe. Cette interface est identique pour les équipes agiles et non agiles.

+++

+++**Mise à jour de maintenance le 4 novembre 2021**

**Les nouvelles tâches renvoient par défaut une contrainte de tâche incorrecte**

_Tâches_

Lorsque l’utilisateur crée une tâche à l’aide du bouton &quot;[!UICONTROL Nouvelle tâche]&quot; alors que l’option Date de début par défaut de la nouvelle tâche est définie sur &quot;[!UICONTROL Aujourd’hui]&quot;, la contrainte de tâche de la tâche créée est définie sur &quot;[!UICONTROL Dès que possible]&quot; plutôt que sur &quot;[!UICONTROL Ne pas démarrer avant]&quot;.

**Les champs ne s’affichent pas sur les cartes des Stories agiles**

_Agile_

Lorsque l’utilisateur consulte un Storyboard agile, les cartes affichent uniquement les champs [!UICONTROL Description] et [!UICONTROL Statut]. Aucun autre champ, y compris les champs personnalisés, n’apparaît.

**Les cartes reviennent dans la colonne d’origine avant de passer à une nouvelle colonne**

_Agile_

Lorsque l’utilisateur fait glisser une carte dans une nouvelle colonne du Storyboard, il voit la carte qui se déplace. Lorsqu’il la lâche dans la nouvelle colonne, elle apparaît toutefois brièvement dans sa colonne d’origine avant de s’afficher dans sa nouvelle colonne.

**Valeurs non disponibles pour les champs personnalisés dans le filtre**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur tente de créer un filtre à l’aide d’un champ personnalisé, la valeur de ce champ personnalisé ne s’affiche pas et ne peut pas être saisie dans le filtre.

**Des pages ne se chargent pas dans le navigateur [!DNL Firefox]**

_[!DNL Workfront]_

Lorsque l’utilisateur travaille dans [!DNL Workfront] à l’aide du navigateur [!DNL Firefox], les pages ne se chargent pas et le message d’erreur suivant apparaît :

&quot;[!UICONTROL Une erreur s’est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d’actualiser cette page de navigateur.]&quot;

Cette erreur se produit de manière aléatoire et peut affecter n’importe quelle zone de [!DNL Workfront].

**Erreur liée à la date lors de la création d’un projet à partir d’un modèle**

_Modèles_

Si l’utilisateur crée un projet à partir d’un modèle et définit le mode de planification sur [!UICONTROL Date de début], puis sélectionne une contrainte de tâche et tente de créer le projet, celui-ci n’est pas créé et un message d’erreur basé sur la contrainte de tâche apparaît.

La boîte de dialogue **[!UICONTROL Exporter le graphique Gantt] ne répond pas**

_Graphique Gantt_

Si l’utilisateur tente d’exporter le [!UICONTROL graphique Gantt] et sélectionne l’option &quot;[!UICONTROL Ce qui apparaît à l’écran]&quot; et qu’il se trouve dans la nouvelle expérience [!DNL Workfront], le [!UICONTROL graphique Gantt] n’est pas exporté et la boîte de dialogue ne répond pas. L’utilisateur ne peut ni fermer ni cliquer en dehors de la boîte de dialogue.

**Les icônes ne s’affichent pas correctement**

_[!DNL Workfront]_

Les images des icônes ne s’affichent pas correctement. Cela a été signalé dans plusieurs situations, y compris sans s’y limiter :

* Des images des fonctions ou des groupes de tâches lors du partage d’un objet
* Des icônes à gauche et à droite des rapports de calendrier
* Le tri des icônes sur les colonnes du rapport

**Ajout de cases à cocher aux demandes dans la section [!UICONTROL Soumises] de la zone des [!UICONTROL Demandes]**

_Demandes_

Nous avons ajouté des cases à cocher à gauche des noms de demande dans la [!UICONTROL Liste des demandes soumises] de la zone des [!UICONTROL Demandes]. Cela facilite la sélection d’une demande et l’affichage d’informations supplémentaires.

**Les trimestres personnalisés sont désormais compatibles avec les filtres de l’équilibreur de charge de travail**

_[!UICONTROL Équilbreur de charge de travail]_

Les filtres de l’[!UICONTROL équilibreur de charge de travail] sont désormais compatibles avec les trimestres personnalisés.

**Mise à jour de l’opérateur de filtre pour le champ Durée dans les filtres de l’équilibreur de charge de travail**

_[!UICONTROL Équilbreur de charge de travail]_

Nous avons mis à jour les opérateurs de filtre lors du filtrage des zones de l’[!UICONTROL équilibreur de charge de travail] en fonction de leur [!UICONTROL Durée].

+++


## Mises à jour d’octobre 2021

+++**Mise à jour de maintenance le 28 octobre 2021**

**[!UICONTROL Accueil] et [!UICONTROL Mes tâches] affichent une page vierge**

_[!UICONTROL Accueil]/[!UICONTROL Mes tâches]_

Lorsque l’utilisateur accède à [!UICONTROL Accueil] ou Mes tâches, une page vierge s’affiche.

**Impossible d’afficher ni de modifier les détails du [!UICONTROL Groupe de rubriques]**

_Demandes_

Lorsque l’utilisateur tente d’afficher ou de modifier les détails d’un groupe de rubriques, la page qui s’ouvre affiche &quot;[!UICONTROL Détails du groupe de rubriques]&quot;dans l’en-tête, mais tout le reste est vierge.

**Les boutons radio devant rester vides sont remplis automatiquement**

_Demandes_

Lorsque l’utilisateur envoie une demande avec un champ de bouton radio obligatoire et qu’aucune valeur n’a été sélectionnée pour ce champ avant de soumettre la demande, la première valeur est automatiquement sélectionnée lors de l’envoi de la demande.

+++

+++**Mise à jour de maintenance le 21 octobre 2021**

**Impossible d’ajouter un filtre dans l’[!UICONTROL équilibreur de charge de travail]**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur tente d’ajouter un filtre dans l’[!UICONTROL équilibreur de charge de travail], le panneau [!UICONTROL Ajouter un filtre] s’ouvre, mais son contenu ne se charge pas, et l’utilisateur ne peut pas ajouter le filtre.

**Le scrum board agile n’affiche aucune Story**

_Agile_

Lorsque l’utilisateur tente d’afficher le scrum board dans l’itération d’une équipe, le scrum board apparaît vierge.

**Le storyboard scrum est vierge lorsque des filtres sont utilisés**

_Agile_

Lorsque l’utilisateur tente de consulter un storyboard scrum avec un filtre autre que le filtre &quot;[!UICONTROL Toute l’équipe]&quot;, un écran vierge s’affiche. L’utilisateur ne peut pas revenir au filtre &quot;[!UICONTROL Toute l’équipe]&quot;.

**Les listes ne sont visibles que sur une petite partie de l’écran.**

_Listes_

Lorsque l’utilisateur tente de consulter une liste avec un navigateur [!DNL Safari] sur un [!DNL Mac] qui utilise le [!DNL Big Sur OS], la liste n’apparaît que sur une petite partie de l’écran. L’utilisateur peut faire défiler la liste, mais la partie est parfois si petite qu’il est difficile, voire impossible de lire la liste.

**Les boutons radio devant rester vides sont remplis automatiquement**

_Demandes_

Lorsque l’utilisateur envoie une demande avec un champ de bouton radio obligatoire et qu’aucune valeur n’a été sélectionnée pour ce champ avant de soumettre la demande, la première valeur est automatiquement sélectionnée lors de l’envoi de la demande.

+++

+++**Mise à jour de maintenance (correctif) le 21 octobre 2021**

**[!UICONTROL Accueil] et [!UICONTROL Mes tâches] affichent une page vierge**

_[!UICONTROL Accueil]/[!UICONTROL Mes tâches]_

Lorsque l’utilisateur accède à [!UICONTROL Accueil] ou [!UICONTROL Mes tâches], une page vierge s’affiche.

+++

+++**Mise à jour de maintenance le 20 octobre 2021**

L’**[!UICONTROL équilibreur de charge de travail] est défini comme option de planification par défaut**

_[!UICONTROL Équilbreur de charge de travail]_

Si l’utilisateur avec le [!UICONTROL Planificateur] défini sur les valeurs par défaut tente de l’utiliser, il constate que l’[!UICONTROL équilibreur de charge de travail] a été défini sur les valeurs par défaut.

+++

+++**Mise à jour de maintenance (correctif) le 19 octobre 2021**

**Impossible d’affecter une demande au moment de sa création**

_Demandes_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] crée une demande et tente d’affecter un utilisateur en saisissant son nom dans le champ [!UICONTROL Affectations], la liste déroulante n’apparaît pas dans le champ et l’utilisateur ne peut pas sélectionner le nom de la personne affectée.

**Le storyboard scrum est vierge lorsque des filtres sont utilisés**

_Agile_

Lorsque l’utilisateur tente de consulter un storyboard scrum avec un filtre autre que le filtre &quot;[!UICONTROL Toute l’équipe]&quot;, un écran vierge s’affiche. L’utilisateur ne peut pas revenir au filtre &quot;[!UICONTROL Toute l’équipe]&quot;.

+++

+++**Mise à jour de maintenance le 14 octobre 2021**

**Les modèles partagés à l’échelle du système ne sont pas visibles**

_Modèles_

Lorsque l’utilisateur crée un projet et tente d’utiliser un modèle qui a été partagé à l’échelle du système, il ne voit pas le modèle dans la liste des modèles disponibles et ne peut pas l’utiliser.

**Erreur lors de la création de projets à partir de modèles**

_Modèles_

Lorsque l’utilisateur tente de créer un projet à partir d’un modèle contenant un formulaire personnalisé avec une section visible uniquement par les administrateurs, la création du projet est impossible et le message suivant apparaît :

&quot;[!UICONTROL Catégorie avec valeur(s) de clé primaire &#39;xxxxxxxxxxxxxxxx&#39; introuvable]&quot;

**Mise à jour des liens pour copier et déplacer les tâches**

_Tâches_

Les liens permettant de copier et de déplacer les tâches ont été mis à jour et sont passés à &quot;[!UICONTROL Copier vers]&quot; et &quot;[!UICONTROL Déplacer vers]&quot;, à la fois sur la page de la tâche et dans la liste de tâches.

**Suppression de la limite de recherche de fonction lors du remplacement du taux de facturation d’un projet**

Fonctions

REMARQUE : cette mise à jour se trouve actuellement dans l’environnement de prévisualisation et entrera en production avec la publication de la production 22.1. Consultez &quot;Aperçu de la publication 22.1&quot; pour en savoir plus.

Le remplacement des taux de facturation des fonctions dans un projet recherche désormais toutes les fonctions dans le système.

Auparavant, [!DNL Workfront] recherchait des fonctions dans les 2 000 premiers rôles, par ordre alphabétique.

+++

+++**Mise à jour de maintenance le 7 octobre 2021**

**[!UICONTROL Les notifications in-app disparaissent du ]centre de notifications**

_Notifications_

Lorsque l’utilisateur consulte le centre de notification, certaines notifications auparavant visibles ne le sont plus. Dans certains cas, la notification peut disparaître avant que l’utilisateur ne la voie.

**Les annonces ne sont pas visibles sur la page [!UICONTROL Toutes les annonces]**

_Notifications_

Lorsque l’utilisateur ouvre la page [!UICONTROL Toutes les annonces] de la zone des [!UICONTROL Notifications], aucune annonce n’est visible dans les zones suivantes :

* [!UICONTROL Boîte de réception]
* [!UICONTROL Favoris]
* [!UICONTROL Brouillons]
* [!UICONTROL Supprimé]

**Erreur lors de l’affectation dans l’[!UICONTROL équilibreur de charge de travail]**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur tente une affectation dans l’[!UICONTROL Équilibreur de charge de travail], la tâche n’est pas affectée et le message d’erreur suivant apparaît :

&quot;[!UICONTROL Une erreur s’est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d’actualiser cette page de navigateur.]&quot;

+++


## Mises à jour de septembre 2021

+++**Mise à jour de maintenance le 30 septembre 2021**

**Erreur lors de la navigation rapide à ou depuis l’[!UICONTROL Accueil]**

_Page d’accueil_

Lorsque l’utilisateur navigue rapidement à ou depuis l’[!UICONTROL Accueil], la page ne se charge pas et le message d’erreur suivant apparaît :

&quot;[!UICONTROL Une erreur s’est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d’actualiser cette page de navigateur.]&quot;

Cela peut également se produire en naviguant vers l’[!UICONTROL Accueil] depuis une épingle.

+++

+++**Mise à jour de maintenance le 23 septembre 2021**

Erreur **[!UICONTROL Accès refusé] lors de l’affichage des tickets soumis à[!DNL Workfront]**

_Événements_

Lorsque l’utilisateur ayant soumis un ticket à [!DNL Workfront] tente de l’afficher, le message d’erreur suivant apparaît :

&quot;[!UICONTROL Accès refusé : Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.]&quot;

**Le résumé de l’analyse de rentabilité indique des valeurs incorrectes**

_Projets_

Lorsque l’utilisateur consulte le panneau résumant l’[!UICONTROL Analyse de rentabilité], les valeurs affichées ne reflètent pas les valeurs dans chacune des sections de l’[!UICONTROL Analyse de rentabilité].

**Les en-têtes des colonnes ne correspondent pas aux colonnes des listes.**

_Configuration_

Lorsque l’utilisateur se trouve dans la zone [!UICONTROL Configuration] et affiche une liste, telle que celle des [!UICONTROL Formulaires personnalisés] ou des [!UICONTROL Niveaux d’accès], les en-têtes des colonnes de cette liste ne correspondent pas aux colonnes de la liste.

**Les utilisateurs ne disposant pas des autorisations de partage adéquates peuvent joindre des formulaires personnalisés à des objets.**

_Formulaires personnalisés_

Lorsqu’un formulaire personnalisé apparaît dans la nouvelle expérience [!DNL Adobe Workfront] est défini de manière à être visible à l’échelle du système, tous les utilisateurs peuvent joindre ce formulaire personnalisé à un objet. Ils devraient cependant être uniquement en mesure de consulter le formulaire personnalisé et non pas le joindre à un objet, sauf s’il a été partagé spécifiquement avec eux.

+++

+++**Mise à jour de maintenance le 16 septembre 2021**

**Modification impossible des groupes**

_Groupes_

Lorsque l’utilisateur tente de modifier ou de supprimer un groupe, celui-ci n’est ni modifié ni supprimé, et le message suivant apparaît :

&quot;[!UICONTROL Réessayons. Groupe avec valeur(s) de clé primaire &quot;(ID du groupe)&quot; introuvable]&quot;

L’**[!UICONTROL optimisateur de portfolio] n’affiche aucun projet**

_Portefeuilles_

Lorsque l’utilisateur tente de consulter les projets dans l’[!UICONTROL optimisateur de portfolio], la liste des projets ne s’affiche pas et l’utilisateur ne peut donc pas interagir avec aucun d’eux.

+++

+++**Mise à jour de maintenance (correctif) le 10 septembre 2021**

**Date et heure affichées au format UTC lors de la modification sur la ligne**

_Listes_

Lorsque l’utilisateur modifie une date ou une heure sur la ligne (dans une liste d’objets), la date et l’heure sont affichées au format UTC. La date et l’heure ne sont pas affichées au format UTC dans [!DNL Workfront]. Ce problème affecte uniquement l’affichage, et non les données réelles.

**Le texte ne s’affiche pas de la bonne couleur lorsqu’une mise en forme conditionnelle est appliquée**

_Rapports_

Lorsque l’utilisateur consulte un rapport avec une mise en forme conditionnelle modifiant la couleur du texte, la couleur du texte ne change pas à l’écran.

+++

+++**Mise à jour de maintenance le 9 septembre 2021**

**Les événements n’affichent pas les détails de l’événement**

_Page d’accueil_

Lorsque l’utilisateur sélectionne un événement dans la [!UICONTROL Liste de travail] dans la nouvelle expérience [!DNL Adobe Workfront], certains champs sont vides dans l’aperçu du panneau de droite. Lorsque l’utilisateur ouvre l’événement et consulte les [!UICONTROL Détails de l’événement], ces champs contiennent toutefois des valeurs.

**Les utilisateurs ont besoin des autorisations de niveau Contribution pour afficher la section [!UICONTROL Approbations] dans la nouvelle expérience Workfront**

_Approbations_

Les utilisateurs ont besoin des autorisations de niveau [!UICONTROL Contribution] sur un objet pour afficher la section [!UICONTROL Approbations] dans la nouvelle expérience [!DNL Workfront]. Ils ne devraient avoir besoin que des autorisations de niveau [!UICONTROL Vue] pour consulter l’onglet [!UICONTROL Approbations] lorsqu’il existe un processus d’approbation sur l’objet.

Erreur **[!UICONTROL Oups] lors de l’utilisation de filtres**

_Listes_

Lorsque l’utilisateur tente d’utiliser l’un des filtres suivants :

* [!UICONTROL Tous les projets]
* [!UICONTROL Projets auxquels je participe]
* [!UICONTROL Mes tâches actuelles]

la liste devient vide et le message d’erreur suivant apparaît :

&quot;[!UICONTROL Réessayons.]&quot;

La section **[!UICONTROL Tâches] devient vide lors de la modification sur la ligne**

_Modèles_

Lorsque l’utilisateur tente de modifier des tâches sur la ligne dans un modèle en utilisant une vue qui inclut le champ &quot;[!UICONTROL Affecter à : Nom]&quot; et que l’affectation contient un utilisateur, la section [!UICONTROL Tâches] devient vide et l’utilisateur ne peut pas modifier les tâches de modèle.

**Exportation impossible de l’[!UICONTROL optimisateur de portfolio]**

_Portefeuilles_

Lorsque l’utilisateur tente d’exporter l’[!UICONTROL optimisateur de portfolio] et clique sur n’importe quelle option d’exportation, l’[!UICONTROL optimisateur de portfolio] n’est pas exporté.

**Les notifications de réponse ne sont pas envoyées**

_Notifications_

Lorsque l’utilisateur répond à une mise à jour dans [!DNL Workfront], les autres utilisateurs participant au fil de commentaire ne reçoivent aucune notification.

**Les modifications apportées aux données personnalisées entraînent un décalage**

_Champs personnalisés_

Lorsque l’utilisateur modifie des données personnalisées qui déclenchent des modifications d’autres données affichées, le chargement des modifications est lent.

**L’icône de regroupement &quot;[!UICONTROL Tout réduire ou tout développer]&quot; ne s’affiche pas**

_Rapports_

L’icône &quot;[!UICONTROL Tout réduire ou tout développer]&quot; ne s’affiche pas dans l’en-tête d’une liste ou d’un rapport lorsque des regroupements sont appliqués à la liste ou au rapport.

Les options **[!UICONTROL Vérifier] et [!UICONTROL Annuler] n’apparaissent pas lorsque l’affectation de tâche est modifiée**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur tente de modifier l’affectation de tâche pour une tâche et que la période de cette tâche atteint ou dépasse le bord visible de la page, les boutons [!UICONTROL Vérifier] et [!UICONTROL Annuler] n’apparaissent pas et l’utilisateur ne peut ni enregistrer ni annuler les modifications d’affectation.

**L’ajout d’un champ personnalisé sur l’[!UICONTROL Accueil] fait disparaître certaines données de champ**

_[!UICONTROL Page d’accueil]_

Lorsqu’un champ personnalisé est ajouté sur l’[!UICONTROL Accueil], les données d’autres champs commencent à disparaître et à s’afficher incorrectement.

**Impossible d’afficher des éléments liés lors de la connexion en tant qu’autre utilisateur**

_Intégrations_

Si l’administrateur a tenté d’afficher les éléments liés depuis un fournisseur externe alors qu’il était connecté en tant qu’autre utilisateur, il n’a pas pu ouvrir les dossiers liés et il n’a pas pu afficher les éléments.

+++

+++**Mise à jour de maintenance le 2 septembre 2021**

**Impossible d’épingler le tableau de bord personnalisé**

_Tableaux de bord_

Lorsque l’utilisateur tente d’épingler un tableau de bord personnalisé, le tableau de bord n’est pas épinglé et le message d’erreur suivant apparaît :

&quot;[!UICONTROL Un problème est survenu au moment d’épingler cet élément. Contactez [!DNL Workfront] pour remédier à l’erreur.]&quot;

**[!DNL Workfront Proof]Le résumé d’impression est vide**

[!DNL Workfront Proof]

Lorsque l’utilisateur ouvre le résumé d’impression pour imprimer une épreuve, l’en-tête s’affiche, mais le résumé lui-même est vide.

+++


## Mises à jour d’août 2021

+++**Mise à jour de maintenance le 26 août 2021**

**Le texte d’en-tête des colonnes apparaît sur un arrière-plan gris foncé dans [!DNL Safari]**

_Listes_

Le texte d’en-tête des colonnes apparaît sur un arrière-plan gris foncé dans le navigateur [!DNL Safari]. Ce problème n’apparaît dans aucun autre navigateur pris en charge.

**Erreur inattendue lors de la définition des prédécesseurs**

_Tâches_

Lorsque l’utilisateur tente de définir une tâche en tant que prédécesseur en la modifiant sur la ligne, le prédécesseur n’est pas défini et le message suivant apparaît :

&quot;[!UICONTROL Une erreur inattendue s’est produite]&quot;

+++

+++**Mise à jour de maintenance le 19 août 2021**

**Les filtres enregistrés disparaissent après la sélection d’un filtre qui n’affiche aucun événement**

_Listes_

Les filtres enregistrés disparaissent dans une liste d’événements après la sélection d’un filtre qui n’affiche aucun résultat.

**Les événements n’affichent pas les détails de l’événement**

Résumé de l’_[!UICONTROL Accueil]_

Lorsque l’utilisateur sélectionne un événement dans la [!UICONTROL Liste de travail] dans la [!DNL Adobe Workfront Classic], certains champs sont vides dans l’aperçu du panneau de droite. Lorsque l’utilisateur ouvre l’événement et consulte les [!UICONTROL Détails de l’événement], ces champs contiennent toutefois des valeurs.

+++

+++**Mise à jour de maintenance le 12 août 2021**

**Impossible de personnaliser la vue agile du projet**

_Agile_

Lorsque l’utilisateur tente de personnaliser une vue agile existante d’un projet, la fenêtre se ferme et l’utilisateur ne peut pas modifier la vue.

**Le nom ne change pas dans les nouvelles versions du document.**

_Documents_

Lorsque l’utilisateur charge une nouvelle version d’un document, le nom du document ne s’adapte pas au nom de la version la plus récente.

**L’icône du prédécesseur n’est pas verte lorsque le prédécesseur est terminé**

_Tâches_

Lorsqu’une tâche comporte une tâche précédente et que celle-ci est terminée, l’icône de prédécesseur de la tâche dépendante ne devient pas verte.

Lorsqu’un formulaire personnalisé apparaît dans la nouvelle expérience [!DNL Adobe Workfront] est défini de manière à être visible à l’échelle du système, tous les utilisateurs peuvent joindre ce formulaire personnalisé à un objet. Ils devraient cependant être uniquement en mesure de consulter le formulaire personnalisé et non pas le joindre à un objet, sauf s’il a été partagé spécifiquement avec eux.

+++

+++**Mise à jour de maintenance (correctif) le 6 août 2021**

**Impossible de sélectionner les calendriers dans les paramètres du calendrier [!DNL Outloo]k**

_Page d’accueil_

Lorsque l’utilisateur consulte son Calendrier [!DNL Outlook] dans l’accueil de la nouvelle expérience [!DNL Workfront] et ouvre les paramètres, les cases à cocher pour sélectionner les calendriers n’apparaissent pas. Si l’utilisateur clique sur l’emplacement de la case à cocher, le calendrier réagit comme si la case était bien là.

**Impossible d’autoriser de nouveau ou de vérifier la connexion à [!UICONTROL Webdam]**

_[!DNL Workfront Fusion]_

Les utilisateurs d’[!DNL Adobe Workfront Fusion] avec des scénarios connectés à [!UICONTROL Webdam] doivent savoir que les connexions à [!UICONTROL Webdam] exigent une réauthentification manuelle tous les 14 jours. L’API [!UICONTROL Webdam] ne prend pas en charge la réautorisation automatique pour le moment.

+++

+++**Mise à jour de maintenance le 5 août 2021**

**Impossible d’interagir avec le document dans le [!UICONTROL panneau de résumé] ni dans le menu [!UICONTROL Plus]**

_Documents_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] consulte un document et tente d’effectuer une sélection dans le [!UICONTROL panneau de résumé] ou le menu [!UICONTROL Plus], le document est désélectionné et le [!UICONTROL panneau de résumé] ou le menu [!UICONTROL Plus] se vident.

Pas de bouton **[!UICONTROL Nouvelle demande]**

_Demandes_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] accède à la page [!UICONTROL Demande], le bouton [!UICONTROL Nouvelle demande] ne s’affiche pas et il ne peut soumettre aucune demande.

**Les utilisateurs ne disposant pas des autorisations de partage adéquates peuvent joindre des formulaires personnalisés à des objets.**

_Formulaires personnalisés_

Lorsqu’un formulaire personnalisé apparaît dans la nouvelle expérience [!DNL Adobe Workfront] est défini de manière à être visible à l’échelle du système, tous les utilisateurs peuvent joindre ce formulaire personnalisé à un objet. Ils devraient cependant être uniquement en mesure de consulter le formulaire personnalisé et non pas le joindre à un objet, sauf s’il a été partagé spécifiquement avec eux.

**Impossible de modifier les paramètres d’épreuve lors de la création d’une nouvelle épreuve**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur crée une épreuve et tente d’en modifier les paramètres, celui-ci revient au paramètre précédent.

Le **[!UICONTROL storyboard] ne se charge pas correctement**

_Agile_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] accède à un [!UICONTROL storyboard], le chargement du tableau peut prendre jusqu’à 10 secondes. Ce long temps de chargement est dû au chargement de toutes les cartes par le système, alors qu’il ne devrait charger que 50 cartes à la fois.

+++


## Mises à jour de juillet 2021

+++**Mise à jour de maintenance (correctif) le 29 juillet 2021**

**Impossible de charger la nouvelle épreuve ni la nouvelle version de l’épreuve**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur tente de charger une nouvelle épreuve ou une nouvelle version d’une nouvelle épreuve dans l’expérience [!DNL Workfront] classique, la page de la nouvelle épreuve ou de la nouvelle version est vierge et l’utilisateur ne peut pas télécharger l’épreuve ni la version.

+++

+++**Mise à jour de maintenance le 29 juillet 2021**

Les pages **[!UICONTROL Activité dans l’épreuve] et [!UICONTROL Paramètres de la visionneuse d’épreuve] restent toujours disponibles**

_[!DNL Workfront Proof]_

Les pages [!UICONTROL Activité dans l’épreuve] et [!UICONTROL Paramètres de la visionneuse d’épreuve] restent maintenant toujours visibles, même si l’utilisateur n’a pas accès à la mise à jour de ces pages.

Auparavant, lorsque l’utilisateur disposant d’un profil d’autorisation d’épreuve personnalisé ouvrait un document, les pages [!UICONTROL Activité dans l’épreuve] et [!UICONTROL Paramètres de la visionneuse d’épreuve] sur la gauche n’étaient pas systématiquement visibles.

**Message d’erreur lors de l’utilisation de l’option [!UICONTROL Pourcentage] pour les [!UICONTROL Heures affectées]**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur sélectionne l’option [!UICONTROL Pourcentage] pour les [!UICONTROL Heures affectées] et que des tâches sont répertoriées dans la section [!UICONTROL Tâches non affectées], le message d’erreur suivant apparaît :

&quot;[!UICONTROL Une erreur s’est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d’actualiser cette page de navigateur.]&quot;

+++

+++**Mise à jour de maintenance le 22 juillet 2021**

**Les nouveaux noms de version d’épreuve sont tronqués**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur télécharge la nouvelle version d’une épreuve dont le nom du fichier contient un point dans [!DNL Adobe Workfront Classic], la fin du nom du fichier est tronquée.

+++

+++**Mise à jour de maintenance (correctif) le 19 juillet 2021**

**Erreur lors de la tentative de navigation vers des projets, des feuilles de temps, des tâches ou des programmes**

Dans la nouvelle expérience [!DNL Adobe Workfront], lorsque l’utilisateur tente d’accéder à des projets, des feuilles de temps, des tâches ou des programmes, il rencontre un message d’erreur &quot;[!UICONTROL Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.]&quot;

+++

+++**Mise à jour de maintenance le 15 juillet 2021**

**La priorité par défaut des nouvelles demandes est incorrecte**

_Demandes_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] crée une demande, celle-ci ne respecte pas la priorité par défaut définie dans les [!UICONTROL Préférences du projet], et elle ne peut pas être modifiée avant l’envoi de la demande.

Le lien **[!UICONTROL Accéder à l’épreuve] ne renvoie pas vers un commentaire**

_Notifications par e-mail_

Lorsque l’utilisateur reçoit une notification par e-mail concernant un commentaire d’épreuve et qu’il clique sur [!UICONTROL Accéder à l’épreuve], il est redirigé vers le mauvais commentaire dans l’épreuve ou n’est redirigé vers aucun commentaire.

**Les valeurs de champ Rich Text ne sont pas transférées après la conversion d’un événement en tâche**

_Formulaires personnalisés_

Lorsque l’utilisateur convertit un événement en tâche, et qu’un formulaire personnalisé contenant une valeur saisie dans un champ de texte au format Rich Text est joint à l’événement, la valeur du champ de texte n’est pas transférée après la conversion.

**Les valeurs de champ personnalisé changent après la sélection**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] crée une nouvelle épreuve et saisit une valeur dans certains champs personnalisés d’une épreuve, la valeur de certains champs précédents revient aux valeurs par défaut sans prendre en compte la valeur saisie par l’utilisateur.

La saisie semi-automatique **[!UICONTROL Affecter à] ne fonctionne pas**

_[!UICONTROL Page d’accueil]_

Lorsque l’utilisateur dans [!DNL Adobe Workfront Classic] crée un projet, une tâche ou une demande dans la zone [!UICONTROL Accueil], le champ de saisie semi-automatique [!UICONTROL Affecter à] ne renseigne pas les noms d’utilisateur.

**Les heures ne sont pas correctement arrondies**

_Feuilles de temps_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] accède aux [!UICONTROL Feuilles de temps] > [!UICONTROL Toutes les feuilles de temps], il constate que le nombre total d’heures pour certaines feuilles de temps est arrondi à une décimale au lieu d’incréments de 0,25. Le nombre total d’heures indiqué sur la feuille de temps individuelle est toutefois correct. Par exemple, dans la zone Toutes les feuilles de temps, une feuille de temps affiche un total de 44,8 heures, mais lorsque la feuille est ouverte, elle indique un total de 44,75 heures.

**Impossible de déléguer les approbations**

_[!UICONTROL Page d’accueil]_

Lorsque l’utilisateur dans [!DNL Adobe Workfront Classic] clique sur [!UICONTROL Déléguer mes approbations] dans la zone [!UICONTROL Accueil], et qu’il commence à saisir le nom de l’utilisateur auquel il tente de déléguer, aucun résultat ne s’affiche dans la liste de [!UICONTROL saisie semi-automatique] et il ne peut sélectionner aucun utilisateur.

La vue des **[!UICONTROL graphiques Gantt] n’est pas disponible pour les rapports de tâches**

_Rapports_

REMARQUE : cela affecte également les rapports de projet.

Lorsque l’utilisateur ouvre un rapport de tâche dans la nouvelle expérience [!DNL Adobe Workfront], l’option permettant de sélectionner un [!UICONTROL graphique Gantt] n’apparaît pas sur la barre d’outils du rapport. Si la vue du [!UICONTROL graphique Gantt] est sélectionnée pour s’afficher par défaut dans le rapport, un format de liste s’affiche à sa place.

**Cliquer sur [!UICONTROL Voir plus] sur le rapport ne charge rien**

_Tableaux de bord_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] consulte un rapport dans un tableau de bord et clique sur le bouton [!UICONTROL Voir plus], rien ne se passe et il ne peut pas afficher tous les éléments du rapport.

+++

+++**[!DNL Adobe Workfront Fusion]Mise à jour de maintenance le 1 juillet 2021**

**Impossible de copier des modules**

_[!DNL Adobe Workfront Fusion]_

Lorsque l’utilisateur sélectionne plusieurs modules et tente de les copier et de les coller, les modules ne sont pas collés.

+++

+++**Mise à jour de maintenance le 1 juillet 2021**

**Les couleurs définies pour les cartes ne sont pas respectées**

_Kanban_

Lorsque l’utilisateur définit des couleurs spécifiques pour les cartes spécifiques dans les paramètres de l’équipe de la nouvelle expérience [!DNL Adobe Workfront], les cartes kanban ne changent pas de couleur.

**Impossible de coller du texte dans le champ de message personnalisé**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur crée une nouvelle épreuve dans la [!UICONTROL visionneuse de relecture Web] et tente de coller du texte dans le champ [!UICONTROL Message] de la section [!UICONTROL Notification par e-mail], il ne parvient pas à coller le texte. Cela semble uniquement se produire lorsque le texte a un format de paragraphe particulier, et qu’un saut de paragraphe est présent.

**Les demandes sont soumises avec des champs obligatoires vides**

_Demandes_

Lorsque l’utilisateur crée et soumet une demande, les informations contenues dans les champs obligatoires ne l’accompagnent pas.

Pas de bouton **[!UICONTROL Nouvelle demande]**

_Demandes_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] accède à la page [!UICONTROL Demande], le bouton [!UICONTROL Nouvelle demande] ne s’affiche pas et il ne peut soumettre aucune demande.

**Erreur lors du développement d’un formulaire personnalisé**

_Projets_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] tente de développer un formulaire personnalisé joint à un projet, il ne parvient pas à ouvrir le formulaire personnalisé et le message d’erreur suivant apparaît : &quot;[!UICONTROL Une erreur s’est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d’actualiser cette page de navigateur.]&quot; Actualiser la page ne résout pas le problème.

L’image de marque **[!DNL Adobe Workfront]apparaît désormais dans les e-mails du centre d’annonce**

E-mails

À mesure que l’image de marque [!DNL Adobe Workfront] est déployée dans toute l’application, les mises à jour suivantes ont été apportées aux e-mails du centre d’annonce :

* Le lion [!DNL Adobe Workfront] a été ajouté à la zone de contenu principale.
* Le logo [!DNL Adobe Workfront] a été ajouté au pied de page.

À l’avenir, cette image de marque sera présente sur d’autres types d’e-mails provenant de Workfront.

+++


## Mises à jour de juin 2021

+++**Mise à jour de maintenance le 24 juin 2021**

**Impossible de modifier une équipe**

_Agile_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] clique sur [!UICONTROL Modifier] pour ouvrir la page d’équipe [!DNL Edit] pour une équipe agile, la page se charge, puis les paramètres disparaissent et elle se vide.

**Données supprimées d’une demande soumise**

_Demandes_

Lorsque l’utilisateur remplit une demande dans la nouvelle expérience [!DNL Adobe Workfront], les valeurs qu’il a entrées pour certains champs personnalisés disparaissent une fois la demande soumise, parfois même les champs obligatoires.

**Les colonnes ne s’affichent pas**

_Kanban_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] ajoute une colonne personnalisée [!UICONTROL Champs supplémentaires] à un tableau kanban, plus aucun en-tête de colonne ne s’affiche sur le tableau.

+++

+++**[!DNL Adobe Workfront Fusion]Mise à jour de maintenance le 23 juin 2021**

**Suppression du lien périmé dans les e-mails de notification**

_[!DNL Adobe Workfront Fusion]_

Nous avons supprimé le lien menant aux paramètres de notification des e-mails de notification [!DNL Adobe Workfront Fusion].
Pour plus d’informations sur la modification des paramètres de notification, consultez les organisations et les équipes [!DNL Adobe Workfront Fusion].

+++

+++**Mise à jour de maintenance le 17 juin 2021**

La vue des **[!UICONTROL graphiques Gantt] n’est pas disponible pour le rapport de tâches**

_Rapports_

Lorsque l’utilisateur ouvre un rapport de tâche dans la nouvelle expérience [!DNL Adobe Workfront], l’option permettant de sélectionner un [!UICONTROL graphique Gantt] n’apparaît pas sur la barre d’outils du rapport. Si la vue du [!UICONTROL graphique Gantt] est sélectionnée pour s’afficher par défaut dans le rapport, un format de liste s’affiche à sa place.

**L’erreur de limite de caractères ne survient pas lorsque les demandes sont soumises**

_Demandes_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] tente de soumettre une demande avec un champ dépassant la limite de caractères, la demande ne s’envoie pas et aucun message d’erreur n’apparaît. L’avertissement &quot;plus de [!UICONTROL [nombre] caractères&quot; apparaît dans [!DNL Adobe Workfront Classic], et lorsque l’utilisateur tente de soumettre la demande, le message d’erreur &quot;Points suivants à vérifier : saisissez 2 000 caractères au maximum (vous avez saisi [nombre] caractères).]&quot; apparaît.

+++

+++**Mise à jour de maintenance le 10 juin 2021**

**Les tâches de modèle réorganisées ne sont pas déplacées**

_Modèles_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] fait glisser une tâche de modèle vers un nouvel emplacement dans une liste, le nombre de tâches de modèle est mis à jour, mais la liste n’est pas réorganisée.

**Les tâches enfants ne sont pas sélectionnées avec les tâches parents**

_Modèles_

Lorsque l’utilisateur sélectionne une tâche parente dans un projet créé à partir d’un modèle, les tâches enfants ne sont pas automatiquement sélectionnées.

**Modifier les jalons d’une liste de tâches sur la ligne affiche tous les jalons**

_Projets_

Lorsqu’un chemin jalonné est ajouté à un projet et qu’un utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] modifie la colonne [!UICONTROL Jalon : nom] de cette liste de tâches sur la ligne, tous les chemins jalonnés apparaissent dans le menu déroulant, plutôt que simplement les chemins jalonnés joints à ce projet.

+++

+++**Mise à jour de maintenance le 3 juin 2021**

**L’invite fait trembler la page.**

_Rapports_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] exécute un rapport avec une invite, les colonnes du rapport se déplacent rapidement de gauche à droite.

**Quelques phrases de la page [!UICONTROL Nouvelle épreuve] ne sont pas correctement traduites**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur accède à la page [!UICONTROL Créer une nouvelle épreuve] dans [!DNL Workfront Proof] et que son contenu est traduit dans une langue autre que l’anglais, certaines phrases restent en anglais.

**Les libellés Désactivé et Supprimé sont ajoutés aux utilisateurs[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Les libellés d’utilisateur [!UICONTROL Désactivé] et [!UICONTROL Supprimé] ont été ajoutés aux zones suivantes dans l’épreuve [!DNL Workfront] :

* Page des [!UICONTROL détails de l’épreuve]
* [!UICONTROL Vues de relecture]
* [!UICONTROL Visionneuse de relecture]
* [!UICONTROL Workflows de relecture]
* Page [!UICONTROL Imprimer les commentaires]
* Page [!UICONTROL Utilisateur]

+++


## Mises à jour de mai 2021

+++**Mise à jour de maintenance le 27 mai 2021**

Le calendrier **[!UICONTROL Date d’engagement] s’affiche lors d’une mise à jour**

_Tâches_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] commence la mise à jour d’une tâche, le calendrier [!UICONTROL Date d’engagement] le calendrier s’affiche sans que l’utilisateur sélectionne le champ [!UICONTROL Date d’engagement].

Le menu **[!UICONTROL Plus] n’apparaît pas dans les filtres, les vues et les regroupements**

_Listes_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Adobe Workfront] affiche les filtres, les vues ou les regroupements pour une liste, l’icône du menu [!UICONTROL Plus] n’apparaît pas. Il ne peut donc pas partager ni, s’il y est autorisé, supprimer des filtres, des vues ou des regroupements.

**Copier et coller le [!UICONTROL Numéro de référence] d’un projet y ajoute &quot;[!UICONTROL Ceci]&quot;**

_Projets_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] accède à un projet et copie le [!UICONTROL Numéro de référence] de la zone [!UICONTROL Présentation], puis le colle, le mot &quot;[!UICONTROL Ceci]&quot; est ajouté à la fin du nombre.

Les e-mails de **[!UICONTROL Sommaire quotidien] sont envoyés alors qu’ils sont désactivés**

_Notifications par e-mail_

Certains utilisateurs reçoivent des notifications de [!UICONTROL Résumé quotidien] par e-mail alors qu’elles n’ont pas été activées dans leurs paramètres utilisateur.

**Erreur : l’objet n’existe plus**

_Objets_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] tente d’ouvrir certains objets, le message d’erreur &quot;[!UICONTROL (L’objet) n’existe plus. L’adresse Web est peut-être mal orthographiée. Vérifiez-la, puis tentez d’y accéder à nouveau.]&quot; apparaît. Le lien de l’objet s’affiche toujours dans les listes, les éléments récents, les favoris, les résultats de recherche, etc., mais il n’est pas accessible et il n’apparaît pas dans la Corbeille avec les objets supprimés.



+++

+++**Mise à jour de maintenance le 20 mai 2021**

**Les options d’épreuve ont disparu**

_Épreuves_

Lorsque l’utilisateur charge une autre version d’une épreuve dans [!DNL Workfront], les liens [!UICONTROL Épreuve ouverte] et [!UICONTROL Workflow de relecture] sont absents, ce qui donne l’impression qu’il s’agit d’un document plutôt que d’une épreuve. Lorsque ces liens sont manquants, le libellé [!UICONTROL En attente] s’affiche également et les autres utilisateurs ne peuvent pas générer l’épreuve tant que son statut est défini sur [!UICONTROL En attente].

**Les utilisateurs ne reçoivent aucune diffusion de rapports planifiés**

_Rapports_

Lorsque la diffusion de certains rapports est planifiée, il arrive que les utilisateurs ne reçoivent pas ces rapports.

**Impossible de supprimer l’accès au modèle de mise en page**

_Tableaux de bord_

Lorsque l’utilisateur ouvre les options de [!UICONTROL Partage] d’un tableau de bord pour supprimer l’accès à un modèle de mise en page, l’icône [!UICONTROL Supprimer] n’apparaît pas près du modèle de mise en page et il ne parvient pas à en supprimer l’accès.

+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 17 mai 2021**

**Le tableau de bord de l’organisation affiche désormais correctement le nombre de scénarios actifs**

_[!DNL Workfront Fusion]_

Le tableau de bord de l’[!UICONTROL organisation] affichait auparavant un champ vide au lieu du nombre de scénarios en cours d’utilisation.

**La navigation dans la banque de données affiche désormais les libellés des colonnes**

_[!DNL Workfront Fusion]_

Les structures de données qui utilisaient les libellés des colonnes affichaient auparavant le nom de la colonne dans la vue de [!UICONTROL navigation dans la banque de données].  Désormais, le libellé de la colonne s’affiche.  Si aucun libellé n’est identifié pour la colonne, le nom de la colonne s’affiche.

**L’erreur d’initialisation du scénario n’affecte plus les données webhook**

_[!DNL Workfront Fusion]_

Auparavant, un scénario initié par webhook (y compris ceux pour lesquels les événements en temps réel servaient de déclencheurs) qui rencontrait une erreur lors de l’initialisation du scénario pouvait entraîner une perte d’accès à ces données webhook.  Désormais, si une erreur se produit lors de l’initialisation du scénario (par exemple s’il est impossible de vérifier une connexion), les données webhook sont conservées dans la file d’attente webhook, et l’exécution est automatiquement relancée.  Après trois tentatives infructueuses, le scénario est désactivé et les informations restent dans la file d’attente.

**Les enregistrements des files d’attente webhook sont désormais traités par plus petits lots**

_[!DNL Workfront Fusion]_

Auparavant, si l’utilisateur activait un scénario inactif auquel était associée une file d’attente webhook contenant plusieurs enregistrements, [!DNL Workfront Fusion] tentait de traiter la file d’attente complète en une seule fois (mais en plusieurs cycles).  Selon le nombre d’enregistrements traités, la durée d’une telle exécution dépassait parfois la durée maximale d’exécution (40 minutes).  Désormais, lorsqu’un scénario inactif avec une file d’attente d’enregistrements webhook associée est activé, Workfront Fusion traite jusqu’au nombre maximal d’enregistrements identifiés en une seule fois (généralement 2 enregistrements par exécution).

**Les banques de données affichent désormais correctement les valeurs &quot;0&quot;**

_[!DNL Workfront Fusion]_

Auparavant, les valeurs 0 s’affichaient comme étant vides dans les banques de données. &lt;...>

+++

+++**Mise à jour de maintenance le 13 mai 2021**

**Le calendrier déroulant s’affiche derrière l’en-tête [!UICONTROL Tâches non affectées]**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur accède à l’[!UICONTROL équilibreur de charge de travail] dans [!DNL Workfront Classic], l’en-tête [!UICONTROL Tâches non affectées] dissimule le haut du sélecteur de dates, et l’utilisateur ne peut pas changer le mois sélectionné.

**Impossible de coller du texte dans le champ de message personnalisé**

_[!DNL Workfront Proof]_

Remarque : ce problème semble uniquement concerner le navigateur Web [!DNL Google Chrome] pour le moment.

Lorsque l’utilisateur crée une nouvelle épreuve dans [!DNL Workfront Proof] et tente de coller du texte provenant d’un e-mail dans le champ [!UICONTROL Message] de la section [!UICONTROL Notification par e-mail], il ne parvient pas à coller le texte.

**Les champs non pris en charge s’affichent dans le créateur**

_Formulaires personnalisés_

Lorsque l’utilisateur crée un formulaire personnalisé et tente de créer un champ calculé à l’aide d’un champ dynamique, tel que [!UICONTROL Nombre de risques ouverts], la zone de calcul devient rouge et les modifications ne peuvent pas être enregistrées. Les champs dynamiques ne doivent pas s’afficher dans le sélecteur de champs calculés.

**L’aperçu des tâches dans la [!UICONTROL Liste de travail] ne se charge pas**

_Page d’accueil_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] est affecté à un modèle de mise en page qui inclut des champs personnalisés sur l’[!UICONTROL Accueil], la page ne répond pas et ne charge pas les tâches de la [!UICONTROL Liste de travail] si l’utilisateur les sélectionne.

**Les objets de la [!UICONTROL Liste de travail] ne se chargent pas sur l’[!UICONTROL Accueil]**

_[!UICONTROL Page d’accueil]_

Lorsque l’utilisateur clique sur un objet de la [!UICONTROL Liste de travail de l’accueil], l’en-tête de l’objet s’affiche dans le panneau de droite, mais les détails de l’objet n’apparaissent pas. Le message &quot;[!UICONTROL La page ne répond pas.]&quot; finit par apparaître.

**Problèmes liés aux champs Rich Text dans[!DNL Microsoft Outlook]**

_Intégrations Workfront_

Lorsque l’utilisateur met à jour un champ Rich Text avec l’intégration [!DNL Workfront for Outlook], il ne peut pas :

* Revenir en arrière
* Copier du texte
* Coller du texte
* Soumettre une demande avec tous les champs renseignés

+++

+++**Mise à jour de maintenance le 6 mai 2021**

Le champ **[!UICONTROL Devise] ne fonctionne pas correctement**

_Listes_

Lorsque l’utilisateur tente de modifier sur la ligne le champ Devise dans une liste, les modifications ne peuvent pas être enregistrées en raison des problèmes suivants :

* Les listes Tâche et Événement n’autorisent pas la saisie des symboles des devises
* Les listes n’autorisent pas la saisie des abréviations des devises lors de l’utilisation d’un paramètre régional autre que l’anglais
* Les listes Sous-tâche et Événement autorisent uniquement l’abréviation de devise USD, et ce quelle que soit la devise définie pour le projet

**Le nom ne se met pas à jour en fonction du nouveau nom de l’épreuve**

_Documents_

Lorsque l’utilisateur crée une nouvelle version d’une épreuve et qu’il met à jour le nom de celle-ci, l’objet document dans [!DNL Workfront] conserve le nom d’origine et ne se met pas à jour en fonction du nouveau nom de l’épreuve.

Les boutons **[!UICONTROL Analyse de rentabilité] ne fonctionnent pas lorsque des formulaires personnalisés sont joints**

_Projets_

Lorsqu’un projet est créé dans la nouvelle expérience [!DNL Workfront] à partir d’un modèle de projet et qu’un formulaire personnalisé y est joint, les utilisateurs ne peuvent pas soumettre, rejeter, ni approuver d’analyse de rentabilité.

**Les épreuves archivées s’affichent dans les listes et les rapports**

_Épreuves_

Lorsque l’utilisateur consulte sa liste de travail sur l’[!UICONTROL Accueil] ou [!UICONTROL Mes tâches], les épreuves déjà archivées apparaissent dans la liste. Les épreuves archivées s’affichent également dans les rapports et les tableaux de bord.

**Les paramètres d’accès aux projets créés à partir d’un modèle sont incorrects**

_Projets_

Lorsque l’utilisateur crée un projet à partir d’un modèle, les paramètres d’accès du modèle ne sont pas transférés vers le projet nouvellement créé.

**Les objets de la [!UICONTROL Liste de travail] ne se chargent pas sur l’[!UICONTROL Accueil]**

_[!UICONTROL Page d’accueil]_

Lorsque l’utilisateur clique sur un objet de la [!UICONTROL Liste de travail de l’accueil], l’en-tête de l’objet s’affiche dans le panneau de droite, mais les détails de l’objet n’apparaissent pas. Le message &quot;[!UICONTROL La page ne répond pas.]&quot; finit par apparaître.

+++


## Mises à jour d’avril 2021

+++**Mise à jour de maintenance le 29 avril 2021**

L’intégration **[!DNL SharePoint]authentifie à l’aide des informations d’identification provenant d’une intégration distincte**

_Intégrations Workfront_

Lorsque l’utilisateur possède plusieurs intégrations [!DNL SharePoint], une authentification [!DNL SharePoint] tente d’authentifier à l’aide des informations d’identification d’une autre intégration [!DNL SharePoint].

**Impossible de charger ou d’exporter des fichiers des produits [!DNL Adobe]**

_Intégrations Workfront_

Lorsque l’utilisateur tente de charger ou d’exporter des fichiers à l’aide de l’intégration [!DNL Workfront for Adobe Creative Cloud], le message d’erreur &quot;[!UICONTROL Impossible de lire &quot;les étapes&quot; de propriété d’un objet non défini]&quot; s’affiche, et il est impossible de télécharger ou d’exporter les fichiers.

**Les fichiers n’apparaissent pas dans[!DNL Internet Explorer]**

_Documents_

Lorsque l’utilisateur avec un navigateur [!DNL Internet Explorer] accède à la zone [!UICONTROL Documents] d’un objet, la page [!UICONTROL Documents] est vierge et aucun fichier n’est chargé. Pour certains utilisateurs, l’écran charge quelques-uns des fichiers, mais le nombre de fichiers qui s’affichent ne correspond pas au nombre indiqué près de la section [!UICONTROL Documents].

+++

+++**Mise à jour de maintenance le 22 avril 2021**

**Les tâches ne sont pas ajoutées dans le bon ordre**

_Modèles_

Lorsque l’utilisateur ajoute une tâche à un modèle, la tâche ne reçoit pas le numéro de tâche attendu et elle est ajoutée au mauvais endroit.

**Les épreuves sont désormais regroupées dans un seul e-mail**

_Épreuves_

[!DNL Workfront] envoie désormais un seul e-mail pour les épreuves associées et non plus un e-mail pour chaque fichier inclus.
+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 15 avril 2021**

**L’erreur &quot;[!UICONTROL Scénario rejeté]&quot; survient lors de l’exécution d’un scénario**

_[!DNL Workfront Fusion]_

Lorsque l’utilisateur tente d’exécuter un scénario, celui-ci ne s’exécute pas et le message &quot;[!UICONTROL Scénario rejeté.]&quot; apparaît.

+++

+++**Mise à jour de maintenance le 15 avril 2021**

L’**[!UICONTROL équilibreur de charge de travail] affiche un nombre d’heures prévues incorrect**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur consulte le nombre d’heures prévues d’une tâche dans l’[!UICONTROL Équilibreur de charge de travail], la valeur du nombre d’heures prévues ne correspond pas au nombre d’heures prévues affectées à la tâche.

**La barre de navigation supérieure n’apparaît pas dans[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur accède à n’importe quelle page [!DNL Workfront Proof] hormis le Tableau de bord, la barre de navigation supérieure disparaît. L’utilisateur ne peut accéder à aucune fonctionnalité de la barre de navigation, comme les paramètres de son compte ou son profil.

**Amélioration des formulaires personnalisés**

_Formulaires personnalisés dans mon groupe_

Pour une meilleure expérience de remplissage de formulaires personnalisés, nous avons amélioré l’affichage des longs libellés de champ personnalisé. Lorsqu’il y a suffisamment d’espace horizontal pour les afficher dans leur intégralité, ces libellés ne sont plus tronqués.

+++

+++**Mise à jour de maintenance le 8 avril 2021**

**Impossible de créer des épreuves dans l’intégration [!DNL Adobe Creative Cloud]**

_Intégrations Workfront_

Lorsque l’utilisateur tente de créer directement une épreuve à partir du [!DNL Adobe Creative Cloud], l’épreuve n’est pas générée.

+++

+++**Mise à jour de maintenance le 1 avril 2021**

**Problèmes d’affichage du panneau de résumé dans[!DNL Chrome]**

_[!UICONTROL Résumé]_

Lorsque l’utilisateur ouvre le panneau de [!UICONTROL résumé] dans le navigateur [!DNL Chrome], l’interface utilisateur du panneau de résumé ne se comporte pas comme prévu. L’utilisateur ne peut pas faire défiler l’écran, les icônes disparaissent parfois et certains objets se chevauchent parfois.

La zone **[!UICONTROL Équipes] dans [!UICONTROL Configuration] n’affiche pas toutes les équipes**

_[!UICONTROL Configuration]_

Lorsque l’administrateur accède à la zone [!UICONTROL Équipes] dans [!UICONTROL Configuration], seules les équipes qu’il a créées s’affichent. Les équipes créées par d’autres administrateurs n’apparaissent pas.

**Impossible d’ajouter des mises à jour aux projets dont le statut est défini sur [!UICONTROL En attente d’approbation]**

_Projets_

Si l’utilisateur tente d’ajouter une mise à jour à un projet dont le statut est défini sur [!UICONTROL En attente d’approbation] et qu’il n’est pas l’utilisateur affecté à l’approbation du projet, la mise à jour n’est pas ajoutée et le message suivant apparaît :

Les projets dont le statut est défini sur &quot;[!DNL Pending Approval]&quot; ne peuvent pas être modifiés. Vous pouvez modifier le projet en changeant son statut.

+++


## Mises à jour de mars 2021

+++**Mise à jour de maintenance le 26 mars 2021**

**Les boutons de l’analyse de rentabilité ne s’affichent pas correctement**

_Projets_

Lorsque l’utilisateur consulte une analyse de rentabilité en mode plein écran, les boutons [!UICONTROL Enregistrer] et [!UICONTROL Annuler] s’affichent au milieu de l’écran par-dessus certains éléments de l’analyse de rentabilité.

**Impossible de modifier le tri dans un rapport**

_Rapports_

Lorsque l’utilisateur de la nouvelle expérience [!DNL Workfront] tente de modifier le tri dans un rapport, le tri reste celui sélectionné lors de la création du rapport.

**Partage des nouvelles épreuves désactivé**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur avec le paramètre [!UICONTROL Partage public] activé par défaut pour les épreuves crée une épreuve, celle-ci est créée avec le partage désactivé. Les autres utilisateurs ne peuvent pas voir le bouton [!UICONTROL Partager] ni partager l’épreuve.

**Erreur &quot;[!UICONTROL Échec de la génération de l’épreuve]&quot; lors de la création d’une épreuve**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur tente de créer une épreuve, celle-ci n’est pas créée et le message d’erreur suivant apparaît :

&quot;[!UICONTROL Échec de la génération de l’épreuve ; erreur interne]&quot;

+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 25 mars 2021**

**Suppression d’un champ de collection ou de référence redondant du panneau de mappage**

_[!DNL Workfront Fusion]2.0_

Lorsque l’utilisateur emploie un terme de l’API [!DNL Workfront] pour sélectionner un champ de collection ou de référence à inclure dans la sortie d’un module [!DNL Workfront], la sortie de ce module affiche ce champ avec deux points (par exemple [!UICONTROL propriétaire:nom]) et dans les attributs (le nom est un champ sous le propriétaire). Le champ contenant les deux points est vide et renvoie des données incorrectes s’il est plus tard mappé à un module dans le scénario.

+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 18 mars 2021**

**Les paramètres de modèle de projet s’appliquent désormais aux projets créés avec [!DNL Workfront Fusion] 2.0**

_[!DNL Workfront Fusion]2.0_

Lors de la création d’un projet à partir d’un modèle avec [!DNL Workfront Fusion] 2.0, les paramètres du modèle sont appliqués au nouveau projet. Cela se produit également lors de la création d’un projet à partir d’un modèle dans l’application [!DNL Workfront].

+++

+++**Mise à jour de maintenance le 18 mars 2021**

**Les paramètres de modèle de projet s’appliquent désormais aux projets créés avec l’API**

API _[!DNL Workfront]_

Lors de la création d’un projet à partir d’un modèle avec l’API [!DNL Workfront], les paramètres du modèle sont appliqués au nouveau projet. Cela se produit également lors de la création d’un projet à partir d’un modèle dans l’application [!DNL Workfront].

+++

+++**Mise à jour de maintenance (correctif) le 15 mars 2021**

**Le composant partagé ne fonctionne pas comme prévu**

_[!DNL Workfront Proof]_

Si des comptes [!DNL Workfront Proof] autonomes sont déplacés vers un composant partagé, la fonctionnalité suivante peut se déclencher lorsque l’utilisateur ajoute une nouvelle version d’une épreuve ou d’un document :

* L’utilisateur ne peut pas supprimer l’utilisateur [!UICONTROL Épreuve Studio].
* Le message par défaut n’apparaît pas dans la nouvelle version.

**Partage de liens public non activé pour la nouvelle version d’une épreuve**

_Documents_

Lorsque l’utilisateur active le partage de liens public pour une épreuve puis charge une nouvelle version de l’épreuve, le partage de liens public ne s’active pas automatiquement pour la nouvelle version de l’épreuve.

Les boutons **[!UICONTROL Approuver], [!UICONTROL Modifications] et [!UICONTROL Rejeter] n’apparaissent pas dans l’épreuve**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur consulte une épreuve dans la visionneuse d’épreuve, les boutons [!UICONTROL Approuver], [!UICONTROL Modifications] et [!UICONTROL Rejeter] n’apparaissent pas dans la partie supérieure de l’écran.

**Impossible de modifier le tri dans un rapport**

_Rapports_

Lorsque l’utilisateur de la nouvelle expérience [!DNL Workfront] tente de modifier le tri dans un rapport, le tri reste celui sélectionné lors de la création du rapport.

**Le message personnalisé de l’épreuve disparaît lors du passage à la nouvelle version**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur joint un message personnalisé à une épreuve puis charge une nouvelle version de cette épreuve, le message personnalisé n’apparaît plus sur la nouvelle épreuve.

**La liste des utilisateurs ne s’affiche pas**

_Listes_

Lorsque l’utilisateur tente d’afficher une liste d’utilisateurs et que la vue inclut la colonne &quot;[!UICONTROL Icônes de statut]&quot;, la liste ne s’affiche pas.

L’option **&quot;[!UICONTROL Notifier les destinataires à propos de cette épreuve]&quot; est désactivée quels que soient les paramètres du workflow**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur crée une épreuve et n’active pas manuellement l’option &quot;[!UICONTROL Notifier les destinataires à propos de cette épreuve]&quot;, le destinataire prévu n’est pas notifié, même si l’option est activée dans les paramètres du workflow.

**Impossible de modifier la période**

_[!UICONTROL Analytique améliorée]_

Lorsque l’utilisateur affiche l’[!UICONTROL analytique améliorée] et clique sur le calendrier pour modifier la période, les dates ne changent pas.

**Impossible de télécharger le document partagé publiquement**

_Documents_

Lorsque l’utilisateur clique sur un lien partagé pour télécharger un document, le document ne se télécharge pas et le navigateur affiche une erreur indiquant que la page n’existe pas.

+++

+++**Mise à jour de maintenance le 11 mars 2021**

**Une section de formulaire personnalisé ne s’exporte pas pour les utilisateurs qui ne sont pas administrateurs**

_Formulaires personnalisés_

Si un formulaire personnalisé joint à un objet comporte un saut de section dont le contenu de la section exige un accès supérieur à &quot;[!UICONTROL Vue]&quot; pour s’afficher, seuls les administrateurs sont en mesure d’exporter le contenu de la section.

**Le nom du document téléchargé n’est pas correct**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur télécharge un document à partir de la [!UICONTROL visionneuse d’épreuve], le nom du document est celui d’une version précédente du document, et non pas celui de la version qui a été téléchargée.

+++

+++**Mise à jour de maintenance le 4 mars 2021**

**Erreur d’accès au modèle de mise en page**

_Modèles de mise en page_

Lorsque l’utilisateur inscrit dans la nouvelle expérience [!DNL Workfront] passe à l’expérience [!DNL Classic] et tente d’accéder à un modèle de mise en page [!DNL Classic], l’erreur &quot;[!UICONTROL Cette page n’existe pas.]&quot; s’affiche.

**Impossible de modifier les filtres dans l’[!UICONTROL équilibreur de charge de travail]**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsque l’utilisateur tente de modifier un filtre dans l’[!UICONTROL équilibreur de charge de travail], le créateur de filtres ne s’ouvre pas.

Le lien **&quot;[!UICONTROL Voir toutes les notifications]&quot; dans les notifications par e-mail ne renvoie pas vers la bonne page**

_Notifications par e-mail_

Lorsque l’utilisateur clique sur le lien &quot;[!UICONTROL Voir toutes les notifications]&quot; dans une notification envoyée par e-mail, il est dirigé vers une page contenant le message suivant :

&quot;[!UICONTROL L’utilisateur n’existe plus. L’adresse Web est peut-être mal orthographiée. Vérifiez-la, puis tentez d’y accéder à nouveau.]&quot;

**L’utilisateur n’est pas redirigé vers le commentaire de l’épreuve dans lequel il est identifié.**

_Notifications par e-mail_

Lorsque l’utilisateur est identifié dans un commentaire d’épreuve et qu’il clique sur le lien [!UICONTROL Accéder à l’épreuve] dans une notification reçue par e-mail, il est redirigé vers l’épreuve, mais pas vers le commentaire spécifique. Si l’utilisateur se trouve dans [!DNL Workfront Classic], il est redirigé vers la page [!UICONTROL Détails du document] plutôt que vers le commentaire dans l’épreuve.

**Les utilisateurs ajoutés à [!DNL Workfront] reçoivent des notifications par e-mail**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur qui n’appartient pas au workflow ouvre une épreuve depuis [!DNL Workfront], le système crée automatiquement une étape, ajoute cet utilisateur à l’épreuve et envoie une notification de [!UICONTROL Nouvelle épreuve] par e-mail.

**Le panneau de résumé du document s’obscurcit et plus aucune action n’est possible**

_Documents_

Lorsque l’utilisateur se trouve sur une page du document et survole le panneau de résumé du document avec le curseur, le panneau s’obscurcit et d’autres boutons peuvent apparaître. L’utilisateur ne peut pas cliquer sur les actions du panneau de résumé.

**Modification des performances du flux de mise à jour**

_Flux de mise à jour_

Nous avons réduit le nombre de mises à jour concernant les utilisateurs s’affichant dans l’onglet [!UICONTROL Mises à jour], qui sont passées de 50 à 25 à la fois pour de meilleures performances.

+++

+++**Mise à jour de maintenance (correctif) le 1 mars 2021**

**Aucun e-mail concernant les nouvelles épreuves n’est envoyé**

_[!DNL Workfront Proof]_

REMARQUE : ce problème a été corrigé le 26 février 2021 dans la nouvelle expérience [!DNL Workfront].
Ce problème a été corrigé le 1er mars 2021 dans l’expérience [!DNL Classic].

Lorsque l’utilisateur crée une épreuve et active l’option [!UICONTROL Notifier les destinataires à propos de cette épreuve], aucun e-mail n’est envoyé pour notifier le destinataire.

+++


## Mises à jour de février 2021

+++**Mise à jour de maintenance le 25 février 2021**

L’outil **[!UICONTROL Planification] ne se charge dans aucune zone**

_Gestion des ressources_

Lorsque l’utilisateur dont le nom d’utilisateur contient une apostrophe tente d’accéder à l’outil [!UICONTROL Planification] dans [!DNL Workfront Classic], la page est vierge et l’outil ne se charge pas.

**Le nom ne change pas dans les nouvelles versions de l’épreuve**

_Documents_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] charge une nouvelle version d’un document au nom différent, le nom ne s’adapte pas au nom de la version la plus récente.

Erreur de **[!UICONTROL partage de document] lors de la suppression de projets**

_Projets_

Lorsque l’utilisateur avec un statut d’administrateur système a accès à un projet qui a été copié et tente de le supprimer ou de supprimer un document du projet, il ne peut pas supprimer l’objet et l’erreur &quot;[!UICONTROL Partage de documents avec valeur(s) de clé primaire introuvable.]&quot; s’affiche.

**Le rapport d’utilisateur n’applique pas tous les filtres**

_Rapports_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] crée un rapport d’utilisateur avec une règle de filtrage incluant le champ [!UICONTROL ID du parent principal], aucune autre règle de filtrage du rapport n’est appliquée.

**Les champs calculés ne sont pas recalculés après les modifications**

_Formulaires personnalisés_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] modifie et enregistre un formulaire personnalisé qui contient des champs calculés. ces champs ne sont pas mis à jour.

**Des documents sont supprimés lors de la suppression d’un formulaire personnalisé**

_Formulaires personnalisés_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] supprime un formulaire personnalisé de document joint à des documents, ces documents sont également supprimés.

+++

+++**Mise à jour de maintenance le 18 février 2021**

**Case à cocher inutile supprimée de la zone des [!UICONTROL Demandes]**

_Demandes_

Nous avons supprimé la case à cocher à gauche des noms de demande dans la Liste des demandes soumises de la zone des [!UICONTROL Demandes]. Cette case à cocher n’était liée à aucune fonctionnalité ; nous l’avons donc supprimée pour éviter toute confusion.

**Accès aux documents impossible à partir des liens**

_Documents_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] clique sur certains liens de document, il ne peut pas accéder au document et le message d’erreur suivant apparaît : &quot;[!UICONTROL Le document n’existe plus. L’adresse Web est peut-être mal orthographiée. Vérifiez-la, puis tentez d’y accéder à nouveau.]&quot;. La même erreur se produit avec le lien [!UICONTROL Afficher les détails] dans les notifications par e-mail concernant les épreuves.

+++

+++**Mise à jour de maintenance de Workfront Fusion le 16 février 2021**

**[!DNL Workfront Fusion]Les fuseaux horaires affichés dans la version 2.0 sont inexacts**

_Scénarios_

Cette mise à jour corrige le problème d’affichage des fuseaux horaires dans [!DNL Fusion] 2.0. Les utilisateurs peuvent désormais voir leur fuseau horaire sous les champs de saisie de dates.

+++

+++**Mise à jour de maintenance le 11 février 2021**

**Les épreuves ne se chargent pas vers le dossier sélectionné**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur ouvre un dossier et ajoute une nouvelle épreuve, celle-ci est chargée dans la zone générale des [!UICONTROL Documents] et non pas dans le dossier.

**La barre de navigation supérieure disparaît lorsqu’un trop grand nombre de pages est épinglé**

_Navigation_

Lorsque l’utilisateur épingle plus de 60 pages, la barre de navigation supérieure disparaît, ce qui empêche l’utilisateur d’accéder à [!UICONTROL Rechercher], [!UICONTROL Menu principal], [!UICONTROL Notifications], etc.

**Impossible de saisir du texte dans le champ Rich Text**

_Listes_

Lorsque l’utilisateur tente de modifier un champ Rich Text sur la ligne, il ne peut saisir qu’un seul caractère.

+++

+++**Mise à jour de maintenance le 4 février 2021**

**Les rapports exportés affichent l’image de marque [!DNL Workfront Classic]**

_Rapports_

Lorsque l’utilisateur dans la nouvelle expérience Workfront exporte un rapport, le logo qui s’affiche dans le rapport exporté correspond aux paramètres de [!DNL Workfront Classic] sous [!UICONTROL Configuration] > [!UICONTROL Système] > [!UICONTROL Image de marque].

+++


## Mises à jour de janvier 2021

+++**Mise à jour de maintenance le 28 janvier 2021**

**Les commentaires n’indiquent pas &quot;[!UICONTROL Au nom de]&quot;**

_Mises à jour_

Lorsque l’administrateur de [!DNL Workfront] se connecte en tant qu’autre utilisateur et répond à un commentaire dans la zone [!UICONTROL Mises à jour] d’un objet, le texte &quot;[!UICONTROL Au nom de]&quot; ne s’affiche pas avant le nom d’utilisateur.

**Impossible de joindre un document**

_Demandes_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] tente d’ajouter un document à une nouvelle demande émise par un fournisseur de documents externe, la liste des [!UICONTROL Documents] ne se charge pas, ce qui empêche l’utilisateur de sélectionner le document et de répondre à la demande.

**L’écran s’étend à droite, ce qui cause des problèmes de navigation**

_[!UICONTROL Calendrier de l’accueil]_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] ouvre le [!UICONTROL Calendrier de l’accueil] alors que des articles doivent être envoyés dans plusieurs semaines, l’écran s’étend à droite et il est impossible de voir la semaine entière. Si l’utilisateur sélectionne un élément pour ouvrir le panneau des [!UICONTROL Détails] avec cet affichage et qu’il souhaite consulter les détails d’un autre élément, il doit faire défiler l’écran vers la gauche, ce qui ferme le panneau des [!UICONTROL Détails].

**Correction du libellé du processus de validation à usage unique**

_Projets_

Lors de l’utilisation d’un processus d’approbation à usage unique pour un projet dans la nouvelle expérience [!DNL Workfront], celui-ci s’affiche désormais sous la forme &quot;[!UICONTROL Processus de validation à usage unique]&quot; au lieu de &quot;\&lt;Personnalisé\>&quot; dans la zone de texte [!UICONTROL Modifier le projet]. Cette option n’est pas encore disponible pour l’ensemble des tâches et des événements.

**Amélioration de l’aspect des formulaires personnalisés**

_Projets_

Nous avons amélioré l’aspect des formulaires personnalisés dans la nouvelle expérience [!DNL Workfront] pour les projets.

**La fonctionnalité d’API de la devise du projet correspond désormais à la fonctionnalité in-app.**

_Projets_

Vous ne pouvez pas modifier la devise d’un projet s’il contient déjà des informations financières. Avec la dernière mise à jour de maintenance, la fonctionnalité d’API pour cette situation correspond désormais à l’expérience dans l’interface de [!DNL Workfront].

**La semaine suivante n’est pas générée automatiquement**

_Feuilles de temps_

Lorsque l’utilisateur accède à la zone [!UICONTROL Feuilles de temps], seule la feuille de temps de la semaine en cours apparaît. La feuille de temps des semaines à venir n’est pas générée automatiquement.

+++

+++**Mise à jour de maintenance le 21 janvier 2021**

**Le tri manuel par colonne affiche tous les résultats**

_Rapports_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] clique sur une barre du graphique d’un rapport, puis sur un en-tête de colonne pour trier manuellement les résultats de ce regroupement, tous les résultats du rapport s’affichent, et non pas uniquement les résultats du regroupement sélectionné en premier lieu.

Modifications du paramètre **&quot;[!UICONTROL Autoriser le partage de l’épreuve par une URL ou un code intégré]&quot;**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur crée une épreuve et désélectionne le paramètre [!UICONTROL Autoriser le partage de l’épreuve par une URL ou un code intégré], le paramètre est de nouveau coché une fois l’épreuve générée. Si l’utilisateur ne coche pas la case du paramètre, celle-ci n’est pas cochée après la génération de l’épreuve.

Les utilisateurs de **[!DNL Mac]ne peuvent pas coller de texte dans les champs de texte de la visionneuse d’épreuve**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur tente de coller du texte dans certains champs de la visionneuse d’épreuve, le texte n’apparaît pas dans le champ.

+++

+++**Mise à jour de maintenance le 14 janvier 2021**

**Impossible de mettre à jour les paramètres des notifications par e-mail**

_Configuration_

Lorsque l’utilisateur tente de mettre à jour les paramètres des notifications par e-mail, il ne peut pas accéder à la zone des [!UICONTROL Notifications par e-mail] et le message d’erreur suivant apparaît : &quot;[!UICONTROL Réessayons. Oups ! Un problème est survenu. Contactez [!DNL Workfront] pour nous aider à comprendre l’erreur et y remédier.]&quot;

Le **[!UICONTROL graphique Gantt] tronque certains champs**

_Listes_

Lorsque l’utilisateur ouvre le [!UICONTROL graphique Gantt] dans certaines zones de la liste, le texte de certains champs, tels que [!UICONTROL Description], est tronqué. L’utilisateur doit double-cliquer sur le champ pour afficher le texte complet.

**Impossible d’envoyer les fichiers depuis les [!UICONTROL Détails du document]**

_Documents_

Lorsque l’utilisateur dans la nouvelle expérience [!DNL Workfront] tente d’envoyer un document à partir de la page [!UICONTROL Détails du document], le message d’erreur suivant apparaît : &quot;[!UICONTROL Une erreur s’est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d’actualiser cette page de navigateur.]&quot;

+++

+++**Mise à jour de maintenance le 7 janvier 2021**

**La boîte de dialogue Déléguer les approbations se ferme**

_Page d’accueil_

Lorsque l’utilisateur tente de déléguer des approbations sur l’[!UICONTROL Accueil] et clique sur une date, la boîte de dialogue se ferme sans sélectionner la date ni permettre à l’utilisateur de terminer la délégation à l’utilisateur.

**Problème lors du déplacement d’un document vers une tâche**

_Documents_

Lorsque l’utilisateur tente de déplacer un document ou une épreuve dans la nouvelle expérience [!DNL Workfront], certaines tâches en dehors du projet n’indiquent pas le projet parent comme prévu.

**Le nom du PDF téléchargé n’est pas correct**

_[!DNL Workfront Proof]_

Lorsque l’utilisateur reçoit un lien de téléchargement par e-mail ([!UICONTROL Épreuve] > [!UICONTROL Imprimer les commentaires] > [!UICONTROL PDF]) et exporte le fichier, le titre du fichier téléchargé contient des nombres aléatoires au lieu de l’ID de l’épreuve.

+++
