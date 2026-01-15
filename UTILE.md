# UTILE

git config --global pull.rebase true

git pull --rebase

Avant de commencer à travailler :
git pull --rebase origin main

## TOUJOURS

git checkout webromain
git pull --rebase origin main

une fois config git effectuée :
git pull origin main

## POUR LIVRER

git checkout main
git merge webromain
git push
