# Valet+ Magento Project

## Getting started

### 1.- Clone valet-install

`git clone git@github.com:PMET-public/valet-install.git ~/.vi`

### Set your auth.json credentials

1. `cd ~/.vi`
2. `cp auth.json.sample auth.json`

### PATH that Bash up!

Add `export PATH=$PATH:$HOME/.vi/bin` to .bash_profile (for bash) or .zshrc (for zsh) depending on your shell (echo $SHELL)

--- 

## Usage

From the Magento 2 project root folder:

`magevars` Creates symlinks of auth.json and copies .env.sample

`vp -i` Install Magento project in Valet+
