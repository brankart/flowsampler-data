## Shallow water flows

These data have been produced by the program 'flow_sampler.F90'
(in the examples of the repository 'flowsampler').

### Name of the files

```
<exp>_<nnnn>_diag.nc
```

where

```
<exp> : name of the experiment
<nnnn> : index of time step
```

### List of experiments

```
adv2, adv3, adv4, adv5 : sample of 4 flows with the advective constraint only
advdif3 : sample of 1 flow with the advective constraint
          and the laplacian dissipation penalty
advfrc3 : sample of 1 flow with the advective constraint, the forcing term
          and the laplacian dissipation penalty
advfrc4a : sample of 1 flow with the advective constraint, the forcing term,
           the laplacian dissipation penalty, and the nonlinear dissipation penalty (gamma=0.1)
advfrc4b : sample of 1 flow with the advective constraint, the forcing term,
           the laplacian dissipation penalty, and the nonlinear dissipation penalty (gamma=1)
```

### Content of the NetCDF files

```
lon : longitude
lat : latitude
psi : stream function
u : zonal velocity
v : meridional velocity
unorm : norm of velocity
zeta : relative vorticity
roughness : laplacian dissipation penalty
slope_penalty : nonlinear dissipation penalty
advresidual : residual of the advection constraint (xi)
```

