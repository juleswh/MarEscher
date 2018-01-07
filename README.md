# MarEscher

MarEscher est un l'ogiciel libre d'aide à l'activité maraîchère développé avec TypeScript et Angular 5 à l'aide du framework [Electron](https://github.com/electron/electron). Nous sommes parti du travail de Maxime Gris : [angular-electron](https://github.com/maximegris/angular-electron).

## Téléchargement

*Insérer ici lien vers logiciel fini*

## Installation

- Sur votre système, installez nodejs et npm avec votre gestionaire de paquets préféré ou depuis les sources (nodejs>=6.0, npm>=3.0)
- Après avoir cloné ce dépot, ouvrez un terminal dans le dossier de MarEscher puis installez les dépendance avec :
```sh
npm install
```
- Installez angularCLI :
```sh
npm install -g @angular/cli
```
- Vous pouvez lancer l'application en local pour du développement avec la commande :
```sh
npm start
```
- Faites-vous(nous) plaisir en développant de nouvelles fonctionnalités !

## Empaqueter :
Pour créer les binaires pour toutes les plateformes exécutez l'une de ces commandes :

|Commandes|Description|
|--|--|
|`npm run start:web`| Lance l'application dans le navigateur |
|`npm run electron:linux`| Crée un binaire pour les systèmes linux |
|`npm run electron:windows`| Sous windows, crée un binaire pour un système windows 32/64 bit |
|`npm run electron:mac`|  Sous MAC, crée un fichier .app pour MAC |
