# Fonts

https://github.com/FortAwesome/Font-Awesome/releases/tag/v4.7.0

https://medium.com/source-words/how-to-manually-install-update-and-uninstall-fonts-on-linux-a8d09a3853b0

sudo pacman -S powerline-fonts

sudo pacman -S ttf-font-awesome (5 version)

sudo apt-get install -y fonts-font-awesome

# i3

https://github.com/tobi-wan-kenobi/bumblebee-status

# Interesting repos

https://gitlab.com/dwt1

# Useful commands

xrandr -q | grep ' connected' | head -n 1 | cut -d ' ' -f1 | xargs -I {} xrandr --output {} --brightness 0.7

fortune | cowsay -f $(ls /usr/share/cowsay/cows | shuf -n 1) | lolcat

curl cheat.sh/pacman

# Useful programs

slim (lightweight login manager)

rofi -show run (run command)

conky (system widget)

ranger, mc (file managers)

neofetch, pfetch (distro info)

exa, lsd (better ls)

most (like less)

shopt -s autocd (turn on auto chande directory)

fish (console)

powerline-shell (nice PS1 for bash)

nitrogen, feh (wallpapers)

tmux (console splitter)

neomutt (email client)

vscodium (free vscode) 

tilix (terminal)

compton (transparency)

xfce4-panel, tint2 (panels)
