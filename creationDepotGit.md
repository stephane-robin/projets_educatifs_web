# CREATION D'UN DEPOT SUR GITHUB

1. Créer le projet sur l'ordinateur. Par exemple le dossier local contenant le projet pourra s'appeler monProjet.
2. Créer le repository vide sur Github. Ne pas l'initialiser avec un README.md et un .gitignore. Cela compliquerait le workflow inutilement. Copier l'URL créée pour le projet. Elle ressemble à https://github.com/nom-compte-github/monProjet.git.
3. Lier le dossier local au repository distant avec les commandes suivantes :
```bash
git init
git add .
git commit -m "commit initial, configuration"
git branch -M main
git remote add origin https://github.com/nom-compte-github/monProjet.git
git push -u origin main
```
4. Il faut ensuite donner l'identifiant de connexion github puis valider le token comme un mot de passe.
