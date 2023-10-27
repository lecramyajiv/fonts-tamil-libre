Meera Inimai Font
================

Meera Inimai is a free licensed unicode font for Tamil Script. This is designed by Anilan N. G. with typography guidance from Hussain K. H. and linguistic guidance from A. K. M. Kutty. The opentype features of the font is compiled by Santhosh Thottingal.

Meera Inimai is a san-serif typeface. It is best used as a screen font for body text.
It is also useful for body text of printed pamphlets or single page designs.  
Usage of Meera Inimai can be thought of similar to Helvetica  and its variation Arial.  
Tamil characters are inherently vertically-elliptical and orthography of Roman glyphs 
of Meera Inimai are naturally based on this characteristics.  Even though similar in nature
Meera Roman glyphs differ from Helvetica but holds san-serif characteristics and 
smoothly sit with its Tamil glyphs.

The font is maintained by Swathanthra Malayalam Computing project. The source code is available at https://gitlab.com/smc/meera-tamil

Sample text rendered usingMeera Inimai

![Wikipedia Article about Tamil rendered using Meera Inimai](http://thottingal.in/fonts/MeeraTamil/samples/MeeraTamil-Wiki-2.png "Wikipedia Article about Tamil rendered using Meera Inimai")


License:
--------

This Font is licensed under the SIL Open Font License, Version 1.1. See http://scripts.sil.org/OFL

Building from source
--------------------
1. Install fontforge and python-fontforge
2. Install the python libraries required for build script:
    ```
    pip install -r tools/requirements.txt
    ```
3. Build the ttf, woff, woff2 files: 
   ``` 
   make
   ```