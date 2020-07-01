## Computer-Security-Checklist
#### Disable Ipv6 module 
Add this line in etc/default/grub
```
GRUB_CMDLINE_LINUX_DEFAULT="quiet splash ipv6.disable=1"
```
After that run:
```
update-grub
```
Reboot!
#### Disable in BIOS (press F10 on boot) 
```
System configuration > Virtualisation Technology
System configuration > Build-in Device Option:
> Camera
> Microphone
> Bluetooth
```
#### Clear your web browser's cache, cookies, and history

