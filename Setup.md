# Set up things
## Inital things

# 1. [Homebrew](https://brew.sh/)

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
`

# 2. iterm2

`brew install --cask iterm2`

[**terminal setup --optional**](https://chamikakasun.medium.com/iterm2-zsh-oh-my-zsh-the-most-power-full-terminal-on-macos-2021-guide-macos-big-sur-5bb498976dc9)


# 3. VScode

`brew install --cask visual-studio-code`

# 4. lando

[Download lando here](https://lando.dev/)

# 5. Git set up

[follow this guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

**Summary for ssh**

> $ ssh-keygen -t ed25519 -C "your_email@example.com"
> cd ~/.ssh
> cat id_***.pub

**Summary for config**
> git config --global user.name "FIRST_NAME LAST_NAME"
> git config --global user.email "MY_NAME@example.com"

***

## Extra things

### 1. rectangle

`brew install --cask rectangle`

### 2. jetbrains things

[Download Jetbrains here](https://www.jetbrains.com/toolbox-app/)

### 3. alfred

`brew install --cask alfred`

### 4. numi

`brew install --cask numi`

### 5. notion

`brew install --cask notion`

### 6. spotify

`brew install --cask spotify`


***
# Post install - setting up folders

> cd ~
> mkdir dev && cd dev
> mkdir _working && mkdir archive && mkdir testing

## Explaination

### _working

_working is where all the current projects go. The underscore keeps the folder at the top of the list and first to be accessed when tabbed.

### archive

All inactive projects go here

### testing

A place to pull random projects or create test projects

### Further

A `side` folder could be added for side projects but thats just for nerds