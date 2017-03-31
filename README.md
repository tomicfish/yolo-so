![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

# Build Darknet lib
Use Command 

	make lib -j8

this will build Darknet to libdarknet.so, and copy it to ./depoly
 - if "dlopen is undefined", gcc with -ldl

# Port darknet to new machine
### Deploy Environment settings
 - mkl
 - opencv ( if needed )

### Run from source Environment settings

 - mkl
 - icc
 - opencv ( if needed )

### config path
change Makefile library path

if libmkl.so not found
 - export LD_LIBRARY_PATH=/path/to/library/mklml_2017.0.1/lib/:$LD_LIBRARY_PATH

#Darknet#
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).



