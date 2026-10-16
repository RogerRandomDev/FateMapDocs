# MapLoader

The maploader for FateMaps is a set of resources you drag and drop into your project to allow the mapmaker to create maps for it.

[MapLoader Repository](https://github.com/RogerRandomDev/FatemapLoader)

## Setup

Once you install and add them to your project they should appear as follows.


![Example Structure](../images/maploader_setup_format.png)

Any 3d models you intend to place on a map using the map maker are placed into the Models folder.
Any textures/materials you intend to apply to the map in the mapmaker should be placed into Materials folder. You must create a .FMT file for the mapmaker to use them. [FMT](../FMT.md)

Once added, go into the ```FateMap/decompilers/compiled``` folder. depending on versions, you may have more loaders. different version loaders are not guaranteed to work on different versions of maps.
Add a node3D to your scene in Godot and give it the loader's script. it should have a parameter whe you select it for a target file. If you already have a compiled ```.fatemap``` file you can set it to the file path for it. A version mismatch can cause it to fail to load if you try. Otherwise, loading a map in the editor or game will recreate the map with all the compile settings used.