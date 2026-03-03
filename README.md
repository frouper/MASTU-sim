# Tokamak Particle Tracker 

A 3D simulation of charged particles magnetically confined within a spherical tokamak of MAST-U dimensions. 

A 2D MHD equilibrium is computed with [FreeGS](https://github.com/freegs-plasma/freegs) and loaded from a .npz file into the project. The equilibrium fields are interpolated onto a 3D grid from which particle positions are integrated with a boris pusher. 

[Taichi Lang](https://www.taichi-lang.org/) is used for GPU-accelerated computation and rendering of the particles, coil and wall geometries. 

Dependencys: NumPy and Taichi

