# Mille Noms

WORK IN PROGRESS, fonctionnel mais tout juste.

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)  [![forthebadge](http://forthebadge.com/images/badges/powered-by-electricity.svg)](http://forthebadge.com)
Bot discord pour serveur multi jdr.

Il change votre pseudo selon le salon écrit/vocal où vous intéragissez (écrivez / connectez).
Il vous remet votre pseudo discord de base si aucun ne correspond.

## Pré-requis

Il vous faut 2 choses :

* Un salon **"vos-pseudos"**

Qui référencit les pseudos à prendre en compte pour chaque personne.
Le format des pseudos doit être écris dans le salon #vos-pseudos sous cette forme :
`.<le nom du jdr><espace>:<espace><votre pseudo>`

Sans les chevrons <>.

**Exemple** :

.lancer : Shaker

.défaut : Créateur de mille noms

.donjons et Dragons : Jean Edouard de la Haute

* Une structure de votre serveur

Où chaque jdr se trouve dans une catégorie du même nom. Nous avons fait notre serveur comme suit pour que les personnes n'ayant pas tel ou tel rôle (correspondant à un jdr) ne soient pas envahies par eux.

Vue serveur :

![vue serveur](/images/mille-noms_vue_serveur.png)

Vue du rôle Cthulhu :

![vue chtullhu](/images/mille-noms_vue_chtullu.png)

## Installation

Invitez le bot sur votre serveur : [invitation](https://discord.com/api/oauth2/authorize?client_id=845214061519437835&permissions=8&scope=bot)

## Démarrage

Ensuite il ne vous reste qu'à écrire ou à vous connecter dans le salon de votre choix.

## Programmé avec

Python3 sur Ubuntu avec wsl 2

## Avis / Test / Bug

Si vous souhaitez commenter ou tester le bot, rejoignez [son serveur](https://discord.gg/HfaeJYV2jd).

## Auteur
* **Guillaume Roubaud** _alias_ [@groubaud101](https://github.com/groubaud101)
