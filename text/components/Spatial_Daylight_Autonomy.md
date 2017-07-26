## ![](../../images/icons/Spatial_Daylight_Autonomy.png) Spatial Daylight Autonomy

![](../../images/components/Spatial_Daylight_Autonomy.png)

Calculate annual solar exposure (ASE).

#### Inputs
* ##### analysisGrid [Required]
An analysis grid output from run Radiance analysis.
* ##### blindStates [Optional]
List of state ids for all the sources for input hoys.
* ##### occSchedule [Default]
An annual occupancy schedule.
* ##### threshold [Default]
Threshhold for daylight autonomy in lux (default: 300).
* ##### targetArea [Default]
Minimum target area percentage for this grid (default: 55).

#### Outputs
* ##### report
The execution information, as output and error streams
* ##### sDA
Script variable Python
* ##### prblmHrs
Problematic hours for each point.


[Check Hydra Example Files for Spatial Daylight Autonomy](https://hydrashare.github.io/hydra/index.html?keywords=HoneybeePlus_Spatial Daylight Autonomy)