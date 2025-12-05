# Dependencies
You need a python env with:
* numpy
* scipy
* statsmodels
* pybind11
* Cython

Reading the raw data requires the bin2py module part of a package developed by Chichilnisky lab. To install this package:
1. Unzip artificial-retina-software-pipeline_DR.zip
2. cd to `{zip_folder}/utilities`
3. `pip install .`

Sometimes importing the installed bin2py gives errors right after installation. Try restarting the kernel or your system.