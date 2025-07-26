# MintySway

Sway window manager setup for **Linux Mint Cinnamon (latest version)**.

> **Note:**  
> This configuration is **designed for and only tested on Linux Mint Cinnamon Edition (latest release)**.  
> It is a **single, all-in-one config file**—no scattered dotfiles or directories.  
> All setup, usage, and customization instructions are clearly documented as comments in the config file itself.

![Screenshot of Sway Mint](mint-sway.png)

## Quick Install

This will back up any existing Sway configuration you have and replace it with MintySway:

```bash
mv ~/.config/sway ~/.config/sway-old 2>/dev/null
git clone https://github.com/zulubit/MintySway.git ~/.config/sway
```

- The first command safely moves any old config out of the way (if it exists).
- The second command clones this repo as your new Sway config directory.

### Next Steps

1. Read the comments in ~/.config/sway/config for dependency installation and setup guidance.
2. Adjust the config for your device names and preferences as needed.
3. Log in to a Sway session to start using MintySway.

