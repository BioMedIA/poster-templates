# About this template

Customisable conference poster template with BioMedIA logo and Imperial 
colour style.

Adapted from Kevin Keraudren's template from the internal BioMedIA pages
and from baposter/examples/ECCS2011/poster.tex 

The template by Kevin Keraudren has been slightly modified to feature the biomedia 
logo and have a colour style consistent with the Imperial College branding. 
Also the background of the boxes is now white which makes it easier to include
non-rasterised figures that by default have a white background. Lastly, I tried
to make it as easy as possible to customise the colours of everything. 
Kevin's original code has some cool tikz figure magic which I didn't use. 
His template is still available on the internal BioMedIA pages. 

Christian Baumgartner (c.f.baumgartner@gmail.com)

Date: 11. October 2016

# Visual example

![](thumbnail.png)

# Original README by Kevin:

The present poster has been written using the "baposter" Latex class available at:
http://www.brian-amberg.de/uni/poster/

The two reasons why this class has been chosen is that:
  - it is the first result returned by a Google Search for "latex poster"
   (02/07/2012)
  - it is documented enough, with really nice examples.

The full (original) package is in "baposter.tar.bz2". It has been slightly modified to fit
the BioMedia PPT template:
  - removing the option "cmyk" to the package "xcolor" to get the right colors
    (see BUG.txt)
  - centering the title for the boxes.

See "patch.diff" for those modification (a fix for the grid is proposed as
well).

It is important to to be aware that almost everything in baposter is made with
Tikz/Pgf (http://www.texample.net/tikz/). The whole poster is a
"tikzpicture". It does not prevent you to place other tikzpictures on your
poster, but as embedded pictures inherit the style of their parents, you might
have to reset some parameters to their default values to have what you expect,
for instance "inner sep" and "outer sep". See "diagramme.tex" for an example,
and refer to the Tikz/pgf manual for help.

Happy coding!

Kevin Keraudren,
kevin.keraudren10@imperial.ac.uk
02/07/2012

