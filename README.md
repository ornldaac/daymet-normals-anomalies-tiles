# Python - Daymet Jupyter Notebook Tutorial

This is a repository containing a Jupyter Notebooks using the *Pydap* library to work with [Daymet](https://daymet.ornl.gov/) data from a THREDDS server.

## Prerequisites
To run these notebooks locally, you will need to install the following software.

* Python

Python libraries:
* pydap
* numpy
* matplotlib
* iPython
* ipywidgets
* jupyter

## Installing
For scientific computing, [anaconda](https://conda.io/docs/user-guide/install/index.html) is recommended as it come pre-installed with packages such as *numpy*, *iPython*, and *matplotlib*.

Most operating systems, however, come with Python. To install the necessary python libraries, you can copy the [requirements.txt](https://raw.githubusercontent.com/kvgarimella/daymet-tutorials/master/requirements.txt) from this repository and run:

```bash
pip install -r requirements.txt
```
## Tutorial
In [this notebook](https://github.com/kvgarimella/daymet-tutorials/blob/master/Daymet_Normals_Anomalies_Agg_Tiles.ipynb), the Daymet data is aggregated by tile. This means
that the data for all years for one variable is stored in one netCDF4 file.
