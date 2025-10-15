# redoKP6-desi
Tutorial to reproduce the Lyman-alpha KP6 results for the DR1.

**Step 1**. We need to generate the deltas from the QSO spectra found in DESI DR1. To do this, we need to install PICCA and calculate the deltas with this program. The specifications are in the tutorial: 
[Reproduce Lya BAO results for DESI Y1 without a bookkeeper.](https://desi.lbl.gov/trac/wiki/LymanAlphaWG/ReproduceDESIY1#no1)

**Step 2**. Once the deltas have been generated without errors, the log directory will be generated in the `delta-ciii`, `delta-lya`, and `delta-lyb directories`. This directory contains the `delta_attributes.fits.gz` file, which contains information about the average of the calculated deltas, the associated errors, and the continuum. We will graph this information and compare it with that obtained by DESI DR1.
