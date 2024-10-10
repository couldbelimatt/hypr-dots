# My edit of 1amSimp1e's Dot Files 📁


### Highly recomended to use with CachyOS!!

## [Late Night🌃]()

![](https://fuji.s-ul.eu/KDu0u966)
![](https://fuji.s-ul.eu/e8oXLpoo)

## Credits

[1amSimp1e](https://github.com/1amSimp1e/dots)\
[LierB's FastFetch Config](https://github.com/LierB/fastfetch) \
[CachyOS](https://cachyos.org)

## Hyprland Installation

> Just [R.T.F.M](https://en.wikipedia.org/wiki/RTFM)

- First of all, Install the newest [Hyprland](https://hyprland.org/) or use CachyOS's  version in the installer. \
This worked best for me, as I'm on Nvidia.

 ```
  yay -S hyprland-git
 ```

- Then, follow the [Official Installation Guide](https://wiki.hyprland.org/Getting-Started/Installation/) to make sure you know what you're doing.

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

Once you download them and unpack them, place them into `~/.fonts` or `~/.local/share/fonts.`

Then run this command for your system to detect the newly installed fonts.

```
fc-cache -fv
```

## Copy Files 

```
git clone https://github.com/couldbelimatt/hypr-dots.git
cd dots
cp -r ./configs/* ~/.config/
```


