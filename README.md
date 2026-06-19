# cuprate_parametrization
Database of model parameters for superconducting cuprates. We provide parameters for 1-band Hubbard and 3-band Emery model. Crystal structures are taken from MaterialsProject. Tight-binding parameters are obtained using maximally localized Wannier functions (MLWFs). Interaction parameters are obtained using cRPA. Superconducting T_c values are taken from experimental literature. 

For details see [1]. The paramater names are as in the paper. In addition, parameters named "n" are DFT occupancies of Wannier orbitals, while "X" are the off-diagonal elements of the DFT single-particle density-matrix.

Data is given as parseable python code - a list of dictionaries, one per compound and crystallographically inequivalent CuO2 layer, with entries corresponding to various parameters and experimental Tc.

Energy unit is eV, temperature unit is K.

Folder PLOTS contains the following PDF's:
1) DFT bandstructure and partial DOS results; in particular   

   a) "BandStructureCombo" files show the bandstructure with relevant orbital character coming from each CuO2 and pure Cu plane and CuO chain
   
   b) "Bands" files show DFT bandstructure and RESPACK downfolded bandstructure, 1- and 3-band models, with MLWFs and atomic orbitals (AO)
   
   c) "Bands_w90_all_layers" files show DFT bandstructure and Wannier90 downfolded band structures, 1- and 3-band models, for a single layer and all layers simultaneously (for multi-layer compounds)
   
   d) "PartialDoses" files show partials DOS results for Cu d and O p orbitals relevant for downfolding, as well as the energy windows estimated from them

2) cRPA results that can be used to derive the models ("SM_..." files)
   
3) full statistical analyses used as basis for the publication [1]. "best_fits_full.pdf" shows analyses with interactions taken at specific Matsubara frequencies, "best_fits_plasmon.pdf" shows analyses with parameters of the effective Holstein terms, instead.

See example_script.ipynb to get started.

If you find this database useful, cite

[1] arXiv:xxxx.xxxxx (to appear soon)
