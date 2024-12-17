# lakes-bang

Some codes in follow up for the lakes datajam in Bangalore.

Work in progress.

[00]

[01_lake_example_bang_west.ipynb](01_lake_example_bang_west.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13Ndo2P9i1Uxp6jhfoIibQ0MxqEgNZ2Yl?usp=sharing)

This code shows how you can download Sentinel 2 data (10 meter resolution) for free  and create a True Color image, how you can compute a water index (Modified Normalized Difference Water Index (MNDWI)) and how you can create an animation out of this.
This code uses the Pystac library in Python. The advantage is that we can extract only the data we need. Moreover, we can avoid downloading the data (even the small part) on a hard disk as the computations happen in memory.  
