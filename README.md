# CFDlecture
2D channel flow for CFD lecture

Code created by ChatGPT 4o with the following prompt:
- Please generate a 2dimensional channel flow simulation code in Python.
- The code should use the Euler scheme for time advancement and second-order central difference schemes for advection, diffusion pressure terms.
- constant pressure gradient is given to drive the flow.
- The SMAC method is used for pressure-flow coupling.
- The SOR method is used to solve the pressure poisson equation.
- Show temporal advancement of vertical profile of streamwise velocity.
- Detail explanation should be written as comments.
- use for-loops for better readability

Code debugged by ryo

1. 2d-channel_baseline.ipynb
   - for-loops used for matrix calculations for better readability
   - very slow
1. 2d-channel_slicing.ipynb
   - list comprehensions (with slicing), instead of for-loops, used for matrix calculations
   - much faster than baseline, e.g., x100
