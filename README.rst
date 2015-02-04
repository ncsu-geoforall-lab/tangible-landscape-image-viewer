Tangible Landscape Image Viewer
===============================

Simple image viewer designed to be used with Tangible Landscape system.

Tangible Landscape Image Viewer provides very limited but specialized
functionality. It is possible to zoom the image very smoothly and the
image is resized when the window is resized.

The application is an application for web browser, i.e. application
is an HTML5 web page which has to be open in the web browser.

It's trying to solve the problems with various image viewers, especially
on MS Windows, such as missing fine zoom or GIF support. For other
platforms the default image viewer, such as *eye* on Ubuntu 12.04, is
usually enough. Also sometimes the web browser itself can also provide
enough functionality, but zooming is usually limited.


Usage
-----

Run from command line or put one of these commands to some desktop
shortcut:

::

    chromium-browser --app=path/to/tangeom-image.html

::

    firefox path/to/tangeom-image.html


Controlling the image
---------------------

Use mouse wheel to zoom. Use left click to stretch the image to the
whole window (which is the default).


License
-------

The BSD 2-Clause License


Authors
-------

Vaclav Petras, wenzeslaus gmail com, NCSU OSGeoREL
