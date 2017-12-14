# MarEscher

MarEscher est un l'ogiciel libre d'aide à l'activité maraîchère développé en JavaScript/HTML/CSS à l'aide du framework [Electron](https://github.com/electron/electron).

## Installation

*Insérer ici lien vers logiciel fini*

## Installation velue pour développeurs

- Sur votre système linux (pour windows et mac vous trouverez des infos sur le site d'Electron), installez nodejs et npm avec votre gestionaire de paquets préféré.
- Après avoir cloné ce dépot, ouvrez un terminal dans le dossier de MarEscher puis installer Electron avec la commande suivante :
```sh
npm install electron --save-dev --save-exact
```
- Lancez MarEscher à l'aide de la commande suivante (sous linux) :
```sh
./node_modules/.bin/electron .
```
- Faites-vous(nous) plaisir en développant de nouvelles fonctionnalités !

Pour créer les binaires pour toutes les plateformes (windows, macOS, linux 32/64 bits, ARM...), installez electron-packager depuis npm. Puis, dans le dossier du projet lancez la commande :
```sh
electron-packager . --all --name "MarEscher" --version "0.1"
```