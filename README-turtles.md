# The effects of warming on loggerhead turtle nesting counts

[https://doi.org/10.5061/dryad.b8gtht7n5](https://doi.org/10.5061/dryad.b8gtht7n5)

## Description of the data and file structure

This dataset contains digitised polygons representing loggerhead turtle nesting beaches across the globe. The data were obtained by delineating polygons using Google satellite imagery within QGIS 3.32.2 (QGIS Development Team, 2020). Spatial-temporal fluctuations of nest counts across nesting grounds were analyzed using the Mann-Kendall trend analysis (Kendall, 1990) with the ‘MannKendall’ function in the R package ‘Kendall’. The dataset **does not include locations of nests**, and the polygons represent generalised beach boundaries** **and no precise nesting locations or coordinates have been included. 



**File structure**

**Shapefile:** `nestingbeaches_GCB.shp`

* **Code:** Individual polygon code representing one beach.
* **Beach Name:** Name of the beach, when available.
* **Country:** Country where each beach is located..
* **State:** State/ island/ region of the country where each beach is located.
* **RMU:** Regional management unit.
* **MannKendal:** Mann-Kendall slope of loggerhead turtle nesting trends.

## Code/Software

This dataset was processed and analysed using the following software:

* **QGIS:** Version 3.32.2 (QGIS Development Team, 2020)
* \**R: ** Version 4.3.0 (R Core Team, 2023). 
* \**R Packages: '**Kendall', used for Mann-Kendall trend analysis.

