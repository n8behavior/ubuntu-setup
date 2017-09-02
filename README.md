Setup & Tweaks
==============

etckeeper
---------

enable `etckeeper` ASAP

Dotfiles
--------
```
cd $HOME && git init
git config --global user.email mike@thesandmans.com
git config --global user.name n8behavior
```
- force_color_prompt
- touch up prompt

Docker Machine (old)
```
# Docker stuff
export MACHINE_STORAGE_PATH=/media/raid10/docker
MACHINE_BASH_SCRIPTS=$PWD/Source/github.com/docker/machine/contrib/completion/bash/
source $MACHINE_BASH_SCRIPTS/docker-machine.bash
source $MACHINE_BASH_SCRIPTS/docker-machine-wrapper.bash
source $MACHINE_BASH_SCRIPTS/docker-machine-prompt.bash
```

VIM
---
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

.vimrc
```
execute pathogen#infect()
syntax on
filetype plugin indent on

set softtabstop=4 shiftwidth=4 expandtab
autocmd FileType make set noexpandtab shiftwidth=8 softtabstop=0

" reStructuredText style tables
let g:table_mode_corner_corner="+"
let g:table_mode_header_fillchar="="

let g:ctrlp_user_command = 'ag %s -l --nocolor -g ""'
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
- `sed -i 's/XKBOPTIONS=""/XKBOPTIONS="ctrl:nocaps"/' /etc/default/keyboard`
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
vim-nox build-essential curl tmux autoconf automake git chromium-browser openssh-server silversearcher-ag etckeeper mdadm
```
RAID10
------

```
$ sudo mdadm --assemble --name=raid10 --scan
```
add `UUID=4d9301ce-c41f-4c0c-9786-44658908551d /media/raid10 ext4 	defaults 1 2` to `/etc/fstab`
