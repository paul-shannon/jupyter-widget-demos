# A Simple d3-based Jupyter Javascript Interacctive Widget

Wanting to become proficient at creating Jupyter notebook and lab interactive widgets
I studied, and learned a lot from the documentation offered here:

  https://github.com/ipython/ipywidgets

and the detailed, incremental presentation provided here:

  http://ipywidgets.readthedocs.io/en/latest/examples/Widget%20Custom.html

The next step seemed to be to progress to (quoting directly from the README):

## More advanced examples

Examples of custom widget libraries built upon ipywidgets are

- [bqplot](https://github.com/bloomberg/bqplot) a 2d data visualization library
  enabling custom user interactions.
- [pythreejs](https://github.com/jovyan/pythreejs) a Jupyter - Three.js wrapper,
  bringing Three.js to the notebook.
- [ipyleaflet](https://github.com/ellisonbg/ipyleaflet) a leaflet widget for Jupyter.

However, when I looked at those examples, I found them to be more complicated
that I could, at the time, comprehend

  - ipyleaflet:  500 lines of python, 800 lines of javascript
  - pqplot: 4300 lines of python, 15000 lines of javascript
  - pythree: 800 lines of python, 2000 lines of javascript

With helpful advice from the jupyter-js-widget development team, I embarked up on
an intermediate widget, presented here: Simple3dCircle.  It has only 70 lines of python,
and 143 lines of javascript.  I present it in three forms:

 - self-contained within a single jupyter notebook, using javascript "magic"
 - following the [jupyter widget cookiecutter](https://github.com/jupyter/widget-cookiecutter),
   as an installable notebook extension (pending)
 - with whatever modifications are needed to function as a jupyter lab widget (pending)

I welcome suggestions and critique.
