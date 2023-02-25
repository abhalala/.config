# abhalala/.config

> # **DISCLAIMER**: Highly unstable config files **USE AT YOUT OWN DISCRETION**

- **Window Manager** - [Hyprland](https://github.com/hyprwm/Hyprland)
- **Shell** - [Fish](https://fishshell.com/) with [Oh My Fish](https://github.com/oh-my-fish/oh-my-fish)
- **Terminal** - [WezTerm](https://github.com/wez/wezterm)
- **Panel** - [Waybar](https://aur.archlinux.org/waybar-hyprland-git)
- **Notification** - [Dunst]()
- Launcher - [Wofi]()
- File Manager - [Nemo]()
- Editor - [Neovim]() with [LazyVim]() template running on [Neovide]()

## Install Dependencies 📦

### Display Manager
```bash
paru -S sddm-catppuccin-git sddm-config-editor-git
```

### Core
```bash
paru -S hyprland-git xfce-polkit dunst wofi wofi-emoji-git wl-clipboard wf-recorder wlogout grimblast-git hyprpicker-git hyprpaper-git xdg-desktop-portal-hyprland-git ffmpegthumbnailer tumbler wtypecolord imagemagick swaylock-effects qt5-wayland qt6-wayland waybar-hyprland-git pamixer pipewire
```

### Audio
```bash
paru -S pipewire pipewire-alsa pipewire-audio  pipewire-jack  pipewire-pulse wireplumber
```

### Themes
```bash
paru -S catppuccin-gtk-theme-mocha bibata-cursor-theme nwg-look catppuccin-mocha-grub-theme-git kvantum
```

### Apps
```bash
paru -S cava pavucontrol ranger fish rustup gdb ripgrep  bat lsd neovim neovide viewnior noise-suppression-for-voice nemo nemo-fileroller
```

## Install
```bash
git clone https://github.com/abhalala/.config $HOME/.temp_config
cd $HOME/.temp_config
rsync -avxHAXP --exclude '.git*' .* ~/.config
```


