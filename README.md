# holoiso-win600-driver
The Anbernic-Win600 driver in holoiso.

Usage:

```
sudo pacman -Sy gcc git
git clone https://github.com/lualiliu/holoiso-win600-driver
cd holoiso-win600-driver/src
make install
reboot
```

Completed:

The IRQ now checks for a specific keycombo to invoke Home menu
The IRQ now checks for a specific keycombo *and* launches a complicated system of timers to invoke the on-screen keyboard (still unstable)

Todo:

Fix the deadlock while unloading the module
