.. role::  raw-html(raw)
    :format: html


4. Advanced Raster Data Processing
####################################

The assignment can be accessed and submitted via GitHub classroom. :raw-html:`&rarr;` `Accept Assignment 3: Advanced Raster Data Processing <https://classroom.github.com/a/DjY4tXxy>`_

This assignment contains **2 Jupyter Notebooks**. The first one (12-introduction-rasterio.ipynb) is just a short introduction to the raster data processing using the rasterio package. The second notebook (13-Advanced-Raster-Data-Analysis.ipynb) is the more important one, since it contains the exercises.

.. important::

	It seems like the sat-search package needs Python 3.7 to work properly. Therefore, please set up a **new conda environment with python 3.7** to do the assignment. It is important that you **install sat-search version 0.2.3**.

  .. code::

    $ conda create -n advgeo37 python=3.7 rasterio jupyter matplotlib
    $ conda activate advgeo37
    $ pip install sat-search==0.2.3
