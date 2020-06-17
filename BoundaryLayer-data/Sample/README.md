## Sample of velocity profiles

These data have been produced by the program 'bl_sampler.F90' 
(in the examples of the repository 'flowsampler').

### Name of the files

<type><nnnn>-<gamma>-<psi>.txt

where

<type> : 'p' or 'c', for Poiseuille or Couette flow (with an 'r' appended for the reduced variables)
<nnnn> : index of the sample member
<gamma> : value of the gamma parameter
<psi> : value of the psi parameter

### Content of the files

For types 'p' and 'c' :

column 1 : x-coordinate (x)
column 2 : velocity gradient (g)
column 3 : velocity (u)

For types 'pr' and 'cr' :

column 1 : reduced x-coordinate (xr)
column 2 : reduced velocity (ur)

