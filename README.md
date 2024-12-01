<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="Ahmed_Taoudi Fut" />

  &#xa0;

  <!-- <a href="https://ahmed_taoudifut.netlify.app">Demo</a> -->
</div>

<h1 align="center">FUT Team Builder : FutCoach </h1>



<!-- Status -->

<!-- <h4 align="center"> 
	🚧  Ahmed_Taoudi Fut 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-fonctionnalités">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="https://github.com/tawdi" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

**FutCoach** est une application qui permet aux utilisateurs de créer et gérer leur équipe Ultimate Team (FUT) en respectant des formations tactiques comme le 4-3-3 ou le 4-4-2. Les utilisateurs peuvent ajouter, positionner et modifier des joueurs tout en prenant en compte les règles de formation et la chimie de l’équipe. L’application offre également une gestion dynamique des joueurs via des formulaires, un calcul de la chimie, et permet de sauvegarder les configurations dans `localStorage`.

## :sparkles: Fonctionnalités ##

:heavy_check_mark: **Ajout dynamique de joueurs** : Ajouter des joueurs via un formulaire avec des champs pour le nom, la position, les statistiques, etc. Les joueurs sont ensuite positionnés selon la formation choisie (ex. 4-3-3, 4-4-2).\

:heavy_check_mark: **Positionnement des joueurs selon la formation tactique** : Les joueurs sont automatiquement positionnés selon des formations prédéfinies (4-3-3 ou 4-4-2).\

:heavy_check_mark: **Calcul de la chimie de l’équipe** : Le score de chimie est calculé en fonction des relations entre les joueurs (même club, même championnat, même nationalité).\

:heavy_check_mark: **Gestion des cartes de joueurs** : Ajouter, modifier et supprimer des joueurs tout en respectant les règles de formation (maximum de 11 joueurs pour la formation principale).\

:heavy_check_mark: **Formulaire dynamique pour la gestion des joueurs** : Les joueurs peuvent être ajoutés ou supprimés dynamiquement, et leurs positions sont ajustées en fonction de la formation choisie.\

:heavy_check_mark: **Support du LocalStorage** : Sauvegarder les configurations d’équipe et de formation localement avec `localStorage` pour les récupérer lors de la réouverture de l’application.\

:heavy_check_mark: **Design responsive** : L’application est entièrement responsive, garantissant une expérience optimale sur desktop, tablette et mobile.

## :rocket: Technologies ##

The following tools were used in this project:

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript (Vanilla)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)

## :white_check_mark: Requirements ##

Avant de commencer :checkered_flag:, assurez-vous d'avoir un navigateur moderne (comme Chrome, Firefox, Edge) installé.

## :checkered_flag: Starting ##

```bash
```bash
# Clonez ce projet
$ git clone https://github.com/Youcode-Classe-E-2024-2025/Ahmed_Taoudi-fut.git

# Accédez au dossier du projet
$ cd ahmed_taoudi-fut

# Ouvrez index.html dans votre navigateur pour voir l'application en action


```

## :memo: License ##


#### f

# FUT Team Builder : FutCoach

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
