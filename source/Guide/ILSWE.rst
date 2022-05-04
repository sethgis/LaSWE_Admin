
.. figure:: ../_static/Images/wind.png


*******************************************************************************
Updating the Index of Land Susceptibility to Wind Erosion (ILSWE) Output
*******************************************************************************
ILSWE is the final output after intergration of all other wind erosion factors.
After computing ILSWE output,the output is reclassified into 5 descrete classes applying quantile classification procedures, and later uploaded through the django admin. The classification applied can be accessed through QGIS on raster classification and symbolization functionalities. Once the raster is ready, the system manager can update the dataset, with proper tagging by giving proper names, years and data pixel resolution just like with other outputs. The process is illustrated below.


.. figure:: ../_static/Images/ilswe.png

After adding the raster successfully,the system manager should click the save button, clear cache in order for the updates to reflect on the user interface. The resolution should always be a maximum of 100 meterS, this is considered as the minimum processing resolution during factor computation.

.. figure:: ../_static/Images/wind.png



.. toctree::
   :maxdepth: 3


