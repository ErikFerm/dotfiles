# dotfiles
Use make to setup the different parts properly. The setupscripts in each folder depends on the script being executed from the base directory. If you try to run the scripts independently they might not work properly.

## make
make help will print all the available rules.
```zsh
$ make help
golang                         Will install go
neovim                         Will install & setup neovim
zshell                         Will install & setup zsh
help                           Display this help message
```

## Ubuntu
For this setup to work on ubuntu you need git and make. Before using make run:
```zsh
sudo apt-get update
sudo apt-get install build-essential git
```
