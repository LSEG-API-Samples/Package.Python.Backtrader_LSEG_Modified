# Package.Python.Backtrader_LSEG_Modified
We are contributing this minor fix back to the Backtrader package community through making the source code available here. 

Library: Python backtesting framework for trading strategies (matplotlib-based plotting).
Source: GitHub - mementum/backtrader at e22205427bc0ac55723677c88573737a172590ef, License GPL-3.0.
What we changed: Removed the obsolete from matplotlib.dates import warnings and imported the needed symbols directly (removed in matplotlib 3.3.0+). 
Where we changed it: plot/locator.py
Type: Bug fix / compatibility fix, minor. No new feature.
Objective: Stop backtrader crashing on import with modern matplotlib.

License: GPL-3.0 
