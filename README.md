# holoiso-win600-driver
The Anbernic-Win600 driver in holoiso.

## Usage

```
sudo pacman -Sy gcc git
git clone https://github.com/Elveman/anbernic-win600-dkms.git
cd anbernic-win600-dkms
# to be added later...
```

## Completed:

+ The IRQ now checks for a specific keycombo to invoke Home menu
+ The IRQ now checks for a specific keycombo *and* launches a complicated system of timers to invoke the on-screen keyboard (still unstable)
+ Fixed the deadlock while unloading the module

## Todo:

+ Make Keyboard button work on press rather than on release
+ Make Keyboard button more consistent
