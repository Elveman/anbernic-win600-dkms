# holoiso-win600-driver
The Anbernic-Win600 driver in holoiso.

Usage:

```
sudo rm -rf "/lib/modules/$(uname -r)/kernel/drivers/input/joystick/xpad.ko.xz"
sudo pacman -Sy gcc git
git clone https://github.com/lualiliu/holoiso-win600-driver
cd holoiso-win600-driver
makepkg -si
```

Completed:

The Win key maps to the Home key of the xbox controller.
