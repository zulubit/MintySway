# MintySway

Sway window manager setup for **Linux Mint Cinnamon (latest version)**.

> **Note:**  
> This configuration is **designed for and only tested on Linux Mint Cinnamon Edition (latest release)**.  
> It is a **single, all-in-one config file**—no scattered dotfiles or directories.  
> All setup, usage, and customization instructions are clearly documented as comments in the config file itself.

![Screenshot of Sway Mint](mint-sway.png Sway itself, see the [Sway Wiki](https://github.com/swaywm/sway/wiki).

## Quick Install

Back up your existing sway config and clone MintySway into place with:

```bash
mv ~/.config/sway ~/.config/sway-old 2>/dev/null
git clone https://github.com/YOUR-REPO/MintySway.git ~/.config/sway
```

- The first command safely moves any old config out of the way (if it exists).
- The second command clones this repo as your new Sway config directory.

### Next Steps

1. Edit the new config (at `~/.config/sway/config`) to set your device names and preferences as explained in the comments.
2. Log in to a Sway session.
