# Kitchenplan Configuration

This is a Kitchenplan configuration repository. This repository contains all configuration to install and configure our OSX workstations. More information about Kitchenplan and on how to use it can be found in the [Kitchenplan README](https://github.com/kitchenplan/kitchenplan).


# Profile

create ~/.bash_profile

    # git
    GIT_AUTHOR_NAME="Mathieu Ledru"
    GIT_COMMITTER_NAME="$GIT_AUTHOR_NAME"
    git config --global user.name "$GIT_AUTHOR_NAME"
    GIT_AUTHOR_EMAIL="matyo91@gmail.com"
    GIT_COMMITTER_EMAIL="$GIT_AUTHOR_EMAIL"
    git config --global user.email "$GIT_AUTHOR_EMAIL"
    GIT_MERGE_AUTOEDIT=no
    
    alias gs='git status'
    alias gd='git diff'
    alias gc='git commit -a -m'
    alias gpull='git pull'
    alias gpush='git push'
    alias gup='git up'
    
    # vagrant
    alias vu='vagrant up'
    alias vs='vagrant ssh'
