---
title: '« Mises à jour : lignes supplémentaires dans le commentaire effectué via l’API ou Workfront Fusion »'
description: « Lorsqu’un utilisateur ou une utilisatrice envoie un commentaire via l’API ou via Workfront Fusion, le commentaire affiché dans la zone Mises à jour affiche des lignes supplémentaires. Parfois, il y a tellement de lignes que l’utilisateur ou l’utilisatrice doit faire défiler l’écran pour voir le contenu du commentaire. »
hidefromtoc: true
feature: Updates and Notifications
source-git-commit: 1854e4a003722f1398c703dfba7bc23ef534f81f
workflow-type: ht
source-wordcount: '167'
ht-degree: 100%

---


# Mises à jour : lignes supplémentaires dans le commentaire effectué via l’API ou [!DNL Workfront Fusion]

Lorsqu’un utilisateur ou une utilisatrice envoie un commentaire via l’API ou via [!DNL Workfront Fusion], le commentaire affiché dans la zone Mises à jour affiche des lignes supplémentaires. Parfois, il y a tellement de lignes que l’utilisateur ou l’utilisatricedoit faire défiler la page vers le bas pour voir le contenu du commentaire.

Cela a été signalé dans la nouvelle expérience de commentaire.

**Solution de contournement**

Ce problème est dû à des espaces ou des sauts de ligne dans le HTML envoyé dans le commentaire.

Pour éviter ce problème, assurez-vous que tous les HTML se trouvent sur une seule ligne, sans espaces ni sauts de ligne entre les éléments HTML.

Pour afficher les commentaires concernés sans les lignes supplémentaires, passez à l’expérience de commentaire classique.

_Premier signalement le 27 octobre 2023._
