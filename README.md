# Valet+ Magento Project

## Getting started

### Requirements

- Composer (https://getcomposer.org/download/)
- Valet Plus (https://github.com/weprovide/valet-plus)

### Clone valet-install to ~/.valet-install

`git clone git@github.com:PMET-public/valet-install.git ~/.valet-install`

### Set your global auth.json credentials

https://devdocs.magento.com/guides/v2.3/install-gde/prereq/connect-auth.html

1. `cd ~/.valet-install`
2. `cp auth.json.sample auth.json`
3. `code auth.json`

### PATH that Bash up!

Add `export PATH=$PATH:$HOME/.valet-install/bin` to .bash_profile (for bash) or .zshrc (for zsh) depending on your shell.

💡 `echo $SHELL`

--- 

## Usage

From the Magento 2 project root folder:

1. `magevars` Creates a symlink of auth.json and copies .env.sample
2. `composer install` Installs Magento's PHP modules
3. `vp -i` Install Magento project in Valet+
