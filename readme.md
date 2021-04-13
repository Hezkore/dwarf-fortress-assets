# Dwarf Fortress Assets

## Tileset
**'hezkore.png'** is a 16x16 tilset based on [Kenran](http://dwarffortresswiki.org/index.php/File:Kenran.png), [Nice curses](http://dwarffortresswiki.org/index.php/File:Nice_curses_12x12.png) and [Yayo tunur](http://dwarffortresswiki.org/index.php/File:Yayo_tunur_1040x325.png) with my own edits and additions.

![tileset preview](https://github.com/Hezkore/Dwarf-Fortress-Assets/blob/master/hezkore.png?raw=true)

## Colors
**'colors.txt'** provides softer colors than the default theme. \
The colors are a bit more washed out than the original colors, but still provides good contrast between all of the different shades.

## How do I use these?
GitClone *(recommended)* or download this repository.
* Tilset
	* Symlink *(recommended)* or extract **'hezkore.png'** to your **'data/art/'** folder
	
	* Open your **'data/init/init.txt'** file
		* If `[GRAPHICS:NO]` then:
			* Change `[FONT:curses_640x300.png]` to `[FONT:hezkore.png]`
			* Change `[FULLFONT:curses_800x600.png]` to `[FULLFONT:hezkore.png]
		* If `[GRAPHICS:YES]` then:
			* Change `[GRAPHICS_FONT:curses_square_16x16.png]` to `[GRAPHICS_FONT:hezkore.png]`
			* Change `[GRAPHICS_FULLFONT:curses_square_16x16.png]` to `[GRAPHICS_FULLFONT:hezkore.png]`

* Colors
	* Remove your **'data/init/colors.txt'** file
	
	* Symlink *(recommended)* or extract **'colors.txt'** to **'data/init/colors.txt'**

## New versions / updating
If you've GitCloned this repository and symlinked the files, then all you have to do is `Git Pull` to download the newest versions of the graphics and colors.