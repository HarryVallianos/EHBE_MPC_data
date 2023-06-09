# EHBE MPC experiment data

This repository hosts data from the Experimental House of Building Energetics (EHBE) of Hydro-Québec in Shawinigan. 

It is a two-storey house with an excavated basement and an attached garage. The house is 7.6 m by 7.9 m (its footprint is 60 m2) with a fully uninsulated basement. It is a typical Québec residence, with R-20 insulation for the walls, R-30 insulation for the roof, and a total of 19 m2 of fenestration consisting of double-glass windows with an air gap. The house is oriented 35° west of south and is heated with an electric baseboard in each room controlled with an individual thermostat.

The house has been used to test real-time Model Predictive Control using different model resolutions.

For more information prease refer to our article: [TBD]

## Repository structure

EHBE_MPC_data
* data
  * 2019.csv            : Includes business-as-usual data from 2019 for reference. Can be used for model calibration.
  * 2023.csv            : Includes data from experiments in 2023 with different control strategies described in events_metadata.
  * events_metadata.csv : Includes information about which control strategy was applied during the day. Reference is business-as-usual, while floor, orientation and multi-zone are Model Predictive Controllers using a floor model, orientation model and multi-zone model respectively.
  * room_metadata.csv   : Includes information about each separate room.
* README

## Citation

If you use the data of this repository please reference our article:
[TBD]

### Authors
[Charalampos Vallianos](https://www.linkedin.com/in/charalampos-vallianos-629798193/),
Matin Abtahi,
Andreas Athienitis,
Benoit Delcroix,
Luis Rueda,

## Publications using data form this repository
