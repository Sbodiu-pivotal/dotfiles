# [Sergiu](https://github.com/sbodiu-pivotal)’s dotfiles

These are the base dotfiles that I start with when I set up a
new environment.

## Setup

TBD

Create local export configuration: .exports.local

    export DOTFILES_DIR_PATH='$HOME/.dotfiles'
    export OS='osx'
    # Important for omzsh theme
    export DEFAULT_USER='add name'

Create local git configuration: .gitconfig.local

    [user]
        name = 'add name'
        email = 'add name@email'
    [credential]
        helper = osxkeychain

Added __Oh My Zsh is a way of life!__

    git submodule add git://github.com/robbyrussell/oh-my-zsh.git
