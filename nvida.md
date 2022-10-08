# Nvida Drivers For Linux
Nvida Drivers For Linux


# Installtion


# Basic Drivers


**Arch Linux**


`sudo pacman -Syu nvida nvidia-utils lib32-nvidia-utils`


**Ubuntu 20.04 and higher**


` sudo apt purge nvida* -y && sudo ubuntu-drivers autoinstall`


**Fedora 36 and higher**


**Enable RPM Fusion repositories**


```
sudo dnf install \
  https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm


  sudo dnf install \
  https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm


  sudo dnf group update core
  ```
**sudo dnf install akmod-nvidia xorg-x11-drv-nvidia-cuda**


**Reboot after installing Nvidia**

# Arch Only


# Installing Paru 


```
sudo pacman -Syu git base-devel`


sudo pacman -S --needed base-devel


git clone https://aur.archlinux.org/paru.git


cd paru


makepkg -si
```


# Installing Optimus Manager for Nvidia and Intel Laptops


`paru -Syu optimus-manager`


`paru -Syu optimus-manager-qt`



**Reboot after installing Optimus Manager**


# Making Nvida as Default on Optimus Deveices


Just open the app, click it in the system tray, mark nvidia as default and you're done!