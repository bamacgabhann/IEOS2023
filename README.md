# IEOS2023

Welcome to the IEOS 2023 Introduction to Geospatial Python workshop.

The intention of this workshop is not so much to _teach_ you Python; but rather to show you some of what is possible for geospatial data in Python. So when the workshop is over, it won't be so much that you _know_ Python: more that you're ready to learn, and have an idea of what you need to learn to be able to do what you want to do with it. We all have our own projects and priorities - hopefully here you'll be pointed in the right directions to work on those. As Donald Rumsfeld said, _"As we know, there are known knowns; there are things we know we know. We also know there are known unknowns; that is to say we know there are some things we do not know. But there are also unknown unknowns—the ones we don't know we don't know."_ Our assumption here is that geospatial Python is an unknown unknown to you: we might not be able to turn it into a known known, but we can at least make it a known unknown.

So in this workshop, we'll introduce you to the basics of the Python language. We'll introduce you to some of the libraries which can be used for geospatial data - _shapely_ for geometry, _pyproj_ for projections, _geopandas_ for tables of geospatial and attribute data, _movingpandas_ for moving objects, _Fiona_ for file formats, _osmnx_ for working with OpenStreetMap data, _GDAL_/_Rasterio_ for raster data, and _Folium_ and _EOmaps_ for data visualisation. We'll drag some libraries along the way which aren't geospatial in themselves, but which are key to data processing and visualisation - such as _matplotlib_ for plots, and _numpy_ for maths. And if we have time, we might point you in a few other directions too.

## 0. Getting Started with Python
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bamacgabhann/IEOS2023/main?labpath=ieos2023%2F0_Getting_started_with_python.ipynb)
 - Git and github for Version Control  
 - conda, pyenv, and poetry for Virtual Environments and Package Management  
 - VS Code, PyCharm, Spyder, and Jupyter Notebooks for writing code  
  
## 1. The Python Language
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bamacgabhann/IEOS2023/main?labpath=ieos2023%2F1_The_Python_Language.ipynb)
 - Modules  
 - Variables  
 - functions  
 - scope  
 - classes  
 - flow  
  
## 2. Data types
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bamacgabhann/IEOS2023/main?labpath=ieos2023%2F2_Data_Types.ipynb)
 - strings (str)  
 - integers (int)  
 - floating point variables (float)  
 - tuples  
 - lists  
 - dictionaries  
 - binary (0b)  
 - hex (0x)  
 - 8/32/64-bit  
  
## 3. Vector data
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bamacgabhann/IEOS2023/main?labpath=ieos2023%2F3_Vector_data.ipynb)
 - shapely for points, lines, and polygons  
 - geopandas for attribute data  
 - pyproj for projections  
 - Fiona for reading and writing files  
 - vector geoprocessing with geopandas, osmnx, and movingpandas  
  
## 4. Raster data
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bamacgabhann/IEOS2023/main?labpath=ieos2023%2F4_Raster_data.ipynb)
 - reading raster data with GDAL/Rasterio  
 - writing raster data  
 - processing raster data  
 - working with bands  
 - combining vector and raster data  
 - raster data in the cloud (geemap) (info only)  
 - EOmaps for visualising and interpreting EO data (info only)  

(The Raster exercise is minimally adapted from the Raster tutorial in *Michael Dorman's _<a href='https://geobgu.xyz/presentations/p_2023_ogh/02-raster.html'>Working with Spatial Data in Python</a>_*.)
