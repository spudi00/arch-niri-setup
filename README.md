<img width="1920" height="1080" alt="screenshot-2026-02-27_23-04-12" src="https://github.com/user-attachments/assets/4e7fea76-af29-4914-af41-395023d1c5f7" />


# Mounting HDD
sudo mkdir /mnt/hdd
UUID=4ACAE882CAE86B9F  /mnt/hdd  ntfs-3g  uid=1000,gid=1000,umask=022  0  0


# Packages
Install yay (AUR helper)
sudo pacman -S --needed git base-devel
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si

# Packages from official repos (pacman)
sudo pacman -S --noconfirm kitty vesktop steam mpv eog obs-studio neovim ntfs-3g qbittorrent cava rocm-smi-lib flatpak 

# Packages from AUR (yay)
yay -S --noconfirm spotify zen-browser-bin noctalia-shell
