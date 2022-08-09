# Nvida on Arch LInux
 Nvida on Arch Linux


# Installtion


# Basic Drivers


sudo pacman -Syu nvida nvidia-utils


# Paru 


sudo pacman -Syu git base-devel


sudo pacman -S --needed base-devel


git clone https://aur.archlinux.org/paru.git


cd paru


makepkg -si



paru -Syu optimus-manager


paru -Syu optimus-manager-qt


# Making Nvida as Default


just open the app click it in the taskbar in system tray and make nvida as default and done