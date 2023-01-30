## Install termux from F-droid.org

#### Commands

```
termux-setup-storage
pkg update && pkg upgrade -y
exit
```

#### Other dependencies are installed
```
pkg install openssl-tool -y
pkg install git curl -y 
```

#### Change shell, Instal zsh

```
pkg install zsh
chsh -s zsh
exit 
```


####  Instal Oh My Zsh

Ohmyz from https://ohmyz.sh/#install

Configure zsh with nano or nvim

```
nano .zshrc 
nvim .zshrc
```


#### Inatall Neo vim

```
pkg install neovim -y
```

Configure neovim

Use package managers, `lazy.nvim` recommended
