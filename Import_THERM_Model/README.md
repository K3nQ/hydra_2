### Description 
This file shows you how import a THERM model into Grasshopper from a THERM XML file. The resulting imported geometries possess all material and boundary condition properties that exist in the original THERM XML such that they can be written into any new THERM XML files.
The file also shows how to do a few simple and useful analyses of the THERM results with the help of Rhino/Grasshopper's geometric calculation abilities.  These include:
1) The visualization of only parts of the mesh below/above a certain threshold.
2) The calculation of an average temperature along a line/polyline.
3) The selection of the coldest/warmest point in a given region.
All of these operations are useful for identifying condensation within constructions and helping decide where to locate vapor barrirers in the construction.
To use this file, you wil need to download and install [THERM](https://windows.lbl.gov/software/therm)
 Also, it is recommended that you familiarize yourself with the basics of the THERM export workflow using [this example file](http://hydrashare.github.io/hydra/viewer?owner=chriswmackey&fork=hydra_2&id=THERM_Export_Workflow).

This file has been submitted by [chriswmackey](https://github.com/chriswmackey)

[Check out this example on Hydra!](http://hydrashare.github.io/hydra/viewer?owner=chriswmackey&fork=hydra_2&id=Import_THERM_Model)
### Tags 
HBExampleFiles, Honyebee, THERM, Export, Geometry, Polygon, Boundary, Condition, Finite, Element, Heat, Transfer, Conduction, LBNL, Steady State, U-Value, R-Value, Energy, Glazing, Thermal, Bridging, Bridge, Wall, Construction, Conduction, Condensation, Import, XML, Grasshopper
### Thumbnail 
![Screenshot](https://raw.githubusercontent.com/chriswmackey/hydra/master/Import_THERM_Model/thumbnail.png)
