# Index collaboratif des commandes `git`



## Revenir à la liste des commandes

Pour revenir à la liste complète des commandes, [cliquez ici](index.html)



## Commande `git status`


### Description

La commande `git status` montre l'état du répertoire de travail. En particulier, elle indique les fichiers qui ont été modifiés depuis le dernier commit. La commande fait la distinction entre les fichiers déjà ajoutés à l'index et ceux qui ne le sont pas. Elle indique également les fihiers qui ne sont pas encore suivis par `git`.


### Exemples

```
$ git status
Sur la branche master

Aucun commit

Fichiers non suivis:
  (utilisez "git add <fichier>..." pour inclure dans ce qui sera validé)
        index.md
        status.md

aucune modification ajoutée à la validation mais des fichiers non suivis sont présents (utilisez "git add" pour les suivre)
```

Dans ce exemple, on voit le dépôt est vide pour le moment, vu qu'il ne contient aucun commit. Il y a deux fichies présents dans le dépôt, mais il ne sont pas encore ajouté à l'index.

```
$ git status
Sur la branche master

Aucun commit

Modifications qui seront validées :
  (utilisez "git rm --cached <fichier>..." pour désindexer)
        nouveau fichier : index.md
        nouveau fichier : status.md
```

Cette fois-ci, les fichiers sont dans l'index, mais le commit n'a pas encore été fait.

```
$ git status
Sur la branche master
rien à valider, la copie de travail est propre
```

Cette fois-ci, tout le travail a été enregistré correctement dans des commits.
