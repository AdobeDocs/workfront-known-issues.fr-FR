---
title: 'Workfront Fusion : le module de recherche Jira renvoie une erreur'
description: Le module de recherche utilisé par le connecteur Jira hérité peut entraîner une erreur. Une solution de contournement est disponible.
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 0f4dba4664f645920752cc0c346782c9582b0e54
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 4%

---


# Workfront Fusion : le module de recherche Jira renvoie une erreur

>[!NOTE]
>
>Ce problème est dû à une modification apportée par Jira à son produit.

Le module de recherche utilisé par le connecteur Jira hérité peut entraîner l’erreur suivante :

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

Cela est dû à une obsolescence du côté Jira.

Notez que :

* Seul le module Recherche est affecté. Actuellement, les autres points d’entrée de l’API Jira utilisés par le connecteur Fusion ne sont pas affectés par cette obsolescence.

* Le déploiement géographique peut entraîner des incohérences. Atlassian déploie cette modification à l’échelle régionale, ce qui signifie que certaines instances Jira Cloud peuvent toujours prendre temporairement en charge les points d’entrée plus anciens. Cela peut entraîner un comportement incohérent entre les environnements.

**Solution de contournement**

Si vous rencontrez cette erreur, vous pouvez remplacer le module de recherche du connecteur Jira hérité par le module de recherche du nouveau connecteur. Notez que le nouveau connecteur permet de sélectionner la version d’API utilisée. Veillez à sélectionner **V3** dans le champ **Version de l’API** lors de la création de la connexion.

_Premier signalement le mardi 15 septembre 2025._

