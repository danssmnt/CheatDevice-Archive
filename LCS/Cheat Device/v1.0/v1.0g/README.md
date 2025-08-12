# LCS Cheat Device v1.0g

## Release Date
13 or 14 oct 2007

## Changelog
 - Adds support for 3.10OE-A and up.
 
## Release Notes
> You must use lcscheatdevice371.prx for 3.71 M33 or higher.
 
## Archival Notes
``lcscheatdevice.prx`` and ``lcscheatdevice_2009.prx`` are ALMOST the same, for some reason, the original one (compiled in 2007) doesn't load on latest firmwares (6.61), while the 2009 version does, but the only difference between them is the 0x69 file byte:
	- original ver -> ``0x1D``
	- 2009 ver -> ``0x2A``
	
My theory is that this is a flag for compatible firmware versions (kinda like the ``PSP_FW_VERSION`` flag), but I really don't know. For now, archive should have both.

Last version to be officially released for LCS?