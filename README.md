# Vanguard

A level by Maxime 'Fubar' Dupuis with additionnal assets from Kevin 'Ravidge' Brook, Gavin 'Equinoxo' Sawford and Sebastian 'Seba' Grus

## The project folder "content\vanguard"
- **cp_vanguard.vmf** is used for compiling the level.
- **cp_vanguard.vmm** is used for editing the level.

## The root folder
- **paklist.txt** is meant to be used with bspzip.exe for the packaging of assets.
- **contributors.csv** is a list of assets and their authors.

## The asset folder "tf\"
All the dependencies are included in the tf folder as well as the uncompressed and unpackaged bsp.
In Addition to assets to be bspzipped, you'll find a thumbnail image in tf\materials\vgui\maps.

##Compiling
The recommended parameters for vrad.exe are: -both -final -StaticPropLighting -StaticPropPolys -TextureShadows
