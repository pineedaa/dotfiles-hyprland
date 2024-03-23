# Pineedaa's dotfiles
## Screenshots
![desktop](assets/empty-desktop.png)
![desktop](assets/browser-files.png)
![desktop](assets/browser-terminal.png)
![desktop](assets/editor-terminal.png)


# Apps

- OS: [ArchLinux](https://archlinux.org/)
- WM: [Hyprland](https://hyprland.org/)
- Terminal: [Alacritty](https://alacritty.org/)
- File explorer: [Thunar](https://wiki.archlinux.org/title/Thunar)
- Menu: [Wofi](https://github.com/fuzzybritches0/wofi)
- Shell: [Zsh](https://www.zsh.org/)

The necessary packages for this environment can be installed with:
```
yay -S alacritty \n
bat \n
bc \n
blueman \n
bluez \n
brightnessctl \n
dunst \n
epapirus-icon-theme \n
eza \n
grim \n
hypridle \n
hyprland \n
hyprlock \n
hyprpaper \n
network-manager-applet \n
orchis-theme \n
slurp \n
waybar \n
wl-clipboard \n
wlsunset \n
wofi
```

# Theme

The theme I chose is [orchis-dark-compact](https://aur.archlinux.org/packages/orchis-theme) and it can be installed with [yay](https://aur.archlinux.org/packages/yay):

`$ yay -S orchis-theme`

And the icon pack is [papirus]() that can be installed with pacman:
`$ pacman -S epapirus-icon-theme`

The theme and icon pack can be applied with the [nwg-look](https://archlinux.org/packages/extra/x86_64/nwg-look/) package.


# Install

You can clone this dotfiles where you prefere and inside the folder you can simply execute `stow .`.
You can install the [stow](https://www.gnu.org/software/stow/manual/stow.html) package with pacman.
