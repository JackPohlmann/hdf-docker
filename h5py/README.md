## Docker image with HDF5 library, and h5py

## Ingredients:

* HDF5-1.10.5 Library
* Python 3.7.3
* Numpy
* h5py

## Major differences

* H5py is installed using pip
* Fortran is enabled in the hdf5 build

## Instructions

* Can comment out the `make check` and `make check-install` lines for faster compilation.
