---
title: "Fiches horaires : la feuille de temps épinglée est placée sur une page vierge"
description: '"Lorsqu’un utilisateur clique sur une épingle de Workfront destinée à atteindre sa feuille de temps, elle accède plutôt à une page vierge. Une solution de contournement est disponible. »'
hidefromtoc: true
feature: Timesheets
source-git-commit: d3068f21ba6e1a9a1dd4a9ed78da43cef88f4fde
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 7%

---


# Feuilles de temps : la feuille de temps épinglée est placée sur une page vierge.

Lorsqu’un utilisateur clique sur une épingle de Workfront destinée à atteindre sa feuille de temps, elle accède plutôt à une page vierge.

En effet, l’URL de la feuille de temps a changé. la valeur `/own` à la fin de l’URL n’est plus l’URL correcte. Si l’utilisateur a épinglé une URL qui inclut `/own`, cette épingle mène à une page vierge.

**Solution de contournement**

1. Décochez la feuille de temps.
1. Supprimer `/own` à partir de la fin de l’URL
1. Réépinglez la feuille de temps.

_Premier signalement le mercredi 7 mai 2024._
