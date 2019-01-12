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

`npm init -y` answers 'yes' to all prompts

----------

`yarn add webpack webpack-cli --dev` only need pre-build

----------
