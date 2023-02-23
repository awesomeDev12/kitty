# Kitty

To use my config file
```
git clone https://github.com/awesomeDev12/kitty.git ~/.config/kitty
```

ArchWiki Reference manual for [kitty.conf](https://man.archlinux.org/man/community/kitty/kitty.conf.5.en)

ArchWiki Reference manual for [kitty](https://man.archlinux.org/man/community/kitty/kitty.1.en)

### Themes (kitty-themes)

Clone the entire kitty-themes repository
```
git clone --depth 1 https://github.com/dexpota/kitty-themes.git ~/.config/kitty/kitty-themes
```

To use a theme 

Replace *gruvbox_dark.conf* with the theme of your choice

```
cp ~/.config/kitty/kitty-themes/themes/gruvbox_dark.conf ~/.config/kitty/theme.conf
```

### Installation 

Install kitty on Arch-Linux
```
pacman -sS kitty
sudo pacman -S kitty
```

Install kitty on Ubuntu
```
apt search kitty
sudo apt install kitty
```
