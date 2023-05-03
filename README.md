### Amazon Shallow Cumulus Forcings for LES/CRM and 1D models. 

This repositories contains the initial 
condition and the large-scale forcing 
to reproduce the Shallow Cumulus(ShCu)
convection in Central Amazon(CAMZ). 

The initial conditions, large-scale forcing, and surface 
fluxes for the Amazon ShCu data set were created, 
averaging data set from 30 representative 
cases of ShCu in CAMZ during the intesive operational period 1 and 2, IOP1 and IOP2 
respectively. This composite is called Amazon ShCu, its mass flux time 
evolution is show in Fig.1. 

<p float="">
 <img src="fig/mass_flux_2d_small.png" width="320" />
</p>
Figure1. The time evolution (average every 5 minutes) of the updraft mass flux (uMF) [kgm−2s−1] profiles
for the Amazon ShCu. The mixing layer height (Zi, black lines) is defined at the minimum buoyancy flux (B), cloud base
height [km] (Hbase, red dashed lines) at the maximum CF level, cloud top [km] (Htop, black dot-
ted lines) at the level where CLW<0.001 [gkg−1]  above cloud base and the
level of free convection (LFC [km], purple dashed lines) at the level where B>0, above Zi.

To make 

<p float="left">
  <img src="fig/mass_flux_2d_small.png" width="320" />
  <img src="/fig/mass_flux_2d_medium.png" width="300" /> 
  <img src="/fig/mass_flux_2d_large_all.png" width="370" />
</p>
Figure1. The time evolution (average every 5 minutes) of the updraft mass flux (uMF) [kgm−2s−1] profiles
for small, medium and large. The
mixing layer height (Zi, black lines) is defined at the minimum buoyancy flux (B), cloud base
height [km] (Hbase, red dashed lines) at the maximum CF level, cloud top [km] (Htop, black dot-
ted lines) at the level where CLW<0.001 [gkg−1] (Oue et al., 2016) above cloud base and the
level of free convection (LFC [km], purple dashed lines) at the level where B>0, above Zi.


_____
## Data:

The data  was created to run in
the System for Atmospheric
Modeling (SAM) v.6.10.6 (Khairoutdinov & Randall, 2003) and a versio to 
Single Column Atmospheric Model, version 6 (SCAM6) (Gettelman et al., 2019)

Two dataset were created: 


### References

Gettelman, A., Truesdale, J. E., Bacmeister, J. T., Caldwell, P. M., Neale, R. B., Bogenschutz, P. A., & Simpson, I. R. (2019). The Single Column Atmosphere Model version 6 (SCAM6): Not a scam but a tool for model evaluation and development. Journal of Advances in Modeling Earth Systems, 11, 1381– 1401. https://doi.org/10.1029/2018MS001578

Khairoutdinov, M. F., and D. A. Randall, 2003: Cloud Resolving Modeling of the ARM Summer 1997 IOP: Model Formulation, Results, Uncertainties, and Sensitivities. J. Atmos. Sci., 60, 607–625, https://doi.org/10.1175/1520-0469(2003)060<0607:CRMOTA>2.0.CO;2.
