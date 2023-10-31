# ArchLinux-PackLists

__Clone the repo:__

```bash
sudo pacman -S --needed git
git clone https://github.com/anisbsalah/ArchLinux-PackLists.git
cd ArchLinux-PackLists
```

## 1- Choose what desktop environment to install (e.g. KDE Plasma)

```bash
cd kde-plasma
```

## 2- Install packages from the packages lists

```bash
sudo pacman -S --needed - < name_of_packages_list.txt
```

## 3- Enable services

```bash
sudo systemctl enable acpid.service
sudo systemctl enable avahi-daemon.service
sudo systemctl enable bluetooth.service
sudo systemctl enable cups.service
sudo systemctl enable ntpd.service
sudo systemctl enable reflector.timer
sudo systemctl enable sddm.service
sudo systemctl enable sshd.service
sudo systemctl enable tlp.service
sudo systemctl enable wpa_supplicant.service
``` 
