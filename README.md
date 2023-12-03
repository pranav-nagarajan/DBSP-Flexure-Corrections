# DBSP Flexure Corrections

This repository serves as a tutorial for computing flexure corrections for the Double Spectrograph (DBSP) at Palomar Observatory based on telluric lines (specifically, the A band of molecular oxygen). Telluric models can be generated using the <a href="https://telfit.readthedocs.io/en/latest/">Telfit</a> package.

The tutorial also demonstrates how to compare a DBSP observation (i.e. a 1D spectrum extracted by <a href="https://pypeit.readthedocs.io/en/release/index.html">PypeIt</a>) to a <a href="https://archive.stsci.edu/hlsp/bosz/search.php">BOSZ Kurucz</a> model spectrum to derive a radial velocity. The flexure correction is applied to this radial velocity measurement to recover the literature value for the RV standard star <a href="http://simbad.u-strasbg.fr/simbad/sim-id?Ident=HD++40460">HD 40460</a>.

This method of RV determination is used in the publication "Spectroscopic follow-up of black hole and neutron star candidates in ellipsoidal variables from _Gaia_ DR3" (<a href="https://academic.oup.com/mnras/article/524/3/4367/7225539?guestAccessKey=136aa124-1fdf-41dd-9274-fd9069751300&utm_source=authortollfreelink&utm_campaign=mnras&utm_medium=email">Nagarajan et al. 2023</a>).
