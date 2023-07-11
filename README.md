# NeovimConfig

### install neovim
sudo apt-get install neovim

### install vim-plug
Unix Linux:
```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

Windows:
```
iwr -useb https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim |`
    ni "$(@($env:XDG_DATA_HOME, $env:LOCALAPPDATA)[$null -eq $env:XDG_DATA_HOME])/nvim-data/site/autoload/plug.vim" -Force
```

### Install dependencies
```
pip install pynvim \
sudo apt-get install ruby-full \
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash \
nvm install node
npm install -g neovim
gem install neovim
```

### Install Font
```
wget https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/FiraCode.zip ~/
unzip -d ~/.fonts ~/FiraCode.zip -u
fc-cache -f -v
```


