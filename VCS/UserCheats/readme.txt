#cheat VCS CheatDevice v2.4 for GTA Vice City Stories
#cheat By Edison Carter

#cheat vcscheatdevice.prx is tested on 3.03OE-C, 3.10OE-A, should work on up to 3.52OE-A.
#cheat For 3.71 M33 or higher use vcscheatdevice371.prx instead.

#cheat To install on SE/OE:  (replace X: with the drive letter of your PSP)

#cheat mkdir X:\SEplugins
#cheat copy vcscheatdevice.prx X:\SEplugins
#cheat echo ms0:/SEplugins/vcscheatdevice.prx >> X:\SEplugins\game.txt

#cheat in the OE recovery menu (hold R button while booting):
#cheat go into Advanced->Advanced Configuration and make sure "Plain Modules in UMD/ISO" is enabled
#cheat go into Plugins and enable vcscheatdevice.prx


#cheat To install to DevHook, run CheatDeviceInstall.exe, or to install manually:

#cheat mkdir X:\dh\kd
#cheat copy vcscheatdevice.prx X:\dh\kd

#cheat (replace X: with the drive letter of your PSP)

#cheat edit one of these files:

#cheat for emulated FW 2.71 edit: X:\dh\271\flash0\kd\pspbtcnf_game.txt
#cheat for emulated FW 2.82 edit: X:\dh\282\f0\kd\pspbtcnf_game_dh.txt
#cheat for emulated FW 3.01 edit: X:\dh\301\f0\kd\pspbtcnf_game_dh.txt
#cheat for emulated FW 3.02 edit: X:\dh\302\f0\kd\pspbtcnf_game_dh.txt

#cheat and add the line

#cheat ms0:/dh/kd/vcscheatdevice.prx

#cheat after the line that look like:

#cheat ms0:/dh/kd/devhook.prx
#cheat or
#cheat /kd/devhook.prx #DEVHOOK


#cheat IMPORTANT NOTE: After installing, wait at least 15 seconds before turning
#cheat off USB or pulling out your memory stick.  The PC caches your changes and
#cheat doesn't write them out until a while later.  If your memory card gets
#cheat corrupt, use chkdsk /f X:

#cheat Disclaimer: USE THIS AT YOUR OWN RISK.  I advise against saving your game
#cheat after using cheats.  Please note that when you spawn vehicles, you are
#cheat using a game cheat that will lower your criminal rating!

#cheat Thanks to:
#cheat ADePSP for the installer!
#cheat vettefan for finding the place marker and no visible car damage and sideways tires
#cheat winchy for radar and hud flags
#cheat jas0nuk for 3.71 M33 NID patches
