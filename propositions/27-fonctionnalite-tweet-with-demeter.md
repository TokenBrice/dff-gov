# #27 - Fonctionnalité "Tweet with Demeter"

### Contexte

La proposition "#26 - Gestion du Twitter DeFi France" a récemment été acceptée. Elle a notamment pour objectif de rendre le compte Twitter plus actif. C'est dans ce sens que cette nouvelle proposition va aussi.

### Objet

La mise en place d'un système de publication Twitter communautaire pourrait être ajouté à Demeter. Concrètement, n'importe qui pourrait proposer une publication dans un canal dédié du serveur Discord. Si un administrateur Twitter la juge pertinente, il pourrait la soumettre aux votes en seulement deux clics.

Tout le monde serait invité à voter. Pour qu'une proposition soit acceptée, il faudrait que :&#x20;

* Au moins 4000 points de réputation se soient exprimés (somme des votes en faveur et contre)
* La majorité des points de réputation soit en faveur
* Au moins 5 personnes avec le rôle @🐤Membre soient en faveur (mesure sybil résistante)

Une proposition serait refusée si :&#x20;

* Au moins 4000 points de réputation se sont exprimés (somme des votes en faveur et contre)
* La majorité des points de réputation est contre

Si une proposition n'était pas acceptée endéans les 48h, elle serait alors automatiquement rejetée.

Une fois acceptée, le contenu (le message sélectionné par un admin) est automatiquement posté sur Twitter par Demeter.

Un mois après le lancement de la fonctionnalité, si l'on constatait qu'1/3 des propositions étaient rejetées par manque de participation. Les 4000 points de réputation requis seraient abaissés à 2500.&#x20;

### Implémentation

Création d'un nouveau canal "#🐦-gestion-twitter"

Création d'un nouveau rôle "@Twitter-admin"

Ajout de 7 nouveaux paramètres au bot Discord Déméter :

* twitter-admin-role : @Twitter-admin
* twitter-member-role: @🐤Membre
* twitter-proposal-duration: 2 jours (48h)
* twitter-min-rep-proposal: 4000
* twitter-min-in-favor-members: 5
* twitter-access-token: Jeton d'accès au compte Twitter qui devra être généré par un @Twitter-admin
* twitter-refresh-token: Jeton permettant d'obtenir un nouveau jeton d'accès après son expiration. Il devra aussi être généré par un @Twitter-admin.

La fonctionnalité pourra être désactivée en effaçant le jeton d'accès (twitter-access-token).

### Rédacteur

[OoTsun](https://app.gitbook.com/u/7X8PEdE3ERU9ob8UNY8rAUwz4073 "mention")
