# Exercice

## Lancer le projet

[] Forker le projet
[] Installer les dépendances 
[] Lancer le projet en mode dev et vérifier son fonctionnement 

## Creation d'un workflow

Créer un workflow github action qui :

[ ] Run le linter
[ ] Build le dossier de prod (Dossier dist)
[ ] Recupère le dossier dist 
[ ] Deploie les sources sur une Github page

## Tips

- Gerer les permissions de votre workflow dans les paramètres du projet.
- Activer Github pages dans les paramètres
- Utilisez `npm ci` pour l'installation des dependances (évite la mise à jour du fichier lock)
- dans `vite.config.js` utilisez le paramètre `base`pour specifier le chemin de vos fichiers sources
- Utiliser des [artifacts pour deployer la page](https://github.com/actions/upload-pages-artifact)

