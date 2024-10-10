<div align="center">
    <h3> My edit of 1amSimp1e's Dot Files 📁</h3>
</a>

### Highly recomended to use with CachyOS!!

## [Late Night🌃]()

![](https://fuji.s-ul.eu/KDu0u966)
![](https://fuji.s-ul.eu/e8oXLpoo)

## Credits

[1amSimp1e](https://github.com/1amSimp1e/dots)\
[LierB's FastFetch Config](https://github.com/LierB/fastfetch)
[CachyOS](https://cachyos.org)

## Dependencies

> Just [R.T.F.M](https://en.wikipedia.org/wiki/RTFM)

- First of all, Install the newest [Hyprland](https://hyprland.org/) or use CachyOS's  version in the installer. \
This worked best for me, as I'm on Nvidia.

  ```zsh
  yay -S hyprland-git
  ```


- Install waybar, Rofi, Dunst, kitty terminal, swaybg, swaylock-fancy, pulsemixer, light, Brillo:

```
paru -S waybar rofi dunst kitty swaybg swaylock-fancy-git pulsemixer light brillo
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
git clone -b late-night-🌃 https://github.com/iamverysimp1e/dots
cd dots
cp -r ./configs/* ~/.config/
```


