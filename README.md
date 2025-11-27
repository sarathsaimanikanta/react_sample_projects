# Create React App

*Build & Test · PRs Welcome*

## ⚠ Caution — Deprecated

Create React App was a major tool for bootstrapping React projects from , but it is now in **long-term stasis.You should migrate to a modern React framework listed in **“Start a New React Project.”*

## Documentation

* *Creating an App* – How to create a new app
* *User Guide* – How to develop apps bootstrapped with Create React App
* Works on *macOS, Windows, and Linux*
* If something doesn’t work, *file an issue*
* Questions → Ask in *GitHub Discussions*

# Quick Overview

    npx create-react-app my-app
    cd my-app
    npm start

If you've previously installed Create React App globally:

    npm uninstall -g create-react-app
    # or
    yarn global remove create-react-app

(npx comes with npm 5.2+ and higher)

Open the app at:

    http://localhost:3000/

To build for production:

    npm run build

# Get Started Immediately

No need to install or configure:

* webpack
* Babel

Everything is preconfigured.Just create a project and write code.

# Creating an App

Node requirement: *Node 14.0.0+* (use latest LTS recommended)

You can use *nvm* or *nvm-windows* to manage Node versions.

### Using npx

    npx create-react-app my-app

### Using npm

    npm init react-app my-app

### Using Yarn

    yarn create react-app my-app

Project structure:

    my-app
    ├── README.md
    ├── node_modules
    ├── package.json
    ├── .gitignore
    ├── public
    │   ├── favicon.ico
    │   ├── index.html
    │   └── manifest.json
    └── src
        ├── App.css
        ├── App.js
        ├── App.test.js
        ├── index.css
        ├── index.js
        ├── logo.svg
        ├── serviceWorker.js
        └── setupTests.js

# Running Commands

Navigate into your project:

    cd my-app

## Start the app

    npm start
    # or
    yarn start

## Run tests

    npm test
    # or
    yarn test

## Build for production

    npm run build
    # or
    yarn build
