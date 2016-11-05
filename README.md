# A Simple d3-based Jupyter Widget

Wishing to become proficient at creating Jupyter notebook and lab interactive widgets,
I studied the excellent documentation offered by the jupyter/ipywidgets project:

  https://github.com/ipython/ipywidgets

and the detailed, incremental presentation provided here:

  http://ipywidgets.readthedocs.io/en/latest/examples/Widget%20Custom.html

I then tried to move up to more advanced examples (quoting here directly from the README):

<hr>
Examples of custom widget libraries built upon ipywidgets are

- [bqplot](https://github.com/bloomberg/bqplot) a 2d data visualization library
  enabling custom user interactions.
- [pythreejs](https://github.com/jovyan/pythreejs) a Jupyter - Three.js wrapper,
  bringing Three.js to the notebook.
- [ipyleaflet](https://github.com/ellisonbg/ipyleaflet) a leaflet widget for Jupyter.

<hr>

I found these to be rather large and (for me at the time) rather confusing.   These
are big, rich widgets, worth emulating, but perhaps not the easiest examples for a
novice widget programmer to learn form:

  - ipyleaflet:  500 lines of python, 800 lines of javascript
  - pqplot: 4300 lines of python, 15000 lines of javascript
  - pythree: 800 lines of python, 2000 lines of javascript

So, with helpful advice from the jupyter-js-widget development team, I embarked upon
an intermediate widget "Simple-d3-circles" which I present here.  It has only 70 lines of python,
143 lines of javascript, and demonstrates the features I most wanted to understand.

I present it in three forms:

 - self-contained within a single jupyter notebook, using javascript "magic"
 - following the [jupyter widget cookiecutter](https://github.com/jupyter/widget-cookiecutter),
   as an installable notebook extension (pending)
 - with whatever modifications will be needed for it to function as a jupyter lab widget (pending)

I welcome suggestions.
