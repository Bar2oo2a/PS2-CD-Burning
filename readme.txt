.oO  PSX/PS2 Disc Patcher v3.0  Oo.



oO What it Does Oo

	This program can patch psx and ps2 cd and dvd images for different regions.
	
	It also supports the patching of the main exe filename for psx and ps2 cd
	and dvd images.
	
	It can patch discs to make them appear to be 'master discs'.
	(Lets you play burnt discs on debug PS2s!)



oO Images Types Supported Oo

	Psx (mode 2) cd images that are either 2048 or 2352 bytes per sector.
	Ps2 (mode 2) cd images that are either 2048 or 2352 bytes per sector.
	Ps2 dvd iso images.
	Ps2 dvd gi images.
	(cd and dvd images with image headers are supported as long
	as their 'bytes per sector' format is supported)

	

oO History Oo

	v3.0
		-master disc patching is now correct for both cd and dvd!
		
	v2.5
		- fixed master disc patching to not fuk up your image!
		  (note is still doesnt patch PROPER master disc info)
		- fixed a few little bugs where image file wasnt properly closed when an
		  error occurred
		
	v2.0
		- added ps2 logo encryption
		- fixed a big where cdrwin made iso files were having there header
		  size wrongly calculated
	
	v1.5
		- added support for images that are either 2048 or 2352 bytes per sector
		- added support for images with image headers (*.gi images now supported)
		- fixed a signature patch bug on cd images
		- fixed the patching or american and japanese psx region info

	v1.0
		- initial release.
		- supports cd and dvd iso images (not dvd *.gi images yet)
		- supports psx and ps2 discs
		- supports japan, usa and europe regions for both psx and ps2
		- supports exe filename patching (even on dvd unicode file descriptors)
		- ps2 logo encryption not supported yet
		- master disc patching information is not fully implemented
