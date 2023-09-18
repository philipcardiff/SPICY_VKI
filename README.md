SPICY_VKI
========

Installation
========
You can install spicy via `pip`: 

`pip install spicy_vki`

This will install the package with all its mandatory dependencies, namely: 

```
"numpy>=1.20",
"scikit-learn>=1.0",
"ipython>=7.16.1",
"scipy>=1.5",
"shapely>=1.7.0",
```

Note that if you want to run the tutorial in the `./Tutorials` folder, you need `matplotlib` for visualization purposes. Installing spicy with the optional depedencies:

`pip install spicy_vki[tutorials]`

will install matplotlib. The turotials are available in the github repository SPICY_VKI.


SPICY
=====

The repository contains the codes linked to the SPICY project (Super-resolution and Pressure from Image veloCimetrY).

SPICY is a software developed at the von Karman Institute to perform data assimilation of image velocimetry using constrained Radial Basis Functions (RBF). 
The framework works for structured data (as produced by cross-correlation-based algorithms in PIV or Optical FlowS) and unstructured data (produced by tracking algorithms in PTV).

While the main scope is the assimilation of velocity fields, SPICY can also be used for the regression of other fields (e.g., temperature fields).
The theoretical foundation of the constrained RBF approach is described in - P. Sperotto, S. Pieraccini, M.A. Mendez, A Meshless Method to Compute Pressure Fields from Image Velocimetry, Measurement Science and Technology 33(9), May 2022. (pre-print at https://arxiv.org/abs/2112.12752).

The GitHub folder contains four tutorials. These include regression of synthetic velocity fields as well as the solution of Poisson problems.

The documentatation can be found here: https://spicy-vki.readthedocs.io/en/latest/index.html


The list of proposed exercises is following:

1 - Solution of a Laplace problem on the unit square.

2 - Regression of the velocity field of a 2D Lamb-Oseen vortex.

3 - Regression of the velocity field and integration of the Poisson equation for the 2D flow past a cylinder.

4 - Regression of the velocity field and integration of the Poisson equation for the 3D Stokes flow past a sphere.

Tutorials 2 - 4 are taken from the article from Sperotto et al. (2022) https://arxiv.org/abs/2112.12752
 
 
 
 
 
 
 
 
