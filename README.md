# Projet DevOps


Projet de conteneurisation et déploiement d'une application web.


## Contributeurs

- Michelle SONG 21106878 ([@misoop](https://github.com/misoop))
- Camelia BOUALI 21108238 ([@cmla16](https://github.com/cmla16))
- Arthur ESCRIOU (chargé du projet)


## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- Node.js : Seules les versions [Active LTS et Maintenance LTS](https://nodejs.org/en/about/previous-releases) sont compatibles avec Strapi (actuellement v18 et v20)

- Votre gestionnaire de paquets Node.js préféré :
    - [npm](https://docs.npmjs.com/cli/v6/commands/npm-install) (v6 ou version ultérieure)
    - yarn



## Script

Pour démarrer l'application, exécuter : 

```bash
docker compose up
```

Ou alors, exécuter le fichier `script.sh` qui est fourni.

Ouvrir http://localhost:5173 pour visualiser dans le navigateur.
Pour accéder à l'API Strapi, ouvrir http://localhost:1337.


## Informations

Il y a en tout 3 conteneurs permettant d'activer l'application :
- **postgres** : contenant la base de données PosgreSQL qu'utilise notre projet Strapi, crée à partir de l'image postgres du Docker Hub
- **strapi** : contenant le projet Strapi, crée à partir du dossier `projet-dev`
- **strapi-frontend** : contenant la partie front de l'application, crée à partir du dossier `opsci-strapi-fontend` par Arthur Escriou


## Demo

Vous pouvez trouver le screencast présentant brièvement les codes et les différentes fonctionnalités de l'application dans le fichier `screencast-final.mov`.


## Sreenshots et logs

![Capture d'écran des logs](logs.png)
