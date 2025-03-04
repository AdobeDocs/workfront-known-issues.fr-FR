---
title: 'Intégrations : erreur outlookIdentityToken lors de l’utilisation de Workfront pour Outlook'
description: Lorsque l’utilisateur utilise l’intégration Workfront for Outlook, une erreur peut s’afficher.
hidefromtoc: true
feature: Workfront Integrations and Apps
source-git-commit: 19d438b3a368b076aa03a89fe6648ec4b225225f
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---


# Intégrations : erreur outlookIdentityToken lors de l’utilisation de Workfront pour Outlook

Lorsque l’utilisateur utilise l’intégration Workfront for Outlook, le message d’erreur suivant peut s’afficher :

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Solution de contournement**


Pour résoudre cette erreur, vous devez activer les jetons Microsoft 365 hérités pour votre organisation. Comme cela doit être effectué dans Microsoft 365, Workfront ne peut pas activer ces jetons pour votre organisation.

Pour obtenir des instructions sur l’activation des jetons hérités de Microsoft 365, voir [Activation ou désactivation des jetons Exchange Online hérités](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) dans la documentation de Microsoft.

Pour plus d&#39;informations sur les jetons hérités, voir [Puis-je réactiver les jetons hérités Exchange Online ?](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) dans la documentation de Microsoft.


_Premier signalement le 3 mars 2025._
