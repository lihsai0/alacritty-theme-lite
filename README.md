## Alacritty Theme Lite

A lightweight repo only with the theme config for Alacritty themes.

For more information about Alacritty theme, please visit [alacritty/alacritty-theme](https://github.com/alacritty/alacritty-theme).

## Installation

### Clone the repo

**Option 1:** use this repo directly

```sh
# We use Alacritty's default Linux config directory as our storage location here.
mkdir -p ~/.config/alacritty/themes
git clone https://github.com/lihsai0/alacritty-theme-lite ~/.config/alacritty/themes
```

**Option 2:** use this repo as a submodule

This is very useful when you want to keep the theme config in your dotfiles repo.

```sh
git submodule add git@github.com:lihsai0/alacritty-theme-lite.git alacritty/themes
```

### Import the theme

Add an import to your `alacritty.toml` (Replace `{theme}` with your desired colorscheme):

```toml
[general]
import = [
    "~/.config/alacritty/themes/themes/{theme}.toml"
]
```
