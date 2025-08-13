# LCS Cheat Device v1.0g

## Release Date
13 or 14 oct 2007

## Changelog
 - Adds support for 3.10OE-A and up.
 
## Archival Notes
Last version to be officially released for LCS.

`Less than 3.71 FW` and `Every other FW` verions are ALMOST the same, for some reason, the original one (compiled in 2007) doesn't load on latest firmwares (6.61), while the other version does, but the only difference between them is the 0x69 file byte:
 - original ver: `0x1D`
 - hexed ver: `0x2A`
	
My theory (@danssmnt) is that this is a flag for compatible firmware versions (kinda like the `PSP_FW_VERSION` flag), but I really don't know. For now, archive should have both.

Feel free to correct any of the above info if you know more about it.