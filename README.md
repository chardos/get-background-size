Background-Size
===============

A JQUERY plugin to get the size of a background-image applied by CSS. Returns the height and width of the original image (doesn't take into account background-size CSS property).


How to use it:
--------------
Call it to a specified image, with width or height as an argument.

E.G.
var width = $('img').backgroundSize('width');
var height = $('img').backgroundSize('height');