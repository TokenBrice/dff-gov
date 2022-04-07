---
description: Proposition implémentée le 11 mars 2022 ✅
---

# 📜 #20 - simplification du Captcha présenté aux nouveaux arrivants dans le salon 👋-bienvenue

## CONTEXTE

Ce captcha a fait son apparition fin 2021 avec le déploiement de Déméter V2. De nombreux retours nous signalent qu'il est très compliqué à résoudre. L'utilisateur doit, à trois reprises consécutives, retrouver un emoji caché dans une image.

## PROPOSITION

Étant donné que :

* le captcha, avec ses trois étapes, est compliqué à résoudre,
* et qu'_a priori_, deux étapes suffiraient largement à mettre les éventuels bots en échecs, diminuons le nombre d'étapes à seulement deux.

Toutefois, s'il s'avère que des bots réussissent désormais le captcha, une contre proposition pourra être rédigée afin de redéfinir 3 étapes.

Sinon, à l'avenir, il pourrait aussi être envisagé de ne proposer qu'une seule étape afin de simplifier au maximum l'onboarding des nouveaux membres.

## Implémentation

La 🛠 Team Déméter ajoutera une commande de configuration à Déméter. Elle permettra de définir le nombre d'étapes requises par le captcha. Une fois l'implémentation terminée, il suffira qu'un membre de la team tape la commande dans le serveur Discord.

Exemple : /guild config captcha-step:2
