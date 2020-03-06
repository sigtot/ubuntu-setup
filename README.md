# Ubuntu setup guide v0.1

## Install dotfiles


## Add bin scripts
Clone the scripts in [binscripts](https://github.com/sigtot/binscripts) into `$HOME/bin`

## Install the apt deps in `apt-deps.sh`
```bash
sh apt-deps.sh
```

## Setup dwm and st
1) Clone [dwm](https://github.com/sigtot/my-dwm) and [st](https://github.com/sigtot/my-st) repos into e.g. `/usr/local/src/`
2) Change their permissions to the home user
3) In both directories, run
```bash
sudo make clean install
```
4) Copy dwm.desktop file into /usr/share/xsessions
5) Verify dotfiles installation correctly put a .xinitrc symlink into $HOME
6) Relog and dwm/st should work!


