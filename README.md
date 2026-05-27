# cuprate_parametrization
Database for 1-band Hubbard and 3-band Emery model parameters for superconducting cuprates. Crystal structures are taken from MaterialsProject. Tight-binding parameters are obtained using maximally localized Wannier functions. Interaction parameters are obtained using cRPA. Superconducting T_c values are taken from experimental literature. 

For details see arXiv:xxxx.xxxxx.

Data is given as parseable python code - a list of dictionaries with entries corresponding to various parameters and experimental Tc.

Energy unit is eV, temperature unit is K.

Folder PLOTS contains PDF's with DFT bandstructure and partial DOS results, as well as cRPA results that were used to derive the models.

See example_script.ipynb to get started.

If you find this database useful, cite

arXiv:xxxx.xxxxx
