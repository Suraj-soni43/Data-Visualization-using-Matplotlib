# Data-Visualization-using-Matplotlib
Matplotlib is one of the most popular Python packages used for data visualization. It is a cross-platform library for making 2D plots from data in arrays. It provides an object-oriented API that helps in embedding plots in applications using Python GUI toolkits such as PyQt, WxPythonotTkinter. It can be used in Python and IPython shells, Jupyter notebook and web application servers also

Matplotlib graphs your data on Figures each of which can contain one or more Axes
Parts of a Figure
Figure
- The Figure keeps track of all the child Axes, a smattering of 'special' artists (titles, figure legends, etc)
Axes
- A given figure can contain many Axes, but a given Axes object can only be in one Figure. The Axes contains two (or three in the case of 3D) Axis objects
Axis
- These are the number-line-like objects. They take care of setting the graph limits and generating the ticks (the marks on the axis) and ticklabels
Artist
- Basically everything you can see on the figure is an artist (even the Figure, Axes, and Axis objects). This includes Text objects, Line2D objects, collections objects, Patch objects
- 
