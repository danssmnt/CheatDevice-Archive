LCS CheatDevice v1.0e PRX for GTA Liberty City Stories
By Edison Carter

This is the PRX version for use with DevHook, SE/OE firmware editions
and whatever else can run a PRX.

Game disk versions supported:

 original US version         -- works
 original UK/Euro version    -- works
 new patched US version      -- works
 new patched UK/Euro version -- not working


To install with SE or FW 3.03 OE-C or later:

 see http://www.gtaforums.com/index.php?showtopic=266386 for more detailed and updated instructions.
 wherever it says vcscheatdevice.prx substitute lcscheatdevice.prx

 briefly, the instructions are:

  (replace X: with the drive letter of your PSP)

  mkdir X:\SEplugins
  copy lcscheatdevice.prx X:\SEplugins
  edit X:\SEplugins\game.txt (create it if not already there) and add the line:
    ms0:/SEplugins/lcscheatdevice.prx


To install with DevHook:

 mkdir X:\dh\kd
 copy lcscheatdevice.prx X:\dh\kd

  (replace X: with the drive letter of your PSP)

 edit one of these files:

  for emulated FW 2.71 edit: X:\dh\271\flash0\kd\pspbtcnf_game.txt
  for emulated FW 2.82 edit: X:\dh\282\f0\kd\pspbtcnf_game_dh.txt
  for emulated FW 3.01 edit: X:\dh\301\f0\kd\pspbtcnf_game_dh.txt
  for emulated FW 3.02 edit: X:\dh\302\f0\kd\pspbtcnf_game_dh.txt

 and add the line

  ms0:/dh/kd/lcscheatdevice.prx

 after the line that looks like:

  ms0:/dh/kd/devhook.prx
  or
  /kd/devhook.prx #DEVHOOK


Disclaimer: USE THIS AT YOUR OWN RISK.

Thanks to:
Lloyd for help with finding car colors.
Jérémie Blanc for finding car speed at offset 0x0124.
GFCC for the Vice City never fall off bike cheat, it was instructive.
Waterbottle for finding car health.
Jérémie Blanc for finding memory locations for no reload.
ADePSP for the FAQ and CheatSync.
ADePSP, MURDOC and Jérémie Blanc for testing Cheat Maker.
Vettefan for radar map enable/disable location.
Mister Enchilada for finding radar blips for Player Target teleport.
Waterbottle for originally discovering how to create objects in the game.
Joek2100 for additional object creation discoveries.
Vettefan for camera zoom distance.
Ditlew and Fanjita for documenting the syscalls for 333MHz on fw2.6.
-DeMoN-, Waterbottle, joek2100, Vettefan, Jérémie Blanc and Ade for testing Construction Mode.
joek2100 for changing where you spawn when the game loads.
Waterbottle for all hidden packages found.
Vettefan for sideways tires, no physical car damage, drivable rc toys and gangs don't attack you.
Mister Enchilada for vehicle spawns at the airport.
Vettefan for heavy cars.
