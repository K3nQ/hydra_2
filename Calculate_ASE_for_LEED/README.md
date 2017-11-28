### Description 
Annual Sun Exposure (ASE) is calculated for the LEED v4 daylight credit. This example breaks down the calculation methods of ASE into discrete components so that you can understand what ASE means and calculate it for your building geometry.

Specifically, ASE measures the percentage of floor area that receives more than 1000 lux of DIRECT SUN ONLY for more than 250 occupied hours per year. As such, this example begins by calculating only the direct sun falling on a horizontal outdoor surface. This is then multiplied by window transmittance and used to select sun positions that only have values above the 100 lux threshold. The resulting sun vectors are then used in a "sunlight hours" calculation to determine the floor area that exceeds 250 hours per year.

The Illuminating Engineering Society's (IES) published guide "Lighting Measurement 83 (LM-83)" cautions that spaces with more than 10% ASE will likely result in visual discomfort. This guideline has been adopted by LEED and this example will tell you whether you are meeting or failing these criteria.

This file has been submitted by [chriswmackey](https://github.com/chriswmackey)

[Check out this example on Hydra!](http://hydrashare.github.io/hydra/viewer?owner=chriswmackey&fork=hydra_2&id=Calculate_ASE_for_LEED)
### Tags 
LBExampleFiles, EPW, Climate, Glare, Direct, Sun, Solar, Annual, Exposure, ASE, LEED v4, HumanCenteredFacades, Grasshopper
### Thumbnail 
![Screenshot](https://raw.githubusercontent.com/chriswmackey/hydra/master/Calculate_ASE_for_LEED/thumbnail.png)
