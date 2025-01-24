

# **Calculatrice Simple - Projet React**

## Description

Cette application est une **calculatrice simple** construite avec **React**. Elle permet de réaliser des calculs de base comme l'addition, la soustraction, la multiplication et la division. Elle est conçue pour être simple à utiliser et offre une interface claire et intuitive.

## Fonctionnalités

- Addition, soustraction, multiplication et division.
- Affichage des résultats en temps réel.
- Interface utilisateur responsive.

## Technologies Utilisées

- **React** : Librairie JavaScript pour construire l'interface utilisateur.
- **CSS** : Styles pour l'interface.
- **React Hooks** : Utilisation des hooks pour gérer l'état de l'application (ex. `useState`).

## Prérequis

Avant de commencer, assurez-vous d'avoir installé **Node.js** et **npm** sur votre machine.

- [Télécharger Node.js](https://nodejs.org/)

## Installation

### 1. Clonez ce dépôt

```bash
git clone https://github.com/ton-utilisateur/calculatrice-react.git
cd calculatrice-react
```

### 2. Installez les dépendances

```bash
npm install
```

### 3. Démarrer le serveur de développement

```bash
npm start
```

L'application sera accessible sur [http://localhost:3000](http://localhost:3000).

## Utilisation

1. **Saisir un nombre** : Cliquez sur les boutons numériques.
2. **Choisir une opération** : Cliquez sur les boutons d'opérations (`+`, `-`, `*`, `/`).
3. **Calculer le résultat** : Cliquez sur le bouton égal (`=`).
4. **Effacer l'écran** : Cliquez sur le bouton "C" pour réinitialiser la calculatrice.

## Structure du projet

```
calculatrice-react/
│
├── public/
│   └── index.html      # Fichier HTML principal
│
├── src/
│   ├── components/     # Composants de l'application
│   │   └── Calculator.js   # Composant de la calculatrice
│   │
│   ├── App.js          # Composant principal de l'application
│   ├── index.js        # Point d'entrée de l'application
│   └── style.css       # Styles globaux
│
├── package.json        # Dépendances et scripts
└── README.md           # Ce fichier
```

