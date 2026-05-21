# Han et al. (in prep.), JGR: Solid Earth - Model Setup
The content of each file can be identified by the file name, as described below

**01. Boundary Conditions:** Slab Temperature ($Kelvin$) and Basal Heat Flux ($mW \ m^{-2}$) calculated from large-scale thermomechanical subduction models for the Nankai and Tohoku subduction zones - Figures 2 and 3  

**02. PermeabilityProfile:** log10(permeability) ($m^{-2}$) - Figures 4 and 5  

**03. BC Test Results:** The calculated seafloor heat flow from the models with a different bottom boundary conditions (insulated & constant temperature corresponding to the initial slab temperature at 40-km depth) ($mW \ m^{-2}$).  

**04. rho_fluid Test Results:** The calculated seafloor heat flow from the models with a different fluid density ($mW \ m^{-2}$).  

For the Nankai/Tohoku_rhoT_Calculated_SeafloorHeatflow, the fluid density was defined as,  
$\rho_f = \rho_{f0}(1-\alpha_0T-\alpha_1T^2)$,  
where $\rho_{f0}=1036.5 \ kg \ m^{-3}$, $\alpha_0=1.367 \times 10^{-4} \ ^{\circ} C^{-1}$, and $\alpha_1=2.159 \times 10^{-6} \ ^{\circ} C^{-2}$ (Kawada et al., 2014).    

For the Nankai/Tohoku_rhoTP_Calculated_SeafloorHeatflow, the fluid density was defined as,  
$\rho_f = \rho_{f0}(1-\alpha_0T + \beta p_0)$,  
where $\rho_{f0}=1036.5 \ kg \ m^{-3}$, $\alpha_2 \times 10^{-4} \ ^{\circ} C^{-1}$, $\beta=4 \times 10^{-10} Pa^{-1}$, and $p_0 = \rho_{f0} \|\mathbf(g)\| (-y)$ (Vallis, 2017). 
  
### References
Kawada, Y., M. Yamano, and N. Seama (2014), Hydrothermal heat mining in an incoming oceanic plate due to aquifer thickening: Explaining the high heat flow anomaly observed around the Japan Trench, Geochemistry, Geophysics, Geosystems, 15(4), 1580-1599.  

Vallis, G. K. (2017), Atmospheric and oceanic fluid dynamics, Cambridge University Press.


