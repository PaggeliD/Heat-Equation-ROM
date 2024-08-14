# A Reduced Order Modelling (ROM) method for the Heat Equation in NGSolve.

This repository contains a reduced order modelling method for the heat equation using NGSolve as the Finite Element software. The project has been developed for a Numerical Analysis Workshop which was organized by the Department of Mathematics of Aristotle University of Thessaloniiki. For those interested, a tutorial of a finite element solver of the heat equation can also be found [here](https://github.com/JSchoeberl/iFEM/blob/master/timedependent/intro/heatequation.ipynb). 

## Dependencies

The code was implemented using Python 3.10.12 on Ubuntu 22.04 and the required dependencies of this project are:
* [NumPy](https://numpy.org/)
* [SciPy](https://scipy.org/)
* [Matplotlib](https://matplotlib.org/)
* [NGSolve](https://ngsolve.org/)
* [Jupyter Notebook](https://jupyter.org/)
* [Paraview](https://www.paraview.org/)

## References

The mathematical concept of Reduced Basis Methods for partial differential equations, that have also been used in this project, and many more can be found in [Quarteroni et al. (2015)](https://doi.org/10.1007/978-3-319-15431-2).

## Visuals

Finally, we display some visuals to get your attention going. From left to right, the solutions of FOM and ROM.

<p float="middle">

<img src="https://github.com/PaggeliD/Heat-Equation-ROM/blob/main/sols/u_approx/png_files/uh_sol.gif" alt="FOM" width=389 />
<img src="/home/paschalis/Documents/Github-ROM/Heat-ROM/sols/u_red_r4/png_files/ur_sol.gif" width=389 />

</p>
