# Comparison between Elmer and commercial sotware

This is the anisotropic test. The geometry is arbitrary and did not follow any project or reference.
Simulation is carried out with a sinusoidal primary current input and a open secondary (high resistance value).
The model for core losses is a very simple one, just to get a uniform evaluation accross the different software platforms.
The core magnetizing curves are obtained from measurement and extrapolated.

For this simulation, Is = 0.02 A

The files are as described bellow:
 - Aniso_nLin_WindingPlot_0p02 - Results from commercial software for current and induced voltage. 
 - Aniso_nLin_LossPlot_0p02 - Results from core losses. 
 - res_3d_t_ld_30.dat - Output values from Elmer with a timestep of 1/30 of the period.
 - res_3d_t_ld_50.dat - Output values from Elmer with a timestep of 1/50 of the period.
 - res_3d_t_ld_100.dat - Output values from Elmer with a timestep of 1/100 of the period.
 - res_3d_t_ld.dat.names - Identification of output varibles.
 - BH_DL_2_data.dat - Longitudinal direction BH curve.
 - BH_DT_2_data.dat - Transversal direction BH curve.
 - case_3d_ld_t_5_nlfa_v2.sif - Elmer FEM simulation file.
 - plot_curves.ipynb - Jupyter notebook for processing the results.
 - reluctivity_anisot - reluctivity function for anisotropic non linear BH curve evaluation.
 - transient_3d_lpri_extR_T.definition - Elmer circuit definition.

