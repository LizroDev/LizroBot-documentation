---
description: Cette note de mise à jour contient les principales modifications.
---

# Note de mise à jour v3

{% hint style="warning" %}
Cette note de mise à jour est encore incomplète et sera complétée d'ici les prochains jours.\
Certains points indiqués sur cette note de mise à jour seront également disponibles dans les prochains jours.
{% endhint %}

Après 6 mois de développement, voici la mise à jour de la version 3 du bot.

### Bot&#x20;

Modifications liée au bot Discord&#x20;

#### Général :&#x20;

* Adapation de toutes les commandes en /SlashCommands
* Possibilité de faire les commandes n'ayant pas de lien avec le serveur en messages privés
* Uniformisation des messages (notamment de la couleur des messages)
* Possibilité d'avoir la version premium pour une durée limitée
* &#x20;Utilisation des nouvelles intéractions de Discord&#x20;
* Ajout d'alias pour certaines commandes
* En cas d'erreur d'utilisation de la commande, le bot indique désormais l'utilisation correct
* En cas d'erreur d'utilisation de la commande, la commande n'est plus visible publiquement

#### Commandes d'informations :

* La commande help a été refaite, la navigation entre les catégories se fait désormais par un menu de sélection.
* La commande weather affiche désormais les prévisions pour les prochains jours
* La mise en forme des messages a été revue

#### Commandes de jeux :&#x20;

* Ajout du jeu Puissance 4 (2 joueurs)
* Ajout d'un module de paris sportif gratuit (football), plus d'informations sur notre [Discord](https://lizro.me/discord)
* Ajout du jeu BlackJack (1 joueur)

#### Commandes de musique :&#x20;

* Le bot ne peut désormais plus écouter les autres membres dans un salon lorsqu'il est connecté pour jouer de la musique
* Ajout d'un controlleur de musique (`music`) avec des boutons&#x20;
* Ajout de la commande `lyrics` permettant d'obtenir les paroles d'une chanson
* Ajout de la commande `shuffle` qui permet de mélanger la file d'attente
* Ajout de la commande `rewind` qui permet de revenir en arrière
* Ajout de la commande `restart` qui permet de rejouer la musique
* Ajout de la commande `playsoundcloud` qui permet de rechercher et jouer une musique sur SoundCloud
* Ajout de la commande `playnow` qui permet de jouer une musique sans prendre en compte la file d'attente
* Ajout de la commande `playlist` qui permet d'ajouter une playlist entière

#### Commandes d'administration :&#x20;

* La commande `giveaway` a été améliorée&#x20;
* La commande `reaction-role` a été simplifiée et offre plus de possibilités
* La commande `key` devient `premium`
* Ajout de la commande `settings` qui permet de modifier directement depuis le serveur Discord la configuration de certains modules

#### Commandes de modération :&#x20;

* Modification de la commande `antécédents`
* Ajout de la commande utilisateur `Antécédents` (clique droit sur un utilisateur > Applications)
* Modification des commandes

#### Commandes utilitaires :&#x20;

* Ajout de la commande `wiki` qui permet de chercheer rapidement un article sur Wikipedia
* Ajout de la commande `math` qui permet de calculer une expression mathématique
* Ajout des commandes messages`translate-fr` et `translate-en` qui permettent de traduire le contenu d'un message (clique droit sur un message > Applications)
* Ajout de la commande message `QRCode` qui permet de générer un QRCode avec le contenu du message (clique droit sur un message > Applications)
* Refonte du module de suggestions

#### Commandes de niveaux :&#x20;

* Le spam de messages ne fonctionne désormais plus
* L'XP attribuée est désormais aléatoire à chaque message (variation modifiable)&#x20;
* Il est désormais possible d'attribuer des rôles une fois que l'utilisateur a atteint un certain niveau

#### Auto-modération :&#x20;

* Ajout détection automatique du spam
* Ajout détection automatique du flood
* Ajout détection automatique des insultes
* Ajout détection automatique des majuscules excessives

### Site web  :&#x20;

* Refonte de tout le design du site web
* Il n'y désormais plus de chargement entre les pages
* Amélioration des performances
* Les modifications effectuées sur le Dashboard sont désormais instantanées&#x20;
* Ajout de cette documentation communautaire&#x20;



#### &#x20;&#x20;
