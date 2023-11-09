# DCLpaper
Treeage models referenced in the dynamic cycle length (DCL) paper by Eric Wong, David Naimark et al.
The hospital discharge models are FCL_Weibull2strat.trex (fixed cycle length), DCL_Weibull2strat.trex (dynamic cycle length) and DCL_pDES_Weibull2strat.trex
(hybrid dynamic cycle length with pseudo-DES features)

The OR waitlist modelas are OpenPhantom_pseudoDES_producn0.trex (showing all horizon options). Each horizon option needs to run as a separate model
OpenPhantom_pseudoDES_producnX.trex where X = 1 for fixed entry horizon plus phantoms, X = 2 for fixed exit horizon and X = 3 for fixed entry horizon (without phantoms).

For any issues please contact david.naimark@sunnybrook.ca

Please feel free to modify these models and use in your own work but please cite this GitHub URL
