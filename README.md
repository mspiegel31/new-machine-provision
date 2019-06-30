# Machine provisioning

# Prereqs
1. use python 3.x
1. install pipenv
1. `pipenv install`
1. `pipenv shell`
1. install [bitwarden cli](https://github.com/bitwarden/cli)

### notes:
1. use inventories to separate dev vs server machines

### Todo:
Goals:
1. automatically generate ssh keys and add to github _securely_
    - look at the ansible vault


1. install base
    - dotfile repo
    - system libs/tools
        - docker
        - ~zsh~
        - oh-my-zsh
        - ~tree~
        - ~stow~
        - bat
        - nvm
        - jenv
        - ~htop~

1. server
    - os: ubuntu
1. dev machine
    - os: arch?


1. install personal desktop env
    - manjaro/arch
    - intellij
    - code-insiders
        - extensions for code-insiders
    - imwheel
        - needs autostart
    - steam
    - conky
    - google-music
    - pamac/yay?

## Reference
1. [ansible best practices](https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html#content-organization)