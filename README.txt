###################################################
# MoinMoin Kaijin (japanese “ash and dust”) Theme #
###################################################

This theme is based on the “modern” theme, copyrighted 2003-2005 by 
Nir Soffer and Thomas Waldmann.

The FamFam Silk Icons are licenced under a Creative Commons Attribution 2.5
License (http://creativecommons.org/licenses/by/2.5/).

Kaijin is licenced under a Creative Commons Attribution-Noncommercial-Share
Alike 2.0 Germany Licence (http://creativecommons.org/licenses/by-nc-sa/2.0/de/deed.en).

This Theme was created by Stefan Imhoff (http://stefanimhoff.de/). 

No warranty!

Installation
============

1. Place the folder `kaijin` with its contents in your htdocs directory:

    /htdocs/kaijin/css/…
                 /images/…

2. Place the file `kaijin.py` in the theme directory:

    /MoinMoin/theme/kaijin.py

Optional
========

If you would like to use some FamFam Silk Icons instead of the modern Icons
you need to do following steps:

3. Replace the folder `img` in the `kaijin` folder with the `img` folder from
`OPTIONAL`.

    /htdocs/kaijin/img

4. Copy `config.py` to:

    /MoinMoin/config.py

5. Copy `__init__.py` to:

    /MoinMoin/theme/__init__.py

Customizing
===========

If you want to customize this theme, most action takes place in `screen.css`.

To increase the font-size replace `body { font-size: 75%; }` with your size. 
75% is 12px base font size. 14px would be 87.5% base font size.
