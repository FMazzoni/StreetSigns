# StreetSigns

One can open the Colab Notebook Here:
<a href="https://colab.research.google.com/github/FMazzoni/StreetSigns/blob/main/BostonStreetSigns.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

This gives all street signs in Boston MA using OSNMX package. One can obtain street intersection data and derive a good estimate for all street signs within a given city. Bigger cities like Boston will have more inaccuracies and will need some cleaning after the fact. Accounting for "nan" streets and fixing boundary conflicts are potential issues. For smaller cities this can be enough to get a very close estimate. The data is gathered from OpenStreetMaps, the OSMNX and Plotly packages can very quickly obtain and visualize this data. 
