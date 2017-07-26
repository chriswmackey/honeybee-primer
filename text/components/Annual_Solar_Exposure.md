## ![](../../images/icons/Annual_Solar_Exposure.png) Annual Solar Exposure

![](../../images/components/Annual_Solar_Exposure.png)

Calculate annual solar exposure (ASE).

#### Inputs
* ##### analysisGrid [Required]
An analysis grid output from run Radiance analysis.
* ##### blindStates [Optional]
List of state ids for all the sources for input hoys.
* ##### occSchedule [Default]
An annual occupancy schedule.
* ##### threshold [Default]
Threshhold for solar exposure in lux (default: 1000).
* ##### targetHrs [Default]
Minimum targe hours for each point (default: 250).
* ##### targetArea [Default]
Minimum target area percentage for this grid (default: 10)

#### Outputs
* ##### report
The execution information, as output and error streams
* ##### success
Script variable Python
* ##### perArea
Percentage area that doesn't meet the target.
* ##### prblmPts
A list of problematic test points.
* ##### prblmHrs
Problematic hours for each point.


[Check Hydra Example Files for Annual Solar Exposure](https://hydrashare.github.io/hydra/index.html?keywords=HoneybeePlus_Annual Solar Exposure)