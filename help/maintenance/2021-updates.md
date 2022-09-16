---
title: Mises à jour de la maintenance de Workfront pour 2021
description: Historique des mises à jour de maintenance 2021 pour [!DNL Adobe Workfront]
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
source-git-commit: 7fa90198186a7b0f392683d432a7da0424943da2
workflow-type: tm+mt
source-wordcount: '10019'
ht-degree: 3%

---

# 2021 [!DNL Workfront] Mises à jour de maintenance

Les mises à jour de maintenance suivantes ont été effectuées en 2021 :

## Mises à jour en décembre 2021

+++**Mise à jour de maintenance le 23 décembre 2021**

**Nouvelles tâches par défaut à une contrainte de tâche incorrecte**

_Tâches_

Lorsqu’un utilisateur crée une tâche à l’aide de la fonction &quot;[!UICONTROL Nouvelle tâche]&quot;, et la variable [!UICONTROL Nouvelle tâche - Début par défaut] L’option Date est définie sur &quot;[!UICONTROL Aujourd&#39;hui],&quot; la contrainte de tâche de la tâche créée est définie sur &quot;[!UICONTROL Dès que possible]&quot; plutôt que &quot;[!UICONTROL Ne pas démarrer avant].&quot; Cela peut également se produire lors de l’utilisation de modèles de projet.

**Ouverture du planning dans [!UICONTROL Groupes] la zone mène à une page vierge ;**

_Configuration_

Lorsqu’un utilisateur consulte des groupes dans la variable [!UICONTROL Configuration] et tente d’ouvrir, de modifier ou de copier un planning, le planning ne s’ouvre pas et l’utilisateur voit une page vierge.

**Les modifications ne s’affichent pas lors de la réorganisation du volet de navigation gauche**

_Navigation_

Lorsqu’un utilisateur tente de réorganiser le panneau de navigation de gauche en faisant glisser un élément, l’élément revient à son emplacement précédent lorsque l’utilisateur le fait glisser. Si l’utilisateur actualise la page, le panneau de gauche affiche le nouvel ordre.

**Le lien permettant d’envoyer un document demandé conduit à une page vierge.**

_Documents_

Lorsqu’un utilisateur reçoit une demande d’envoi de document et clique sur le lien vers l’objet dans lequel le document a été demandé, le lien mène à une page vierge. Cela peut se produire lorsque vous cliquez sur un lien dans un email ou dans une notification in-app.

**[!UICONTROL Équilibreur de charge de travail] affiche 0 heure allouée**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur consulte la variable [!UICONTROL Équilibreur de charge de travail] et possède le[!UICONTROL Afficher les dates prévues]&quot; activée, toutes les dates suivantes afficheront 0 heure allouée.

**Les bons à tirer disparaissent par intermittence des dossiers**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur est connecté [!DNL Workfront Proof] affiche un dossier, il apparaît vide. Si l’utilisateur réexamine les informations ultérieurement, les bons à tirer sont visibles.

+++

+++**Mise à jour de maintenance le 16 décembre 2021**

**Cliquer sur l’annonce dans la liste de notifications mène à une page vierge.**

_Notifications_

Lorsqu’un utilisateur ouvre sa liste de notifications de la fonction [!UICONTROL Notifications] , puis clique sur une annonce, elle est redirigée vers une page vierge et l’annonce ne s’affiche pas.

**Le panneau Résumé affiche &quot;[!UICONTROL Aucune sélection]&quot; lorsque la tâche est sélectionnée ;**

_Tâches_

Lorsqu’un utilisateur ouvre un résumé du document dans la fonction [!UICONTROL Documents] d’un projet, puis passe à la liste des tâches, sélectionne une tâche et tente d’ouvrir le résumé de la tâche, le résumé de la tâche ne s’affiche pas et l’utilisateur voit le message suivant :

[!UICONTROL Aucune sélection. Sélectionnez un document dans la liste pour afficher les détails.]

Le message mentionne des documents même si l’utilisateur figure dans la liste des tâches.

**[!UICONTROL Travail non attribué] ne charge pas**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur dans la variable [!UICONTROL Équilibreur de charge de travail] crée un filtre à l’aide de la fonction [!UICONTROL Attribution : ID de rôle] , le champ [!UICONTROL Travail non attribué] ne se charge pas.

**Ajout d’un modèle à l’aide de &quot;[!UICONTROL Personnalisation et ajout]&quot; efface les valeurs de champ personnalisées**

_Projets_

Si un utilisateur joint un modèle à un projet à l’aide de l’option[!UICONTROL Personnalisation et ajout]&quot;, et qu’un formulaire personnalisé est déjà associé au projet, les valeurs des champs personnalisés ne sont pas transférées et doivent être saisies manuellement. Cela se produit même lorsque le modèle inclut le même formulaire personnalisé.

+++

+++**Mise à jour de maintenance (correctif) le 10 décembre 2021**

**[!UICONTROL Oups] erreur lors de l’association d’un modèle à un projet existant**

_Projets_

Lorsqu’un utilisateur tente de joindre un modèle à un projet existant, celui-ci n’est pas joint et l’utilisateur voit l’erreur suivante :

&quot;[!UICONTROL Oups ! Un problème est survenu. Veuillez contacter [!DNL Workfront] donc nous pouvons comprendre ce qui s&#39;est mal passé et y remédier.]&quot;

+++

+++**Mise à jour de maintenance le 9 décembre 2021**


**Le panneau de navigation à gauche réduit se développe au chargement de la page.**

_Navigation_

Lorsqu’un utilisateur a défini sa navigation de gauche pour qu’elle soit réduite, puis actualisée une page, la navigation de gauche est développée sur la page rechargée. La navigation de gauche est également développée si l’utilisateur ouvre une page dans un nouvel onglet.

**[!UICONTROL Équilibreur de charge de travail] affiche 0 heure allouée**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur consulte la variable [!UICONTROL Équilibreur de charge de travail] et possède le[!UICONTROL Afficher les dates prévues]&quot; activée, toutes les dates suivantes afficheront 0 heure allouée.

+++

+++**Mise à jour de maintenance le 8 décembre 2021**

**L’approbation est réinitialisée lorsqu’une mise à jour est effectuée**

_Approbations_

Si un utilisateur prend une décision sur une validation à l’aide de l’en-tête de l’objet, puis met immédiatement à jour l’objet, les icônes de validation réapparaissent dans l’en-tête et la décision de validation n’est pas enregistrée.

**[!UICONTROL Impossible de modifier en ligne une affectation dans un rapport]**

_Rapports_

Lorsqu’un utilisateur tente d’intégrer une modification d’affectation dans un rapport, la valeur du champ ne change pas et la modification n’est pas enregistrée.


+++

+++**Mise à jour de maintenance le 2 décembre 2021**

**Barre oblique supplémentaire ajoutée lors de la saisie manuelle de l’URL**

_Demandes_

Lorsqu’un utilisateur répond à une requête et commence manuellement à saisir une URL, une barre oblique supplémentaire est ajoutée à un moment près du début de l’URL. L’utilisateur ne peut pas supprimer la barre oblique.

**Les sections personnalisées ne peuvent pas être supprimées du panneau de navigation de gauche**

_Navigation_

Lorsqu’un utilisateur tente de supprimer une section personnalisée du panneau de navigation de gauche en cliquant sur le X en regard de la section , la section n’est pas supprimée.

**Le travail non assigné ne se charge pas**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur dans la variable [!UICONTROL Équilibreur de charge de travail] crée un filtre à l’aide de la fonction [!UICONTROL Attribution : ID de rôle] , le champ [!UICONTROL Travail non attribué] ne se charge pas.

**Pages non chargées dans certains navigateurs**

_[!DNL Workfront]_

Lorsqu’un utilisateur travaille dans [!DNL Workfront], les pages ne se chargent pas et l’utilisateur voit le message d’erreur suivant :

&quot;[!UICONTROL Une erreur s&#39;est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d&#39;actualiser cette page de navigateur.]&quot;

Cela a été signalé dans

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Cette erreur se produit de manière aléatoire et peut affecter n’importe quelle zone de [!DNL Workfront].

+++


## Mises à jour en novembre 2021

+++**Mise à jour de maintenance le 18 novembre 2021**

**[!DNL Workfront]pour [!DNL Jira] &quot;[!UICONTROL ClientID ou clientSecret non valide]&quot; erreur lors de la connexion**

_Intégrations Workfront_

Les utilisateurs ont été déconnectés du [!DNL Jira] pour l’intégration à Workfront. Lorsqu’un utilisateur tente de se connecter à la variable [!DNL Workfront for Jira] intégration, ils ne peuvent pas se connecter et le message d’erreur suivant s’affiche :

&quot;[!UICONTROL ClientID ou clientSecret non valide]&quot;

**Le formulaire personnalisé joint à la requête ne se met pas à jour lorsqu’une nouvelle rubrique de file d’attente est sélectionnée**

_Demandes_

Lorsqu’un utilisateur crée une requête et sélectionne une rubrique de file d’attente qui joint automatiquement un formulaire personnalisé à la requête, puis sélectionne une autre rubrique de file d’attente, le formulaire personnalisé de la première rubrique de file d’attente reste associé à la requête.

**Les icônes ne s’affichent pas correctement**

_[!DNL Workfront]_

Les images d’icônes ne s’affichent pas correctement. Cela a été signalé dans de nombreuses zones à travers [!UICONTROL Workfront].

**Les tâches ne sont pas exportées vers PDF lorsque l’option &quot;Autres tailles&quot; est sélectionnée.**

_Tâches_

Si un utilisateur tente d’exporter une liste de tâches vers PDF et sélectionne le[!UICONTROL Autres tailles]&quot;, ils peuvent sélectionner une taille et cliquer sur [!UICONTROL Exporter], mais la liste n’est pas exportée. Il n’y a pas de message d’erreur et aucune autre indication que l’exportation a échoué.

**L’indicateur d’image ne s’affiche pas dans les notifications par e-mail**

_Notifications_

Lorsqu’un utilisateur ajoute une image à une mise à jour et qu’un email de notification est envoyé au destinataire de la mise à jour, l’email n’indique pas qu’il y a une image dans la mise à jour.

**Pages non chargées dans certains navigateurs**

_[!DNL Workfront]_

Lorsqu’un utilisateur travaille dans [!DNL Workfront], les pages ne se chargent pas et l’utilisateur voit le message d’erreur suivant :

&quot;[!UICONTROL Une erreur s&#39;est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d&#39;actualiser cette page de navigateur.]&quot;

Cela a été signalé dans

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Cette erreur se produit de manière aléatoire et peut affecter n’importe quelle zone de Workfront.

+++

+++**Mise à jour de maintenance le 11 novembre 2021**

**Problème avec les intégrations de documents, page vierge sur la fenêtre contextuelle de téléchargement de document[!DNL Google Drive*]*

_Documents_

Lorsqu’un utilisateur tente d’ajouter un nouveau document à [!DNL Workfront] de [!DNL Google Drive] en utilisant [!UICONTROL Ajouter] >[!UICONTROL De [!DNL Google Drive]], l’écran contextuel de chargement reste vide.

**Impossible d’utiliser plusieurs filtres dans l’équilibreur de charge de travail**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur tente d’utiliser plusieurs filtres dans la variable [!UICONTROL Équilibreur de charge de travail], ils rencontrent les problèmes suivants :

* Si l’utilisateur sélectionne deux filtres, seul le filtre inférieur est appliqué.
* Si l’utilisateur sélectionne plus de deux filtres, aucun résultat ne s’affiche.

**&quot;[!UICONTROL Dossiers de projet]&quot; En-tête de document manquant dans la zone de documents du projet**

_Projets_

Lorsqu’un utilisateur se trouve dans un projet et consulte les documents du projet, le titre &quot;[!UICONTROL Dossiers de projet]&quot; est absent du volet de navigation de gauche. La flèche de liste déroulante existe toujours et l’utilisateur peut sélectionner un dossier.

**Les colonnes de la carte Kanban sont trop larges et ne peuvent pas être ajustées.**

_Agile_

Lorsqu’un utilisateur consulte un panorama Kanban comportant plusieurs colonnes, celles-ci sont trop larges et il doit faire défiler l’écran pour afficher ou déplacer les cartes vers les colonnes les plus à droite. Les largeurs des colonnes ne sont pas ajustables. Par conséquent, l’utilisateur ne peut pas réduire les colonnes afin qu’elles soient toutes visibles à l’écran en même temps.

**Interface améliorée pour la création d’une nouvelle équipe**

_Équipes_

La création d’équipes est désormais plus intuitive avec de nouveaux indices visuels. Lorsque vous sélectionnez la variable [!UICONTROL Changer d’équipe] sur n’importe quelle page de l’équipe, l’icône [!UICONTROL Créer une équipe] comporte une icône pour indiquer &quot;[!UICONTROL new]&quot; et le lien est séparé du reste de la liste afin de ne pas ressembler à un nom d’équipe. Cette interface est la même pour les équipes agiles et non agiles.

+++

+++**Mise à jour de maintenance le 4 novembre 2021**

**Nouvelles tâches par défaut à une contrainte de tâche incorrecte**

_Tâches_

Lorsqu’un utilisateur crée une tâche à l’aide de la fonction &quot;[!UICONTROL Nouvelle tâche]&quot;, et l’option Nouvelle tâche par défaut Date de début est définie sur &quot;[!UICONTROL Aujourd&#39;hui],&quot; la contrainte de tâche de la tâche créée est définie sur &quot;[!UICONTROL Dès que possible]&quot; plutôt que &quot;[!UICONTROL Ne pas démarrer avant].&quot;

**Les champs ne s’affichent pas sur les cartes d’articles agiles**

_Agile_

Lorsqu’un utilisateur affiche un storboard Agile, les cartes n’affichent que la variable [!UICONTROL Description] et [!UICONTROL État] champs. Aucun autre champ, y compris les champs personnalisés, ne s’affiche.

**Les cartes reviennent à la colonne d’origine avant de passer à une nouvelle colonne.**

_Agile_

Lorsqu’un utilisateur fait glisser une carte dans une nouvelle colonne du storyboard, il peut voir la carte en cours de déplacement. Cependant, lorsque l’utilisateur fait glisser la carte dans la nouvelle colonne, elle apparaît brièvement dans la colonne d’origine avant de s’afficher dans la nouvelle colonne.

**Valeurs non disponibles pour les champs personnalisés dans le filtre**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur tente de créer un filtre à l’aide d’un champ personnalisé, la valeur de ce champ personnalisé ne s’affiche pas et ne peut pas être saisie dans le filtre.

**Pages ne se chargeant pas dans [!DNL Firefox] browser**

_[!DNL Workfront]_

Lorsqu’un utilisateur travaille dans [!DNL Workfront] à l’aide d’une [!DNL Firefox] , les pages ne se chargent pas et l’utilisateur voit le message d’erreur suivant :

&quot;[!UICONTROL Une erreur s&#39;est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d&#39;actualiser cette page de navigateur.]&quot;

Cette erreur se produit de manière aléatoire et peut affecter n’importe quelle zone de [!DNL Workfront].

**Erreur liée à la date lors de la création d’un projet à partir d’un modèle.**

_Modèles_

Si un utilisateur crée un projet à partir d’un modèle et définit le mode de planification sur [!UICONTROL Date de début], sélectionne ensuite une contrainte de tâche. Lorsque l’utilisateur tente de créer le projet, celui-ci n’est pas créé et l’utilisateur voit un message d’erreur basé sur la contrainte de tâche.

**[!UICONTROL Exporter le diagramme de Gantt] boîte de dialogue ne répond pas**

_Graphique Gantt_

Si un utilisateur dans la nouvelle [!DNL Workfront] tente d’exporter l’expérience [!UICONTROL Graphique Gantt] et sélectionne le[!UICONTROL Ce que je vois]&quot;, l’option [!UICONTROL Graphique Gantt] n’est pas exportée et la boîte de dialogue ne répond pas. L’utilisateur ne peut pas fermer ou cliquer en dehors de la boîte de dialogue.

**Les icônes ne s’affichent pas correctement**

_[!DNL Workfront]_

Les images d’icônes ne s’affichent pas correctement. Cela a été signalé dans des situations, notamment :

* Images des rôles ou groupes de tâches lors du partage d’un objet
* Icônes gauche et droite des rapports de calendrier
* Tri des icônes sur les colonnes du rapport

**Ajoutez des cases à cocher aux requêtes dans le [!UICONTROL Envoyé] de la section [!UICONTROL Demandes] area**

_Demandes_

Nous avons ajouté des cases à cocher à gauche des noms de requête dans la variable [!UICONTROL Liste envoyée] de [!UICONTROL Demandes] zone. Cela facilite la sélection d’une requête et l’affichage d’informations supplémentaires.

**Les trimestres personnalisés sont désormais pris en charge dans les filtres de l’équilibreur de charge de travail**

_[!UICONTROL Équilbreur de charge de travail]_

Les filtres de la variable [!UICONTROL Équilibreur de charge de travail] prennent désormais en charge les trimestres personnalisés.

**Mise à jour de l’opérateur de filtre pour le champ Durée dans les filtres de l’équilibreur de charge de travail**

_[!UICONTROL Équilbreur de charge de travail]_

Nous avons mis à jour les opérateurs de filtrage lors du filtrage de la variable[!UICONTROL  Équilibreur de charge de travail] zones par [!UICONTROL Durée].

+++


## Mises à jour en octobre 2021

+++**Mise à jour de maintenance le 28 octobre 2021**

**[!UICONTROL Accueil] et [!UICONTROL Mon travail] affichage d’une page vierge**

_[!UICONTROL Accueil] / [!UICONTROL Mon travail]_

Lorsqu’un utilisateur accède à [!UICONTROL Accueil] ou Mon travail, la page s’affiche comme vide.

**Impossible d’afficher ou de modifier [!UICONTROL Groupe de rubriques] détails**

_Demandes_

Lorsqu’un utilisateur tente d’afficher ou de modifier les détails d’un groupe de rubriques, la page qui s’ouvre affiche &quot;[!UICONTROL Détails du groupe de rubriques]&quot; dans l’en-tête, mais n’est pas renseigné.

**Les boutons radio vierges requis sont remplis automatiquement.**

_Demandes_

Lorsqu’un utilisateur envoie une demande avec un champ de bouton radio obligatoire et qu’il n’a pas sélectionné de valeur pour ce champ avant d’envoyer la demande, la première valeur est automatiquement sélectionnée lors de l’envoi de la demande.

+++

+++**Mise à jour de maintenance le 21 octobre 2021**

**Impossible d’ajouter un filtre dans [!UICONTROL Équilibreur de charge de travail]**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur dans la variable [!UICONTROL Équilibreur de charge de travail] tente d’ajouter un filtre, la variable [!UICONTROL Ajouter un filtre] s’ouvre, mais le contenu du panneau ne se charge pas et l’utilisateur ne peut pas ajouter le filtre.

**Carte de défilement agile n’affichant pas d’articles**

_Agile_

Lorsqu’un utilisateur tente d’afficher le Scrum board dans l’itération d’une équipe, le Scrum board s’affiche comme vide.

**La carte d’article de scrum est vide lors de l’utilisation de filtres**

_Agile_

Lorsqu’un utilisateur tente d’afficher un panorama de narration avec un script à l’aide d’un filtre autre que le[!UICONTROL Toute l&#39;équipe]&quot;, un écran vide s’affiche. L’utilisateur ne peut pas revenir au[!UICONTROL Toute l&#39;équipe]&quot;.

**Les listes ne sont visibles que dans une petite zone de l’écran.**

_Listes_

Lorsqu’un utilisateur tente d’afficher une liste tout en utilisant une [!DNL Safari] d’un navigateur [!DNL Mac] en utilisant la variable [!DNL Big Sur OS], la liste n’apparaît que sur une petite zone de l’écran. L’utilisateur peut faire défiler la liste, mais la zone peut être si petite que la liste est difficile ou impossible à lire.

**Les boutons radio vierges requis sont remplis automatiquement.**

_Demandes_

Lorsqu’un utilisateur envoie une demande avec un champ de bouton radio obligatoire et qu’il n’a pas sélectionné de valeur pour ce champ avant d’envoyer la demande, la première valeur est automatiquement sélectionnée lors de l’envoi de la demande.

+++

+++**Mise à jour de maintenance (correctif) le 21 octobre 2021**

**[!UICONTROL Accueil] et [!UICONTROL Mon travail] affichage d’une page vierge**

_[!UICONTROL Accueil] / [!UICONTROL Mon travail]_

Lorsqu’un utilisateur accède à [!UICONTROL Accueil] ou [!UICONTROL Mon travail], la page s’affiche comme vide.

+++

+++**Mise à jour de maintenance le 20 octobre 2021**

**[!UICONTROL Équilibreur de charge de travail] défini comme option de planification par défaut**

_[!UICONTROL Équilbreur de charge de travail]_

Si un utilisateur possède la variable [!UICONTROL Planificateur] défini lorsque la valeur par défaut est définie pour l’utiliser, il indique que la variable [!UICONTROL Équilibreur de charge de travail] a été défini comme valeur par défaut.

+++

+++**Mise à jour de maintenance (correctif) le 19 octobre 2021**

**Impossible d’affecter une requête lors de sa création**

_Demandes_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] l’expérience crée une requête et tente d’affecter un utilisateur en saisissant son nom dans la variable [!UICONTROL Affectations] , le champ n’affiche pas la liste déroulante et l’utilisateur ne peut pas sélectionner le nom de la personne désignée.

**La carte d’article de scrum est vide lors de l’utilisation de filtres**

_Agile_

Lorsqu’un utilisateur tente d’afficher un panorama de narration avec un script à l’aide d’un filtre autre que le[!UICONTROL Toute l&#39;équipe]&quot;, un écran vide s’affiche. L’utilisateur ne peut pas revenir au[!UICONTROL Toute l&#39;équipe]&quot;.

+++

+++**Mise à jour de maintenance le 14 octobre 2021**

**Les modèles partagés à l’échelle du système ne sont pas visibles**

_Modèles_

Lorsqu’un utilisateur crée un projet et tente d’utiliser un modèle qui a été partagé à l’échelle du système, il ne peut pas voir le modèle dans la liste des modèles disponibles et ne peut pas l’utiliser.

**Erreur lors de la création de projets à partir de modèles**

_Modèles_

Lorsqu’un utilisateur tente de créer un projet à partir d’un modèle contenant un formulaire personnalisé avec une section visible uniquement par les administrateurs, il ne peut pas créer le projet et le message suivant s’affiche :

&quot;[!UICONTROL Catégorie avec la ou les valeurs de clé Principale &quot;xxxxxxxxxxxxxxxx&quot; introuvable]&quot;

**Mise à jour des liens pour copier et déplacer des tâches**

_Tâches_

Les liens permettant de copier et de déplacer des tâches ont été mis à jour vers &quot;[!UICONTROL Copier vers]&quot; et &quot;[!UICONTROL Déplacer vers]&quot; à la fois sur la page de la tâche et dans une liste de tâches.

**Suppression de la limite de la recherche de rôle de tâche lors du remplacement des taux de facturation d’un projet**

Fonctions

REMARQUE : Cette mise à jour se trouve actuellement dans l’environnement Aperçu et sera en production avec la version de production 22.1. Pour plus d’informations, voir &quot;Présentation de la version 22.1&quot;.

Le remplacement des taux de facturation des rôles de tâche dans un projet recherche désormais tous les rôles de tâche dans le système.

Auparavant, [!DNL Workfront] ont recherché des rôles de tâche dans les 2000 premiers rôles par ordre alphabétique.

+++

+++**Mise à jour de maintenance le 7 octobre 2021**

**[!UICONTROL Les notifications in-app disparaissent de] centre de notifications**

_Notifications_

Lorsqu’un utilisateur consulte le centre de notification, certaines notifications précédemment visibles ne sont plus visibles. Dans certains cas, la notification peut disparaître avant que l’utilisateur ne la voie.

**Les annonces ne sont pas visibles sur la [!UICONTROL Toutes les annonces] page**

_Notifications_

Lorsqu’un utilisateur ouvre la variable [!UICONTROL Toutes les annonces] de la page [!UICONTROL Notifications] , aucune annonce n’est visible dans les zones suivantes :

* [!UICONTROL Boîte de réception]
* [!UICONTROL Favoris]
* [!UICONTROL Brouillons]
* [!UICONTROL Supprimé]

**Erreur lors de l’attribution dans la variable [!UICONTROL Équilibreur de charge de travail]**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur tente d’effectuer une affectation à partir de la variable [!UICONTROL Équilibreur de charge de travail], le travail n’est pas affecté et l’utilisateur voit l’erreur suivante :

&quot;[!UICONTROL Une erreur s&#39;est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d&#39;actualiser cette page de navigateur.]&quot;

+++


## Mises à jour en septembre 2021

+++**Mise à jour de maintenance le 30 septembre 2021**

**Erreur lors de la navigation rapide vers ou en dehors de [!UICONTROL Accueil]**

_Page d’accueil_

Lorsqu’un utilisateur accède rapidement à ou à partir de [!UICONTROL Accueil], la page ne se charge pas et l’utilisateur voit l’erreur suivante :

&quot;[!UICONTROL Une erreur s&#39;est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d&#39;actualiser cette page de navigateur.]&quot;

Cela peut également se produire lors de la navigation vers [!UICONTROL Accueil] via une épingle.

+++

+++**Mise à jour de maintenance le 23 septembre 2021**

**[!UICONTROL Accès refusé] erreur lors de l’affichage des tickets envoyés à[!DNL Workfront]**

_problèmes_

Lorsqu’un utilisateur a envoyé un ticket à [!DNL Workfront] et tente d’afficher le ticket, l’erreur suivante s’affiche :

&quot;[!UICONTROL Accès refusé : Oups ! Un problème est survenu. Veuillez contacter [!DNL Workfront] donc nous pouvons comprendre ce qui s&#39;est mal passé et y remédier.]&quot;

**Le résumé des cas d’entreprise affiche des valeurs incorrectes.**

_Projets_

Lorsqu’un utilisateur affiche la variable [!UICONTROL Analyse de cas] récapitulatif, les valeurs affichées ne reflètent pas les valeurs de chaque [!UICONTROL Analyse de cas] sections.

**Les en-têtes de colonne ne correspondent pas aux colonnes des listes.**

_Configuration_

Lorsqu’un utilisateur se trouve dans la variable [!UICONTROL Configuration] et affiche une liste, telle que [!UICONTROL Forms personnalisée] ou [!UICONTROL Niveaux d’accès], les en-têtes de colonne de cette liste ne s’alignent pas sur les colonnes de la liste.

**Les utilisateurs ne disposant pas des autorisations de partage appropriées peuvent joindre des formulaires personnalisés à des objets.**

_Formulaires personnalisés_

Lorsqu’un formulaire personnalisé apparaît dans la nouvelle [!DNL Adobe Workfront] est définie pour être visible à l’échelle du système, tous les utilisateurs peuvent joindre ce formulaire personnalisé à un objet . Cependant, ils doivent pouvoir uniquement afficher le formulaire personnalisé et ne pas pouvoir le joindre à un objet, sauf s’il a été partagé spécifiquement avec eux.

+++

+++**Mise à jour de maintenance le 16 septembre 2021**

**Impossible de modifier les groupes**

_Groupes_

Lorsqu’un utilisateur tente de modifier ou de supprimer un groupe, celui-ci n’est ni modifié ni supprimé, et le message suivant s’affiche :

&quot;[!UICONTROL Réessayons. Groupe avec des valeurs de clé Principales &quot;(ID de groupe)&quot; introuvable]&quot;

**[!UICONTROL Portfolio Optimizer] non-affichage des projets**

_Portefeuilles_

Lorsqu’un utilisateur tente d’afficher des projets dans la variable [!UICONTROL Portfolio Optimizer], la liste des projets ne s’affiche pas et l’utilisateur ne peut donc pas interagir avec les projets.

+++

+++**Mise à jour de maintenance (correctif) le 10 septembre 2021**

**Date et heure marquées comme UTC lors de la modification en ligne**

_Listes_

Lorsqu’un utilisateur modifie une date ou une heure intégrée (dans une liste d’objets), la date et l’heure sont signalées comme étant UTC. La date et l’heure ne sont pas définies en UTC dans [!DNL Workfront]. Ce problème affecte uniquement l’affichage, et non les données réelles.

**La couleur du texte ne s’affiche pas correctement lors de l’application d’une mise en forme conditionnelle**

_Rapports_

Lorsqu’un utilisateur consulte un rapport avec une mise en forme conditionnelle qui modifie la couleur du texte, la couleur du texte s’affiche telle quelle.

+++

+++**Mise à jour de maintenance le 9 septembre 2021**

**Les problèmes n’affichent pas les détails du problème**

_Page d’accueil_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] l’expérience sélectionne un problème dans la variable [!UICONTROL Liste de tâches], l’aperçu dans le panneau de droite affiche certains champs sans valeurs saisies. Cependant, si vous accédez au problème et affichez le [!UICONTROL Détails du problème], des valeurs sont entrées pour ces champs.

**Les utilisateurs ont besoin des autorisations de contribution pour afficher la variable [!UICONTROL Approbations] dans la nouvelle expérience Workfront**

_Approbations_

Les utilisateurs ont besoin de [!UICONTROL Contribution] autorisations sur un objet pour afficher la variable [!UICONTROL Approbations] dans la nouvelle section [!DNL Workfront] Expérience. Ils ne devraient avoir besoin que de [!UICONTROL Affichage] autorisations pour afficher la variable [!UICONTROL Approbations] lorsqu’il existe un processus d’approbation sur l’objet.

**[!UICONTROL Oups] erreur lors de l’utilisation de filtres**

_Listes_

Lorsqu’un utilisateur tente d’utiliser l’un des filtres suivants :

* [!UICONTROL Tous les projets]
* [!UICONTROL Projets auxquels je participe]
* [!UICONTROL Mes tâches actuelles]

la liste est vide et l’utilisateur voit l’erreur suivante :

&quot;[!UICONTROL Réessayons.]&quot;

**[!UICONTROL Tâches] n’est pas renseignée lors de la modification en ligne**

_Modèles_

Lorsqu’un utilisateur tente d’intégrer des tâches de modification dans un modèle à l’aide d’une vue qui inclut le[!UICONTROL Attribuer à : Nom]&quot; et l’affectation contient un utilisateur, la variable [!UICONTROL Tâches] est vide et l’utilisateur ne peut pas modifier les tâches du modèle.

**Impossible d’exporter [!UICONTROL Portfolio Optimizer]**

_Portefeuilles_

Lorsqu’un utilisateur tente d’exporter la variable [!UICONTROL Portfolio Optimizer] et clique sur l’une des options d’exportation, la variable [!UICONTROL Portfolio Optimizer] n’est pas exportée.

**Les notifications ne sont pas envoyées pour les réponses**

_Notifications_

Lorsqu’un utilisateur répond à une mise à jour dans [!DNL Workfront], les autres utilisateurs du fil de commentaire ne reçoivent pas de notifications.

**Les modifications apportées aux données personnalisées entraînent un retard**

_Champs personnalisés_

Lorsqu’un utilisateur modifie des données personnalisées qui déclenchent des modifications d’autres données affichées, les modifications se chargent lentement.

**Groupement &quot;[!UICONTROL Réduire ou Développer tout]&quot; icône ne s’affiche pas**

_Rapports_

Le &quot;[!UICONTROL Réduire ou Développer tout]&quot; ne s’affiche pas dans l’en-tête d’une liste ou d’un rapport lorsque des regroupements sont appliqués à la liste ou au rapport.

**[!UICONTROL Vérifier] et [!UICONTROL Annuler] options non visibles lors de la modification de l’affectation des tâches**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur tente de modifier l’allocation de tâche pour une tâche, et que la période de cette tâche s’étend au-delà ou au-delà du bord de la page visible, l’événement [!UICONTROL Vérifier] et [!UICONTROL Annuler] les boutons ne sont pas visibles et l’utilisateur ne peut pas enregistrer ou annuler les modifications d’affectation.

**Ajout d’un champ personnalisé à [!UICONTROL Accueil] provoque des données de champ manquantes**

_[!UICONTROL Page d’accueil]_

Lorsqu’un champ personnalisé est ajouté à [!UICONTROL Accueil], d’autres champs commencent à manquer de données et à s’afficher incorrectement.

**Impossible d’afficher les éléments liés lors de la connexion en tant qu’autre utilisateur**

_Intégrations_

Si un administrateur a tenté d’afficher les éléments liés depuis un fournisseur externe alors qu’il était connecté en tant qu’autre utilisateur, il n’a pas pu ouvrir les dossiers liés et il n’a pas pu afficher les éléments.

+++

+++**Mise à jour de maintenance le 2 septembre 2021**

**Impossible d’épingler le tableau de bord personnalisé**

_Tableaux de bord_

Lorsqu’un utilisateur tente d’épingler un tableau de bord personnalisé, celui-ci n’épingle pas et affiche l’erreur suivante :

&quot;[!UICONTROL Quelque chose s’est mal passé lors de la mise en classe. Veuillez contacter [!DNL Workfront] nous pouvons donc réparer ceci.]&quot;

**[!DNL Workfront Proof]résumé d’impression vide**

[!DNL Workfront Proof]

Lorsqu’un utilisateur ouvre la synthèse d’impression pour imprimer un BAT, l’en-tête s’affiche, mais la synthèse elle-même est vide.

+++


## Mises à jour en août 2021

+++**Mise à jour de maintenance le 26 août 2021**

**Dans [!DNL Safari] le texte des en-têtes de colonne comporte un arrière-plan gris foncé**

_Listes_

Dans le [!DNL Safari] , un arrière-plan gris foncé s’affiche sur les en-têtes de colonne, mettant le texte en surbrillance. Il ne s’agit d’aucun problème avec les autres navigateurs pris en charge.

**Erreur inattendue lors de la définition des prédécesseurs**

_Tâches_

Lorsqu’un utilisateur tente de définir une tâche en tant que prédécesseur à l’aide d’une modification en ligne, le prédécesseur n’est pas défini et l’utilisateur voit le message suivant :

&quot;[!UICONTROL Une erreur inattendue s&#39;est produite]&quot;

+++

+++**Mise à jour de maintenance le 19 août 2021**

**Filtres enregistrés manquants après la sélection d’un filtre qui n’affiche aucun problème**

_Listes_

Il manque des filtres enregistrés dans une liste de problèmes après avoir sélectionné un filtre qui n’affiche aucun résultat.

**Les problèmes n’affichent pas les détails du problème**

_[!UICONTROL Accueil] summary_

Lorsqu’un utilisateur se connecte à [!DNL Adobe Workfront Classic] sélectionne un problème dans la variable [!UICONTROL Liste de tâches], l’aperçu dans le panneau de droite affiche certains champs sans valeurs saisies. Cependant, si vous accédez au problème et affichez le [!UICONTROL Détails du problème], des valeurs sont entrées pour ces champs.

+++

+++**Mise à jour de maintenance le 12 août 2021**

**Impossible de personnaliser la vue agile sur le projet**

_Agile_

Lorsqu’un utilisateur tente de personnaliser une vue agile existante sur un projet, la fenêtre se ferme et l’utilisateur ne peut pas la modifier.

**Le nom ne change pas dans les nouvelles versions du document.**

_Documents_

Lorsqu’un utilisateur charge une nouvelle version d’un document, le nom du document ne se met pas à jour pour correspondre au nom de la version la plus récente.

**L’icône du prédécesseur n’est pas verte lorsque le prédécesseur est terminé.**

_Tâches_

Lorsqu’une tâche comporte une tâche de prédécesseur et que celle-ci est terminée, l’icône de prédécesseur de la tâche dépendante ne devient pas verte.

Lorsqu’un formulaire personnalisé apparaît dans la nouvelle [!DNL Adobe Workfront] est définie pour être visible à l’échelle du système, tous les utilisateurs peuvent joindre ce formulaire personnalisé à un objet . Cependant, ils doivent pouvoir uniquement afficher le formulaire personnalisé et ne pas pouvoir le joindre à un objet, sauf s’il a été partagé spécifiquement avec eux.

+++

+++**Mise à jour de maintenance (correctif) le 6 août 2021**

**Impossible de sélectionner les calendriers dans [!DNL Outloo]k Paramètres du calendrier**

_Page d’accueil_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] l’expérience visionne leur [!DNL Outlook] Calendrier à l’accueil. Pour ouvrir les paramètres, les cases à cocher de sélection des calendriers sont manquantes. Si l’utilisateur clique sur l’emplacement de la case à cocher, le calendrier répond comme si la case était activée.

**Impossible de réautoriser ou de vérifier la connexion à [!UICONTROL Webdam]**

_[!DNL Workfront Fusion]_

[!DNL Adobe Workfront Fusion] utilisateurs avec des scénarios de connexion à [!UICONTROL Webdam] Notez que [!UICONTROL Webdam] les connexions nécessitent une réauthentification manuelle tous les 14 jours. Le [!UICONTROL Webdam] Actuellement, l’API ne prend pas en charge la réautorisation automatique.

+++

+++**Mise à jour de maintenance le 5 août 2021**

**Impossible d’interagir avec le document dans [!UICONTROL Panneau Résumé] ou [!UICONTROL Plus] menu**

_Documents_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] l’expérience consulte un document et tente d’effectuer une sélection dans le [!UICONTROL Panneau Résumé] ou le [!UICONTROL Plus] , le document est désélectionné, ce qui entraîne la [!UICONTROL Panneau Résumé] ou [!UICONTROL Plus] pour afficher la zone vide.

**[!UICONTROL Nouvelle requête] bouton manquant**

_Demandes_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] l’expérience se rend à la fonction [!UICONTROL Demandes] , [!UICONTROL Nouvelle requête] ne s’affiche pas et ne peut pas envoyer de requête.

**Les utilisateurs ne disposant pas des autorisations de partage appropriées peuvent joindre des formulaires personnalisés à des objets.**

_Formulaires personnalisés_

Lorsqu’un formulaire personnalisé apparaît dans la nouvelle [!DNL Adobe Workfront] est définie pour être visible à l’échelle du système, tous les utilisateurs peuvent joindre ce formulaire personnalisé à un objet . Cependant, ils doivent pouvoir uniquement afficher le formulaire personnalisé et ne pas pouvoir le joindre à un objet, sauf s’il a été partagé spécifiquement avec eux.

**Impossible de modifier les paramètres du BAT lors de la création d’un BAT**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur crée un BAT et tente de modifier les paramètres, le paramètre revient à un paramètre précédent.

**[!UICONTROL Story Board] ne se charge pas correctement**

_Agile_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] l’expérience accède à un [!UICONTROL Story Board], le chargement du panorama peut prendre jusqu’à 10 secondes. Le retard de chargement est dû au chargement de toutes les cartes par le système, alors qu’il ne doit charger que 50 cartes à la fois.

+++


## Mises à jour en juillet 2021

+++**Mise à jour de maintenance (correctif) le 29 juillet 2021**

**Impossible de charger le nouveau BAT ou la nouvelle version du BAT**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur tente de charger un nouveau BAT ou une nouvelle version d’un BAT dans la [!DNL Workfront] , la page du nouveau BAT ou de la nouvelle version est vide et l’utilisateur ne peut pas télécharger le BAT ou la version.

+++

+++**Mise à jour de maintenance le 29 juillet 2021**

**[!UICONTROL Activité de BAT] et [!UICONTROL Paramètres de la visionneuse de BAT] pages toujours disponibles**

_[!DNL Workfront Proof]_

Le [!UICONTROL Activité de BAT] et [!UICONTROL Visionneuse de BAT] Les pages Paramètres sont désormais toujours visibles, même si l’utilisateur n’a pas accès à la mise à jour de ces pages.

Auparavant, lorsqu’un utilisateur disposant d’un profil d’autorisation de BAT personnalisé naviguait vers un document, la variable [!UICONTROL Activité de BAT] et [!UICONTROL Paramètres de la visionneuse de BAT] les pages de gauche n’étaient pas toujours visibles.

**Message d’erreur lors de l’utilisation de [!UICONTROL Pourcentage] option pour [!UICONTROL Heures affectées]**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur sélectionne la variable [!UICONTROL Pourcentage] option pour [!UICONTROL Heures affectées], et des travaux sont répertoriés dans la section [!UICONTROL Travail non attribué] , l’utilisateur voit l’erreur suivante :

&quot;[!UICONTROL Une erreur s&#39;est produite et nous nous efforçons de la résoudre. Pour continuer votre travail, essayez d&#39;actualiser cette page de navigateur.]&quot;

+++

+++**Mise à jour de maintenance le 22 juillet 2021**

**Les nouveaux noms de version de BAT sont coupés.**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur se connecte à [!DNL Adobe Workfront Classic] télécharge une nouvelle version d&#39;un BAT contenant un point dans le nom du fichier, le nom du fichier est coupé à la fin.

+++

+++**Mise à jour de maintenance (correctif) le 19 juillet 2021**

**Erreur lors de la tentative de navigation vers des projets, des feuilles de temps, des tâches ou des programmes**

Dans la nouvelle [!DNL Adobe Workfront] expérience, lorsqu’un utilisateur tente d’accéder à des projets, des feuilles de temps, des tâches ou des programmes, il voit le message d’erreur &quot;[!UICONTROL Oups ! Un problème est survenu. Veuillez contacter [!DNL Workfront] donc nous pouvons comprendre ce qui s&#39;est mal passé et y remédier.]&quot;

+++

+++**Mise à jour de maintenance le 15 juillet 2021**

**La priorité par défaut sur les nouvelles requêtes est incorrecte**

_Demandes_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] crée une requête, la requête ne respecte pas la priorité par défaut définie dans [!UICONTROL Préférences du projet] et ils ne peuvent pas ajuster la priorité avant d’envoyer la demande.

**[!UICONTROL Accéder au BAT] lien ne dirige pas vers un commentaire**

_Notifications par e-mail_

Lorsqu’un utilisateur reçoit une notification par courrier électronique pour un commentaire de BAT, il clique sur [!UICONTROL Accéder au BAT], ils sont dirigés vers le mauvais commentaire dans le BAT ou ils ne sont pas du tout dirigés vers un commentaire.

**Valeurs de champ de texte enrichi non transférées après la conversion d’un problème en tâche**

_Formulaires personnalisés_

Lorsqu’un utilisateur convertit un problème en tâche et qu’il y a un formulaire personnalisé associé avec une valeur saisie dans un champ de texte avec mise en forme de texte enrichi, la valeur du champ de texte n’est pas reportée après la conversion.

**Les valeurs de champ personnalisées changent après sélection**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] l’expérience crée un BAT et elle saisit une valeur dans certains champs personnalisés sur un BAT. La valeur de certains champs précédents revient aux valeurs par défaut au lieu de la valeur saisie par l’utilisateur.

**[!UICONTROL Attribuer à] typeforward ne fonctionne pas**

_[!UICONTROL Page d’accueil]_

Lorsqu’un utilisateur se connecte à [!DNL Adobe Workfront Classic] crée un projet, une tâche ou une requête à partir de la fonction [!UICONTROL Accueil] , la zone [!UICONTROL Attribuer à] le champ type ne renseigne pas les noms d’utilisateur.

**Les heures arrondissent incorrectement**

_Feuilles de temps_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] l’expérience accède à [!UICONTROL Feuilles de temps] > [!UICONTROL Toutes les feuilles de calcul], ils constatent que le nombre total d’heures pour certaines feuilles de temps est arrondi à une décimale au lieu de 0,25, mais que le nombre total d’heures s’affiche correctement dans la feuille de temps individuelle. Par exemple, dans la zone Toutes les feuilles de temps, une feuille de temps affiche 44,8 heures au total, mais lors de l’ouverture de la feuille de temps, elle affiche 44,75 heures au total.

**Impossible de déléguer les approbations**

_[!UICONTROL Page d’accueil]_

Lorsqu’un utilisateur se connecte à [!DNL Adobe Workfront Classic] clics [!UICONTROL Déléguer mes approbations] dans le [!UICONTROL Accueil] et ils commencent à saisir le nom de l’utilisateur auquel ils tentent de déléguer ; aucun résultat ne s’affiche dans la variable [!UICONTROL typeforward] et ne peuvent pas sélectionner d’utilisateur.

**[!UICONTROL Graphique Gantt] La vue n’est pas disponible pour les rapports de tâches**

_Rapports_

REMARQUE : Cela affecte également les rapports de projet.

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] l’expérience ouvre un rapport Tâche, l’option permettant de sélectionner un [!UICONTROL Graphique Gantt] est absent de la barre d’outils du rapport. Si la variable [!UICONTROL Graphique Gantt] est sélectionnée pour s’afficher par défaut dans le rapport. un format de liste s’affiche à la place.

**Cliquer [!UICONTROL Voir Plus] sur le rapport ne charge rien**

_Tableaux de bord_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] une expérience affiche un rapport sur un tableau de bord et elle clique sur la variable [!UICONTROL Voir Plus] , rien ne se passe et ils ne peuvent pas afficher tous les éléments du rapport.

+++

+++**[!DNL Adobe Workfront Fusion]Mise à jour de maintenance le 1er juillet 2021**

**La copie des modules ne fonctionne pas**

_[!DNL Adobe Workfront Fusion]_

Lorsqu’un utilisateur sélectionne plusieurs modules et tente de les copier et de les coller, les modules ne sont pas collés.

+++

+++**Mise à jour de maintenance le 1er juillet 2021**

**Jeu de couleurs pour les cartes non respectées**

_Kanban_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] l’expérience définit des couleurs de carte spécifiques dans les paramètres de l’équipe. Ces couleurs ne sont pas répercutées sur les cartes Kanban.

**Impossible de coller le texte dans le champ de message personnalisé**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur crée un BAT dans le [!UICONTROL Visionneuse de test Web] et ils tentent de coller du texte dans le [!UICONTROL Message] dans le champ [!UICONTROL Notification par email] ne peuvent pas coller le texte. Cela ne semble se produire que lorsque le texte a une mise en forme de paragraphe et qu’il y a un saut de paragraphe.

**Les demandes sont envoyées avec des champs obligatoires vierges**

_Demandes_

Lorsqu’un utilisateur émet une requête et l’envoie, les informations contenues dans les champs requis ne sont pas envoyées avec la requête.

**[!UICONTROL Nouvelle requête] bouton manquant**

_Demandes_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] l’expérience se rend à la fonction [!UICONTROL Demandes] , [!UICONTROL Nouvelle requête] ne s’affiche pas et ne peut pas envoyer de requête.

**Erreur lors du développement d’un formulaire personnalisé**

_Projets_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] expérience tente d’étendre un formulaire personnalisé joint à un projet. Il ne peut pas ouvrir le formulaire personnalisé et voir le message d’erreur &quot;[!UICONTROL Une erreur s’est produite et nous travaillons à résoudre le problème. Pour poursuivre votre travail, essayez d’actualiser cette page de navigateur.]&quot;L’actualisation de la page ne résout pas le problème.

**[!DNL Adobe Workfront]la marque apparaît maintenant dans les emails du centre d’annonce**

Emails

Comme la variable [!DNL Adobe Workfront] l’identité graphique est déployée dans l’application. les mises à jour suivantes ont été apportées aux emails du centre d’annonce :

* Le [!DNL Adobe Workfront] lion a été ajouté à la zone de contenu principale.
* Le [!DNL Adobe Workfront] Le logo a été ajouté au pied de page.

À l’avenir, cette valorisation de marque s’affichera sur d’autres types d’emails provenant de Workfront.

+++


## Mises à jour en juin 2021

+++**Mise à jour de maintenance le 24 juin 2021**

**Impossible de modifier une équipe**

_Agile_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] clics sur une expérience [!UICONTROL Modifier] pour ouvrir le [!DNL Edit] Page Équipe pour une équipe Agile, la page se charge initialement, puis les paramètres disparaissent et elle reste vide.

**Données supprimées d’une requête envoyée**

_Demandes_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] l’expérience remplit une requête, les valeurs saisies de la requête envoyée sont absentes pour certains champs personnalisés, y compris parfois les champs obligatoires.

**Les colonnes ne s’affichent pas**

_Kanban_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] expérience ajoute une [!UICONTROL Champs supplémentaires] sur un panorama Kanban, tous les en-têtes de colonne ne s’affichent plus sur le panorama.

+++

+++**[!DNL Adobe Workfront Fusion]Mise à jour de maintenance le 23 juin 2021**

**Suppression du lien rompu dans les emails de notification**

_[!DNL Adobe Workfront Fusion]_

Nous avons supprimé le lien vers les paramètres de notification de [!DNL Adobe Workfront Fusion] e-mails de notification.
Pour plus d’informations sur la modification des paramètres de notification, voir [!DNL Adobe Workfront Fusion] organisations et équipes.

+++

+++**Mise à jour de maintenance le 17 juin 2021**

**[!UICONTROL Graphique Gantt] La vue n’est pas disponible pour le rapport Tâche**

_Rapports_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] l’expérience ouvre un rapport Tâche, l’option permettant de sélectionner un [!UICONTROL Graphique Gantt] est absent de la barre d’outils du rapport. Si la variable [!UICONTROL Graphique Gantt] est sélectionnée pour s’afficher par défaut dans le rapport. un format de liste s’affiche à la place.

**Erreur de limite de caractères non survenue lors des envois de requête**

_Demandes_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] une expérience tente d’envoyer une requête et dépasse la limite de caractères d’un champ. elle ne peut pas envoyer la requête et aucun message d’erreur ne s’affiche. Dans [!DNL Adobe Workfront Classic], l’utilisateur voit l’avertissement &quot;[!UICONTROL [nombre] lorsqu’ils tentent d’envoyer la demande, le message d’erreur &quot;Veuillez vérifier les points suivants : Ne saisissez pas plus de 2 000 caractères (vous avez saisi [nombre] ).]&quot;

+++

+++**Mise à jour de maintenance le 10 juin 2021**

**Les tâches de modèle réorganisées ne sont pas déplacées.**

_Modèles_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] expérience fait glisser une tâche de modèle vers un nouvel emplacement dans une liste, le nombre de tâches de modèle est mis à jour, mais elle ne réorganise pas.

**Tâches enfants non sélectionnées avec les tâches parents**

_Modèles_

Lorsqu’un utilisateur sélectionne une tâche mère sur un projet créé à partir d’un modèle, les tâches filles ne sont pas automatiquement sélectionnées.

**La modification en ligne des jalons d’une liste de tâches affiche tous les jalons**

_Projets_

Lorsqu’un chemin d’accès de jalon est ajouté à un projet et qu’un utilisateur est ajouté à la nouvelle [!DNL Adobe Workfront] les modifications intégrées de l’expérience [!UICONTROL Milestone : Nom] sur cette liste de tâches, tous les chemins d’accès aux jalons apparaissent dans le menu déroulant, plutôt que simplement les chemins d’accès aux jalons qui ont été associés à ce projet.

+++

+++**Mise à jour de maintenance le 3 juin 2021**

**L’invite fait trembler la page.**

_Rapports_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] expérience exécute un rapport avec une invite, les colonnes du rapport se déplacent rapidement de gauche à droite.

**Quelques phrases sur [!UICONTROL Nouveau BAT] ne traduisent pas correctement les pages**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur accède à la variable [!UICONTROL Nouvelle création de BAT] page [!DNL Workfront Proof] et que le contenu est traduit dans une autre langue que l&#39;anglais, certaines expressions s&#39;affichent toujours en anglais.

**Étiquettes désactivées et supprimées ajoutées aux utilisateurs[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

[!UICONTROL Désactivé] et [!UICONTROL Supprimé] des libellés d’utilisateur ont été ajoutés aux zones suivantes dans [!DNL Workfront] Bon à tirer :

* [!UICONTROL Détails du BAT] page
* [!UICONTROL Vues du contrôle]
* [!UICONTROL Visionneuse de vérification]
* [!UICONTROL Workflows de vérification]
* [!UICONTROL Imprimer les commentaires] page
* [!UICONTROL Utilisateur] page

+++


## Mises à jour en mai 2021

+++**Mise à jour de maintenance le 27 mai 2021**

**[!UICONTROL Date de validation] le calendrier s’affiche pour les mises à jour**

_Tâches_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] l’expérience entre dans une mise à jour d’une tâche, la variable [!UICONTROL Date de validation] le calendrier s’affiche sans que l’utilisateur ne sélectionne [!UICONTROL Date de validation] champ .

**[!UICONTROL Plus] menu manquant dans les filtres, les vues et les regroupements**

_Listes_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Adobe Workfront] l’expérience affiche les filtres, les vues ou les regroupements pour une liste, la variable [!UICONTROL Plus] l’icône de menu est manquante, ce qui les empêche de partager ou, s’ils y ont accès, de supprimer des filtres, des vues ou des regroupements.

**Copie et collage d’un projet [!UICONTROL Numéro de référence] ajoute &quot;[!UICONTROL Ceci]&quot;**

_Projets_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] l’expérience accède à un projet et copie la variable [!UICONTROL Numéro de référence] de la [!UICONTROL Présentation] , puis colle le mot &quot;[!UICONTROL Ceci]&quot; est ajouté à la fin du nombre.

**[!UICONTROL Résumé quotidien] les emails sont envoyés lorsqu’ils sont désactivés ;**

_Notifications par e-mail_

Certains utilisateurs reçoivent [!UICONTROL Résumé quotidien] notifications par e-mail lorsqu’elles n’ont pas été activées dans leurs paramètres utilisateur.

**L’erreur de l’objet n’existe plus**

_Objets_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] l’expérience tente d’ouvrir certains objets, le message d’erreur &quot;[!UICONTROL Le (objet) n’existe plus : Vous avez peut-être tapé l’adresse web de manière incorrecte. Vérifiez deux fois et essayez à nouveau de saisir l’adresse.]Le lien de l’objet apparaît toujours dans les listes, les récents, les favoris, les résultats de recherche, etc., mais il n’est pas accessible et il n’apparaît pas dans la Corbeille avec les objets supprimés.



+++

+++**Mise à jour de maintenance le 20 mai 2021**

**Les options de BAT sont manquantes**

_Épreuves_

Lorsqu’un utilisateur charge une autre version d’un BAT dans [!DNL Workfront], la variable [!UICONTROL Bon à tirer ouvert] et [!UICONTROL Workflow de vérification] des liens sont manquants, ce qui donne l&#39;impression qu&#39;il s&#39;agit d&#39;un document plutôt que d&#39;une preuve. Lorsque ces liens sont manquants, le libellé [!UICONTROL En attente] s’affiche également et les autres utilisateurs ne peuvent pas générer le BAT lorsqu’il est dans celui-ci ; [!UICONTROL En attente] statut.

**Utilisateurs ne recevant pas de diffusions de rapports planifiées**

_Rapports_

Lorsque la remise de certains rapports est planifiée, les utilisateurs ne reçoivent parfois pas les rapports.

**Impossible de supprimer l’accès pour le modèle de mise en page**

_Tableaux de bord_

Lorsqu’un utilisateur s’ouvre [!UICONTROL Partage] options d’un tableau de bord pour supprimer l’accès à un modèle de mise en page, pas [!UICONTROL Supprimer] s’affiche en regard du modèle de mise en page et ne peut pas supprimer l’accès.

+++

+++**[!DNL Workfront Fusion]Mise à jour de la maintenance le 17 mai 2021**

**Le tableau de bord de l’organisation affiche désormais correctement le nombre de scénarios principaux.**

_[!DNL Workfront Fusion]_

Le [!UICONTROL Organisation] Le tableau de bord présentait auparavant un champ vierge au lieu du nombre de scénarios utilisés.

**La navigation dans l’entrepôt de données affiche désormais les libellés de colonne.**

_[!DNL Workfront Fusion]_

Les structures de données qui utilisaient les libellés de colonne affichaient auparavant le nom de la colonne dans la variable [!UICONTROL navigation dans l’entrepôt de données] vue.  Désormais, le libellé de colonne s’affiche.  Si aucun libellé n’est identifié pour la colonne, le nom de la colonne s’affiche.

**L’erreur d’initialisation du scénario n’affecte plus les données de webhook.**

_[!DNL Workfront Fusion]_

Auparavant, un scénario initié par webhook (y compris ceux qui utilisent des événements temps réel pour se déclencher) qui rencontrait une erreur lors de l’initialisation du scénario pouvait entraîner une perte d’accès à ces données webhook.  Désormais, si une erreur se produit lors de l’initialisation du scénario (par exemple, si vous ne pouvez pas vérifier une connexion), les données du webhook sont conservées dans la file d’attente du webhook et l’exécution est automatiquement relancée.  Après trois tentatives infructueuses, le scénario est désactivé et les informations restent dans la file d’attente.

**Les enregistrements des files d’attente webhook sont désormais traités par lots plus petits.**

_[!DNL Workfront Fusion]_

Auparavant, si un utilisateur activait un scénario inactif auquel était associée une file d’attente webhook de plusieurs enregistrements, [!DNL Workfront Fusion] tenterait de traiter la file d’attente entière en une seule exécution (plusieurs cycles toutefois).  Selon la quantité d&#39;enregistrements traités, cela peut parfois entraîner une exécution unique dépassant le temps d&#39;exécution maximum (40 minutes).  Désormais, lorsque vous activez un scénario inactif qui comporte une file d’attente d’enregistrements webhook associée, Workfront Fusion traite jusqu’au nombre maximum d’enregistrements identifiés dans une seule exécution (généralement 2 enregistrements par exécution).

**Les entrepôts de données affichent désormais correctement les valeurs &quot;0&quot;.**

_[!DNL Workfront Fusion]_

Auparavant, les valeurs d’entrepôt de données de 0 s’affichaient comme vides. &lt;...>

+++

+++**Mise à jour de la maintenance le 13 mai 2021**

**Le calendrier déroulant s’affiche derrière le [!UICONTROL Travail non attribué] header**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur accède à la variable [!UICONTROL Équilibreur de charge de travail] in [!DNL Workfront Classic], le haut du sélecteur de données est masqué derrière le [!UICONTROL Travail non attribué] qui empêche l’utilisateur de naviguer vers différents mois.

**Impossible de coller le texte dans le champ de message personnalisé**

_[!DNL Workfront Proof]_

Remarque : Ce problème semble affecter uniquement la variable [!DNL Google Chrome] navigateur web pour l’instant.

Lorsqu’un utilisateur crée un BAT dans [!DNL Workfront Proof] et ils tentent de coller le texte d’un courrier électronique dans le [!UICONTROL Message] dans le champ [!UICONTROL Notification par email] ne peuvent pas coller le texte.

**Les champs non pris en charge s’affichent dans le créateur**

_Formulaires personnalisés_

Lorsqu’un utilisateur crée un formulaire personnalisé et tente de créer un champ calculé à l’aide d’un champ dynamique, tel que [!UICONTROL Nombre de risques ouverts]: la zone de calcul met en surbrillance le rouge et ne vous permet pas d’enregistrer vos modifications. Les champs dynamiques ne doivent pas s’afficher dans le sélecteur pour les champs calculés.

**Aperçu des tâches dans [!UICONTROL Liste de tâches] ne se chargera pas**

_Page d’accueil_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] est affectée à un modèle de mise en page qui inclut des champs personnalisés sur [!UICONTROL Accueil], la page ne répond pas et ne charge pas les tâches à partir de la fonction [!UICONTROL Liste de tâches] si l’utilisateur les sélectionne.

**Objets dans [!UICONTROL Liste de tâches] ne se charge pas dans [!UICONTROL Accueil]**

_[!UICONTROL Page d’accueil]_

Lorsqu’un utilisateur clique sur un objet dans la variable [!UICONTROL Liste de travail à domicile], l’en-tête de l’objet s’affiche dans le panneau de droite, mais les détails de l’objet n’apparaissent pas. Finalement, l’utilisateur voit le message &quot;[!UICONTROL Pages sans réponse.]&quot;

**Problèmes liés aux champs de texte enrichi[!DNL Microsoft Outlook]**

_Intégrations Workfront_

Lorsqu’un utilisateur met à jour un champ de texte enrichi avec la variable [!DNL Workfront for Outlook] intégration, ils ne peuvent pas :

* Retour arrière
* Copier du texte
* Coller le texte
* Envoyer une requête lorsque tous les champs sont renseignés

+++

+++**Mise à jour de maintenance le 6 mai 2021**

**[!UICONTROL Devise] ne fonctionne pas comme prévu**

_Listes_

Lorsqu’un utilisateur tente de modifier la devise en ligneChamp de devise dans une liste, ils ne peuvent pas enregistrer les modifications en raison des problèmes suivants :

* Les listes Tâche et Problème ne permettent pas la saisie de symboles de devise
* Listes ne permettant pas la saisie d’abréviations de devise lors de l’utilisation d’un paramètre régional autre que l’anglais
* Les listes Subtask et Issue ne permettent que l’abréviation de la devise USD, quelle que soit la devise du projet définie.

**Nom non mis à jour pour correspondre au nouveau nom du BAT**

_Documents_

Lorsqu’un utilisateur crée une version d’un BAT et qu’il met à jour son nom, l’objet document dans [!DNL Workfront] conserve le nom d’origine au lieu de correspondre au nouveau nom du BAT.

**[!UICONTROL Analyse de cas] les boutons ne fonctionnent pas lorsque des formulaires personnalisés sont joints**

_Projets_

Lorsqu’un projet dans la nouvelle [!DNL Workfront] l’expérience est créée à partir d’un modèle de projet et un formulaire personnalisé est joint, les utilisateurs ne peuvent pas envoyer, rejeter ou approuver un dossier commercial.

**BAT archivé affiché dans les listes et les rapports**

_Épreuves_

Lorsqu’un utilisateur affiche sa liste de tâches dans [!UICONTROL Accueil] ou [!UICONTROL Mon travail], les bons à tirer déjà archivés apparaissent dans la liste. Les bons à tirer archivés apparaissent également sur les rapports et les tableaux de bord.

**Les paramètres d’accès aux projets créés à partir d’un modèle sont incorrects.**

_Projets_

Lorsqu’un utilisateur crée un projet à partir d’un modèle, les paramètres d’accès du modèle ne sont pas transférés vers le nouveau projet créé.

**Objets dans [!UICONTROL Liste de tâches] ne se charge pas dans [!UICONTROL Accueil]**

_[!UICONTROL Page d’accueil]_

Lorsqu’un utilisateur clique sur un objet dans la variable [!UICONTROL Liste de travail à domicile], l’en-tête de l’objet s’affiche dans le panneau de droite, mais les détails de l’objet n’apparaissent pas. Finalement, l’utilisateur voit le message &quot;[!UICONTROL Pages sans réponse.]&quot;

+++


## Mises à jour en avril 2021

+++**Mise à jour de maintenance le 29 avril 2021**

**[!DNL SharePoint]intégration s’authentifie à l’aide des informations d’identification d’une intégration distincte**

_Intégrations Workfront_

Lorsqu’un utilisateur en possède plusieurs [!DNL SharePoint] intégration, une [!DNL SharePoint] tente d’authentification à l’aide des informations d’identification d’une autre [!DNL SharePoint] intégration.

**Impossible de charger ou d’exporter des fichiers depuis [!DNL Adobe] products**

_Intégrations Workfront_

Lorsqu’un utilisateur tente de charger ou d’exporter des fichiers à l’aide de la variable [!DNL Workfront for Adobe Creative Cloud] intégration, le message d’erreur &quot;[!UICONTROL Impossible de lire la propriété &quot;phases&quot; non définie]&quot; et ne peuvent pas télécharger ni exporter les fichiers.

**Les fichiers ne sont pas visibles dans[!DNL Internet Explorer]**

_Documents_

Lorsqu’un utilisateur dispose d’un [!DNL Internet Explorer] accède au [!UICONTROL Documents] d’un objet, la fonction [!UICONTROL Documents] est vide et ne charge pas les fichiers. Pour certains utilisateurs, l’écran charge certains fichiers, mais le nombre de fichiers qui s’affichent ne correspond pas au nombre affiché en regard de l’option [!UICONTROL Documents] .

+++

+++**Mise à jour de maintenance le 22 avril 2021**

**Tâches ajoutées dans le mauvais ordre**

_Modèles_

Lorsqu’un utilisateur ajoute une tâche à un modèle, la tâche ne reçoit pas le numéro de tâche attendu et la tâche est ajoutée au mauvais endroit.

**Les bons à tirer sont désormais combinés dans un seul email.**

_Épreuves_

[!DNL Workfront] envoie maintenant un email pour les bons à tirer combinés plutôt que d’envoyer un email pour chaque fichier inclus.
+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 15 avril 2021**

**&quot;[!UICONTROL Scénario rejeté]&quot;erreur lors de l’exécution d’un scénario**

_[!DNL Workfront Fusion]_

Lorsqu’un utilisateur tente d’exécuter un scénario, celui-ci ne s’exécute pas et il reçoit le message &quot;[!UICONTROL Scénario rejeté.]&quot;

+++

+++**Mise à jour de maintenance le 15 avril 2021**

**[!UICONTROL Équilibreur de charge de travail] affiche des heures planifiées incorrectes**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur affiche les heures planifiées d’une tâche dans la variable [!UICONTROL Équilibreur de charge de travail] la valeur des heures planifiées ne correspond pas aux heures planifiées affectées à la tâche.

**La barre de navigation supérieure n’est pas visible dans[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur accède à une [!DNL Workfront Proof] en dehors de la page Tableau de bord , la barre de navigation supérieure disparaît. L’utilisateur ne peut pas accéder aux fonctionnalités de la barre de navigation, telles que les paramètres de son compte ou son profil.

**Amélioration des formulaires personnalisés**

_Formulaires personnalisés dans mon groupe_

Pour une meilleure expérience lorsque vous remplissez un formulaire personnalisé, nous avons amélioré l’affichage des libellés de champ personnalisés longs. Lorsqu’il y a suffisamment d’espace horizontal pour les afficher dans leur intégralité, ces libellés ne sont plus tronqués.

+++

+++**Mise à jour de maintenance le 8 avril 2021**

**Impossible de créer des bons à tirer dans [!DNL Adobe Creative Cloud] integration**

_Intégrations Workfront_

Lorsqu’un utilisateur tente de créer un BAT directement à partir de la variable [!DNL Adobe Creative Cloud], le BAT n’est pas généré.

+++

+++**Mise à jour de maintenance le 1er avril 2021**

**Problèmes lors de l’affichage du panneau de résumé dans[!DNL Chrome]**

_[!UICONTROL Résumé]_

Lorsqu’un utilisateur ouvre la variable [!UICONTROL Résumé] lors de l’utilisation du panneau [!DNL Chrome] , l’interface utilisateur du panneau de résumé ne se comporte pas comme prévu. L’utilisateur ne peut pas faire défiler l’écran, les icônes peuvent disparaître et le contenu peut chevaucher d’autres contenus.

**[!UICONTROL Équipes] area dans [!UICONTROL Configuration] ne pas afficher toutes les équipes**

_[!UICONTROL Configuration]_

Lorsqu’un administrateur accède à la variable [!UICONTROL Équipes] area of [!UICONTROL Configuration], ils ne peuvent afficher que les équipes qu’ils ont créées. Les équipes créées par d’autres administrateurs ne sont pas visibles.

**Impossible d’ajouter des mises à jour au projet dans [!UICONTROL En attente d’approbation] status**

_Projets_

Si un utilisateur tente d’ajouter une mise à jour à un projet dans [!UICONTROL En attente d’approbation] et qu’il ne s’agit pas de l’utilisateur chargé d’approuver le projet, la mise à jour n’est pas ajoutée et l’avis suivant s’affiche :

Un projet avec un[!DNL Pending Approval]Le statut &quot; ne peut pas être modifié. Vous pouvez modifier le projet en modifiant son état.

+++


## Mises à jour en mars 2021

+++**Mise à jour de maintenance le 26 mars 2021**

**Les boutons d’un cas d’entreprise ne s’affichent pas correctement**

_Projets_

Lorsqu’un utilisateur consulte un dossier d’entreprise et que la fenêtre est en mode plein écran, la variable [!UICONTROL Enregistrer] et [!UICONTROL Annuler] des boutons s’affichent au milieu de l’écran, chevauchant des éléments de Business Case.

**Impossible de modifier le tri d’un rapport**

_Rapports_

Lorsqu’un utilisateur tente de modifier le tri d’un rapport dans la nouvelle [!DNL Workfront] , le tri ne change pas par rapport au tri sélectionné lors de la création du rapport.

**Partage désactivé sur les nouveaux BAT**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur possède [!UICONTROL Partage public] activé dans leurs paramètres de BAT par défaut crée un BAT, le BAT est créé avec le partage désactivé. Les autres utilisateurs ne peuvent pas voir la variable [!UICONTROL Partager] ou partager le BAT.

**&quot;[!UICONTROL Échec de la génération de la preuve]&quot; erreur lors de la création du BAT**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur tente de créer un BAT, le BAT n’est pas créé et l’utilisateur voit le message d’erreur suivant :

&quot;[!UICONTROL Échec de la génération de la preuve — erreur interne]&quot;

+++

+++**[!DNL Workfront Fusion]Mise à jour de maintenance le 25 mars 2021**

**Suppression d’un champ de collection ou de référence redondant du panneau de mappage**

_[!DNL Workfront Fusion]2,0_

Lorsqu’un utilisateur utilise un terme de la fonction [!DNL Workfront] API permettant de sélectionner un champ de collection ou de référence à inclure dans la sortie d’une [!DNL Workfront] , la sortie de ce module affiche ce champ avec un deux-points (comme [!UICONTROL propriétaire:name]), ainsi que dans les attributs (le nom est un champ sous le propriétaire). Le champ étiqueté avec deux points ne contient pas de données et fournit des données incorrectes si elles sont mappées à un module ultérieurement dans le scénario.

+++

+++**[!DNL Workfront Fusion]Mise à jour de la maintenance le 18 mars 2021**

**Les paramètres de modèle de projet s’appliquent désormais aux projets créés par le biais de [!DNL Workfront Fusion] 2,0**

_[!DNL Workfront Fusion]2,0_

Lors de la création d’un projet à partir d’un modèle à l’aide de la variable [!DNL Workfront Fusion] 2.0, les paramètres du modèle sont appliqués au nouveau projet. Ce comportement est le même lors de la création d’un projet à partir d’un modèle dans la variable [!DNL Workfront] application.

+++

+++**Mise à jour de la maintenance le 18 mars 2021**

**Les paramètres de modèle de projet s’appliquent désormais aux projets créés via l’API.**

_[!DNL Workfront]API_

Lors de la création d’un projet à partir d’un modèle à l’aide de la variable [!DNL Workfront] API, les paramètres du modèle sont appliqués au nouveau projet. Ce comportement est le même lors de la création d’un projet à partir d’un modèle dans la variable [!DNL Workfront] application.

+++

+++**Mise à jour de maintenance (correctif) le 15 mars 2021**

**Le composant partagé ne fonctionne pas comme prévu**

_[!DNL Workfront Proof]_

Si autonome [!DNL Workfront Proof] les comptes sont déplacés vers un composant partagé, la fonctionnalité suivante peut se produire lorsqu’un utilisateur ajoute une nouvelle version d’un BAT ou d’un document :

* L’utilisateur ne peut pas supprimer l’utilisateur [!UICONTROL Bon à tirer de Studio].
* Le message par défaut n’apparaît pas sur la nouvelle version.

**Partage des liens publics non activé sur une nouvelle version d&#39;un BAT**

_Documents_

Lorsqu&#39;un utilisateur active le partage de lien public sur un BAT, puis charge une nouvelle version du BAT, le partage de lien public n&#39;est pas automatiquement activé sur la nouvelle version du BAT.

**[!UICONTROL Approuver], [!UICONTROL Modifications], [!UICONTROL Rejeter] boutons manquants dans le BAT**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur affiche un BAT dans la visionneuse de BAT, la variable [!UICONTROL Approuver], [!UICONTROL Modifications], et [!UICONTROL Rejeter] Les boutons ne figurent pas dans la partie supérieure de l’écran.

**Impossible de modifier le tri d’un rapport**

_Rapports_

Lorsqu’un utilisateur tente de modifier le tri d’un rapport dans la nouvelle [!DNL Workfront] , le tri ne change pas par rapport au tri sélectionné lors de la création du rapport.

**Message personnalisé sur le BAT qui ne passe pas à la nouvelle version**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur joint un message personnalisé à un BAT, puis charge une nouvelle version de ce BAT, le message personnalisé n’apparaît pas sur le nouveau BAT.

**La liste des utilisateurs ne s’affiche pas**

_Listes_

Lorsqu’un utilisateur tente d’afficher une liste d’utilisateurs et que la vue inclut le[!UICONTROL Icônes d’état]&quot;, la liste ne s’affiche pas.

**&quot;[!UICONTROL Informer les destinataires de ce BAT]Option &quot; désactivée, quels que soient les paramètres du workflow**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur crée un BAT et n’active pas manuellement le[!UICONTROL Informer les destinataires de ce BAT]&quot;, le destinataire prévu n’est pas informé. C’est le cas même si l’option est activée dans les paramètres du workflow.

**Impossible de modifier la période**

_[!UICONTROL Analytics amélioré]_

Lorsqu’un utilisateur affiche [!UICONTROL Analyse améliorée] et clique sur le calendrier pour ajuster la plage de dates, les dates ne changent pas.

**Impossible de télécharger le document partagé public**

_Documents_

Lorsqu’un utilisateur clique sur un lien partagé pour télécharger un document, le document ne le télécharge pas et le navigateur affiche une erreur indiquant que la page n’existe pas.

+++

+++**Mise à jour de maintenance le 11 mars 2021**

**Section du formulaire personnalisé non exportée pour les non-administrateurs**

_Formulaires personnalisés_

Si un formulaire personnalisé associé à un objet comporte un saut de section qui requiert un saut au-dessus de &quot;[!UICONTROL Affichage]&quot;accès nécessaire pour afficher le contenu de la section, le contenu de la section ne peut être exporté par aucun autre utilisateur qu’un administrateur.

**Le nom du document téléchargé est incorrect**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur télécharge un document à partir de la fonction [!UICONTROL Visionneuse de BAT], le nom du document contient le nom d’une version précédente du document, et non la version qui a été téléchargée.

+++

+++**Mise à jour de maintenance le 4 mars 2021**

**Erreur lors de l’accès au modèle de mise en page**

_Modèles de mise en page_

Lorsqu’un utilisateur s’inscrit dans la nouvelle [!DNL Workfront] l’expérience passe au [!DNL Classic] et tente d’accéder à une [!DNL Classic] modèle de mise en page, l’erreur &quot;[!UICONTROL Cette page n’existe pas.]&quot;

**Impossible de modifier les filtres dans [!UICONTROL Équilibreur de charge de travail]**

_[!UICONTROL Équilbreur de charge de travail]_

Lorsqu’un utilisateur tente de modifier un filtre dans la variable [!UICONTROL Équilibreur de charge de travail], le créateur de filtres ne s’ouvre pas.

**&quot;[!UICONTROL Voir Toutes les notifications]&quot; lien dans les redirections de notifications électroniques vers une page incorrecte**

_Notifications par e-mail_

Lorsqu’un utilisateur clique sur le bouton[!UICONTROL Voir Toutes les notifications]&quot; dans une notification électronique, ils sont redirigés vers une page contenant le message suivant :

&quot;[!UICONTROL L’utilisateur n’existe plus. L’adresse Web est peut-être mal orthographiée. Vérifiez-la, puis tentez d’y accéder à nouveau.]&quot;

**L’utilisateur n’est pas dirigé vers le commentaire du BAT dans lequel il est balisé.**

_Notifications par e-mail_

Lorsqu’un utilisateur est balisé dans un commentaire de BAT et qu’il clique sur la variable [!UICONTROL Atteindre le bon à tirer] dans une notification par email, ils sont dirigés vers le BAT, mais pas vers le commentaire spécifique. Si l’utilisateur se trouve dans [!DNL Workfront Classic], ils sont dirigés vers le [!UICONTROL Détails du document] plutôt que le commentaire dans le BAT.

**Utilisateurs ajoutés à [!DNL Workfront] réception de notifications par email**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur qui ne figure pas dans le workflow ouvre un BAT à partir de [!DNL Workfront], le système crée automatiquement une étape, ajoute cet utilisateur au BAT et envoie une [!UICONTROL Nouvelle preuve] notification électronique.

**Le panneau de résumé du document s’obscurcit, rendant les actions indisponibles**

_Documents_

Lorsqu’un utilisateur se trouve sur une page de document et passe le pointeur de la souris sur le panneau de résumé du document, le panneau s’obscurcit et peut afficher d’autres boutons. L’utilisateur ne peut pas cliquer sur les actions dans le panneau de résumé.

**Mise à jour des performances du flux**

_Mise à jour du flux_

Nous avons réduit le nombre de mises à jour de l’utilisateur affichées dans la variable [!UICONTROL Mises à jour] de 50 à 25 à la fois pour améliorer les performances.

+++

+++**Mise à jour de maintenance (correctif) le 1er mars 2021**

**Les nouveaux emails de BAT ne sont pas envoyés**

_[!DNL Workfront Proof]_

REMARQUE : Ce problème a été corrigé dans la nouvelle [!DNL Workfront] le 26 février 2021.
Ce problème a été corrigé dans la variable [!DNL Classic] expérience du 1er mars 2021.

Lorsqu’un utilisateur crée un BAT et active l’option [!UICONTROL Informer les destinataires de ce BAT], aucun email n&#39;est envoyé pour notifier le destinataire.

+++


## Mises à jour en février 2021

+++**Mise à jour de maintenance le 25 février 2021**

**[!UICONTROL Planification] ne se charge dans aucune zone**

_Gestion des ressources_

Lorsqu’un utilisateur avec une apostrophe dans son nom d’utilisateur tente d’accéder à la variable [!UICONTROL Planification] dans [!DNL Workfront Classic], la page est vide et l’outil ne se charge jamais.

**Le nom ne change pas sur les nouvelles versions de BAT**

_Documents_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] experience charge une nouvelle version d’un document portant un nom différent. le nom ne se met pas à jour pour correspondre au nom de la version la plus récente.

**[!UICONTROL Document Share] erreur lors de la suppression de projets**

_Projets_

Lorsqu’un utilisateur administrateur système a accès à un projet qui a été copié et qu’il tente de le supprimer ou de supprimer un document du projet, il ne peut pas supprimer l’objet et il voit l’erreur &quot;[!UICONTROL Partage de documents avec des valeurs de clé Principales introuvables.]&quot;

**Le rapport utilisateur n’applique pas tous les filtres**

_Rapports_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] crée un rapport Utilisateur avec une règle de filtrage qui inclut la variable [!UICONTROL ID parent principal] , toutes les autres règles de filtrage du rapport ne sont pas appliquées.

**Champs calculés non recalculés après modification**

_Formulaires personnalisés_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] experience modifie et enregistre un formulaire personnalisé qui contient des champs calculés. ces champs ne sont pas mis à jour.

**Suppression de documents lors de la suppression d’un formulaire personnalisé**

_Formulaires personnalisés_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] l’expérience supprime un formulaire personnalisé Documents joint aux documents, ces documents sont également supprimés.

+++

+++**Mise à jour de maintenance le 18 février 2021**

**Case à cocher inutile supprimée de [!UICONTROL Demandes] area**

_Demandes_

Nous avons supprimé la case à cocher à gauche des noms de requête dans la liste Envoyé du [!UICONTROL Demandes] zone. Cette case à cocher n’était connectée à aucune fonctionnalité. Nous l’avons donc supprimée pour éliminer toute expérience déroutante.

**Impossible d’accéder aux documents à partir de liens**

_Documents_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] l’expérience clique sur certains liens de document, ils ne peuvent pas accéder au document et le message d’erreur s’affiche.[!UICONTROL Le document n’existe plus : Vous avez peut-être tapé l’adresse web de manière incorrecte. Vérifiez deux fois et essayez à nouveau de saisir l’adresse.]&quot; Cette même erreur se produit avec la variable [!UICONTROL Afficher les détails] lien dans les notifications par email du BAT.

+++

+++**Mise à jour de la maintenance de la fusion Workfront le 16 février 2021**

**[!DNL Workfront Fusion]La version 2.0 affiche des fuseaux horaires inexacts**

_Scénarios_

Cette mise à jour corrige un problème en raison duquel [!DNL Fusion] La version 2.0 affichait incorrectement les fuseaux horaires des utilisateurs. Les utilisateurs peuvent désormais voir leur fuseau horaire affiché sous les champs de saisie pour les dates.

+++

+++**Mise à jour de maintenance le 11 février 2021**

**Les bons à tirer ne sont pas téléchargés vers le dossier sélectionné**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur ouvre un dossier et ajoute un nouveau BAT, le BAT est téléchargé dans le [!UICONTROL Documents] de l’objet au lieu du dossier.

**Trop de pages épinglées entraîne la disparition de la navigation supérieure.**

_Navigation_

Lorsqu’un utilisateur dispose de plus de 60 pages épinglées, la navigation supérieure s’affiche, ce qui empêche l’utilisateur d’accéder à [!UICONTROL Rechercher], la variable [!UICONTROL Menu Principal], [!UICONTROL Notifications], etc.

**L’utilisateur ne peut pas saisir de texte dans un champ de texte enrichi.**

_Listes_

Lorsqu’un utilisateur tente d’insérer et de modifier un champ de texte enrichi, il ne peut saisir qu’un seul caractère.

+++

+++**Mise à jour de maintenance le 4 février 2021**

**Les rapports exportés affichent [!DNL Workfront Classic] branding**

_Rapports_

Lorsqu’un utilisateur de la nouvelle expérience Workfront exporte un rapport, le logo qui s’affiche dans le rapport exporté correspond à la variable [!DNL Workfront Classic] paramètres trouvés sous [!UICONTROL Configuration] > [!UICONTROL Système] > [!UICONTROL Marques].

+++


## Mises à jour en janvier 2021

+++**Mise à jour de maintenance le 28 janvier 2021**

**Commentaires n’affichant pas &quot;[!UICONTROL au nom de]&quot;**

_Mises à jour_

Lorsqu’une [!DNL Workfront] l’administrateur se connecte en tant qu’autre utilisateur et répond à un commentaire dans la variable [!UICONTROL Mises à jour] de la zone d’un objet, le texte &quot;[!UICONTROL au nom de]&quot; ne s’affiche pas avant le nom d’utilisateur.

**Impossible de joindre un document**

_Demandes_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] expérience tente d’ajouter un document à une nouvelle requête d’un fournisseur de documents externe, le [!UICONTROL Documents] La liste ne se charge pas, ce qui empêche l’utilisateur de sélectionner le document et d’effectuer la requête.

**La largeur d’écran s’étend à droite, ce qui entraîne des problèmes de navigation.**

_[!UICONTROL Calendrier d’accueil]_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] l’expérience ouvre la fonction [!UICONTROL Calendrier d’accueil] et il y a des articles qui doivent être envoyés certaines semaines, l’écran se développe à droite, ce qui les empêche de regarder la semaine entière en même temps. Si l’utilisateur sélectionne un élément pour ouvrir la [!UICONTROL Détails] dans cet état et pour afficher les détails d’un autre élément, ils doivent faire défiler vers la gauche, ce qui ferme la fenêtre [!UICONTROL Détails] du panneau.

**Balisage du processus de validation à usage unique corrigé**

_Projets_

Lors de l’utilisation d’un processus d’approbation à usage unique pour un projet dans la nouvelle [!DNL Workfront] expérience, s’affiche désormais sous la forme &quot;[!UICONTROL Processus de validation à usage unique]&quot; au lieu de &quot;\&quot;&lt;custom>&quot; dans la variable [!UICONTROL Modifier le projet] de la boîte. Cette option n’est pas encore disponible pour les tâches et les problèmes.

**Amélioration de l’aspect des formulaires personnalisés**

_Projets_

Nous avons amélioré l’aspect de l’utilisation des formulaires personnalisés dans la nouvelle [!DNL Workfront] expérience pour les projets.

**La fonctionnalité d’API de la devise du projet correspond désormais à la fonctionnalité intégrée (in-app).**

_Projets_

Vous ne pouvez pas modifier la devise d’un projet lorsqu’il contient déjà des informations financières. Avec la dernière mise à jour de maintenance, la fonctionnalité de l’API dans ce cas correspond désormais à l’expérience de la fonction [!DNL Workfront] .

**Génération non automatique de la semaine suivante**

_Feuilles de temps_

Lorsqu’un utilisateur accède à la variable [!UICONTROL Feuilles de temps] , ils ne voient que la feuille de temps de la semaine en cours. La feuille de temps pour les semaines à venir n’est pas générée automatiquement.

+++

+++**Mise à jour de maintenance le 21 janvier 2021**

**Le tri manuel par colonne affiche tous les résultats**

_Rapports_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] l’expérience clique sur une barre du graphique d’un rapport, puis sur un en-tête de colonne pour trier manuellement les résultats de ce groupement. tous les résultats du rapport s’affichent, et pas seulement les résultats du groupement sélectionné d’origine.

**&quot;[!UICONTROL Autorisation du partage du BAT via l’URL ou le code incorporé]Modifications des paramètres**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur crée un BAT et désélectionne le paramètre [!UICONTROL Autorisation du partage du BAT via l’URL ou le code incorporé], le paramètre est de nouveau coché une fois le BAT généré. Si l’utilisateur laisse le paramètre coché, il est décoché après la génération du BAT.

**[!DNL Mac]les utilisateurs ne peuvent pas coller dans les champs de texte dans la visionneuse de BAT.**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur tente de coller du texte dans certains champs de la visionneuse de BAT, le texte n’apparaît pas dans le champ.

+++

+++**Mise à jour de maintenance le 14 janvier 2021**

**Impossible de mettre à jour les paramètres des notifications par courrier électronique**

_Configuration_

Lorsqu’un utilisateur tente de mettre à jour les paramètres des notifications par e-mail, il ne peut pas accéder à la variable [!UICONTROL Notifications par e-mail] et voir le message d’erreur &quot;[!UICONTROL Essayons à nouveau. Oups ! Un problème est survenu. Veuillez contacter [!DNL Workfront] donc nous pouvons comprendre ce qui s&#39;est mal passé et y remédier.]&quot;

**[!UICONTROL Graphique Gantt] entraîne la troncature de certains champs.**

_Listes_

Lorsqu’un utilisateur ouvre la variable [!UICONTROL Graphique Gantt] dans certaines zones de liste, certains champs, tels que [!UICONTROL Description]: tronque le texte. L’utilisateur doit double-cliquer sur le champ pour afficher le texte intégral.

**Impossible d’envoyer les fichiers depuis [!UICONTROL Détails du document]**

_Documents_

Lorsqu’un utilisateur accède à la nouvelle [!DNL Workfront] expérience tente d’envoyer un document à partir du [!UICONTROL Détails du document] , le message d’erreur &quot;[!UICONTROL Une erreur s’est produite et nous travaillons à résoudre le problème. Pour poursuivre votre travail, essayez d’actualiser cette page de navigateur.]&quot;

+++

+++**Mise à jour de maintenance le 7 janvier 2021**

**La boîte de dialogue Déléguer les approbations se ferme**

_Page d’accueil_

Lorsqu’un utilisateur tente de déléguer des approbations dans [!UICONTROL Accueil] et qu’ils cliquent sur n’importe quelle date, la boîte de dialogue se ferme sans sélectionner la date ni permettre à l’utilisateur de terminer la délégation de l’utilisateur.

**Problème lors du déplacement d’un document vers une tâche**

_Documents_

Lorsqu’un utilisateur tente de déplacer un document ou un BAT dans la nouvelle [!DNL Workfront] , certaines tâches en dehors du projet ne répertorient pas le projet parent comme prévu.

**Le PDF téléchargé porte un nom incorrect**

_[!DNL Workfront Proof]_

Lorsqu’un utilisateur reçoit un lien de téléchargement par courrier électronique ([!UICONTROL Bon à tirer] > [!UICONTROL Imprimer les commentaires] > [!UICONTROL PDF]) et exporter le fichier, le fichier téléchargé est intitulé avec des nombres aléatoires au lieu de l’identifiant du bon à tirer.

+++
