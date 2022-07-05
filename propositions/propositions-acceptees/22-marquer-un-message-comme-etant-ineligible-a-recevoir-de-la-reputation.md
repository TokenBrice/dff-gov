---
description: En cours d'implémentation
cover: ../../.gitbook/assets/dff-pdf-discussion.png
coverY: 0
---

# 📜 23 - Marquer un message comme étant inéligible à recevoir de la réputation

### Contexte

Le canal #📕-manuel-demeter commence par ceci :

> **DeFi France est un Discord autogéré via un système de réputation**, c'est-à-dire que chaque membre peut **gagner ou faire gagner des points de réputation**. Ces points de **réputations représentent votre implication** dans la communauté, ils sont utilisés par exemple, pour vous assigner des **rôles**, **voter** des propositions, mais également pour la **modération** du Discord, comme déplacer un message hors sujet ou censuré un membre. Le **gain de réputation** a automatiquement lieu **lorsque vous réagissez à un message**, que ça soit via un **émoji** ou une **réponse** \[...].

Rédiger un message en guise de rapide sondage à base de :thumbsup: et :thumbsdown: ou notifier tous les membres du serveur grâce à @everyone apporte parfois une énorme quantité de points de réputation à son auteur. Ces points ne représentent alors plus forcément l'implication dans la communauté.

### Objet

Permettre de marquer un message comme étant inéligible à recevoir de la réputation. Si la communauté ou le propriétaire du message réagit avec l'emoji 🙈, alors on ne prend pas en compte ce message lors du calcul de la réputation. Pour que la communauté puisse activer cette fonctionnalité, la somme des points de réputations de chacun des membres ayant réagis avec l'emoji 🙈 doit être >= à 600. Cette valeur est configurable par les membres disposant du rôle "🛠 Team Déméter".

### Implémentation

Mise à jour du bot Discord Déméter :

* Ajouter un nouveau paramètre "MIN\_REPUTATION\_IGNORE"
* Permettre à tous de consulter la valeur de ce paramètre grâce au bouton situé dans #📕-manuel-demeter
* Si le propriétaire d'un message réagit à son propre message avec l'emoji 🙈 OU Si la communauté réagit à un message avec ce même émoji et que la somme de la réputation de chacun est supérieure à MIN\_REPUTATION\_IGNORE ALORS le message n'est pas pris en compte lors du calcul de la réputation par Déméter

Configuration du paramètre MIN\_REPUTATION\_IGNORE dans Discord via la commande /guild config MIN\_REPUTATION\_IGNORE 300.

Si ce paramètre n'est pas configuré ou si sa valeur est égal à 0, alors la fonctionnalité n'est pas active.

### Rédacteur

[OoTsun](https://app.gitbook.com/u/7X8PEdE3ERU9ob8UNY8rAUwz4073 "mention")
