## ![](../../images/icons/Maximum_Value.png) Maximum Value

![](../../images/components/Maximum_Value.png)

Maximum values for a grid.

#### Inputs
* ##### analysisGrid [Required]
An analysis grid output from run Radiance analysis.
* ##### hoys [Optional]
An optional list of hours for hours of the year if you don't want
* ##### blindStates [Optional]
A list of blind states for light sources as tuples for
* ##### mode [Default]
An integer between 0-2. 0 returns that total values, 1 returns

#### Outputs
* ##### values
A list of maximum values for each sensor.


[Check Hydra Example Files for Maximum Value](https://hydrashare.github.io/hydra/index.html?keywords=HoneybeePlus_Maximum Value)