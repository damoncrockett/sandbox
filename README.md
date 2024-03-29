# sandbox

These instructions assume a fresh Mac without Homebrew, nvm, or yarn

----------

Make GitHub repo for the project and clone locally

----------

install Homebrew

----------

`brew install nvm`

----------

`mkdir ~/.nvm`

----------

add to .bash_profile:

export NVM_DIR=~/.nvm

source $(brew --prefix nvm)/nvm.sh 

----------

`nvm install 16.13.1`

`nvm use 16.13.1`

----------

`corepack enable`

----------

`yarn init -2`

----------

`npm init -y` answers 'yes' to all prompts

----------

`yarn add webpack webpack-cli --dev` only need pre-build

----------

add to .gitignore:

.DS_Store

node_modules

dist

fonts

utils/__pycache__

utils/.ipynb_checkpoints

utils/*.ipynb

.yarn/*

!.yarn/patches

!.yarn/releases

!.yarn/plugins

!.yarn/sdks

!.yarn/versions

.pnp.*

----------

`yarn add webpack-dev-server --dev`

add start and build scripts to package.json

----------

`yarn add css-loader style-loader html-webpack-plugin --dev`

add loader rules and html plugin to webpack config

----------

`yarn add @babel/core babel-loader @babel/preset-env @babel/preset-react --dev`

create babel.config.json

----------

structure project as it appears here

fill out webpack config as it appears here (note: 'template' index.html in project root dir, not src/)

----------

`yarn add react react-dom`

----------

Fill in boilerplate for index.html, index.js, App.js, style.css
