# Amd on Arch Linux
 Amd on Arch Linux


# Installtion


# Basic Drivers


sudo pacman -Syu lib32-mesa mesa vulkan-radeon lib32-vulkan-radeon


**Reboot after installing Amd**


# Switching from Readon to AmdGpu for Vulkun Support



in `/etc/modprobe.d/amdgpu.conf` add
```
options amdgpu si_support=1
options amdgpu cik_support=1
```


**Reboot after installing Optimus Manager**


# Making Nvida as Default on Optimus Deveices


just open the app click it in the taskbar in system tray and make nvida as default and done
