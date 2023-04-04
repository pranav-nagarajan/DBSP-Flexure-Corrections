# DBSP Flexure Corrections

This repository serves as a tutorial for computing flexure corrections for the Double Spectrograph (DBSP) at Palomar Observatory based on telluric lines (specifically, the A band of molecular oxygen). Telluric models can be generated using the <a href="https://telfit.readthedocs.io/en/latest/Tutorial.html">Telfit</a> package.

The tutorial also demonstrates how to compare a DBSP observation (i.e. a 1D spectrum extracted by <a href="https://pypeit.readthedocs.io/en/release/index.html">PypeIt</a>) to a <a href="https://archive.stsci.edu/hlsp/bosz/search.php">BOSZ Kurucz</a> model spectrum to derive a radial velocity. The flexure correction is applied to this radial velocity measurement to recover the literature value for the RV standard star <a href="http://simbad.u-strasbg.fr/simbad/sim-id?Ident=HD++40460">HD 40460</a>.

This method of RV determination is used in a forthcoming publication (Nagarajan and El-Badry (2023)) that describes the results of spectroscopic follow-up of black hole and neutron star candidates in a sample of ellipsoidal variables in Gaia DR3.
