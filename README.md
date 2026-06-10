# My Arch Linux Dotfiles (KDE Plasma on Wayland)

Welcome to my personal dotfiles repository! This repo contains my complete KDE Plasma desktop configuration, including themes, icons, widgets, and wallpapers, all packed and managed using **Konsave**.

## 💻 System Specs

- **OS:** Arch Linux 🐧
- **DE:** KDE Plasma
- **Display Server:** Wayland
- **Shell:** Fish Shell 🐟
- **Terminal:** Konsole

---

## 🚀 How to Apply This Configuration

Since KDE Plasma spreads its configuration across multiple directories, this setup uses `konsave` for easy backup and restore. Follow these steps to apply my theme to your system:

### 1. Install Konsave
Make sure you have `konsave` installed on your Arch system. You can install it from the AUR:
```bash
yay -S konsave
```

### 2. Clone and Import the Profile
Clone this repository, navigate into it, and import the `.knsv` configuration file:
```bash
# Clone the repository
git clone https://github.com/VahramCode/dotfiles.git
cd dotfiles

# Import the plasma profile
konsave -i my_plasma_config.knsv
```

### 3. Activate the Profile
Now, apply the imported profile to your desktop:
```bash
konsave -a my_plasma_config
```

> **Note:** After activating the profile, log out and log back into your session for all changes (especially Wayland and shell components) to take effect perfectly.

---
*Maintained by [RedHood](https://github.com/VahramCode)*
