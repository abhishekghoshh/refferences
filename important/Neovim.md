

### Install neovim with lua-jit
```
sudo apt update && sudo apt upgrade -y
sudo apt install ninja-build gettext libtool libtool-bin autoconf automake cmake g++ pkg-config unzip curl
git clone https://github.com/neovim/neovim.git
cd neovim && git checkout stable
make CMAKE_BUILD_TYPE=Release
sudo make install
echo 'export PATH="$PATH:/path/to/neovim"' >> ~/.zshrc
source ~/.zshrc
```
## Neovim chad
- [Turn VIM into a full featured IDE with only one command](https://www.youtube.com/watch?v=Mtgo-nP_r8Y)
- [Official documentation](https://nvchad.com/docs/quickstart/install)
- [nvchad github](https://github.com/NvChad/NvChad)
- configs present in (~/.config/nvim/lua/custom)
- Shortcuts
	- space + c + h for cheetsheet opening and closing
	- Space -> t -> h (setting themes) [option + control + p/n ]
	- Syntax highlighting [TSInstall #laungage_name] [TSInstallInfo]
	- File explorer [cntrl + n] 
		- m for bookmarking
		- a for adding new file
		- c for copy and p for paste
		- file navigation space + f + f
		- space + f + b for find only opened files
	- Window navigation [ ctrl + h / j / k / l ]
	- Window management [vertical split (:vsp)  split (:sp)] 
	- Tab change (tab) (shift + tab) and close tab ( space + x )
	- Toggle line number [ space + n ]
	- Command line 
		- Horizontal ( space + h )
		- vertical ( space + v )

### Neovim quick start
- [Effective Neovim: Instant IDE](https://www.youtube.com/watch?v=stqUbv-5u2s)
- [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim)
#### Neovim tutorial
- [Effective Neovim: Instant IDE](https://www.youtube.com/watch?v=stqUbv-5u2s)
- [Neovim from Scratch](https://www.youtube.com/playlist?list=PLhoH5vyxr6Qq41NFL4GvhFp-WLd5xzIzZ)
- [0 to LSP : Neovim RC From Scratch](https://www.youtube.com/watch?v=w7i4amO_zaE)
- [Neovim Configuration](https://www.youtube.com/playlist?list=PLsz00TDipIffxsNXSkskknolKShdbcALR)

#### Custom neovim setup
- [The perfect Neovim setup for Go](https://www.youtube.com/watch?v=i04sSQjd-qo)


#### Tmux configuration
- [Tmux has forever changed the way I write code.](https://www.youtube.com/watch?v=DzNmUNvnB04)
- [I made the greatest tool ever! | tmux & cht.sh & fzf](https://www.youtube.com/watch?v=hJzqEAf2U4I)
