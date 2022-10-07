---
description: Proposal en cours de discussion
---

# 💬 #28 - Renouvellement des signataires du multisig DeFi France

### Contexte

Le multisig de DeFi France a été inauguré avec la proposal [#7- Création du multisig de DeFi France](https://docs.defi-france.org/dff/propositions/propositions-acceptees/7-creation-du-multisig-dff) et a été essentiellement utilisé pour la réception d'airdrops, comme Optimism ou Gnosis Safe. Alors que des perspectives nouvelles émergent quant à l'utilisation de cette trésorerie, on propose de renouveler les signataires afin d'assurer au multisig une meilleure réactivité dans les prochains mois.

### Objet

DeFi France ne possède pas à ce jour d'outil capable de procéder à des élections décentralisées et qui prendrait en considération les points de réputation. Cette limite importante dans le fonctionnement de Démeter a entraîné de nombreux débats, étalés dans le temps, et à des blocages de gouvernance. Afin de limiter au maximum les conflits autour du renouvellement des signataires, on propose ici de procéder par consensus communautaire et à l'aide de critères objectifs.

Au 07 octobre 2022, le classement de Demeter se présente de la manière suivante :

<figure><img src="../.gitbook/assets/Capture d’écran 2022-10-07 093148.png" alt=""><figcaption></figcaption></figure>

Et le multisig comporte dix signataires :

| ID  | Anciens signataires |
| --- | ------------------- |
| 1.  | ArthurSW            |
| 2.  | Charles53300        |
| 3.  | CookingCryptos      |
| 4.  | Cyrille             |
| 5.  | Julienperma         |
| 6.  | L0GYKAL             |
| 7.  | Mratsim             |
| 8.  | NolanVanmoortel     |
| 9.  | Owerache            |
| 10. | TokenBrice          |

Les signataires qui ne respectent pas les critères suivants sont appelés à être renouvelés :

* Faire parti du top 20 réputation de Démeter.
* Avoir participé dans les derniers mois aux activités de DeFi France, notamment aux discussions du serveur.
* Être intéressé pour intégrer le multisig pour une durée de six mois.

Parmi les gardiens actuels, cinq ne respectent pas ces critères. On les renouvelle en suivant le classement de Demeter et sous réserve que les nouveaux signataires donnent leur accord. On aboutit ainsi aux changements suivant :

| Ancien          | Nouveau  |
| --------------- | -------- |
| CookingCryptos  | Cesarioo |
| L0GYKAL         | Disiaque |
| Mratsim         | Ootsun   |
| NolanVanmoortel | Théo     |
| Owerache        | Starny   |

La nouvelle liste de signataires, classé par ordre alphabétique, devient donc :

| ID  | Nouveaux signataires |
| --- | -------------------- |
| 1.  | ArthurSW             |
| 2.  | Cesarioo             |
| 3.  | Charles53300         |
| 4.  | Cyrille              |
| 5.  | Disiaque             |
| 6.  | Julienperma          |
| 7.  | Morpheus             |
| 8.  | Ootsun               |
| 9.  | Theo                 |
| 10. | TokenBrice           |

On délimite les responsabilités des signataires en créant un rôle de "Gardien" dans le serveur. Les gardiens ont pour mission de créer et signer les transactions en vérifiant qu'elles soient en adéquation avec les décisions prises par l'Agora. Ils n'ont pas la possibilité de créer des transactions en autonomie et leur durée de mandat est de six mois, avant leur renouvellement.

Pour communiquer entre eux, les gardiens utilisent un ping directement dans le salon Agora. Dans le cas où un gardien ne serait plus disponible pour assurer sa mission, il s'engage à prévenir l'Agora pour un renouvellement avancé de son poste. Le prochain renouvellement des gardiens pourra se faire selon des modalités toutes autres : élections appuyées par Déméter, outil quantitatif sur l'efficience des gardiens, etc.

Enfin, cette proposal vise également à créer un deuxième multisig déployé sur Polygon afin d'économiser des frais de gas.

### Implémentation

* Renouvellement des signataires du multisig suivant la liste établie dans cette proposal.
* Création d'un deuxième multisig sur le réseau Polygon.
* Création du rôle "Gardien" dans le serveur et l'attribuer aux membres nommés.
* Mise à jour de la documentation de DeFi France pour ce rôle.

### Rédacteur

[@Disiaque](https://twitter.com/disiaque\_eth)
