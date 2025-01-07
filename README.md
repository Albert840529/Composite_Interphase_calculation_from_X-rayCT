# Composite_Interphase_Calculation_from_X-rayCT

This repository contains code for quantifying and visualizing the polymer/ceramic interphase in composite materials, as described in this paper: [Cold Sintering with Functionalized Polymers for Ductile Ceramic Matrix Composites with Controllable Mechanical Performance](https://doi.org/10.1016/j.mtla.2024.102238) (DOI: 10.1016/j.mtla.2024.102238). 

In this code, the grayscale distribution of each X-ray CT image is fitted using selected functions (Gaussian or Lorentzian) to differentiate the ceramic and polymer phases. The interphase in the composite is further quantified and visualized based on the fitting results.

Additionally, the present code also calculates the domain size using both Otsu's method and Gaussian fitting for recalculation.

