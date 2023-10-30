# Consigne

**Objectif** : linéariser l'historique des commits : rebase

Instructions
 - 1 personne du groupe fork ce dépôt principal
 - `cette personne configure le dépôt pour interdire les Merge Pull qui n'ont pas un historique linéaire (voir la section suivante)`
 - chaque équipier crée une branche au format `prenom_nom` à partir du commit initial
 - sur cette branche `prenom_nom`, chaque équipier ajout son nom à la liste des auteurs à la fin de ce fichier dans un commit
 - la branche `prenom_nom` doit être propagée au dépôt distant (push)
 - créer 1 Pull Request GitHub pour récupérer les contributions de la branche `prenom_nom` dans la branche principale
 - l'acceptation de la Pull Request mergera enfin la branche `prenom_nom` dans la branche principale du dépôt
 - `les Pull Requests doivent être acceptées l'unes après les autres`
 - `suite à l'acceptation d'une Pull Request, les autres membres du groupe doivent faire un rebase sur le commit le plus à jour de la branche principale`
 - `suite à ce rebase, propagé la mise à jour de leur branche vers le dépôt GitHub avec un "push -f"`
 - `enfin accepter la Pull Request relative à leur branche`
 - à la fin de l'activité, le dépôt du groupe doit :
   - `avoir un historique avec des ponts, représentant les différentes branches, qui ne se chevauchent plus ou un historique sans pont (dépendant de l'option de merge choisie)`
   - avoir une seule branche principale

Pour se faire, vous aurez besoin de
 - l'ensemble des savoirs des exo précédents, et la commande git suivante :
   - **rebase** : réécrire l'historique des commits
 - savoir créer un Pull Request sur GitHub

Je recommande vivement de visualiser les changements de l'historique des commits
après chaque commande git.

**Remarque** : les rebases successifs peuvent être fastidieux pour peu de valeur ajouté. En fonction de la politique de développement de l'équipe, celle-ci peut choisir de faire systèmatiquement des rebases ou non pour alléger son workflow.

# Forcer une historique linéaire avec GitHub

![Forcer une historique linéaire GitHub](./github-linear-history.gif "Forcer une historique linéaire GitHub")

# Partie du fichier à mettre à jour

Auteurs :
 - Fabien Rozar
 - Florian Ah-Yane
 - Mael Pompilius
