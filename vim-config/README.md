# Vim Configuration File

This is my init.vim (now using nvim) file for general use.

Things to remember when using it:
* If using **vim**: rename it to **.vimrc** and place it in the **home directory (~)** 
* If you're using **neovim**: rename it to **init.vim** and place it at:
    ```
    $ ~/.config/nvim/
    ``` 
* Create a directory called undodir at
    ```
    $ ~/.vim/undodir
    ``` 
* It uses [vim plug](https://github.com/junegunn/vim-plug) as the plugin manager
* After setting up the file, run ***:PluginInstall*** at vim command mode
* Some programs are needed:
    ```
    sudo apt install ripgrep fzf nodejs zsh
    ```
* Also install [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh)


.vimrc was inspired on [ThePrimeagen YouTube video](https://www.youtube.com/watch?v=n9k9scbTuvQ)

Also check [this video](https://www.youtube.com/watch?v=q7gr6s8skt0) on Search and Replace using :CocSearch and macros to change several lines in different files!

### Some plugins info

Check the plugins installed and check their **documentation** to setup properly.

For instance, with **CoC** it is possible to install **several extensions** to help coding. vim-dispatch also has features to be explored. ***Read the documentation!***

## Python

Some of the configurations are based on [fisadev vim config](https://github.com/fisadev/fisa-vim-config), check it!

Also, **:CocInstall coc-python** helps you with autocompletion in python. You may also need to install:
```
pip install jedi black pylint
```
**:CocConfig** opens the configuration.json file for CoC, it is also included in this repository.
