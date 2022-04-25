# Setup-walkthrough
This my walkthrough to set up a developer machine
***

# Inital Setup
Do these things first

## 1. [Homebrew](https://brew.sh/)

> `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
`

## 2. iterm2

> `brew install --cask iterm2`

> [**terminal setup --optional**](https://chamikakasun.medium.com/iterm2-zsh-oh-my-zsh-the-most-power-full-terminal-on-macos-2021-guide-macos-big-sur-5bb498976dc9)


## 3. VScode

> `brew install --cask visual-studio-code`

## 4. lando

>[Download lando here](https://lando.dev/)

## 5. Git set up

> [follow this guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

**Summary for ssh**

> `$ ssh-keygen -t ed25519 -C "your_email@example.com"`
> `cd ~/.ssh`
> `cat id_***.pub`

**Summary for config**
> `git config --global user.name "FIRST_NAME LAST_NAME"`
> `git config --global user.email "MY_NAME@example.com"`


## 6. Node

> `brew install brew install node@16`
