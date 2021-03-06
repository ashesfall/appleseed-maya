.. _label_nodes_2dtextures:

2D Textures
===========

.. cssclass:: table-striped table-condensed table-hover

=================== ==================
Nodes               Support Status  
=================== ==================   
Bulge               Supported
Checker             Supported
Cloth               Supported
File                Supported
Fluid Texture 2D    
Fractal             Supported
Grid                Supported
Mandelbrot          Supported [#]_
Mountain            Supported
Movie               Supported [#]_
Noise               Supported
Ocean               **WIP**
PSD File            Supported
Ramp                Supported
Substance           Supported [#]_
Substance Output    Unsupported [#]_
Water               Supported
=================== ==================

.. rubric:: Footnotes

.. [#] The *Mandelbrot2D* node is partially supported only.

.. [#] The *Movie* node requires `OIIO <https://github.com/OpenImageIO/oiio>`_ built with `FFMPEG <https://ffmpeg.org/>`_.

.. [#] In order to use `Substance <https://www.allegorithmic.com/>`_ materials, you need to use the Maya's *Substance* node image file output. This will be covered on its own simple :ref:`tutorial <label_tutorial_3>`.

.. [#] For now, The *Substance Output* is unsupported. This might change in the future.

