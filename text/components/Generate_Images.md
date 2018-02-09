## ![](../../images/icons/Generate_Images.png) Generate Images - [[source code]](https://github.com/ladybug-tools/honeybee-grasshopper/tree/master/plugin/grasshopper/src/HoneybeePlus_Generate%20Images.py)

![](../../images/components/Generate_Images.png)

Hourly results for a sensor for several hours during the year.

#### Inputs
* ##### imgCollection [Required]
An imgage collection from the results of an image-based
* ##### hoys [Optional]
An optional list of hours for hours of the year if you don't want
* ##### blindStates [Optional]
A list of blind states for light sources as tuples for
* ##### mode [Default]
An integer between 0-3.

#### Outputs
* ##### report
The filepath of the image taken with this component.
* ##### images
The filepath of the image taken with this component.


[Check Hydra Example Files for Generate Images](https://hydrashare.github.io/hydra/index.html?keywords=HoneybeePlus_Generate Images)