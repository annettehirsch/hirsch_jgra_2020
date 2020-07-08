# hirsch_jgra_2020

Repository of Analysis Code for the Manuscript entitled: "Atmospheric and land surface contributions to heatwaves: an Australian perspective" by Annette L. Hirsch and Malcolm King  submitted to Journal of Geophysical Research - Atmospheres

This repository contains all the analysis source code for Hirsch and King 2020 [Paper #2020JD033223] and can be used to reproduce the analysis of the manuscript. Note that all directory paths will need to be updated for successful implementation of the code.

Datasets to which the code applies

    WRF-LIS-CABLE simulations for the CORDEX AustralAsia domain on a 0.44˚ x 0.44˚ rotated coordinate system. All data will be published via the Australian National Computational Infrastructure (NCI)
    Australian Gridded Climate Data (AGCD) daily precipitation and temperature dataset [Jones et al. 2009 Australia. Aust. Meteor. Mag.]

Scripts used to prepare the data

    process_wrfout_EF.pbs - to process the wrfout model output files
    process_lisout_EF.pbs - to process the lisout model output files

Notebooks to plot results:

    create_ef_forcing.ipynb - Visualisation of the forcing location and timing
    retrieve_advection_at_level.ipynb - Extract low-level advection and omega from the model outputs
    plot_AWAP.ipynb - Plots the observed summertime temperature time series 
    plot_ef_daily_evolution.ipynb - Plot time series for the seeded regions for different experiments and variables
    check_circulation.ipynb - plot the atmospheric vertical profile time series for different experiments and variables

