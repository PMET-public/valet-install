# Valet+ Magento Project

## Getting started

### Clone valet-install to ~/.vi

`git clone git@github.com:PMET-public/valet-install.git ~/.vi`

### Set your global auth.json credentials

https://devdocs.magento.com/guides/v2.3/install-gde/prereq/connect-auth.html

1. `cd ~/.vi`
2. `cp auth.json.sample auth.json`
3. `code auth.json`

### PATH that Bash up!

Add `export PATH=$PATH:$HOME/.vi/bin` to .bash_profile (for bash) or .zshrc (for zsh) depending on your shell.

💡 `echo $SHELL`

--- 

## Usage

From the Magento 2 project root folder:

`magevars` Creates a symlink of auth.json and copies .env.sample

`vp -i` Install Magento project in Valet+
