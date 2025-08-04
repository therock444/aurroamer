# aurroamer

aurroamer is a terminal-based browser for AUR and official arch repo packages                                                                  

## features

- browse both AUR and official packages
- interactive menu powered by `fzf`
- AUR helper integration, yay, paru, etc. 
- multi-select with bulk install
- favorites system
- optional post-install hooks
- ignored system

## requirements

- `bash`
- `pacman`
- `fzf`
- an AUR helper (`yay`, `paru`, etc.) for AUR support

## installation
you can either use your favorite aur helper, e.g. yay:
```bash
yay -S aurroamer
```
or clone and install it manually
```bash
git clone https://aur.archlinux.org/aurroamer.git
cd aurroamer
makepkg -si
```
## usage
for basic usage instructions, run 
```bash
aurroamer --help
```
