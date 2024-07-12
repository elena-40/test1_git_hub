#Test1

# differences entre git et git hub
git est un projet open sources de gestion de code, cree par Linux
github est une platforme d'hebergement

Workflow git et github de base
- faire une modifivation en local
- git add . (le "." est pour add tout le repertoire)
- git commit -m "message de commit"
- git push origin main (pusser les modifications locales vers github)


Je veux faire un test de commit



1. git init - Cette commande initialise un nouveau dépôt Git dans le répertoire courant.


2. git clone - Clone un dépôt existant depuis une URL vers un répertoire local.
- git clone https://github.com/utilisateur/repo.git

3. git add - Ajoute des modifications de fichiers à la zone de staging (préparation pour le commit).
- git add fichier.txt
- git add .  (Pour ajouter tous les fichiers modifiés) 


4. git commit - Enregistre les modifications ajoutées à la zone de staging dans l'historique du dépôt.
- git commit -m "Message de commit"

5. git status - Affiche l'état actuel du dépôt, indiquant les fichiers modifiés, ajoutés ou non suivis.


6. git log - Affiche l'historique des commits.

7. git pull - Récupère et fusionne les modifications depuis un dépôt distant vers la branche courante.
- git pull origin branche

8. git push - Envoie les commits locaux vers un dépôt distant.
- git push origin branche

9. git branch - Liste les branches locales ou crée/supprime des branches. 
- git branch - Pour lister les branches
- git branch nouvelle-branche - Pour créer une nouvelle branche
- git branch -d branche-a-supprimer

10. git checkout - Change de branche ou restaure des fichiers.
Pour changer de branche :
 - git checkout branche (Pour créer et passer à une nouvelle branche :
 - git checkout -b nouvelle-branche

11. git merge - Fusionne une branche dans la branche courante.
 - git merge branche-a-fusionner

12. git remote - Gère les dépôts distants.
- git remote -v (Pour lister les dépôts distants)
- git remote add origin https://github.com/utilisateur/repo.git (Pour ajouter un dépôt distant)

13. git fetch

Récupère les modifications depuis un dépôt distant sans les fusionner.

sh

git fetch origin

14. git rebase

Applique les commits de la branche courante sur une autre branche.

sh

git rebase branche-cible

15. git stash

Enregistre temporairement les modifications locales pour les appliquer plus tard.

sh

git stash

Pour appliquer les modifications stashed :

sh

git stash pop