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
- group system to have groups ready to bulk install or manage
- snapshot system for backups of all explicitly installed packages
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
## notes
this is 900+ lines of bash and expanding, and it still works (as far as i know)
no, i cant tell you why i made this in bash of all things
refrain from looking too closely
### stability notice
version 3.0.0-5 is feature complete and mostly stable, unless upstream changes force updates (same with reproducible bugs not found yet), this version is considered mostly frozen, contributions or patches welcome, but sanity is not guaranteed
