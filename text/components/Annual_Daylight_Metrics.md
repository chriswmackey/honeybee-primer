## ![](../../images/icons/Annual_Daylight_Metrics.png) Annual Daylight Metrics

![](../../images/components/Annual_Daylight_Metrics.png)

Annual Daylight Metrics

#### Inputs
* ##### analysisGrid [Required]
An analysis grid output from run Radiance analysis.
* ##### blindStates [Optional]
List of state ids for all the sources for input hoys.
* ##### occSchedule [Default]
An annual occupancy schedule.
* ##### threshold [Default]
Threshhold for daylight autonomy in lux (default: 300).
* ##### minmax [Default]
A list for min, max value for useful daylight illuminance

#### Outputs
* ##### report
The execution information, as output and error streams
* ##### DA
Daylight autonomy. The percentage of time that each sensor
* ##### CDA
Continuous daylight autonomy.
* ##### UDI
Useful daylight illuminance. The percentage of time that illuminace
* ##### UDILess
The percentage of time that illuminace falls less than minimum
* ##### UDIMore
The percentage of time that illuminace falls more than maximum


[Check Hydra Example Files for Annual Daylight Metrics](https://hydrashare.github.io/hydra/index.html?keywords=HoneybeePlus_Annual Daylight Metrics)