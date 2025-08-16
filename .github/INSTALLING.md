# Cheat Device Installation Guide

---

> [!WARNING]
> By following this guide you agree you are entirely responsible if somehow you mess up and anything bad happens to your _PSP_ (like bricking...). We can't guarantee this guide will work for every _PSP_ / _PSVita_ and we recommend reading it completely before starting.

> [!INFO]
> Be aware that:
> - **Cheat Device** isn't compatible with PPSSPP.
> - **Cheat Device** is compatible with Adrenaline (PSVita).

> [!INFO]
> Keep in mind `v1.0g` (LCS) and `v2.4` (VCS) have specific PRXs for different firmwares compatibility, check the `README.md` inside the version folder for more info.
> We don't really know about the other versions, they probably don't work on later firmwares.

---

Clone the repo, either press `Code/Download ZIP` on browser, or run the following command on a terminal: 
```
git clone https://github.com/danssmnt/CheatDevice-Archive
```

From there you can access all archived versions (inside LCS and VCS) plus some bonus content!

## LCS
There are two types of Cheat Devices for LCS:
 - (**OLD**) Save Game Exploit (``v0.1`` - ``v1.0d``)
 - PRX (``v1.0d`` - ``v1.0g``)
 
### Save Game Exploit
> [!WARNING]
> This method only works for PSPs with firmware version below 2.8 and with the unpatched _Grand Theft Auto: Liberty City Stories_ version (1.05).

> [!WARNING]
> We recommend doing a backup of your original saved data as the hacked saved game occupies the first save slot!

To install it, simply copy the savedata provided to your PSP ``ms0:/PSP/SAVEDATA/`` directory.

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

### LCS
Copy all `.txt` found inside `LCS/UserCheats` to `ms0:/CHEATS/`.

### VCS
Copy all `.txt` found inside `VCS/UserCheats` to `ms0:/CHEATS/vcs` (create the `vcs` folder if not present).

> [!WARNING]
> All usercheats are **UNTESTED** and can crash your game.
> Also it is recommended to use them in the latest releases of **Cheat Device**.

---

That should be it, now boot up your GTA and everything should work, you might have to wait some seconds for the menu to show! 

---

Guide written by [@danssmnt](https://github.com/danssmnt).
Feel free to correct any mistakes / innacuracies you find!