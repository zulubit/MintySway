# Sway Mint Quickstart

A fast, modern, and minimal Sway window manager setup for Linux Mint—designed to get you productive and stylish with just a few commands.

## Features

- Tiling Wayland window manager (Sway)
- Preconfigured hotkeys, theming, and status bar
- Integrated launcher (fuzzel), notifications (mako), power menu (wlogout)
- Volume and brightness controls
- Ready for screenshots, clipboard, and more

## Quick Install

**1. Install all dependencies:**

```sh
sudo apt update && sudo apt install \
  sway swaylock swayidle foot mako-notifier fuzzel wlogout \
  brightnessctl pulseaudio-utils \
  bumblebee-status \
  xdg-desktop-portal-wlr grim slurp wl-clipboard \
  network-manager \
  fonts-agave \
  ddcutil gammastep
```

**2. Enable user brightness control:**

```sh
sudo gpasswd -a $USER video
# Log out and back in for group change to take effect
```

**3. Copy the sample Sway config:**

```sh
mkdir -p ~/.config/sway
cp path/to/this/config ~/.config/sway/config
```

**3. Install AdwaitaMono Nerd Font:**

You can install it using *Embellish* found on *Software Manager* in mint.

## Usage

- **Start Sway:** Log out of your current session and choose Sway from your display manager, or run `sway` from a TTY.
- **Open terminal:** Super + Enter
- **Launcher:** Super + D
- **Power menu:** Super + Backspace
- **Volume/Brightness:** Use your keyboard’s media keys

## Customization

- **Theming:**  
  Edit color variables at the top of `~/.config/sway/config` for instant style changes.
- **Launcher (fuzzel):**  
  Colors are set inline in the config; for advanced options, see `man fuzzel` or use `~/.config/fuzzel/fuzzel.ini`.
- **Notifications (mako):**  
  Further customize in `~/.config/mako/config`.
- **Power menu (wlogout):**  
  For full theming, edit `~/.config/wlogout/style.css`.

## Resources

- [Sway Wiki](https://github.com/swaywm/sway/wiki)

