# python-geospatial

A collection of Python packages for geospatial analysis with binder-ready notebook examples. Launch the interactive notebook tutorials with **mybinder.org** or **binder.pangeo.io** test all the pre-installed Python pakcages for geospatial analysis.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/giswqs/python-geospatial/master)
[![Pangeo](http://binder.pangeo.io/badge.svg)](http://binder.pangeo.io/v2/gh/giswqs/python-geospatial/master)
[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Author: Qiusheng Wu (https://wetlands.io)

## Installation

It is highly recommended that you use the [conda](https://conda.io/docs/index.html) package manager to install all the requirements. You can either install [Miniconda](https://conda.io/miniconda.html) or the (larger) [Anaconda](https://www.anaconda.com/download/) distribution. It is also recommended that you install [git](https://git-scm.com/downloads) so that you can clone this GitHub reposiotry to your computer. 

Once conda and git are installed, the following commands will create a virtual Python environment named **pygeo** and install all the required packages:

```
git clone https://github.com/giswqs/python-geospatial.git
cd python-geospatial/binder/
conda env create -f environment.yml
source activate pygeo
ipython kernel install --user --name="pygeo"
```

## Tutorials

Launch the interactive notebook tutorials with **mybinder.org** or **binder.pangeo.io** now:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/giswqs/python-geospatial/master)
[![Pangeo](http://binder.pangeo.io/badge.svg)](http://binder.pangeo.io/v2/gh/giswqs/python-geospatial/master)

## Python Packages

This list of Python packages is adapted from the Python list of [Awesome Geospatial](https://github.com/sacridini/Awesome-Geospatial#python). All the listed Python packages have been pre-installed in the binder environment.   

### Geospatial Analysis

* [whitebox](https://github.com/giswqs/whitebox) :zap: - A Python package for advanced geospatial data analysis based on [WhiteboxTools](https://github.com/jblindsay/whitebox-tools).
* [lidar](https://github.com/giswqs/lidar) - lidar is a toolset for terrain and hydrological analysis using digital elevation models (DEMs).
* [pygis](https://github.com/giswqs/pygis) - pygis is a collection of Python snippets for geospatial analysis.
* [ArcGIS Python API](https://developers.arcgis.com/python/) - Esri's Python library for working with maps and geospatial data, powered by web GIS.
* [dask-rasterio](https://github.com/dymaxionlabs/dask-rasterio) - Read and write rasters in parallel using Rasterio and Dask.
* [earthengine-api](https://anaconda.org/conda-forge/earthengine-api) :zap: - The Earth Engine Python API allows developers to interact with Google Earth Engine.
* [EarthPy](https://github.com/earthlab/earthpy) - EarthPy is a python package that makes it easier to plot and work with spatial raster and vector data. 
* [Fiona](http://toblerity.org/fiona/) :zap: - For making it easy to read/write geospatial data formats.
* [GDAL](https://anaconda.org/conda-forge/gdal) - The Geospatial Data Abstraction Library for reading and writing raster and vector geospatial data formats. 
* [geeup](https://github.com/samapriya/geeup) - Simple CLI for Earth Engine Uploads.
* [geojson-area](https://github.com/scisco/area) - Calculate the area inside of any GeoJSON geometry. This is a port of Mapbox's geojson-area for Python.
* [geojsonio](https://github.com/jwass/geojsonio.py) - Open GeoJSON data on geojson.io from Python. 
* [GeoPandas](https://github.com/geopandas/geopandas) - Python tools for geographic data.
* [GIPPY](https://github.com/gipit/gippy) - Geospatial Image Processing for Python.
* [gpdvega](https://github.com/iliatimofeev/gpdvega) - gpdvega is a bridge between GeoPandas and Altair that allows to seamlessly chart geospatial data.
* [mapboxgl-jupyter](https://github.com/mapbox/mapboxgl-jupyter) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook.
* [networkx](http://networkx.github.io/) - To work with networks.
* [OSMnet](https://github.com/UDST/osmnet) - Tools for the extraction of OpenStreetMap street network data.
* [pandana](https://github.com/UDST/pandana) - Pandas Network Analysis - dataframes of network queries, quickly.
* [Peartree](https://github.com/kuanb/peartree) - Peartree: A library for converting transit data into a directed graph for network analysis.
* [pygdal](https://pypi.org/project/pygdal/) - Virtualenv and setuptools friendly version of standard GDAL python bindings.
* [pymap3d](https://github.com/scivision/pymap3d) - Python 3D coordinate conversions for geospace ecef enu eci.
* [Pyncf](https://github.com/karimbahgat/pyncf) - Pure Python NetCDF file reading and writing.
* [PyProj](https://github.com/jswhit/pyproj) - For conversions between projections.
* [PySAL](http://pysal.readthedocs.io/en/latest/) - For all your spatial econometrics needs.
* [PyShp](https://code.google.com/archive/p/pyshp/) - For reading and writing shapefiles.
* [rasterio](https://github.com/mapbox/rasterio) :zap: - rasterio employs GDAL under the hood for file I/O and raster formatting.
* [rasterstats](https://github.com/perrygeo/python-rasterstats/) - Python module for summarizing geospatial raster datasets based on vector geometries.
* [rio-cogeo](https://github.com/mapbox/rio-cogeo) - CloudOptimized GeoTIFF creation plugin for rasterio.   
* [rio-color](https://github.com/mapbox/rio-color) - Color correction plugin for rasterio.
* [rio-hist](https://github.com/mapbox/rio-hist) - Histogram matching plugin for rasterio.
* [rio-tiler](https://github.com/mapbox/rio-tiler) - Get mercator tile from landsat, sentinel or other AWS hosted raster.
* [Rtree](http://toblerity.org/rtree/) - For efficiently querying spatial data.
* [sentinelhub](https://github.com/sentinel-hub/sentinelhub-py) - Download and process satellite imagery in Python scripts using Sentinel Hub services.
* [sentinelsat](https://github.com/sentinelsat/sentinelsat) - Search and download Copernicus Sentinel satellite images.
* [Shapely](https://pypi.python.org/pypi/Shapely) - Manipulation and analysis of geometric objects in the Cartesian plane.
* [ts-raster](https://github.com/adbeda/ts-raster) - ts-raster is a python package for analyzing time-series characteristics from raster data. 
* [urbansim](https://github.com/UDST/urbansim) - New version of UrbanSim, a platform for modeling metropolitan real estate markets.
* [USGS API](https://github.com/kapadia/usgs) - USGS is a python module for interfacing with the US Geological Survey's API.
* [Verde](https://github.com/fatiando/verde) - Verde is a Python library for processing spatial data and interpolating it on regular grids.
* [xarray](http://xarray.pydata.org/en/stable/) - An open source project that aims to bring the labeled data power of pandas to the physical sciences.

### Mapping/Plotting

* [basemap](https://github.com/matplotlib/basemap) - Plot on map projections (with coastlines and political boundaries) using matplotlib.
* [bokeh](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python.
* [Cartopy](http://scitools.org.uk/cartopy/) - A library providing cartographic tools for python for plotting spatial data.
* [Descartes](https://pypi.python.org/pypi/descartes) - Plot geometries in matplotlib.
* [geoplot](https://github.com/ResidentMario/geoplot) - geoplot is a high-level Python geospatial plotting library.
* [geopy](https://github.com/geopy/geopy) - geopy is a Python 2 and 3 client for several popular geocoding web services.
* [folium](https://github.com/python-visualization/folium) - Python Data, Leaflet.js Maps.
* [matplotlib](http://matplotlib.org/) - Python 2D plotting library.
* [mplleaflet](https://github.com/jwass/mplleaflet) - mplleaflet converts a matplotlib plot into a webpage containing a pannable, zoomable Leaflet map.
* [pyWPS](http://pywps.org/) - An implementation of the Web Processing Service standard from the Open Geospatial Consortium. 
* [pyCSW](http://pycsw.org/) - Fully implements the OpenGIS Catalogue Service Implementation Specification.
* [ipyleaflet](https://github.com/jupyter-widgets/ipyleaflet) - A Jupyter / Leaflet bridge enabling interactive maps in the Jupyter notebook.

### Deep Learning

* [label-maker](https://github.com/developmentseed/label-maker) - Data Preparation for Satellite Machine Learning.
* [label-maker-binder](https://github.com/giswqs/label-maker-binder/pulse) - Using label-maker in an interactive notebook on the cloud.
* [Keras](https://keras.io/) - Keras is a high-level neural networks API capable of running on top of TensorFlow, CNTK, or Theano.
* [TensorFlow](https://www.tensorflow.org/) - TensorFlow is an open source software library for numerical computation using data flow graphs.

### General Python

* [dask](https://github.com/dask/dask) - Dask is a flexible parallel computing library for analytics. 
* [imageio](https://imageio.github.io/) - imageio provides an easy interface to read and write a wide range of image data.
* [Mahotas](https://github.com/luispedro/mahotas) - Mahotas is a library of fast computer vision algorithms operating over numpy arrays.
* [NumPy](http://www.numpy.org/) - NumPy is the fundamental package for scientific computing with Python.
* [Pandas](http://pandas.pydata.org/) - Open source library providing high-performance, easy-to-use data structures and data analysis tools.
* [scikit-image](http://scikit-image.org/) - Scikit-image is a collection of algorithms for image processing.
* [scikit-learn](https://github.com/scikit-learn/scikit-learn) - scikit-learn is a Python module for machine learning built on top of SciPy.
* [SciPy](https://github.com/scipy/scipy) - SciPy is open-source software for mathematics, science, and engineering.
* [Statsmodels](http://statsmodels.sourceforge.net/) - Python module that allows users to explore data, estimate statistical models, and perform statistical tests.

## Cloud Computing Platforms

* [Google Earth Engine](https://earthengine.google.com/) :zap: - Planetary-scale geospatial analysis for everyone.
* [Pangeo](http://pangeo.io/) - A community platform for Big Data geoscience.
* [Geospatial Big Data Platform (GBDX)](https://platform.digitalglobe.com/gbdx/) - Cloud computing platform from Digital Globe.
* [Radiant Earth](https://www.radiant.earth/) - Open-source cloud computing infrastructure for geospatial analysis.
* [Radiant MLHub](https://www.mlhub.earth/) - Open Repository for Geospatial Training Data.
* [Sentinel Playground](https://www.sentinel-hub.com/) - Cloud platform for analysis of Sentinel-2A and B and so on.
* [Vane: Query Language](https://owm.io/vaneLanguage) - Creating Basemaps from different satellite images with online processing and computing.

## References

* [Awesome-Geospatial](https://github.com/sacridini/Awesome-Geospatial)
* [SpatialPython](https://github.com/SpatialPython/spatial_python)
* [python-geospatial-ecosystem](https://github.com/loicdtx/python-geospatial-ecosystem)
* [Automating-GIS-processes](https://github.com/Automating-GIS-processes/2018)
* [Geo-Python](https://github.com/geo-python/2018)
* [scipy2018-geospatial-data](https://github.com/geopandas/scipy2018-geospatial-data)
* [Geospatial_Data_with_Python](https://github.com/SocialDataSci/Geospatial_Data_with_Python)
* [Essential geospatial Python libraries](https://medium.com/@chrieke/essential-geospatial-python-libraries-5d82fcc38731)
* [Geo-spatial analysis with Python](https://medium.com/@lisa.mitford/geo-spatial-analysis-with-python-fdddd69eebea)
* [From Analysis Ready Data to Analysis Engines and Everything in between](https://medium.com/@samapriyaroy/from-analysis-ready-data-to-analysis-engines-and-everything-in-between-676d98792d2e)
