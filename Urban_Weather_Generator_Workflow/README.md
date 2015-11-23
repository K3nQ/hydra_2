### Description 
This file shows you how to take building geometry from an urban area along with the OpenStudio libraries and warp rural/airport weather data to reflect the climate of the urban area (and its urban heat island). This is done using a heat balance algorithm in an engine called the urban weather generator.
To run this file, you will need to install the Dragonfly plugin by following the instructions [here](https://github.com/chriswmackey/Dragonfly/blob/master/resources/Installation_Instructions.MD).

The file introduces you to two ways to define building typologies for the urban weather generator: 1) by inputting parameters for a defal Commercial or Residential template and 2) by create a Honeybee Zone and converting it to a building typology for the urban weather generator.  In both cases, this file automatically assigns ASHRAE constructions to the buildings based on the OpenStudio library and the climate zone of the EPW weather file.

This file has been submitted by [chriswmackey](https://github.com/chriswmackey)

[Check out this example on Hydra!](http://hydrashare.github.io/hydra/viewer?owner=chriswmackey&fork=hydra_2&id=Urban_Weather_Generator_Workflow)
### Tags 
DFExampleFiles, Dragonfly, Urban, Weather, Generator, EPW, Climate, Heat, Island, Effect, Workflow, MIT, Urban Microclimate
### Thumbnail 
![Screenshot](https://raw.githubusercontent.com/chriswmackey/hydra/master/Urban_Weather_Generator_Workflow/thumbnail.png)
