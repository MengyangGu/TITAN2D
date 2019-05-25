# TITAN2D
The TITAN2D.rda TITAN2D computer model runs used for testing the parallel partial Gaussian process emulator (Gu and Berger 2016). It contains three dataframes.

The input_variable is a data frame with 683 runs and 4 input variables, where the 4 input variables are volume, initial angle, basal friction angles and internal friction angle. The first 50 runs are used as the training input and the latter 633 runs are used as the testing input.

The pyroclastic_flow_heights is a data frame  with 683 runs of the maximum pyroclastic flow heights at 144 x 160 spatial grids in each simulated eruption for a given set of input variables. The first 50 runs are used as the training input and the latter 633 runs are used as the testing input.

The local_index is a data frame for certain locations of index. The first observation (row) gives the index set of the crater area. The third observation gives the medium to small flow area. The third observation gives the index set of Belham Valley area. See (Gu and Berger 2016) for details.


Gu, M., & Berger, J. O. (2016). Parallel partial Gaussian process emulation for computer models with massive output. The Annals of Applied Statistics, 10(3), 1317-1347.
