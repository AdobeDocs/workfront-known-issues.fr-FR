---
title: 'Intégrations : erreur outlookIdentityToken lors de l’utilisation de Workfront pour Outlook'
description: Lors de l’utilisation de l’intégration Workfront pour Outlook, une erreur peut s’afficher.
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: 87c56abf4a5020632877263329f1455bbf4cc7f3
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 87%

---

# Intégrations : erreur outlookIdentityToken lors de l’utilisation de Workfront pour Outlook

>[!NOTE]
>
>L’intégration de Workfront pour Outlook n’est plus disponible. Cet article sera supprimé prochainement.

Lors de l’utilisation de l’intégration Workfront pour Outlook, le message d’erreur suivant peut s’afficher :

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Solution de contournement**


Pour résoudre cette erreur, vous devez activer les jetons Microsoft 365 hérités pour votre organisation. Cela devant être effectué dans Microsoft 365, Workfront ne peut pas activer ces jetons pour votre organisation.

Pour obtenir des instructions sur l’activation des jetons Microsoft 365 hérités, voir la section [Activer ou désactiver des jetons Exchange Online hérités](https://learn.microsoft.com/fr-fr/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) dans la documentation Microsoft.

Pour plus d&#39;informations sur les jetons hérités, voir la section [Puis-je réactiver les jetons hérités Exchange Online ?](https://learn.microsoft.com/fr-fr/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) dans la documentation Microsoft.


_Premier signalement le 3 mars 2025._
