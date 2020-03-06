# Ubuntu setup guide v0.1

# Install the apt deps in `apt-deps.sh`
```bash
sh apt-deps.sh
```

# Setup dwm and st
1) Clone dwm and st repos into e.g. `/usr/local/src/`
2) Change their permissions to the home user
3) In both directories, run
```bash
sudo make clean install
```
4) Copy dwm.desktop file into /usr/share/xsessions
5) Verify dotfiles installation correctly put a .xinitrc symlink into $HOME
6) Relog and dwm/st should work!


