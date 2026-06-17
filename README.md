# My Arch Linux Dotfiles (KDE Plasma on Wayland)

---
<img width="1920" height="1080" alt="Screenshot_20260617_183312" src="https://github.com/user-attachments/assets/d765c0ac-1894-4401-afc5-93aa88615a56" />



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

## 0.Prerequisites
This Repo uses **Git LFS (Large File Storage)** to manage large theme files. before cloning or applying the theme, make sure you have **git-lfs** installed.
```bash
sudo pacman -S git-lfs
```
### 1. Install Konsave
Make sure you have `konsave` installed on your Arch system. You can install it from the AUR:
```bash
yay -S konsave
```

### 2. Clone and Import the Profile
Clone this repository, navigate into it, and import the `.knsv` configuration file:
```bash
# Clone the repository
GIT_LFS_SKIP_SMUDGE=1 git clone https://github.com/VahramCode/dotfiles.git
# go to dotfiles directory
cd dotfiles
# lfs install
git lfs install
# lfs pull
git lfs pull
# Import the plasma profile
konsave -i my_new_config.knsv
```

### 3. Activate the Profile
Now, apply the imported profile to your desktop:
```bash
konsave -a my_new_config
```

> **Note:** After activating the profile, log out and log back into your session for all changes (especially Wayland and shell components) to take effect perfectly.
---
## for more fun , you can install **ponysay** and **fastfetch** and 
```bash
sudo pacman -S ponysay
sudo pacman -S fastfetch
```
---
## To enable the pony greeting upon every terminal session login , **Do** this :
```bash
nano ~/.config/fish/config.fish
```
Add this code to the last line :
```bash
PYTHONWARNINGS=ignore ponysay "YOUR TEXT"
```
---
# also :
[4k Wallpapers]( https://4kwallpapers.com/ )
>**Note:** you can searching for raiden shogun :)
---
[FishShell](https://fishshell.com/)
>**Note:** you can Read about FishShell :)
---
[ArchLinux](https://archlinux.org/)
>**Note:** you can Read about ArchLinux :)
---

*Maintained by [RedHood](https://github.com/VahramCode)*
