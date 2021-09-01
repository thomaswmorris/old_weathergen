## Overview

This package generates quantitatively realistic atmospheric profiles. In particular, it generates the water vapor mass density, 
the air temperature, and a two-dimensional wind vector at 100m vertical increments up to 20,000m.

## Methodology

weathergen randomizes the phase of the first 32 weighted principal components of the atmospheric variations, fitted to each site for each time-of-day 
and time-of-year bin. Eigenmodes are fitted with to the MERRA-2 reanalysis dataset from 1980 to 2021. The model has a diurnal resolution of three hours 
and a seasonal resolution of around two weeks. 

## Supported sites.

The current version supports three sites: the Chajnantor plateau in the Atacama Desert, the South Pole, and Ngari Prefecture in Tibet. 
