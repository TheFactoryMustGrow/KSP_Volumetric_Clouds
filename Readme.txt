This is a preview build for the raymarched volumetric clouds of EVE. Thank you for the support!

As this is a preview build, keep in mind some things are unfinished.

Installation instructions:
	Remove any existing config packs for EVE (BoulderCo, AVP, SVE, Spectra, 64k clouds, KSRSSVE, etc) then overwrite your GameData folder with the one included. If you leave existing EVE configs they will interact in bad ways and you can get a weird mix of 2d and 3d clouds.

Notes:
	- Quality settings:
		- Check the documentation if you want to change quality settings: https://github.com/LGhassen/EnvironmentalVisualEnhancements/wiki the main one to change is temporal upscaling: https://github.com/LGhassen/EnvironmentalVisualEnhancements/wiki/Temporal-upscaling-and-noise-detiling#temporal-upscaling

	- Known issues
		- Cubemap type 2_1 (the one with 2 textures each containing a face in each RGB channel) isn't supported for the Volumetrics, equirectangular and cubemap with 6 textures are supported.
		- Maps for each volumetric layer (coverage, cloud type, color) need to use the same cubemap/texture type