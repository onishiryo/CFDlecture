# sample programs for CFDlecture

## 1D advection-diffusion eq.
- 1d-adv-diff.ipynb

Code created by ChatGPT 4o with the following prompt:
- Please generate a python code to solve a one-dimensional advection-diffusion equation of T, a function of t (time) and x.
- The code should use the Euler scheme for time advancement and second-order central difference schemes for advection and pressure terms.
- Show temporal advancement of x profile of T with analytical solutions.

Code modified by Ryo Onishi

## 2D channel flow for CFD lecture
1. 2d-channel_baseline.ipynb
   - for-loops used for matrix calculations for better readability
   - very slow
1. 2d-channel_slicing.ipynb
   - list comprehensions (with slicing), instead of for-loops, used for matrix calculations
   - much faster than baseline, e.g., x100

Code created by ChatGPT 4o with the following prompt:
- Please generate a 2dimensional channel flow simulation code in Python.
- The code should use the Euler scheme for time advancement and second-order central difference schemes for advection, diffusion pressure terms.
- constant pressure gradient is given to drive the flow.
- The SMAC method is used for pressure-flow coupling.
- The SOR method is used to solve the pressure poisson equation.
- Show temporal advancement of vertical profile of streamwise velocity.
- Detail explanation should be written as comments.
- use for-loops for better readability

Code debugged and modified by Ryo Onishi

## Linear and non-linear regressions 
- linear_regression_and_nonlinear_regression.ipynb
created by Takuya Takase

## 1D diffusion eq. solved by PINN
- 1D-diffusion_PINN.ipynb
created by Keigo Hirasawa


Free of use. No Warranty.
