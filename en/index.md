![](../thumbnail.png)  
MineExporteR is a mod for Minecraft 1.12.2 that allows you to output your world to external rendering software such as Blender. It features support for modded block and optifine connected textures.

> [**日本語ページはこちら**](https://chik4ge.github.io/mexp)

## Commands
`/mexp pos1 `  
- Set start point of region.

`/mexp pos2`  
- Set end point of region.

`/mexp export`  
- Export selected region as .obj file.  
- **At this time, if you have optifine, set the shader to "None".**  
- **Also, set the Graphics setting to "Fancy".**


## Setting Files  
None(will be added soon)

## How to use
Exported data are located in _envionment_folder/MineExporter_. Then import the data to rendering software.  
**If you are using Blender, run [this script](https://gist.github.com/chik4ge/bb136ee26ebc0f0329ad4893bb4363c7) to disable texture blur and backside culling.**  

## Cautions
- The file will be overwritten with each rendering. It is highly recommended to move the output files to another location before import them into external 3D software.

- This mod is in beta testing. There is a possibility that some blocks may not be output correctly, but we are continuing to develop it so that it will output as much as possible as it looks in Mikra before the official release.

- I am developing the latest version on github, but please use that only if you can build it at your own risk. There is no guarantee that it will work. (Instead, we will try to make the version distributed here as stable as possible).

## Download
[**Download from here**](https://github.com/chik4ge/MineExporteR/releases) **only if you agree to the above Cautions.**  
Click Assets -> MineExporteR-(latest version).jar to Download.

## Known bugs / Unimplemented features
・Tile Entities will not be output.  
・Some CTM methods will not be output.  
・The CTM (different from optifine's) used in Chisel mod, etc. is not supported.

## Discord
If you have any questions or share your creations, you can join the Discord server: 
<iframe src="https://ptb.discord.com/widget?id=968081252857028628&theme=dark" width="350" height="500" allowtransparency="true" frameborder="0" sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts"></iframe>