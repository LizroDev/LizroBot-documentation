---
description: Dans cette page, vous trouverez comment gérer les permissions des commandes.
---

# Gérer les permissions des commandes

### Introduction

Depuis peu, Discord permet aux gérants des serveurs de personnaliser les permissions de chaque commande. Cependant, beaucoup de bots ne sont pas encore prêts pour cette nouveauté. En effet, la plupart des bots gèrent eux-mêmes les permissions des commandes.



C'est pourquoi, nous avons développé un système vous permettant de gérer vos permissions. Ceci ne fonctionne uniquement pour les nouveaux types de commandes (Slash /, les commandes utilisateurs et les commandes messages). Il sera donc nécessaire de supprimer toutes les commandes dites "classiques" qui fonctionnent à l'ancienne avec un préfixe.



### Tutoriel

#### Étape 1 - Se connecter sur le Dashboard

La première étape consiste donc à se connecter sur le [Dashboard](https://lizrobot.com/dashboard) puis sélectionner le serveur dont vous souhaitez gérer les permissions.

#### Étape 2 - Gérez vos permissions

Vous devez désormais configurer les permissions de vos commandes directement depuis Discord.

Pour cela, rendez-vous dans les paramètres de votre serveur puis dans Intégrations :

![Onglet intégrations dans les paramètres du serveur](<.gitbook/assets/Capture d’écran 2022-05-27 à 22.21.14.png>)

Cherchez LizroBot et cliquez sur Gérer à droite :

![Onglet LizroBot](<.gitbook/assets/Capture d’écran 2022-05-27 à 22.22.58.png>)

Maintenant, vous pouvez configurer les salons dans lesquels les utilisateurs peuvent exécuter des commandes.

En descendant, vous trouverez toutes les commandes, en cliquant sur chacune, vous pouvez autoriser ou interdire à des membres de les utiliser.&#x20;

Prenons par exemple la commande `forceskip` qui permet de passer la musique sans vote, si vous souhaitez l'autoriser à une personne, cliquez dessus :&#x20;

![Commande forceskip](<.gitbook/assets/Capture d’écran 2022-05-27 à 22.23.13.png>)

Il vous suffit maintenant de gérer les rôles, les salons et les membres sur toutes les commandes !

{% hint style="warning" %}
Veuillez également le faire sur les commandes de modération et d'administration sinon tous les utilisateurs pourront les utiliser.
{% endhint %}

#### Étape 3 - Ignorer les permissions par défaut et désactiver les commandes classiques

Vous devez donc maintenant activer le bouton "Ignorer les permissions par défaut des commandes Slash". Cela aura pour effet que tous les membres auront accès à toutes les commandes.

Il faut également désactiver "Commandes classiques", sinon les utilisateurs pourront contourner les interdictions en passant par les commandes nécessitant un préfixe.&#x20;

![Dashboard](<.gitbook/assets/Capture d’écran 2022-05-27 à 22.28.11.png>)

Et voilà ! Vous pouvez désormais profiter de vos nouvelles permissions !
