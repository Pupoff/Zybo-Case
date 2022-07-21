# Zybo case for Zybo Z7-10 and Zybo Z7-20

**GLOBAL_VIEW.stl**: Just a preview, not intended to be printed  
**ZyboStage.stl**: To fit the Zybo in. Jacks connector and XADC are accessible.  
**GeneralPurposeStage_noHoles.stl**: Generic box to fit anything. No holes!  
**GeneralPurposeStage_gpioHoles.stl**: Same as *GeneralPurposeStage_noHoles*, with two big square holes to fit a "GPIO tile"  
**bottom_support.stl**: The bottom lid  
**bottom_rubber.stl**: Just a cover for *bottom_support*, print it in flex to have a non-slip surface  
**head_fast.stl**: Top lid with no accessible controller  

**/Tag**: Contains the labels to be placed on each slice.
**/GPIO_ADAU**: Contains the "GPIO tile" for the ADAU codecs (same for ADAU1777 and ADAU1787)

## How to use

-Print *ZyboStage.stl*, *bottom_support.stl*, *bottom_rubber.stl*,*head_fast.stl*, and as many *GeneralPurposeStage_gpioHoles.stl* as needed.  
  
-For each tag you want, print *Back_<myTag>.stl* and *<my_tag>.stl*  
  
-Print the needed "GPIO tiles"  

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
