## Visualising the Gulf Stream

This repository contains python scripts to visualise satellite data in the Gulf Stream. The resulting figures can be found in the post titled "Visualising the Gulf Stream", on the data science blog (https://cyclo-analytics.com/2017/10/26/first-blog-post/).


gulfStreamUV_video.py -> generates the velocity field video.

gulfStreamSSH_video.py -> generates sea-surface height video.

gulfStreamSST_snapshot.py -> generates Figure 1.

gulfStreamUV_snapshots.py -> generates Figure 2.

gulfStream3D.py -> generates Figure 3.


## Dependencies:

Python 2.7.13

Matplotlib 2.0.0

Pandas 0.19.2

Basemap 1.0.7

Scipy 0.19.0

## Example image (from gulfStreamSST_snaphot.py):

![alt text](https://github.com/TomBolton/visualiseGulfStream/blob/master/gulfStreamSST.png  "Gulf Stream Sea-Surface Temperature")

## Data sources

Sea surface temperature data: https://www.ghrsst.org/ or https://podaac.jpl.nasa.gov/GHRSST.

Absolute dynamic topography and geostrophic surface velocity data: https://www.aviso.altimetry.fr/en/my-aviso.html.
