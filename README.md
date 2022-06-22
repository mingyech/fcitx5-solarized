# fcitx5-solarized

[Solarized](https://github.com/altercation/solarized) color theme for Fcitx5

## Installation

### Packages

Install from one of the following repositories:

[![Packaging status](https://repology.org/badge/vertical-allrepos/fcitx5-solarized.svg)](https://repology.org/project/fcitx5-solarized/versions)

### From git

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
