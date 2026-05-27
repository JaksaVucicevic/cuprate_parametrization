# cuprate_parametrization
Database for 1-band Hubbard and 3-band Emery model parameters for superconducting cuprates. Crystal structures are taken from MaterialsProject. Tight-binding parameters are obtained using maximally localized Wannier functions. Interaction parameters are obtained using cRPA. Superconducting T_c values are taken from experimental literature. 

For details see [1].

Data is given as parseable python code - a list of dictionaries with entries corresponding to various parameters and experimental Tc.

Energy unit is eV, temperature unit is K.

Folder PLOTS contains the following PDF's:
1) DFT bandstructure and partial DOS results
2) cRPA results that were used to derive the models
3) full statistical analyses used as basis for the publication [1]

See example_script.ipynb to get started.

If you find this database useful, cite

[1] arXiv:xxxx.xxxxx
