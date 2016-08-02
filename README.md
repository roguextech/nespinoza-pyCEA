pyCEA
-----

In order to use this, please download the original Fortran code from the NASA 
webpage: http://www.grc.nasa.gov/WWW/CEAWeb/ceaguiDownload-unix.htm. Untar the 
content of the file into a folder here and that's it! 

It is assumed the resulting folder name containing all the files is CEA+FORTRAN.

USAGE
-----

Follow the example.py code to check the usage. Can't be easier than that. The code 
needs two inputs:

- The input.mr, which has the mixing ratios of the elements that form the expected 
  compounds. The input.mr has the solar system nebula abundances from Lodders (2003).

- The input.pt is a pressure-temperature profile. In this case, it is made up in order 
  for you to be able to test the code. This will calculate the equilibrium composition at 
  each P-T pair in the file.

The code makes sure everything is in order before compiling. 

OUTPUT
------

The output is a python dictionary that has the mixing ratios of the resulting compounds at 
each P-T point.
