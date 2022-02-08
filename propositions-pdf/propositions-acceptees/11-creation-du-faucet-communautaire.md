---
description: Proposition implémentée ✅
---

# 📜 #11 - Création du « Faucet communautaire »

| ID                 | PROPOSITION                          | CLÔTURE    | VOTE POUR | VOTRE CONTRE | STATUT   |
| ------------------ | ------------------------------------ | ---------- | --------- | ------------ | -------- |
| **Proposition 11** | Création du « Faucet communautaire » | 18/09/2021 | 26 (33 %) | 0 (0 %)      | Acceptée |

## Proposition originale

### Contexte

Le wallet 0xDFF commence à être correctement provisionné (merci entre autres à @Arthursw et @krkr). https://debank.com/profile/0xdff00c26598cb74e8a62f26c8a544ec7eac211b3

### Rappel

Le but est d'éviter aux dffeurs des frais de bridge via un mécanisme de donation communautaire "pay it backward".

### Proposition

Afin que le portefeuille puisse servir de faucet à court terme je propose dans un premier temps les étapes suivantes.

1. création d'un channel Gouvernance -> #faucet Pin message : liens vers des faucets fonctionnels et indication qu'il est possible de demander un dépannage sur le canal
2. transmission de la clef privée du wallet via gpg à toute personne du top10blé qui en fait la demande sur le channel (comme l'a fait @Charles 53300) On part du principe que qn du top10blé a plus à perdre qu'à gagner en partant avec la caisse de $200
3. lorsque qn fait une demande de dépannage un keyholder peut l'accepter et le cas échéant faire la transaction et publier le txid (ok c'est pas idéal niveau vie privée, peut-être à déporter en dm)
4. le refill du wallet est assuré par les bénéficiaires eux-mêmes en mode je donne sur A pour prendre sur B, et/ou par de généreux donateurs

### Perspective

Dans un deuxième temps :

* ça pourra être automatisé via un bot discord type Déméter ou une page nodejs si qn veut bien s'y mettre
* les donations donneront du blé
* il y aura aussi les ETH testnet
