# Gruvbox Material Rofi theme

<p align="center">A simple Gruvbox Material <a href="https://github.com/davatorium/rofi">Rofi</a> color theme.</p>

Based on the <a href="https://github.com/sainnhe/gruvbox-material">Gruvbox Material</a> color palette.</p>

Credits to <a href="https://github.com/undiabler">@undiabler</a> for providing the basis that a shamelessly took and recolored.

I used it to make my personal theme for my Gruvbox Material desktop.
---

<p align="center"><img src="screenshot.jpg"/><blockquote>Font: <a href="https://www.jetbrains.com/lp/mono/">JetBrains Mono</a> 12px.</blockquote></p>

## Getting started
### Installation

1. Copy <a href="gruvbox-material.rasi">gruvbox-material.rasi</a> file to `~/.config/rofi/gruvbox-material.rasi`
2. Add the following lines to your rofi config (`~/.config/rofi/config.rasi`):
```
configuration {
    font: "JetBrains Mono 12";

    display-ssh:    "";
    display-run:    "";
    display-drun:   "";
    display-window: "";
    display-combi:  "";
    show-icons:     true;
}

@theme "~/.config/rofi/gruvbox-material.rasi"
```
