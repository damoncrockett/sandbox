# sandbox

These instructions assume a fresh Mac without Homebrew, nvm, or yarn

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

`nvm install 10.13.0`

`nvm use 10.13.0`

----------

`brew install yarn --without-node`

----------

Make GitHub repo for the project and clone locally

----------

`npm init -y` answers 'yes' to all prompts

----------

`yarn add webpack webpack-cli --dev` only need pre-build

----------

add to .gitignore:

.DS_Store

node_modules

dist

----------

`yarn add webpack-dev-server --dev`

add start and build scripts to package.json

----------

add webpack loaders: css, style, buble

add loader rules to webpack config

----------

structure project as it appears here

fill out webpack config as it appears here (note: 'template' index.html in project root dir, not src/)

----------

add react, react-dom

----------

Fill in boilerplate for index.html, index.js, App.js, style.css (to test css and style loaders)
