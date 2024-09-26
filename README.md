## Install Essentials
```
sudo apt install i3 neofetch rxvt-unicode rofi feh nala ranger gcc unzip git make
```

## Install Bumblebee
```
cd ~/.config/i3
git clone git://github.com/tobi-wan-kenobi/bumblebee-status
```

## Install NerdFonts Agave
```
curl -L -O https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/Agave.zip
sudo unzip Agave.zip -d /usr/share/fonts/truetype/Agave
fc-cache
```

## Install Neovim
The last line contains my own repo in it which you can copy, but I reccomend you setup your own config on [Kickstart Neovim](https://github.com/nvim-lua/kickstart.nvim).

```
mkdir ~/.config/nvim
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux64.tar.gz
sudo rm -rf /opt/nvim
sudo tar -C /opt -xzf nvim-linux64.tar.gz
git clone https://github.com/ratatuli3/kickstart.nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```
