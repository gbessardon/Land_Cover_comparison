# Land_Cover_comparison

This aims at comparing different land cover maps

The scripts here have been run in google colab with data stored in a google drive all the notebook start with option whether to run on colab and drive variables
If running on drive and collab all the necessary library will be installed if outside collab you will need to check your config (detailed list of library necessary tbh)

Open LUCAS.ipynb: Opens the LUCAS Copernicus file (not needed to run the other scripts

Read_open_streetmap.ipynb: Opens the shape file containing the LUCAS copernicus polygons, requests the different OSM data corresponding to the polygon

CORINE.ipynb: Opens the shape file containing the LUCAS copernicus polygons,  and then create segment of the CORINE dataset corresponding to each LUCAS copernicus polygon while reprojecting it and setting a 10-m resolution


ESRI2020.ipynb: Opens the shape file containing the LUCAS copernicus polygons, find the ESRI2020 tile corresponding to each LUCAS copernicus polygon, and then create segment of the ESRI2020 tiles corresponding to each LUCAS copernicus polygon
