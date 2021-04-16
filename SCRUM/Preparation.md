# Préparer un projet Scrum

## Définir la vision du projet

Vous êtes de ceux qui peuvent se rendre à l'aéroport et partir à l'aventure ou comme moi, plutôt planifier avant.

La méthode SCRUM est comme moi, le **PO** défini la vision du produit final dès le début du projet pour savoir ce que nous devons faire.

La destination est ce que l'on appelle un **MVP (Minimum Viable Project)**

Ça permet quoi un MVP ?

- Ça permet d'obtenir des retours rapides de notre produit.
- Réduis les écarts potentiels par rapport à la portée du projet initial.

Essayons de prendre un exemple plus ou moins concret :

Je souhaite une appli mobile qui permette de commander des plats sains disponible sur place ou en livraison.

Ce que je viens de définir est la **vision du projet**.

Maintenant, je vais découper ça sous **forme de thème**. (ex avec un resto, sur la carte il y a entrée/plat/dessert/etc.).

Ici, nos thèmes ont l'air d'être :

- Le profil
- La commande
- Le paiement
- La livraison
- etc.

Ok, j'ai mes **thèmes**, maintenant, je souhaite les décomposer en **fonctionnalités**.

- Le profil
- Connexion
- Enregistrement du MDP
- Commandes
- Favoris
- etc.

Il y a beaucoup de choses, mais si on souhaite faire un MVP, le PO peut décider que pour le profil, nous allons faire

- Connexion
- Enregistrement MDP
  
## Découvrir les user stories

Ok, avec ce que j'ai défini au dessus nous avons déjà, je pense dégrossi la chose. Maintenant, nous allons faire plus dans le détail. Même si j'arrive à concevoir ça dans ma tête, je vais devoir le retranscrire sous forme de code.

Pour ça, nous avons les **User Stories**.

Elles offrent le niveau de détail requis pour savoir ce qu'il faut livrer.

Pour créer de bonnes User Stories il y a une méthode [INVEST](https://en.wikipedia.org/wiki/INVEST_(mnemonic)) de Bill Wake qui est très utilisé.

|     | Description                                                                                          |
| --- | ---------------------------------------------------------------------------------------------------- |
| I   | Indépendante, pas liée aux autres stories                                                            |
| N   | Négociable, tant que nous ne sommes pas en train de travailler avec, elle peut être modifier, annulé |
| V   | Valeur, elles ont du sens                                                                            |
| E   | Estimable, elles doivent être assez descriptives pour qu'on puisse les terminer                      |
| S   | Succincte, suffisamment petite pour être fini dans un sprint                                         |
| T   | Tester                                                                                               |

Don't panic, il y a une méthode qui permet de faire ça rapidement.

```php
En tant que <rôle utilisateur>, je veux
<exigence utilisateur> pour
<bénéfice souhaité>
```

Un exemple :

```php
En tant que <client mobile>, je veux
<créer un profil> pour
<que les prochaines commandes soient plus rapides>
```

## Utiliser les story points et les estimations

Dans la vie de tous les jours, il y a 2 types d'estimations.

Relative et Réel.

**Réel**, il y a exactement 42km entre le point A et B.

**Relative**, la taille d'une girafe est d'environ 2 zèbres.

En SCRUM, nous utilisons les 2.

D'abord, on estime le temps d'une façon grossière d'une user stories. On ne souhaite pas que les parties prenantes pensent qu'on va savoir exactement le temps que ça va nous prendre pour obtenir un résultat.

Cependant, quand on s'engage, il faut être très clair du temps que ça va prendre. On passe donc à l'estimation réel. Au début, évidemment qu'on va se tromper. Mais avec de la pratique et du temps, on commence à prendre l'habitude.


## Élaborer la feuille de route et le plan de release

Une fois tout fait, on doit définir le moment pour effectuer les tâches.

2 outils SCRUM

- Feuille de route
- Guide qui indique quand les thèmes seront traités au cours d'une période donnée.
- Plan de release
- Permet de créer un planning en fonction de la feuille de route