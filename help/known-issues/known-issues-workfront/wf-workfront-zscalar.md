---
title: "Workfront : les paramètres ZScalar peuvent réduire les performances"
description: "Le service Web de ZScalar utilise http/1.1 par défaut, ce qui peut entraîner des performances réduites dans Workfront."
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 77345937934851b8ebfdf257f44e25133eade971
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 6%

---


# Workfront : les paramètres ZScalar peuvent réduire les performances

>[!NOTE]
>
>Il s’agit d’un problème avec ZScalar, qui ne sera pas résolu par Workfront.

Le service Web de ZScalar utilise `http/1.1` par défaut, ce qui peut entraîner des performances réduites dans Workfront.

**Solution de contournement**

Configurez votre logiciel ZScalar pour utiliser `http/2`. Cette configuration ne peut pas être effectuée dans Workfront.

Vous trouverez des informations sur `http/2` dans la documentation ZScalar.

_Premier signalement le mardi 18 novembre 2024._
