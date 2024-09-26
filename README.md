*Install Essentials*
```
sudo apt install i3 neofetch rxvt-unicode rofi feh nala ranger gcc unzip git make
```

*Install Bumblebee*
```
cd ~/.config/i3
git clone git://github.com/tobi-wan-kenobi/bumblebee-status
```

*Install Neovim*
```
mkdir ~/.config/nvim
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux64.tar.gz
sudo rm -rf /opt/nvim
sudo tar -C /opt -xzf nvim-linux64.tar.gz
```

*Install NerdFonts Agave*
```
curl -L -O https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/Agave.zip
sudo unzip Agave.zip -d /usr/share/fonts/truetype/Agave
```
