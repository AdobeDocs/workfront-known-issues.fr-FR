---
title: 'Workfront : les paramètres ZScaler peuvent diminuer les performances.'
description: Le service web de ZScaler utilise http/1.1 par défaut, ce qui peut entraîner une diminution des performances dans Workfront.
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '83'
ht-degree: 100%
---
# Workfront : les paramètres ZScaler peuvent diminuer les performances.

>[!NOTE]
>
>Il s’agit d’un problème lié à ZScaler, qui ne sera pas résolu par Workfront.

Le service web de ZScaler utilise `http/1.1` par défaut, ce qui peut entraîner une diminution des performances dans Workfront.

**Solution de contournement**

Configurez votre logiciel ZScaler pour utiliser `http/2`. Cette configuration ne peut pas être effectuée dans Workfront.

Vous trouverez des informations sur `http/2` dans la documentation ZScaler.

_Premier signalement le mardi 18 novembre 2024._
