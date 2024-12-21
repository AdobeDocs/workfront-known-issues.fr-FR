---
title: 'Épreuves : les épreuves de la capture web ne se génèrent pas.'
description: Lorsqu’une personne tente de créer directement une épreuve de capture web, l’épreuve n’est pas générée.
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 59%

---

# Épreuves : les épreuves de la capture web ne se génèrent pas.

>[!NOTE]
>
>Ce problème a été résolu, car tout fonctionne comme prévu. Voir la solution ci-dessous.

Lorsqu’une personne tente de créer directement une épreuve de capture web, l’épreuve n’est pas générée.

**Solution de contournement**

Ce problème est dû à de longs délais de génération d’épreuves pour certains fichiers de PDF. Pour augmenter le délai d’expiration de la génération à partir des 30 secondes par défaut, modifiez la propriété ci-dessous dans Paramètres de traitement au niveau du compte dans l’administrateur de l’épreuve :

`WebCaptureNavigationTimeout -> 120`

_Premier signalement le vendredi 3 octobre 2024._
