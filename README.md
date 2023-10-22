# inscape_lasertools2_plugin
Inscape plugin LaserTools2 based on original [lasertools](https://github.com/ChrisWag91/Inkscape-Lasertools-Plugin)
**********************************************************************
## Why was this done
When using the very wonderful lasertools plugin, it was inconvenient that for the production of the entire model it was necessary to divide the file into parts: what should be completely engraved, where only lines should be engraved, on the inner cutouts and on the outer contour. Changes were made to the original file to determine the order and type of work. The plugin configuration file has also been changed.

Made in order to get the control program file all_in_one.
***************************************************************************
## Remarks
If you do not use contours for filling - disable the "Add infill" option.

The "passes" option determines the number of passes only for internal and external contours to be cut.
**************************************************************************
## Intsruction
All instructions on [lasertools](https://github.com/ChrisWag91/Inkscape-Lasertools-Plugin)

**regarding changes**

Three specific colors are used, which you can define in the plugin dialog on the "Color" tab. The outline of the contour is painted in these colors. One color for the external contours that will be processed last, by default red **FF0000**. The color for filling closed contours - engravings, by default blue **0000FF**, is processed first. The color for engraving only outline outlines, by default green **00FF00**, is processed in the second turn or in the first if the option "Add infill" is disabled.

Any other colors are processed between the engraving and the outer contour. The number of passes option is also applicable to them.
