# Amd Drivers For Linux
Amd Drivers For Linux


# Installtion


# Basic Drivers

**Arch Linux**
sudo pacman -Syu lib32-mesa mesa vulkan-radeon lib32-vulkan-radeon


On **Ubuntu 20.04 and higher** Its preinstalled you only need to enable vulkun support


On **Fedora 36 and higher** Its preinstalled you only need to enable vulkun support


**Reboot after installing Amd**


# Switching from Readon to AmdGpu for Vulkun Support



in `/etc/modprobe.d/amdgpu.conf` add
```
options amdgpu si_support=1
options amdgpu cik_support=1
```


in `/etc/modprobe.d/radeon.conf` add
```
options radeon si_support=0
options radeon cik_support=0
blacklist radeon
```

**Reboot after switching Readon to amdgpu**