<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="Ahmed_Taoudi Fut" />

  &#xa0;

  <!-- <a href="https://ahmed_taoudifut.netlify.app">Demo</a> -->
</div>

<h1 align="center">Ahmed_Taoudi Fut</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/tawdi/ahmed_taoudi-fut?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/tawdi/ahmed_taoudi-fut?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/tawdi/ahmed_taoudi-fut?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/tawdi/ahmed_taoudi-fut?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/tawdi/ahmed_taoudi-fut?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/tawdi/ahmed_taoudi-fut?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/tawdi/ahmed_taoudi-fut?color=56BEB8" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  Ahmed_Taoudi Fut 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/tawdi" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

Describe your project

## :sparkles: Features ##

:heavy_check_mark: Feature 1;\
:heavy_check_mark: Feature 2;\
:heavy_check_mark: Feature 3;

## :rocket: Technologies ##

The following tools were used in this project:

- [Expo](https://expo.io/)
- [Node.js](https://nodejs.org/en/)
- [React](https://pt-br.reactjs.org/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)

## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com) and [Node](https://nodejs.org/en/) installed.

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/tawdi/ahmed_taoudi-fut

# Access
$ cd ahmed_taoudi-fut

# Install dependencies
$ yarn

# Run the project
$ yarn start

# The server will initialize in the <http://localhost:3000>
```

## :memo: License ##


#### f

# FUT Team Builder

## Contexte du Projet
L'application **FUT Team Builder** permet aux utilisateurs de créer et gérer leur équipe Ultimate Team (FUT) en respectant des formations tactiques comme le 4-3-3 ou le 4-4-2. Les utilisateurs peuvent ajouter, positionner et modifier les joueurs tout en tenant compte des règles de formation et de chimie de l'équipe. L'application offre également une gestion dynamique des joueurs via des formulaires, un calcul de la chimie, et la possibilité de sauvegarder les configurations dans le navigateur à l'aide de `localStorage`.

## Fonctionnalités Clés

- **Intégration UI et Ajout Dynamique des Joueurs**  
  Permet d'ajouter des joueurs via un formulaire dynamique avec des champs pour le nom, la position, les statistiques, etc. Les joueurs sont ensuite positionnés automatiquement selon la formation choisie (ex. 4-3-3, 4-4-2).

- **Positionnement des Joueurs Selon la Formation Tactique**  
  Les joueurs sont positionnés selon les formations tactiques prédéfinies (4-3-3 ou 4-4-2) avec une gestion automatique des positions selon le schéma choisi.

- **Gestion des Cartes de Joueurs**  
  Les utilisateurs peuvent ajouter, modifier et supprimer des joueurs tout en respectant les règles des formations. Le nombre de joueurs est limité à 11 pour la formation principale, les autres joueurs étant réservistes.

- **Formulaires Dynamiques pour la Gestion des Joueurs**  
  Les joueurs peuvent être ajoutés ou supprimés dynamiquement. Le nombre total de joueurs est respecté, et les positions sont ajustées selon la formation sélectionnée.

- **Calcul de la Chimie de l'Équipe**  
  Un système de calcul de chimie évalue la compatibilité des joueurs en fonction de leurs relations (même club, même championnat, même nationalité). Le score de chimie est calculé et affiché en temps réel.

- **Validation des Champs des Formulaires**  
  Tous les champs des formulaires (nom, position, note) sont validés pour garantir des données cohérentes.

- **LocalStorage des Formations et Joueurs (Bonus)**  
  Les configurations de l'équipe et de la formation sont sauvegardées dans `localStorage`, permettant aux utilisateurs de récupérer leurs données lors de la réouverture de l'application.

- **Drag & Drop pour le Changement des Joueurs (Bonus)**  
  Une fonctionnalité de glisser-déposer permet de réorganiser les joueurs dans la formation.

- **Changement de Formation Dynamique (Bonus)**  
  Lors du changement de formation, les positions des joueurs sont automatiquement réajustées.

- **Responsive Design**  
  L'application est entièrement responsive, garantissant une expérience optimale sur desktop, tablette et mobile.

## Technologies Utilisées
- **HTML** : Structure du contenu.
- **CSS** : Mise en page (utilisation de frameworks comme Tailwind CSS ou Bootstrap).
- **JavaScript (Vanilla)** : Interaction dynamique avec le DOM.
- **localStorage** : Sauvegarde locale des données.

## Installation

### Prérequis
Avant de démarrer, assurez-vous d'avoir un navigateur moderne (comme Chrome, Firefox, Edge) pour une expérience optimale.

### Étapes d'Installation
1. Clonez le repository GitHub :

    ```bash
    git clone https://github.com/votre-utilisateur/fut-team-builder.git
    ```

2. Ouvrez le dossier du projet :

    ```bash
    cd fut-team-builder
    ```

3. Ouvrez `index.html` dans votre navigateur pour voir l'application en action.

## Utilisation

1. **Ajouter des Joueurs** : Utilisez le formulaire pour ajouter des joueurs avec leur nom, position, note et autres statistiques.
2. **Choisir une Formation** : Sélectionnez une formation (ex. 4-3-3 ou 4-4-2), et les joueurs seront automatiquement positionnés selon les règles de la formation.
3. **Calculer la Chimie** : Le score de chimie sera affiché en fonction des relations entre les joueurs (club, championnat, nationalité).
4. **Sauvegarde des Données** : Les configurations sont automatiquement sauvegardées dans le `localStorage`, et sont récupérées lors de la réouverture de l'application.

## User Stories

- **Création d'une équipe de 11 joueurs** : L'utilisateur peut ajouter des joueurs via un formulaire dynamique et modifier ou supprimer des joueurs.
- **Adaptation de la formation choisie** : L'utilisateur peut changer de formation et voir les positions des joueurs ajustées en fonction.
- **Calcul de la chimie** : Le score de chimie de l'équipe est calculé automatiquement et mis à jour selon les changements.
- **Sauvegarde et récupération des données** : Les configurations sont sauvegardées localement et récupérées lors de l'ouverture de l'application.

## Lien vers le Repository
Le code source est disponible sur GitHub :

- **GitHub Repository** : [Lien vers le repository](https://github.com/votre-utilisateur/fut-team-builder)

## Lien vers le Site Web Hébergé
Vous pouvez accéder à l'application en ligne via le lien suivant :

- **Site Web Hébergé** : [Lien vers le site](https://votre-site-heberge.com)

## Auteurs
- **Nom de l'auteur** : [Votre Nom]

 
Made with :heart: by <a href="https://github.com/tawdi" target="_blank">ahmed taoudi</a>

&#xa0;

<a href="#top">Back to top</a>
