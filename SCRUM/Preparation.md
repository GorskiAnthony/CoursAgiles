# Préparer un projet Scrum

## Définir la vision du projet

Vous êtes de ceux qui peuvent se rendre à l'aéroport et partir à l'avanture ou comme moi, plutôt planifier avant.

La méthode SCRUM est comme moi, le **PO** défini la vision du produit final dès le début du projet pour savoir ce que nous devons faire.

La destination est ce que l'on appel un **MVP (Minimum Viable Project)**

Ça permet quoi un MVP ? 

- Ça permet d'obtenir des retours rapide de notre produit.
- Réduit les écarts potentiel par rapport à la portée du projet initial.

Essayons de prendre un exemple plus ou moins concret :

Je souhaite une appli mobile qui permette de commander des plats sains disponible sur place ou en livraison.

Ce que je viens de définir est la **vision du projet**.

Maintenant, je vais découper ça sous **forme de thème**. (ex avec un resto, sur la carte il y a entrée/plat/dessert/etc.). 

Ici, nos thème ont l'air d'être :

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
  - etc

Il y a beaucoup de chose, mais si on souhaite faire un MVP, le PO peut décider que pour le profil, nous allons faire 

- Connexion
- Enregistrement MDP

## Découvrir les user stories

Ok, avec ce que j'ai défini au dessus nous avons déjà, je pense dégrossi la chose. Maintenant, nous allons faire plus dans le détail. Même si j'arrive à concevoir ça dans ma tête, je vais devoir le retranscrire sous forme de code.

Pour ça, nous avons les **User Stories**.

Elle offrent le niveau de détail requis pour savoir ce qu'il faut livrer.

Pour créer de bonnes User Stories il y a une méthode [INVEST](https://en.wikipedia.org/wiki/INVEST_(mnemonic)) de Bill Wake qui est très utilisé.

|     | Description                                                                                      |
| --- | ------------------------------------------------------------------------------------------------ |
| I   | Indépendante, pas liée aux autres stories                                                        |
| N   | Négociable, Tant que nous sommes pas entrain de travailler avec, elle peut être modifier, annulé |
| V   | Valeur, elles ont du sens                                                                        |
| E   | Estimable, elles doivent être assez descriptivent pour qu'on puissent les terminer               |
| S   | Succincte, suffisant petite pour être fini dans un sprint                                        |
| T   | Tester                                                                                           |

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

Dans la vie de tout les jours, il y a 2 types d'estimations.

Relative et Réel.

**Réel**, il y a exactement 42km entre le point A et B.

**Relative**, la taille d'une girafe est d'environ 2 zebres.

En SCRUM nous utilisons les 2. 

D'abord, on estime le temps d'une façon grossiere d'une user stories. On ne souhaite pas que les parties prenante pense qu'on va savoir éxactement le temps que ça va nous prendre pour obtenir un résultat.

Cepedant, quand on s'engage, il faut être très clair du temps que ça va prendre. On passe donc a l'estimation réel. Au début évidement qu'on va se tromper. Mais avec de la pratique et du temps, on commence à prendre l'habitude.


## Élaborer la feuille de route et le plan de release

Une fois tout fait, on doit définir le moment pour éffectuer les tâches.

2 outils SCRUM

- Feuille de route
  - Guide qui indique quand les thèmes seront traités au cours d'une période donnée.
- Plan de release
  - Permet de créer un planning en fonction de la feuille de route