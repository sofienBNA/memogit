# memo git
Git est un logiciel local qui permet de sauvegarder des projets au fur est a mesure.
Git hub et la plateforme web qui utilise git pour l'utilisation en collaboration.


Vérifier sa version de GIT
$ git - - version

Définir son nom : 
$ git config - - global user.name « mon nom »

Définir mon adresse mail :
$ git config - - global user.email « mon email »

Repo = dépôt = collection de fichiers liées à un projet

Activer Git pour un répertoire
$ git init 

Créer un nouveau dossier
$ mkdir nomdudossier

Naviguer dans un dossier
$ cd nomdudossier

Lister les éléments dans un dossier
$ ls

ouvrir virtual studio code 
$ code

Vérifiez l'état des modifications dans un dépôt
$ git status

Afficher les modifications apportés aux fichiers
$ git diff

Ajouter les modifications d'un fichier à soumettre
$ git add <FILENAME>

Pour ajouter toutes les modifications d'un seul coup
$ git add .

Pour soumettre les modifications que vous avez ajoutées avec un court message décrivant les modifications
$ git commit -m "your commit message"

Pour envoyer syncroniser les modifications sur git hub
$ git push -u(uniquement la 1er fois) original master