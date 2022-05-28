# EccoLib

A graphics extraction library for the Ecco the Dolphin series.

# Supported Games

- Ecco the Dolphin - Palettes, Blocks, Sprites, Stage Sprites and Level Maps
- Ecco the Dolphin PC - Palettes, Tiles, Blocks, Sprites and Level Maps
- Ecco 2: The Tides of Time - Palettes, Blocks, Sprites, Stage Sprites and Level Maps
- Ecco Jr - Palettes, Blocks, Sprites and Level Maps

# What's the Purpose of the data Directory?

The data directory contains save states from Ecco the Dolphin and Ecco 2.
Currently, EccoLib does not have a means to decompress tiles and other data which are needed to assemble
Level Maps and Stage Sprites. To remedy this issue, a folder with save states is provided with all
the data already compressed. Support for decompressors will be added soon.

# Todo

- Add tile and block extraction support for Ecco the Dolphin.
- Add tile and level data extraction for Ecco 2: The Tides of Time.
- Add stage sprite extraction for Ecco PC.
