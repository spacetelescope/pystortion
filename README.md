[![Build Status](https://travis-ci.org/spacetelescope/pystortion.svg?branch=primary)](https://travis-ci.org/spacetelescope/pystortion)
[![PyPI version](https://badge.fury.io/py/pystortion.svg)](https://badge.fury.io/py/pystortion)
[![PyPI - License](https://img.shields.io/pypi/l/Django.svg)](https://github.com/spacetelescope/pystortion/blob/primary/licenses/AURA.rst)
[![DOI](https://zenodo.org/badge/157456393.svg)](https://zenodo.org/badge/latestdoi/157456393)

> [!WARNING]
> This repository is no longer being maintained and has been archived
>
> For questions or issues, please submit at ticket at https://stsci.service-now.com/stars

# pystortion
Support for distortion measurements in astronomical imagers.

### Functionalities (work in progress)
* Classes to support fitting of bivariate polynomials of arbitrary degree
* Helper functions for crossmatching catalogs
 
### Installation  
`pip install pystortion`

Or, clone the repository:  
`git clone https://github.com/spacetelescope/pystortion`  
and install pystortion:  
`cd pystortion`  
`python setup.py install` or  
`pip install .`

This package was developed in a python 3.5 environment.   

### Example usage
For crossmatch, please see ``tests/test_crossmatch.py``
   

### Documentation
pystortion is documented at https://pystortion.readthedocs.io/  


### Citation
If you find this package useful, please consider citing the Zenodo record using the DOI badge above.
Please find additional citation instructions in [CITATION](CITATION). 



### License
This project is Copyright (c) Johannes Sahlmann STScI/AURA and licensed under
the terms of the Aura license. This package is based upon
the `Astropy package template <https://github.com/astropy/package-template>`_
which is licensed under the BSD 3-clause licence. See the licenses folder for
more information.
