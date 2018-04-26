### Description 
This file shows you how to run the Honeybee Energy Shade benefit components.
Such energy shade benefit compares the cooling load decreased and heating load increased by adding shade in different regions of a surface where shade is being considered.
The methods used by the component are [described in this paper](http://www.ibpsa.org/proceedings/BS2011/P_1209.pdf)

If you are applying this model to a Honeybee energy model that you have built, note the following:
1) This workflow only works with ideal air loads and not fully-detailed HVAC systems.  This is because the component is looking at the solar energy contributed by each window to each zone to determine the value of shade.  So cooling/heating data must be on a zone-by-zone level.
2) Connecting unconditioned zones to the workflow can cause it to fail so it's recommended that only conditioned zones be connected to the "Window Shade Generator" component.

Also, be warned that this script takes a few minutes to run!

This file has been submitted by [chriswmackey](https://github.com/chriswmackey)

[Check out this example on Hydra!](http://hydrashare.github.io/hydra/viewer?owner=chriswmackey&fork=hydra_2&id=Energy_Shade_Benefit)
### Tags 
HBExampleFiles, Honyebee, EPW, Weather, Climate, Energy, Shade, Benefit, Harm
### Thumbnail 
![Screenshot](https://raw.githubusercontent.com/chriswmackey/hydra/master/Energy_Shade_Benefit/thumbnail.png)
