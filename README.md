# Vim-Related
Configuration for Vim

### Requirements
- Ubuntu 18.04 x64
- Vim >= 7.4, e.g. `vim-nox-py2`, the Vim which support python2
- [Vundle, the plug-in manager for Vim](https://github.com/VundleVim/Vundle.vim) or [vim-plug, Minimalist Vim Plugin Manager](https://github.com/junegunn/vim-plug#installation)
### How to use
Based on [Vundle, the plug-in manager for Vim](https://github.com/VundleVim/Vundle.vim#quick-start).

```
sudo apt install cmake python-dev  # for `YouCompleteMe`
sudo apt-get install exuberant-ctags  # for `TagBar`
# Install `Vundle` as [Quick Start](https://github.com/VundleVim/Vundle.vim#quick-start)
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
cp .vimrc.Vundle ~/.vimrc
vim +PluginInstall +qall
python ~/.vim/bundle/YouCompleteMe/install.py # for `YouCompleteMe`
```
Based on Plugin Manager [vim-plug, Minimalist Vim Plugin Manager](https://github.com/junegunn/vim-plug#installation) (Untested but prefer in the future), support On-demand loading for [faster startup time](https://github.com/junegunn/vim-startuptime-benchmark#result).
```
sudo apt install cmake python-dev  # for `YouCompleteMe`
sudo apt-get install exuberant-ctags  # for `TagBar`
# Install `vim-plug` as [installation](https://github.com/junegunn/vim-plug#installation)
curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
cp .vimrc.vimplug ~/.vimrc
vim +PluginInstall +qall
python ~/.vim/bundle/YouCompleteMe/install.py # for `YouCompleteMe`
```
Or [dein.vim, Dark powered Vim/Neovim plugin manager](https://github.com/Shougo/dein.vim)

