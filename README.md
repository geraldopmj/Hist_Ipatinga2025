# Leaflet with a Map of Ipatinga
Map of Ipatinga created with GEE and QGIS.
[Visualize]([https://leafletjs.com/](https://geraldopmj.github.io/Hist_Ipatinga2025/))

**Methodology:** Using Google Earth Engine, land use and land cover classification was performed with the Random Forest algorithm, based on Sentinel-2 L2A images from July 2025. Several spectral indices were calculated and combined with the original bands, resulting in 66 variables used in the model. Next, using QGIS, the classified raster was vectorized. For the final cartographic representation, symbology inspired by old maps was applied, with a classic aesthetic and detailed visual style.

**Map of Ipatinga: © 2025 Geraldo Pereira de Morais Júnior – All rights reserved**  
The OpenStreetMap basemap layer is used under the ODbL 1.0 license.  
This project uses [Leaflet](https://leafletjs.com/) under the BSD 2-Clause License.
