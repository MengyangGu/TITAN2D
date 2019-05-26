# TITAN2D
TITAN2D computer model runs used for testing the parallel partial Gaussian process emulator (Gu and Berger 2016). The TITAN2D.rda contains three dataframes.

The input_variable is a data frame with 683 runs and 4 input variables, where the 4 input variables are volume, initial angle, basal friction angles and internal friction angle of a simulated eruption. The first 50 runs are used as the training input and the latter 633 runs are used as the testing input.

The pyroclastic_flow_heights is a data frame  with 683 runs of the maximum heights of the pyroclastic flow (over time) at 144 x 160 spatial grids in each simulated eruption for a given set of input variables. The first 50 runs are used as the training input and the latter 633 runs are used as the testing input.

The local_index is a data frame for certain locations of index. The first row of the data gives the index set of the crater area. The second row gives the medium to small flow area. The third row gives the index set of Belham Valley area. See (Gu and Berger 2016) for details.

References

Bayarri, M. J., Berger, J. O., Calder, E. S., Dalbey, K., Lunagomez, S., Patra, A. K., Pitman, E. B., Spiller, E. T. and Wolpert, R.L. (2009). Using statistical and computer models to quantify volcanic hazards. Technometrics, 51(4), 402-413.

Gu, M. and Berger, J. O. (2016). Parallel partial Gaussian process emulation for computer models with massive output. The Annals of Applied Statistics, 10(3), 1317-1347.

Patra, A. K., Bauer, A. C., Nichita, C. C., Pitman, E. B., Sheridan, M. F., Bursik, M., Byron, R., Webber, A., Stinton, A.J., Namikawa, L.M. and  Renschler, C. S. (2005). Parallel adaptive numerical simulation of dry avalanches over natural terrain. Journal of Volcanology and Geothermal Research, 139(1-2), 1-21.
