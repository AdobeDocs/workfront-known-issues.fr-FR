---
title: "Modèles de mise en page : les modèles de mise en page provoquent des incohérences dans les rapports"
description: "Les modèles de mise en page de l’expérience Workfront classique ne sont plus disponibles dans l’interface de Workfront, mais peuvent tout de même affecter les données Workfront. Cela peut entraîner des incohérences dans les champs affectés par les modèles de mise en page (tels que Partagés avec) sur les rapports ou les tableaux de bord."
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 045e2bd200aa2fffaf2e763a73eb8729517be197
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 0%

---


# Modèles de disposition : les modèles de mise en page provoquent des incohérences dans les rapports.

Les modèles de mise en page de l’expérience Workfront classique ne sont plus disponibles dans l’interface de Workfront, mais peuvent tout de même affecter les données Workfront. Cela peut entraîner des incohérences dans les champs affectés par les modèles de mise en page (tels que Partagés avec) sur les rapports ou les tableaux de bord.

**Solution de contournement**

Supprimez les modèles de mise en page Classic à l’aide d’un appel API. Vous devez être connecté à Workfront.

>[!NOTE]
>
>Les modèles de mise en page globale et système ne peuvent pas être supprimés.

1. Recherchez le modèle de mise en page que vous souhaitez supprimer à l’aide de l’appel API suivant :
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. Notez l’identifiant du modèle de mise en page que vous souhaitez supprimer.
1. Recherchez votre ID de session à l’aide de l’appel API suivant :
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >Ne partagez jamais votre ID de session avec personne.

1. Insérez l’identifiant du modèle de mise en page et l’identifiant de session dans l’appel API suivant :
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. Collez l’appel API de l’étape 4 dans la barre d’URL de votre navigateur et appuyez sur Entrée.

   Le modèle de mise en page est ainsi supprimé.

