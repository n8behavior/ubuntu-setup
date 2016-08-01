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

```
vim-nox
build-essential
tmux
autoconf
automake
git
git-hub
git-extras
google-chrome
```
