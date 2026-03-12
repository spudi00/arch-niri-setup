
<img width="1920" height="1080" alt="screenshot-2026-03-11_18-59-17" src="https://github.com/user-attachments/assets/3f0526db-93cf-4856-9357-ea1d8f5bcd6e" />
#Niri

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/57911741-fee3-45b2-9a93-491c132c01af" />
#Hyprland


# 🖥️ Arch Linux Setup

Personal setup for getting an Arch system up and running — packages, mounts, and essentials.

---

## 📦 Prerequisites

### Install `yay` (AUR Helper)

```bash
sudo pacman -S --needed git base-devel
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```

---

## 💾 Mounting HDD

```bash
sudo mkdir /mnt/hdd
```

Add to `/etc/fstab`:

```
UUID=4ACAE882CAE86B9F  /mnt/hdd  ntfs-3g  uid=1000,gid=1000,umask=022  0  0
```

---

## 📥 Packages

### Official Repos (`pacman`)

```bash
sudo pacman -S --noconfirm kitty vesktop steam mpv eog obs-studio neovim ntfs-3g qbittorrent cava rocm-smi-lib flatpak
```


### AUR (`yay`)

```bash
yay -S --noconfirm spotify zen-browser-bin noctalia-shell faugus-launcher
```

