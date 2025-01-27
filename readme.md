# Commandes git

Liste des commandes git

## git init
- Permet d'initialiser un repertoire


## git add
- Permet d'ajouter un fichier ou des modifications dans le stagging   

## git commit 
- Permet d'enregistrer une modification en local
- Le message est important

## git push 
- Permet de pousser les modifications en ligne

## git status 
- Permet de vérifier le statut du répertoire
- Permet de lister les modifications à traiter 

## git log
- Permet de lister les modifications en local

## git branch
- Permet de créer une branche

## git checkout
- Permet de passer d'une branche à une autre
- Permet de se déplacer d'une branche à une autre
- Avec -b checkout crée la branche si elle n'existe pas

## git pull
- Permet de récupérer les modifications distantes. 

## git rebase
- Permet de récupérer les modifications de la branche mère.
- Les modifications de la branche mère sont placées en-dessous des modifications de la branche courante
- Les modifications de la branche courante sont placées au-dessus des modifications de la branche mère

## git reset
- Permet de supprimer un commit 
- L'ordre des commit n'est pas toujours sauvegarder 
- Permet aussi de revenir à un commit précis défini par son identifiant
- Pour conserver l'ordre des commit il faut utiliser l'option --no-off
- Attention, à utiliser avec précaution

## git diff 
- Permet de comparer deux commits
