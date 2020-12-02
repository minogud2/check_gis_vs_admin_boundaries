# check_gis_vs_admin_boundaries
Algorithms to check GPS locations vs geojson admin boundaries. 

Check Administrative Levels Based on GPS Coodinates¶
Many surveys collect GPS coordinates, as well as administrative boundaries like Region, Zone or District. However, admin boundaries can change over time, and/or the surveyor could make a mistake during data entry and mark the boundaries incorrectly.

As such, there is a need to cross check the GPS coordinates against the official admin boundaries and/or regularly update the data based on new boundaries-or new official shape files from Governments.

The algorithms below show how to cross check GPS coordinates against geojson files. It requires the following python packages:

pandas, 2. numpy and 3. geopandas.
Although geopandas is realtively easy to install via anaconda, it can be challenging with pip. It requires the installation of Gdal and Fiona in advance of attempting to pip install geopandas. You may need to download the .whl binaries directly. You can download from: https://www.lfd.uci.edu/~gohlke/pythonlibs/
