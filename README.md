# Main
My settings for nvim
# Install
```bash
sudo apt install neovim
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
mv init.vim ~/.config/nvim/init.vim
nvim
:PlugInstall
```
