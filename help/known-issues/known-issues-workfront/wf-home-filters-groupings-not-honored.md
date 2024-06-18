---
title: '« Nouvelle page d’accueil : les valeurs par défaut des filtres de widgets et des regroupements ne respectent pas le modèle de mise en page. »'
description: Lorsqu’un utilisateur ou une utilisatrice consulte le widget Mes projets, Mes tâches ou Mes problèmes sur la nouvelle expérience de page d’accueil, le filtre et le regroupement par défaut de ce widget ne sont pas les paramètres par défaut du modèle de mise en page affecté à cet utilisateur ou à cette utilisatrice.
hidefromtoc: true
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: ht
source-wordcount: '191'
ht-degree: 100%

---

# Nouvelle [!UICONTROL page d’accueil] : les valeurs par défaut des filtres de widgets et des regroupements ne respectent pas le modèle de mise en page.

>[!NOTE]
>
>Ce problème a été résolu, car tout fonctionne comme prévu.

Lorsqu’un utilisateur ou une utilisatrice consulte le widget [!UICONTROL Mes projets], [!UICONTROL Mes tâches] ou [!UICONTROL Mes problèmes] sur la nouvelle expérience de [!UICONTROL page d’accueil], le filtre et le regroupement par défaut de ce widget ne sont pas les paramètres par défaut du modèle de mise en page affecté à cet utilisateur ou à cette utilisatrice.

**Solution** :

Lors de l’utilisation de la nouvelle page d’accueil, il est important de se rappeler que les paramètres utilisateur (préférences) sont hiérarchisés. Par conséquent, si vous définissez un filtre ou un regroupement par défaut pour un widget spécifique à l’aide d’un modèle de mise en page, il se peut qu’il ne prenne pas effet immédiatement en raison des préférences utilisateur existantes. Pour appliquer le nouveau filtre ou regroupement, il sera peut-être nécessaire pour vous ou l’utilisateur ou l’utilisatrice de réinitialiser les préférences. Pour ce faire, il suffit d’ajouter `/resetUser` à votre URL.

_Premier signalement le 3 janvier 2024_
