# ZirconThermoKinematics.jl

This package can be used to simulate the thermal evolution of magmatic systems, consisting of (kinematically) emplaced dikes. 
It can simulate 2D, 2D axisymmetric and 3D geometries, and works in parallel on both CPU (and GPU's). A finite difference discretization is employed for the energy equation, combined with semi-lagrangian advection and tracers to track the thermal evolution of emplaced magma. Dikes are emplaced kinematically and the host rock is shifted to accommodate space for the intruding dikes/sills. Cooling, crystallizing and latent heat effects are taken into account, and the thermal evolution of tracers can be used to simulate zircon age distributions.

Below we give a number of example scripts that show how it can be used to simulate a number of scenarios.


## Installation
This is a julia package, so after installing julia in the usual manner, you can add the package with 
```
]
```