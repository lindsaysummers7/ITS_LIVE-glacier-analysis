# ITS_LIVE-glacier-analysis
Notebooks to import and analyze velocities from NASA's ITS_LIVE using Randolph Glacier Inventory (RGI) centerlines

Lindsay Summers, CryoGARS Glaciology, Boise State University

## Correspondence
Lindsay Summers: lindsaysummers@u.boisestate.edu

## Set-up
See the environment.yml file for required packages. To install the environment with Mamba or Conda, run the following:

micromamba env create -f environment.yml

## General Workflow:

first, you will need the following inputs:
- RGI centerline shapefiles for your region of interest
- a .csv file with a column named "rgi_id" containing the RGI IDs of glaciers you're interested in

Then, you can follow this general workflow:
1. import_itslive_points.ipynb 
2. weighted_average_monthly_velocities.ipynb
