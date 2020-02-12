# Python plotter for xplot (.xpl) files

## xplot_plotly_combo.ipynb
I've simply adjusted what was written in https://github.com/tohojo/xplot.py 
into a plotly syntax instead of matplotlib and made it a jupyter
notebook. I've likely done this very poorly, but it seems to
work...

## xplot.py (Original)
This is a basic implementation of (a subset of) the xplot .xpl format
using matplotlib. It is specifically targeted at drawing TCPTrace time
sequence graphs.

The native xplot is of course a lot faster than matplotlib, but this
makes it possible to take full advantage of matplotlib's styling and
exporting features.

Only tested on Python 3.5 and matplotlib 1.5. May eat your children;
will definitely eat your RAM (a 600 second time sequence diagram eats
~800 MB of RAM).

## License
License: GPLv3.

## Usage
```
python xplot.py <filename>.xpl
```
