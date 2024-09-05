# Fracture-Conditions-Paper-Data
Data used in Wells-Moran et al., 2024

## Identified Crevasse Maps
All crevasse maps are based off of 2014 MODIS Mosaic of Antarctica optical imagery and strain rate fields derived from 2014 ITS_LIVE velocity fields. 

## Predicted Fracture Maps
Predicted fracture maps show 0 where a fracture is predicted and 1 where calculated stresses fall within the various yield criteria. The files for Mohr-Coulomb and Drucker-Prager in the n=3 and n=4 folders are calculated using $\mu=0.4$. In the varying_mu folders within the n=4 folders, the last two numbers in the file name correspond to the $\mu$ value used to create the mask. (e.g. in_dp_n4_00.tif is calculated using $\mu=0.0$, in_mc_n4_05.tif is calculated with $\mu=0.5$)
