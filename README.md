# Han et al. (in prep.), JGR: Solid Earth
This repository contains the data used for figures regarding the manuscript titled as '*A Wide Spectrum of Friction Estimates in Subduction Zones: The Influence of Pre- and Post-Subduction Faulting in the Oceanic Crust*'.

The content of each file can be identified by the file name, as described below

**SubductionZone_ModelConditions_DataType** (e.g., Nankai_MuPrime0.00_Ka1E-10m2_xsw-10km_CalculatedSeafloorHeatFlow)  
- SubductionZone is either Nankai or Tohoku  
- ModelConditions is either non-HC_Model, BestFitModels, or MuPrimeXXX_KaYYYm2_xswZZZkm.  
XXX, YYY, and ZZZ are the values used for each parameter in the models.  
Please note that MuPrimeXXX is not included in the file names of the permeability data.

Each file has either two (x-coordinate (km) and data) or three (x- and y- coordinates (km), and data) columns.

## DataType  
**01. PercentageImprovement:** percentage improvement of the calculated seafloor heat flow of the best-fit models compared to those calculated from the non-HC models (%) - Figure 5  
**02. CalculatedSeafloorHeatFlow:**: calculated seafloor heat flow averaged every 2.5 km (mW m-2) - Figures 6 and 7 & Supplementary Figure 1-8  
**03. Temperature:** temperature distribution (Kelvin) - Figures 6 and 7    
**04. Vx:** pore fluid velocity in x-direction (m s-1) - Figures 6 and 7  
**05. Vy:** pore fluid velocity in y-direction (m s-1) - Figures 6 and 7      
**06. AquiferTemperature**: temperature of the top boundary of the aquifer averaged every 2.5 km (Kelvin) - Figures 6 and 7  
**07. PermeabilityProfile:** log10(permeability) (m-2) - Figures 3 and 4

