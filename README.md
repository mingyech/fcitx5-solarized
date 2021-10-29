# fcitx5-solarized

[Solarized](https://github.com/altercation/solarized) color theme for Fcitx5

## Installation

### Arch Linux

Package avaliable on the [AUR](https://aur.archlinux.org/packages/fcitx5-solarized/): `fcitx5-solarized`

### Other

```sh
git clone https://github.com/mingyech/fcitx5-solarized
mkdir -p ~/.local/share/fcitx5/themes/
cd fcitx5-solarized/
cp -r solarized-dark/ solarized-light/ ~/.local/share/fcitx5/themes/
```

## Configuration

Enable the theme using your fcitx5 config tool, or edit the `Theme` line in `~/.config/fcitx5/conf/classicui.conf`:

```dosini
Theme=solarized-dark
# or
Theme=solarized-light
```
