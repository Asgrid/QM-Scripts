# QM Scripts

## Flipper
Flips an entire dungeon horizontally, vertically, or both.

## Image to dungeon
Converts a PNG into a dungeon floor, with 3 modes of operation:
* **Transparency**: Places floor according to the alpha value of a pixel is higher than the specified cut-off point. Output can be inverted.
* **Brightness**: Places floor when the brightness of a pixel is higher than the specified cut-off point. Output can be inverted.
* **Palette**: A tile type is selected for each color present in the image.

## Fragment finder
Shows the location of all fragments being used inside a dungeon, across all floors.
