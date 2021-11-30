---
description: Proposition implémentée le 02 novembre 2021 ✅
---

# 📜 #15 - Création du salon « Poubelle »

| ID                 | PROPOSITION                    | CLÔTURE    | VOTE POUR | VOTRE CONTRE | STATUT   |
| ------------------ | ------------------------------ | ---------- | --------- | ------------ | -------- |
| **Proposition 15** | Création du salon « Poubelle » | 01/11/2021 | 31 (52%)  | 0 (0%)       | Acceptée |

## **Proposition originale**

### Contexte

L'idée est de garder une trace des messages indésirables, insultants, spams, et publicités dissimulées dans un salon.

### Objet

#### Création du salon poubelle

Le salon « poubelle » sera masqué aux yeux des membres, mais une demande d’accès pourra être faite pour vérifier les abus.

Pour la demande d'accès « afficher ou non la poubelle », la solution retenue est l'auto-attribution d'un rôle nommé _Hélios (_dieu du don de la vue), via demande avec deux nouvelles commandes à Demeter, `!voir poubelle` & `!cacher poubelle` .&#x20;

Un message d'alerte de la part de Demeter s'affichera à la demande du rôle : « _Attention, des projets scams peuvent ce trouver dans les messages du salon #poubelle, faites attention à ne pas cliquer sur n'importe quel lien !_ »

#### Fonctionnement

Réagissez avec un nouveau emoji « poubelle » sur un message que vous considérez comme indésirable, insultant, spam et/ou une publicité dissimulée.&#x20;

Le bot Demeter placera ce message dans le salon « poubelle » lorsque **2 % du taux de blé** sera atteints au fur et à mesure que les membres cliquent sur l’emoji poubelle. Ce taux de base est le même que pour la fonction « déplacement de messages hors sujets ».&#x20;

Si des abus sont constatés, les administrateurs techniques du serveur pourront augmenter progressivement ce taux, sans besoin de vote dans l'Agora, jusqu'à un palier de 10% de la façon suivante :

| Action   | Nouveau taux                                |
| -------- | ------------------------------------------- |
| Base     | 2 %                                         |
| Abus 01  | 3 %                                         |
| Abus 02  | 5 %                                         |
| Abus 03  | 8 %                                         |
| Abus 04  | 10 %                                        |
| Abus 05  | Revote & Rework de la fonction dans l'Agora |

### Implémentation

Le salon poubelle est créé dans un délai raisonnable par les administrateurs techniques du serveur.

### Rédacteur

@Loico.eth
