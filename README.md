# Voidcraft theme for WezTerm

This theme is made to use pure black to get the most out of OLED and XDR Liquid Retina screens. The black color gives deep contrast and saves energy. Bright elements look sharp against this background, and the theme focuses on being simple and easy on the eyes.

## Install

```bash
git clone https://github.com/daniilium/voidcraft-wezterm-theme
cp ./voidcraft-wezterm-theme/voidcraft.toml ~/.config/wezterm/colors/
```

And add the following configs into your wezterm.lua file
```toml
color_scheme = "voidcraft",
use_fancy_tab_bar = false,
window_decorations = "RESIZE",
```
