# My Dotfiles 📁

Rose-pine themed Hyprland rice :)

![](https://limatt.s-ul.eu/aRj18NCR)
![](https://limatt.s-ul.eu/8Fvyoavp)

### Credits

[1amSimp1e](https://github.com/1amSimp1e/dots)\
[LierB's FastFetch Config](https://github.com/LierB/fastfetch) \
[CachyOS](https://cachyos.org)

# Tutorial


> Just [R.T.F.M](https://en.wikipedia.org/wiki/RTFM)

- Install the newest [Hyprland](https://hyprland.org/)

 ```
  yay -S hyprland-git
 ```

## Install Dependencies

```
paru -S waybar rofi dunst kitty swaybg swaylock-fancy-git pulsemixer light brillo fish zen-bin nemo lxappearance
```

- Optional stuff (to replicate my exact setup (CACHYOS ONLY))
```
paru -S ocs-url goxlr-utility vesktop gdm && sudo pacman -S cachyos-gaming-meta
```

### Fonts:

  ```
  paru -S ttf-font-awesome nerd-fonts-git
  ```

Then run this command to detect the newly installed fonts.

```
fc-cache -fv
```

## Clone & move files 

```
git clone https://github.com/couldbelimatt/hypr-dots.git
cd dots
cp -r ./configs/* ~/.config/
```


