# Experimental House of Building Energetics (EHBE) Model Predictive Control (MPC) experiment data

This repository hosts data from the Experimental House of Building Energetics (EHBE) of Hydro-Québec in Shawinigan. 

It is a two-storey house with an excavated basement and an attached garage. The house is 7.6 m by 7.9 m (its footprint is 60 m<sup>2</sup>) with a fully uninsulated basement. It is a typical Québec residence, with R-20 insulation for the walls, R-30 insulation for the roof, and a total of 19 m<sup>2</sup> of fenestration consisting of double-glass windows with an air gap. The house is oriented 35° west of south and is heated with an electric baseboard in each room controlled with an individual thermostat.

The house has been used to test real-time Model Predictive Control using different model resolutions.

For more information prease refer to our article:
> Charalampos Vallianos, Matin Abtahi, Andreas Athienitis, Benoit Delcroix & Luis Rueda (2023) Online model-based predictive control with smart thermostats: application to an experimental house in Québec, Journal of Building Performance Simulation, DOI: https://doi.org/10.1080/19401493.2023.2243602

## Repository structure

EHBE_MPC_data
* data
  * 2019.csv            : Includes business-as-usual data from 2019 for reference. Can be used for model calibration.
  * 2023.csv            : Includes data from experiments in 2023 with different control strategies described in events_metadata.
  * events_metadata.csv : Includes information about which control strategy was applied during the day. Reference is business-as-usual, while floor, orientation and multi-zone are Model Predictive Controllers using a floor model, orientation model and multi-zone model respectively.
  * room_metadata.csv   : Includes information about each separate room.
* README

## Citation

If you use the data of this repository please reference the dataset on zenodo:
>Charalampos Vallianos, Matin Abtahi, Andreas Athienitis, Benoit Delcroix, & Luis Rueda. (2023). Experimental House of Building Energetics Model Predictive Control experiment data (v1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.8021942

and our article:
>Charalampos Vallianos, Matin Abtahi, Andreas Athienitis, Benoit Delcroix & Luis Rueda (2023) Online model-based predictive control with smart thermostats: application to an experimental house in Québec, Journal of Building Performance Simulation, DOI: https://doi.org/10.1080/19401493.2023.2243602

## Publications using data form this repository
1. Charalampos Vallianos, Matin Abtahi, Andreas Athienitis, Benoit Delcroix & Luis Rueda (2023) Online model-based predictive control with smart thermostats: application to an experimental house in Québec, Journal of Building Performance Simulation, DOI: 10.1080/19401493.2023.2243602
2. Charalampos Vallianos, Andreas Athienitis, Benoit Delcroix (2022) Automatic generation of multi-zone RC models using smart thermostat data from homes, Energy and Buildings, DOI: https://doi.org/10.1016/j.enbuild.2022.112571
