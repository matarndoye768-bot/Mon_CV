# Mon CV — Matar Ndoye

Page de CV personnelle réalisée en HTML5, CSS3 et JavaScript.

## Structure du projet
mon-cv/

├── index.html

├── HTML/

│   └── contact.html

├── CSS/

│   └── style.css

├── JS/

│   └── script.js

├── IMAGES/

│   └── photo-profil.jpg

└── README.md
- **index.html** : page principale présentant le profil (photo, coordonnées,
  compétences, langues, expérience, formation, outils, qualités, centres
  d'intérêt).
- **HTML/contact.html** : page de contact avec formulaire (validation HTML5
  native).
- **CSS/style.css** : tout le style du site, regroupé dans un seul fichier
  externe.
- **JS/script.js** : mise en surbrillance du lien actif dans le menu, et
  message de confirmation à l'envoi du formulaire de contact.
- **IMAGES/photo-profil.jpg** : photo de profil affichée dans le CV.

## Choix de design

- **Balises sémantiques** : `<header>`, `<nav>`, `<main>`, 
  `<aside>`, `<footer>` sont utilisées pour structurer les pages, sans aucune
  balise `<table>` pour la mise en page.
- **Mise en page** : CSS Grid pour organiser le CV en deux colonnes (`aside`
  pour les informations personnelles, `main` pour le parcours).
- **Listes** : compétences, langues, formation, outils, qualités et centres
  d'intérêt sont présentés sous forme de listes `<ul><li>`.
- **Palette de couleurs** : couleurs déclarées en variables CSS 
  (vert foncé pour les accents, vert clair pour les titres , blanc
  et gris clair pour les fonds).
- **Effet interactif** : effet `:hover` avec `transition` sur les liens du
  menu de navigation.
- **Responsive** : le site s'adapte aux écrans mobile, tablette et desktop
  grâce à des media queries.

## JavaScript

Le fichier `JS/script.js` ajoute deux fonctionnalités :
1. Mise en surbrillance automatique du lien correspondant à la page actuelle
   dans le menu de navigation.
2. Affichage d'une alerte de confirmation lors de l'envoi du formulaire de
   contact (le formulaire ne pointe vers aucun serveur).

## Déploiement

Le site est déployé en ligne via GitHub Pages :
👉 https://matarndoye768-bot.github.io/Mon_CV/

## Auteur

Matar Ndoye — Étudiant en Licence 2 Informatique, UFR SET, Université Iba
Der Thiam de Thiès.
