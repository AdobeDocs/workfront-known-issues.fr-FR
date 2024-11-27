---
title: "Workfront : les paramètres de ZScaler peuvent entraîner une réduction des performances"
description: Le service Web de ZScaler utilise http/1.1 par défaut, ce qui peut entraîner des performances réduites dans Workfront.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 6%

---

# Workfront : les paramètres de ZScaler peuvent réduire les performances

>[!NOTE]
>
>Il s’agit d’un problème avec ZScaler, qui ne sera pas résolu par Workfront.

Le service Web de ZScaler utilise `http/1.1` par défaut, ce qui peut entraîner des performances réduites dans Workfront.

**Solution de contournement**

Configurez votre logiciel ZScaler pour utiliser `http/2`. Cette configuration ne peut pas être effectuée dans Workfront.

Vous trouverez des informations sur `http/2` dans la documentation de ZScaler.

_Premier signalement le mardi 18 novembre 2024._
