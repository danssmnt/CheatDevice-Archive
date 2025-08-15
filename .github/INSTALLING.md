# Cheat Device Installation Guide

---

> [!WARNING]
> By following this guide you agree you are entirely responsible if somehow you mess up and anything bad happens to your _PSP_ (like bricking...). We can't guarantee this guide will work for every _PSP_ / _PSVita_ and we recommend reading it completely before starting.


> [!NOTE]
> Be aware that:
> - **Cheat Device** isn't compatible with PPSSPP.
> - **Cheat Device** is compatible with Adrenaline (PSVita).

> [!NOTE]
> Keep in mind `v1.0g` (LCS) and `v2.4` (VCS) have specific PRXs for different firmwares compatibility, check the `README.md` inside the version folder for more info.
> We don't really know about the other versions, they probably don't work on later firmwares.

---

## LCS
There are two types of Cheat Devices for LCS:
 - (**OLD**) Save Game Exploit (``v0.1`` - ``v1.0d``)
 - PRX (``v1.0d`` - ``v1.0g``)
 
### Save Game Exploit
> [!WARNING]
> This method only works for PSPs with firmware version below 2.8 and with the unpatched _Grand Theft Auto: Liberty City Stories_ version (1.05).

> [!WARNING]
> We recommend doing a backup of your original saved data as the hacked saved game occupies the first save slot!

To install it, simply copy the savedata provided to your PSP ``ms0:/PSP/SAVEDATA/`` directory and run _Grand Theft Auto: Liberty City Stories_.

### PRX
#### ARK-4
To install it, simply copy the plugin (`.prx`) to `ms0:/seplugins/` and add `{LCS ID}, ms0:/seplugins/lcscheatdevice.prx, on` (replace `LCS ID` with your game ID) to your `PLUGINS.TXT`.

#### Every other CFW
To install it, simply copy the plugin (`.prx`) to `ms0:/seplugins/` and add `ms0:/seplugins/lcscheatdevice.prx 1` to `GAME.TXT`.
Remember to disable it when running other games in order to not cause problems.

---

## VCS
### ARK-4
To install it, simply copy the plugin (`.prx`) to `ms0:/seplugins/` and add `{VCS ID}, ms0:/seplugins/vcscheatdevice.prx, on` (replace `VCS ID` with your game ID) to your `PLUGINS.TXT`.

### Every other CFW
To install it, simply copy the plugin (`.prx`) to `ms0:/seplugins/` and add `ms0:/seplugins/vcscheatdevice.prx 1` to `GAME.TXT`.
Remember to disable it when running other games in order to not cause problems.

---

## Installing UserCheats

To install UserCheats, simply copy the `UserCheats` folder to `ms0:/CHEATS/` and rename it to `lcs` / `vcs`, depending on the game.

> [!WARNING]
> All usercheats are **UNTESTED** and can crash your game.
> Also it is recommended to use them in the latest releases of **Cheat Device**.

That should be it, now boot up your GTA and experience the nostalgia again!

---

Guide written by [@danssmnt](https://github.com/danssmnt).
Feel free to correct any mistakes / innacuracies you find!
