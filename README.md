# Geosoft-Grid-to-Raster
Convert geosoft grid to an open format for useability

## Data
- Gravity grid from Natural Resources Canada
	- http://gdr.agg.nrcan.gc.ca/gdrdap/dap/search-eng.php
	
## Tools
- Mira Geoscience Geoscience Analyst
	- https://mirageoscience.com/mining-industry-software/geoscience-analyst/
- Geoh5py python package
	- https://geoh5py.readthedocs.io/en/stable/
- Rioxarray : goto tool for high level abstracted raster wrangling
	- https://corteva.github.io/rioxarray/stable/
- Geosoft 
	- Viewer: https://www.seequent.com/products-solutions/geosoft-viewer/
		- For access to data conversion
	- Python package: https://pypi.org/project/geosoft/

## Issues
Need Geosoft/login access to use the converter
- Free to sign up to get their viewer, but you can't export
- Geosoft has their own python package, so you could do it this way, however it is much more complicated
	- Use this if you use their gdbs or other stuff and have it already

## Examples
Thomas Martin has a version of going to geoh5py via xarray and back here
	- https://github.com/MiraGeoscience/geoh5py/blob/6b3da659444fcd73323d8f36dba09312e841b7b1/examples/geoh5py_xarray_testing_and_back.ipynb

# Summary
All of the above is a good example of why government data providers should also provide a version in an open format.

e.g. We don't want a future where we have to do this routinely to recover science: - 
- https://github.com/RichardScottOZ/Geosoft-Grid-Reverse-Engineering

## note Loop Project here
- https://github.com/Loop3D/geosoft_grid
