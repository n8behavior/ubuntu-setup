Setup & Tweaks
==============

Dotfiles
--------
- cd $HOME && git init
- touch up prompt with docker-machine expansion
- force_color_prompt
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
- Pathogen
- ctrl-p
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

- `sed -i 's/XKBOPTIONS=""/XKBOPTIONS="ctrl:nocaps"/' /etc/default/keyboard`
- Ctrl+ARROW move to workspace
- Shift+Ctrl+ARROW move window to workspace

Yubikey
-------
- https://raw.githubusercontent.com/Yubico/libu2f-host/master/70-u2f.rules

Devices
-------
- Pair phone
- Hotspot
- chromecast chrome extension

Packages
-----------------

This list is for convenience only.  Use `show-my-packages` to get the current list on target machine

```
vim-nox
build-essential
tmux
autoconf
automake
git
google-chrome
openssh-server
silversearcher-ag
etckeeper
mdadm
```
RAID10
------

```
$ sudo mdadm --assemble --name=raid10 --scan
```
add `UUID=4d9301ce-c41f-4c0c-9786-44658908551d /media/raid10 ext4 	defaults 1 2` to `/etc/fstab`
