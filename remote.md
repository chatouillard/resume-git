# Index collaboratif des commandes `git`



## Revenir à la liste des commandes

Pour revenir à la liste complète des commandes, [cliquez ici](index.html)



## Commande `git remote`


### Description

La commande `git remote` permet de gerer les liens du depot distant.

### Exemples

```
$ git remote

origin
```

en gros, git remote sert a plusieurs choses, il est très varié. il dispose e toutes ces options:

git remote [-v | --verbose]
git remote add [-t <branch>] [-m <master>] [-f] [--[no-]tags] [--mirror=(fetch|push)] <name> <url>
git remote rename <old> <new>
git remote remove <name>
git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
git remote set-branches [--add] <name> <branch>…​
git remote get-url [--push] [--all] <name>
git remote set-url [--push] <name> <newurl> [<oldurl>]
git remote set-url --add [--push] <name> <newurl>
git remote set-url --delete [--push] <name> <url>
git remote [-v | --verbose] show [-n] <name>…​
git remote prune [-n | --dry-run] <name>…​
git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)…​]

```

