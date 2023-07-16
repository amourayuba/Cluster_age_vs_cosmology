# Cluster_age_vs_cosmology

Investigate how cluster age varies with cosmology. This represents the code and data used for the publication 
: https://ui.adsabs.harvard.edu/abs/2021MNRAS.508..100A/abstract 

The codes in analytical_models rely on the functions in https://github.com/amourayuba/Halo_Analytical_Calculations.
And the subsequent dependencies within that project. The codes in simulations require the functions and 
the Simulation class in https://github.com/amourayuba/Simulations.

## Analytical_models 
These are jupyter notebooks, data and figures of various quantities derived from analytical models. Three 
main categories
### Cosmoloy_bases.ipynb 
Various cosmological quantities such as growth rates, power spectrums etc. 
### Halo_Mass_Functions
The cosmological dependance of the halo mass function, as well as number density and abundance. Figures of the 
first part of the paper Amoura et al. (2021)

## simulations 
These are jupyter notebooks, calculations data and figures of various quantities derived from simulations. 

### Getting the Mass Accretion Histories (MAH)
Notebooks for each type of data (Amiga Halo Finder, Bolshoi, Illustris) allowing to create MAH files 
which are lists of elements, one for each halo. Each element is the mass history of that halo. 

### Get_ages.ipynb 
Using the MAH files, it calculates and plots various age quantities. 

### formation_time.ipynb 
Notebooks, data and figures used to generate the main plots of Amoura et al. (2021)


