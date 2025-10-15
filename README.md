# redoKP6-desi
Tutorial to reproduce the Lyman-alpha KP6 results for the DR1.

**Step 1**. We need to generate the deltas from the QSO spectra found in DESI DR1. To do this, install PICCA and calculate the deltas with this program. The specifications are in the Step 1 from the tutorial: 
[Reproduce Lya BAO results for DESI Y1 without a bookkeeper.](https://desi.lbl.gov/trac/wiki/LymanAlphaWG/ReproduceDESIY1#no1)

**Step 2**. Once the deltas have been generated without errors, the `Log` directory will be generated in the `delta-ciii`, `delta-lya`, and `delta-lyb directories`. This directory contains the `delta_attributes.fits.gz` file, which contains information about the average of the calculated deltas, the associated errors, and the continuum. We will graph this information and compare it with that obtained by DESI DR1.

**Step 3**. Once the Correlations, Cross-Correlations and the Covariance matrix have been calculated, in Step 2 of the mentioned tutorial, we proceed to graph said correlations in a 2D map depending on ($r_p$, $r_t$). We will graphically compare these with the results obtained by DESI DR1.

**Step 4**. We can plot the mesuared Correlations and Cross-Correlations obtained with PICCA in 1D with respect to $$r$$ for each range of ​​​​![Equation](https://latex.codecogs.com/svg.latex?\mu) values. From the Step 3 of the mentioned tutorial, we obtain the fit of the Correlation and Cross Correlation functions using the Vega package and, using the file created in the directory output_fitter, we can add the fit of each Correlation. We will graphically compare these with the results obtained by DESI DR1.
