# PalMagic

Presenting the open-source Palworld runtime model swapper PalMagic!
PalMagic has the following features
- Load JSON files with custom model information and apply it to Pals
- Load extra material files if required to apply to Pals
- Apply random custom models from the JSON lists to all applicable wild Pals
- Selectively apply custom models based on the Pal's characteristics
- Allow different custom models per Pal species
- Save the selected custom models selected for Player owned Pals in an individual manner
- Support for ShapeKeys/Morphs, they will be applied randomly to wild Pals and the settings will be saved for Player owned Pals
- Captured Pals will be saved with the settings they are caught with
- A cap of 1000 saved Pals was implemented to avoid making a massive save file, giving priority to the recently used ones
- A couple of hotkeys to cycle through the available custom models for each individual Pal
- Skins applied to Pals that have the following feature (Daedream, Flopie, etc) will be applied now as well to the follower instance

## Controls
- Shift + Z: will cycle through the available custom models for the *closest Pal in proximity to the player* (Can target Summoned Pals)
- Shift + X / Hold Controller Y/Triangle: will cycle through the available custom models for the *Pal your crosshair is aiming at* (Cannot target Summoned Pals)

The project is released in open-source for the Pal Modding Kit created by Okaetsu and uses the UE4SS branch created by Okaetsu as well 
so anybody can build upon it and expand if needed

The mod is also available on [NexusMods](https://www.nexusmods.com/palworld/mods/3834)
