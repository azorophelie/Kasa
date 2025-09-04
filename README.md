# Kasa - Application de location immobilière

**Projet 5 de ma formation Développeur Web chez OpenClassrooms 2024**

Ce projet consiste à réalise la refonte front-end du site Kasa, une plateforme de location d’appartements entre particuliers.
L’objectif principal était de développer une application React fonctionnelle et responsive, en suivant les maquettes Figma et les consignes de la CTO et du designer.


👉 [Lien vers le site Kasa](https://azorophelie.github.io/Kasa/)

🚀 *Ce site a été déployé avec GitHub Pages.*

--- 

## Prérequis
Avant de démarrer le projet, assurez-vous d’avoir installé :

- Node.js 
- npm ou yarn pour gérer les paquets JavaScript
- Un éditeur de code moderne (VS Code recommandé)
- Navigateur web moderne (Chrome, Firefox, Edge, Safari…)

#### 1. Cloner le dépôt
```sh
git clone git@github.com:azorophelie/Kasa.git

cd kasa
```

#### 2. Installer les dépendances 
```sh
npm install
```

#### 3. Installer React Router
```sh
npm install react-router-dom
```

#### 4. Lancer le projet en développement 
```sh
npm start
```

> Optionnel mais recommandé :
#### 5. Installer Sass si tu utilises des fichiers .scss :
```sh
npm install sass
```

## Technologies utilisées

![HTML](https://img.shields.io/badge/HTML-FF69B4)
![CSS](https://img.shields.io/badge/CSS-green)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow)
![Node.js](https://img.shields.io/badge/NODE.JS-blue?style=flat-square)
![NPM](https://img.shields.io/badge/NPM-orange?style=flat-square)
![React](https://img.shields.io/badge/React-purple?style=flat-square)

---

## Objectifs de la mission

- Développer l’ensemble des composants React : Banner, Card, Collapse, Slideshow, Layout, Pages
- Implémenter le routage avec React Router pour toutes les pages du site
- Intégrer la logique des Collapses et de la galerie Slideshow
- Assurer un site responsive et fidèle aux maquettes Figma
- Corriger les comportements interactifs : navigation dans la galerie, ouverture/fermeture des Collapses, page 404


Structure des fichiers
- /src/ : code source React
- App.js : fichier principal de l’application, point d’entrée du projet
- components/ : composants Banner, Card, Collapse, Slideshow, Layout…
- pages/ : pages Home, About, Error…
- data/ : fichier JSON avec les données des appartements
- styles/ : fichiers Sass pour la mise en forme
- /public/ : assets publics (images, favicon…)
  
## Contexte du projet
- Entreprise : Kasa, leader français de la location d’appartements entre particuliers
- Missions : Développer le front-end React complet du site, intégrer les maquettes Figma et les données JSON fournies
- Contraintes : Pas de back-end disponible au début, données statiques dans un fichier JSON
- Collaboration : Laura (CTO), Paul (designer)

##### Ressources fournies
- 🎨 [Maquette Figma](https://www.figma.com/design/2BZEoBhyxt5IwZgRn0wGsL/Kasa_FR?node-id=0-1&p=f&t=t6tZFUiayo3ne0OT-0)
- 📐 [Prototypes Figma](https://www.figma.com/proto/2BZEoBhyxt5IwZgRn0wGsL/Kasa_FR?type=design&node-id=3-0&t=x8RBKuR4UiE3hhBW-0&scaling=scale-down&page-id=0%3A1&starting-point-node-id=3%3A0&show-proto-sidebar=1)
- 🏠 [Fichier JSON des logements](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P9+React+1/logements.json)
- 🛠️ [Coding guidelines Kasa](https://course.oc-static.com/projects/D%C3%A9veloppeur+Web/IW_P8+React+Kasa/Kasa+coding+guidelines+-+IW+-+DW.pdf)


