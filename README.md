# Combine point and extended source lists
Read in stellar catalogs from simulations with Absolute AB mags and 
background galaxy catlogs. Using the WingsTips lib, produce mixed list 
of objects including stars and appropriate sampling of background 
galaxies in STIPS input format

The make_mix.py scripts utilizes classes and methods defined in 
wingtips.py. Samples background galaxies at the same location 
in each filter to generate coherent images. 

The hst_to_wfi.py script is standalone, used to convert HST 
fluxes to WFI fluxes.
