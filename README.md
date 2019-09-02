Setup & Tweaks
==============

etckeeper
---------

enable `etckeeper` ASAP

Dotfiles
--------
```
git config --global push.default simple
git config --global user.email mike@thesandmans.com
git config --global user.name n8behavior
git config --global gpg.program gpg2
git config --global user.signingkey 73ABC7FDECC41AF4
git config --global commit.gpgsign true
```
- force_color_prompt
- touch up prompt

VIM
---
Make it the default editor
```
sudo update-alternatives --config editor
```

Pathogen
```
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```

vim-sensible
```
cd ~/.vim/bundle && git clone https://github.com/tpope/vim-sensible
```

ctrl-p
```
cd ~/.vim/bundle && git clone https://github.com/ctrlpvim/ctrlp.vim
```
table-mode
```
cd ~/.vim/bundle && git clone https://github.com/dhruvasagar/vim-table-mode
```

.vimrc
```
execute pathogen#infect()
syntax on
filetype plugin indent on
set number

set softtabstop=4 shiftwidth=4 expandtab
autocmd FileType make set noexpandtab shiftwidth=8 softtabstop=0

" markdown style tables
let g:table_mode_corner_corner="|"
let g:table_mode_header_fillchar="-"

let g:ctrlp_user_command = 'ag %s -l --nocolor -g ""'
let g:ctrlp_working_path_mode = 'ra'

set listchars=tab:→\ ,space:·,nbsp:␣,trail:•,eol:¶,precedes:«,extends:»

set rtp+=/usr/local/lib/python2.7/dist-packages/powerline/bindings/vim
set noshowmode
```

Desktop
-------
- Auto-hide the laucher
- Enable workspaces
- Natural scrolling
- Disable mouse tap to click

Keyboard
--------

Map CapsLock to Control
```
sudo sed -i 's/XKBOPTIONS=""/XKBOPTIONS="ctrl:nocaps"/' /etc/default/keyboard
```

Ctrl+ARROW move to workspace
```
gsettings set  org.gnome.desktop.wm.keybindings switch-to-workspace-right "['<Control>Right']"
gsettings set  org.gnome.desktop.wm.keybindings switch-to-workspace-left "['<Control>Left']"
gsettings set  org.gnome.desktop.wm.keybindings switch-to-workspace-up "['<Control>Up']"
gsettings set  org.gnome.desktop.wm.keybindings switch-to-workspace-down "['<Control>Down']"
```

Shift+Ctrl+ARROW move window to workspace
```
gsettings set  org.gnome.desktop.wm.keybindings move-to-workspace-right "['<Control><shift>Right']"
gsettings set  org.gnome.desktop.wm.keybindings move-to-workspace-left "['<Control><shift>Left']"
gsettings set  org.gnome.desktop.wm.keybindings move-to-workspace-up "['<Control><shift>Up']"
gsettings set  org.gnome.desktop.wm.keybindings move-to-workspace-down "['<Control><shift>Down']"
```

Yubikey
-------

- https://raw.githubusercontent.com/Yubico/libu2f-host/master/70-u2f.rules
  - _obsolete in 16.10_

Devices
-------
- Pair phone
- Hotspot
- chromecast chrome extension

Packages
-----------------

This list is for convenience only.  Use `show-my-packages` to get the current list on target machine

```
vim-nox build-essential gnupg2 curl tmux autoconf automake git chromium-browser openssh-server silversearcher-ag etckeeper python3-pip
```

nvidia
------
**_obsolete: as of 19.04_**
_note: May have to first-boot with `nomodeset` from grub2 menu_

```
sudo add-apt-repository ppa:graphics-drivers/ppa
```
Then install latest, for example
```
sudo apt install nvidia-390
```

Compiler
--------

Add latest GNU compiler collection
```
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
```
Then add latest, for example
```
sudo apt install g++-8 -y
```
Finally, create **like group** and set auto/current
```
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-9 80 \
  --slave /usr/bin/gcc-ar gcc-ar /usr/bin/gcc-ar-9 \
  --slave /usr/bin/gcc-nm gcc-nm /usr/bin/gcc-nm-9 \
  --slave /usr/bin/gcc-ranlib gcc-ranlib /usr/bin/gcc-ranlib-9 \
  --slave /usr/bin/g++ g++ /usr/bin/g++-9
```

GPG
---
Restore from
- `.gnupg/dirmngr.conf`
- `.gnupg/gpg.conf`
- `.gnupg/pubring.kbx`
or make new
```
gpg2 --full-gen-key
```
If, new reconfig `git` with new key
```
gpg2 --list-secret-keys --keyid-format LONG
```
and https://github.com/settings/keys
```
gpg2 --armor --export 73A....
```
Finally, setup BASH
```
echo 'export GPG_TTY=$(tty)' >> ~/.bashrc
```
Powerline
---------

```
sudo pip install powerline-status
wget https://github.com/powerline/powerline/raw/develop/font/PowerlineSymbols.otf
wget https://github.com/powerline/powerline/raw/develop/font/10-powerline-symbols.conf
mkdir -p ~/.local/share/fonts ~/.config/fontconfig/conf.d/
mv PowerlineSymbols.otf ~/.local/share/fonts/
mv 10-powerline-symbols.conf ~/.config/fontconfig/conf.d/
sudo fc-cache -vf ~/.local/share/fonts/
```
Add 
- `source "/usr/local/lib/python2.7/dist-packages/powerline/bindings/tmux/powerline.conf"` to `.tmux.conf`
- `source "/usr/local/lib/python2.7/dist-packages/powerline/bindings/bash/powerline.sh"` to `.bashrc`

In `.vimrc` add
```
set rtp+=/usr/local/lib/python2.7/dist-packages/powerline/bindings/vim
set noshowmode
```
