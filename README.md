# puppet-vim

## Introduction :
puppet-vim is a vimrc configuration and a plugins collection to make the perfect IDE for puppet workers, this work was done to allow the devops to save time to develop puppet modules and ruby code

#### Prérequisites : 
 * Rubygems / puppet-lint for syntastic plugin
 * Python3 for deoplete and neovim plugin

## Installation : 
```
cd ~
git clone https://github.com/meries/puppet-vim
cd puppet-vim
cp -r .vim* ~/.
cd -
rm -rf puppet-vim
```

## vimrc config
![vimrc](https://cloud.githubusercontent.com/assets/26363773/26524382/4a77f1e4-4331-11e7-85e3-acd0c60090a2.png)
---

## Syntax checking
![syntastic](https://cloud.githubusercontent.com/assets/26363773/26524403/d895c866-4331-11e7-828d-a2e89ca43c02.png)
 ## Autocompletion
![autocompletion](https://cloud.githubusercontent.com/assets/26363773/26524416/029e2950-4332-11e7-87d9-e137248c8ae8.png)
---

## Snippets is awesome
**just write the name of puppet ressource + keyboard touch tab and this is magic ;)**
![animated](https://cloud.githubusercontent.com/assets/26363773/26524418/0565a708-4332-11e7-8c6e-ba5b7fbfeda3.gif)


---
Plugins List : 
---
- vundle : it's a plugins manager for vim (check .vimrc config) https://github.com/VundleVim/Vundle.vim.git
- deoplete : this plugin work with neovim in order to add vim autocompletion https://github.com/Shougo/deoplete.nvim
- nerdtree : vim file explorer see wiki for more informations https://github.com/scrooloose/nerdtree
- powerline : statusline plugin for vim https://github.com/powerline/powerline
- vim-puppet : puppet syntax highlight for vim https://github.com/rodjek/vim-puppet
- syntastic : it's a syntax checking plugin for vim https://github.com/vim-syntastic/syntastic
- vim-airline : status/tabline for vim that's light as air. https://github.com/vim-airline/vim-airline
- vim-airline-themes : themes for vim-airline https://github.com/vim-airline/vim-airline-themes
- vim-snipmate / vim-snippets : snip to provide support for textual snippets, similar to textmate or other vim plugins like ultisnips. https://github.com/honza/vim-snippets
 
