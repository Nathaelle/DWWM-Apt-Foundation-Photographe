# Foundation for Sites Template

Projet initial [Foundation for Sites 6](http://foundation.zurb.com/sites). 

## Installation

L'utilisation de ce template requiert l'installation de :

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)


### Manual Setup

Pour installer le template Foundation, téléchargez-le avec Git :
(en prenant soin de le renommer projectname => nom_de_votre_projet)

```bash
git clone https://github.com/zurb/foundation-sites-template projectname
```

Maintenant ouvrez le dossier en ligne de commande (déplacez-vous dessus), et installez les dépendances requises :

```bash
cd projectname
npm install
```

Enfin, lancez `npm start` pour executer le compilateur Sass. Il sera ré-exécuté à chaque changement (lorsque vous sauvegardez un changement)

NB: Si une erreur survient lors de l'exécution de la commande, réinstallez gulp `npm install gulp-sass`

**Vous trouverez tous les "issues" git (problèmes et pistes correctifs) sur le "repo" git (dépot) [Foundation for Sites](https://github.com/zurb/foundation-sites/issues).**

## Exercice

Objectifs : 
- Manipulation du framework
- Recherches dans une documentation
- Utilisation de la grille 

Enoncé :
M. Pixol, photographe, désire mettre en valeur le fruit de son travail sur un site Web.
Il vous demande, au minimum, d'avoir une page galerie, ou l'on pourra jeter un oeil à l'ensemble de son oeuvre, puis, lorsque l'on clique sur une image, il souhaiterai avoir une vue plein écran de la photographie.