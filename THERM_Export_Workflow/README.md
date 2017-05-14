### Description 
This file shows you how to use the new 'Export to THERM' workflow that is currently being developed for Honeybee.  The file walks you through how to assign material properties and boundary conditions to geomery, how to export this geometry to a THERM XML, and how to import the results back after you have run the THERM simulation.
The benefits of this workflow as opposed to using the THERM interface are threefold:
1) You can completely avoid the drawing interface of THERM, which is notoriuously difficult to manage in comparison to an interface like Rhino.  Note that you still need to open the exported file in THERM but all that you have to do is hit 'simulate' and you do not need to adjust anything else as your materials and boundary conditions are assigned in GH.
2) You can coordinate your THERM models more closely with your Honeybee EnergyPlus models since this worklfow allows you to use materals from both the THERM and EnergyPlus library.  The workflow also allows you to import the U-values from the THERM results to define new constructiosn for your EnergyPlus model.  Furthermore, the workflow helps you coordinate between your energy model geometry and the THERM geometry by automatically converting between Rhino space and the THERM drawing space.
3) As with any of the ladybug visualizations, you now gain the ability to visualize the THERM mesh and datapoints any way you like with any color shceme, legend, etc.  The importing of the mesh point data into GH also give you new geometric capabilities like obvserving the average temperature of a certain part of a mesh.
To use this file, you wil need to download and install THERM [here]( https://windows.lbl.gov/software/therm/7/index_7_5_13.html)

This file has been submitted by [chriswmackey](https://github.com/chriswmackey)

[Check out this example on Hydra!](http://hydrashare.github.io/hydra/viewer?owner=chriswmackey&fork=hydra_2&id=THERM_Export_Workflow)
### Tags 
HBExampleFiles, Honyebee, THERM, Export, Geometry, Polygon, Boundary, Condition, Finite, Element, Heat, Transfer, Conduction, LBNL, Steady State, U-Value, R-Value, Energy, Glazing, Grasshopper
### Thumbnail 
![Screenshot](https://raw.githubusercontent.com/chriswmackey/hydra/master/THERM_Export_Workflow/thumbnail.png)
