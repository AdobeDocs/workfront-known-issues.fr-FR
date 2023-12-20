---
title: "Modèles de mise en page : les modèles de mise en page provoquent des incohérences dans les rapports"
description: Les modèles de disposition de l’expérience Workfront classique ne sont plus disponibles dans l’interface Workfront, mais peuvent tout de même affecter les données Workfront. Cela peut entraîner des incohérences dans les champs affectés par les modèles de disposition (tels que Partagé avec) sur les rapports ou les tableaux de bord.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 1542291f-4797-477e-83b8-0706ac6801ae
source-git-commit: 10507904c2e6d6a8adc182551f6425b78aab4fce
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 86%

---

# Modèles de disposition : les modèles de disposition provoquent des incohérences dans les rapports.

Modèles de mise en page de Classic [!DNL Workfront] ne sont plus disponibles dans la variable [!DNL Workfront] mais peut encore affecter [!DNL Workfront] data. Cela peut entraîner des incohérences dans les champs affectés par les modèles de disposition (tels que [!UICONTROL Partagé avec]) sur les rapports ou les tableaux de bord.

**Solution de contournement**

Supprimez les modèles de disposition classiques à l’aide d’un appel API. Vous devez vous connecter à Workfront.

>[!NOTE]
>
>Les modèles de disposition globaux et de système ne peuvent pas être supprimés.

1. Recherchez le modèle de disposition à supprimer à l’aide de l’appel API suivant :
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. Notez l’ID du modèle de disposition à supprimer.
1. Recherchez votre ID de session à l’aide de l’appel API suivant :
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >Ne partagez jamais votre ID de session avec qui que ce soit.

1. Insérez l’ID du modèle de disposition et l’ID de session dans l’appel API suivant :
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. Collez l’appel API de l’étape 4 dans la barre d’URL de votre navigateur et appuyez sur Entrée.

   Le modèle de disposition est ainsi supprimé.
