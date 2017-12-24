# songbook
A songbook written in TeX

## Usage

To input new song or delete an old one use file [songbook.tex](https://github.com/HudopCz/songbook/blob/master/songbook.tex).  
New song must be included in `poem` environment and after translation into PDF, the new song will be automatically included in songlist. 

To make a double-page document ready to print use file [mydoc2up.tex](https://github.com/HudopCz/songbook/blob/master/mydoc2up.tex). This file will transform the file `songbook.pdf` into the ready-for-print version.  
> **NOTE:** It is expected to use double sided printer, so each even page is upside down. To disable this function, uncomment the commented line with command `includepdf` and comment the uncommented one.
