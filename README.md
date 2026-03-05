# Cosmological Perturbation Theory

Symbolic code for computing **perturbed curvature quantities and
Einstein equations** for a given spacetime metric using **SageMath**.

The notebooks compute background geometric quantities and derive the
**scalar, vector, and tensor components of the perturbed Einstein
equations** for cosmological spacetimes.

This repository is intended as a **symbolic tool for studying
cosmological perturbations in General Relativity**.

The repository currently contains two notebooks:

-   **metric_calc_cartesian.ipynb** -- calculations for a flat spacetime
    using the **Cartesian coordinate system**.
-   **metric_calc_spherical.ipynb** -- calculations for a non-flat
    spacetime using the **spherical coordinate system**.

------------------------------------------------------------------------

# Requirements

This code uses **SageMath**.

Install SageMath from:

https://www.sagemath.org/

If using Jupyter:

``` bash
sage -n jupyter
```

Alternatively, install the Sage kernel in an existing Jupyter
environment.

Python packages used:

-   SageManifolds (included in SageMath)
-   IPython display tools

------------------------------------------------------------------------

# How to Run

1.  Open the desired notebook in a SageMath-enabled Jupyter environment.

2.  **Define the spacetime metric in the first cell.**

3.  If only **background (non-perturbative) quantities** are required,
    the initial cells are sufficient to compute curvature tensors and
    related geometric quantities.

4.  For **perturbation calculations**, set the following flags:

```{=html}
    include_S
    include_V
    include_T
```

to `True` or `False` depending on whether **scalar, vector, or tensor
perturbation modes** are to be included.

------------------------------------------------------------------------

# Author

Samarth Bhatnagar\
BITS Pilani Goa\
M.Sc. Physics + B.E. Computer Science
