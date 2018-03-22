texturestack
============
Widget for compositing textures, like virtual paper dolls.

"Virtual paper doll" is a technique for building sprite graphics used in, eg., the player avatar in Dungeon Crawl Stone Soup. Basically, you just put the sprites one on top of the other, and then move them around like they're one sprite. You might do this with plain Image widgets, but I found it awkward to manage the exact order of the various subwidgets, so I made this widget to handle them for me.

Includes two classes: TextureStack proper requires a list of kivy Texture objects; ImageStack is happy with a list of paths to loadable images.

In case of my death, I, Zachary Spector, wish for this code to be relicensed under [CC0](https://creativecommons.org/choose/zero/).