# Setup & Tweaks

## Git
```
git config --global push.default simple
git config --global user.email mike@thesandmans.com
git config --global user.name n8behavior
git config --global gpg.program gpg2
git config --global user.signingkey $(gpg --list-secret-keys --keyid-format LONG)
git config --global commit.gpgsign true
git config --global core.excludesfile '~/.cvsignore'
git config --global alias.root "rev-parse --show-toplevel"
```

Add to `.bashrc`
```
alias cdroot='cd $(git root)'
```

## VIM
```sh
# Make vim the default editor
sudo update-alternatives --config editor

# Pathogen
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim

# vim-sensible
cd ~/.vim/bundle && git clone https://github.com/tpope/vim-sensible
# ctrl-p
cd ~/.vim/bundle && git clone https://github.com/ctrlpvim/ctrlp.vim
# markdown tables
cd ~/.vim/bundle && git clone https://github.com/dhruvasagar/vim-table-mode
# markdown preview
cd ~/.vim/bundle && git clone https://github.com/suan/vim-instant-markdown
```
Consider Limelight and Goyo, if added use...
```vimscript
autocmd FileType markdown Limelight
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

" This is only necessary if you use "set termguicolors".
let &t_8f = "\<Esc>[38;2;%lu;%lu;%lum"
let &t_8b = "\<Esc>[48;2;%lu;%lu;%lum"
set termguicolors
colorscheme slate
set background=dark
autocmd BufNewFile,BufRead *.md set filetype=markdown
```

## Desktop
- Auto-hide the laucher
- Disable mouse tap to click

## Keyboard

```sh
# Map CapsLock to Control
sudo sed -i 's/XKBOPTIONS=""/XKBOPTIONS="ctrl:nocaps"/' /etc/default/keyboard

# Ctrl+ARROW move to workspace
gsettings set  org.gnome.desktop.wm.keybindings switch-to-workspace-up "['<Control>Up']"
gsettings set  org.gnome.desktop.wm.keybindings switch-to-workspace-down "['<Control>Down']"

# Shift+Ctrl+ARROW move window to workspace
gsettings set  org.gnome.desktop.wm.keybindings move-to-workspace-up "['<Control><shift>Up']"
gsettings set  org.gnome.desktop.wm.keybindings move-to-workspace-down "['<Control><shift>Down']"
```

## Packages

This list is for convenience only.  Use `show-my-packages` to get the current list on target machine

```
vim-nox build-essential gnupg2 curl tmux git chromium-browser openssh-server silversearcher-ag etckeeper python3-pip fontconfig python-is-python3
```

## Compilers

Add latest GNU compiler collection
```
sudo apt install g++-10 -y
```
Finally, create **link group** and set auto/current
```
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-10 100 \
  --slave /usr/bin/gcc-ar gcc-ar /usr/bin/gcc-ar-10 \
  --slave /usr/bin/gcc-nm gcc-nm /usr/bin/gcc-nm-10 \
  --slave /usr/bin/gcc-ranlib gcc-ranlib /usr/bin/gcc-ranlib-10 \
  --slave /usr/bin/g++ g++ /usr/bin/g++-10
```
All them for copy/paste convenience :)
```
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-10 100 --slave /usr/bin/gcc-ar gcc-ar /usr/bin/gcc-ar-10 --slave /usr/bin/gcc-nm gcc-nm /usr/bin/gcc-nm-10 --slave /usr/bin/gcc-ranlib gcc-ranlib /usr/bin/gcc-ranlib-10 --slave /usr/bin/g++ g++ /usr/bin/g++-10
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-9 90 --slave /usr/bin/gcc-ar gcc-ar /usr/bin/gcc-ar-9 --slave /usr/bin/gcc-nm gcc-nm /usr/bin/gcc-nm-9 --slave /usr/bin/gcc-ranlib gcc-ranlib /usr/bin/gcc-ranlib-9 --slave /usr/bin/g++ g++ /usr/bin/g++-9
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-8 80 --slave /usr/bin/gcc-ar gcc-ar /usr/bin/gcc-ar-8 --slave /usr/bin/gcc-nm gcc-nm /usr/bin/gcc-nm-8 --slave /usr/bin/gcc-ranlib gcc-ranlib /usr/bin/gcc-ranlib-8 --slave /usr/bin/g++ g++ /usr/bin/g++-8
```

## GPG
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
gpg2 --armor --export $(gpg --list-secret-keys --keyid-format LONG)
```
Finally, setup BASH
```
echo 'export GPG_TTY=$(tty)' >> ~/.bashrc
```
## Powerline

```
pip3 install --user powerline-status
wget https://github.com/powerline/powerline/raw/develop/font/PowerlineSymbols.otf
wget https://github.com/powerline/powerline/raw/develop/font/10-powerline-symbols.conf
mkdir -p ~/.local/share/fonts ~/.config/fontconfig/conf.d/
mv PowerlineSymbols.otf ~/.local/share/fonts/
mv 10-powerline-symbols.conf ~/.config/fontconfig/conf.d/
sudo fc-cache -vf ~/.local/share/fonts/
```
Add 
- `source "$(python -m site --user-site)/powerline/bindings/tmux/powerline.conf"` to `.tmux.conf`
- `source "$(python -m site --user-site)/powerline/bindings/bash/powerline.sh"` to `.bashrc`

In `.vimrc` add
```
set rtp+=${$(python -m site --user-site)}/powerline/bindings/vim
set noshowmode
```
