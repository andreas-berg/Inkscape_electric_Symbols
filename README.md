# Inkscape_Symbols
Symbols for electric circuits. Contains block diagrams and symbols.
# Getting started
 * Download and install [Inkscape](https://inkscape.org/).
 * Download the latest version of [Inkscape_Symbols_All.svg](https://github.com/upb-lea/Inkscape_electric_Symbols/blob/master/Inkscape_Symbols_All.svg).

After doing so, open Inkscape_Symbols_All.svg and copy the symbols of interest to your inkscape worksheet.

If you want to recieve updates, clone this repository by using [git](https://git-scm.com/):
```
cd /Documents/Folder/of/Interest   
git clone git@github.com:upb-lea/Inkscape_electric_Symbols.git
```
To update the symbols library, use
```
git pull
```
Click the `watch` button to receive update notifications.

# Overview
![Library overview](/Sources/Overview.png)

# Using the library
* Open Inkscape_Symbols_All.svg and copy the symbols of interest to your inkscape sheet.
* __Always draw on the grid!__
* Grid on/off by `#`-key
* Recommended way to move objects: drag them next to a endpoint (it makes a difference where you touch the component), to make sure to work on the rough grid (recommended, not the fine one).
* Recommended way to modify wires: mark line (`F1`-key for mark-tool), press `F2`-key, click on the end of the line so that the fixed point becomes red, now you can move this point.     
* Recommended way to rotate the component: click 2 times on the component until the turning arrows are visible. Turn the component while keeping the `ctrl` key pressed.     
* Recommended way to mirrow components: press `v` (vertical) or `h` (horizontal).
* Recommended way to changes text: click on text, press `t` for editing mode.
* Change color of area: mark area, click on Color.
* Change color of line: mark line, `shift` + click on Color.
* Colors used in this template: `GNOME HIG Colors`.  
* Recommended snapping settings, can be set top right inside Inkscape       
![Recommended Snapping Settings](/Sources/snapping_settings.png)

![How to use the library](/Sources/Using_Symbols.gif)


# Examples
### Example Boost Converter
![Boost converter](/Sources/Example_Boost_Converter2.png)
### Example Dual Active Bridge Converter
![Dual active bridge](/Sources/Example_DAB.png)
### Example Switching Behaviour
![Switching behaviour](/Sources/Example_Switching_behaviour.png)

# Set drawing size
The best thing to do before you start drawing is to consider where the drawing will be used. For example, if the drawing will be used on an A4 (210 mm width) paper with 2.5 cm margins on each side, set the drawing width within Inkscape to 160 mm. For two-column text, use 80 mm image width. This way you will get good drawing results relative to the written text. 

# Use high quality vector graphics inside your documentation software
Follow the steps to use vector graphics in your documentation software. The vector graphics are rendered in very good image quality, unlike conventional png images. However, each program has its own characteristics and requires a different file format. 
### LaTeX
 * In Inkscape: `File` -> `Save Copy` -> `yourdocument.pdf`. 
 * Include this `pdf` in your LaTeX document.

### LibreOffice
Drag and drop the Inkscape `.svg`-file into your writer/impress document.

### MS Office
 * In Inkscape: `File` -> `Save Copy` -> `yourdocument.emf`. 
 * Include this `emf`-file in your Word/PowerPoint document.

# Bug Reports
Please use the issues report button within github to report bugs.

# Contributing to this repository
For new symbol requests, please open an issue with a single example drawing attached. I will then redraw the symbol, modify it if necessary to fit with the other symbols, and add it to the library. 
* Please use lines with rounded ends.
* Always draw on the grid (rough or fine).
* Points of components to which a wire can be connected must lie on the rough grid.
* Use standard line width.

# Changelog
Find the changelog [here](https://github.com/upb-lea/Inkscape_electric_Symbols/blob/master/CHANGELOG.md).

# Troubleshooting
Make sure that you run the latest version of [Inkscape](https://inkscape.org/).
