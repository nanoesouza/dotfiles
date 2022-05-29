# dotfiles
# Dependencies

```
sudo pacman -S --needed --noconfirm kitty rofi feh redshift playerctl pulsemixer dunst \
  flameshot polkit-gnome brightnessctl numlockx xorg-{setxkbmap,xset,xsetroot} \
  nodejs-material-design-icons ttf-jetbrains-mono ttf-fira-{code,mono,sans} wget bat btop \
  bspwm sxhkd polybar ranger papirus-icon-theme cmatrix neofetch typespeed libpulse xclip yt-dlp lsd
 ```
 ```
yay -S --needed --noconfirm i3lock-color-git zscroll-git picom-jonaburg-git nerd-fonts-{jetbrains-mono,fira-code} \
  xcursor-breeze pipes.sh rxfetch pfetch thokr-git ipman spotify
```
> /usr/share/xsessions/bspwm.desktop
```
[Desktop Entry]
Name=bspwm
Comment=Binary space partitioning window manager
Exec=/home/adriano/.login.sh
Type=Application
```
