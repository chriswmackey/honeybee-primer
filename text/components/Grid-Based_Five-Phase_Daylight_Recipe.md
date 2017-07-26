## ![](../../images/icons/Grid-Based_Five-Phase_Daylight_Recipe.png) Grid-Based Five-Phase Daylight Recipe

![](../../images/components/Grid-Based_Five-Phase_Daylight_Recipe.png)

Five-pahse daylight Recipe.

#### Inputs
* ##### skymtx [Required]
A sky matrix or a sky vector. Find honeybee skies under 02::Daylight::Light Sources.
* ##### analysisGrids [Required]
A list of Honeybee analysis grids.
* ##### analysisType [Default]
Analysis type. [0] illuminance(lux), [1] radiation (kwh),
* ##### vmtxPar [Default]
Script variable threePhaseRecipe
* ##### dmtxPar [Default]
Script variable threePhaseRecipe
* ##### reuseVmtx [Optional]
Script variable annualRecipe
* ##### reuseDmtx [Optional]
Script variable threePhaseRecipe

#### Outputs
* ##### analysisRecipe
Five-pahse analysis recipe. Connect this recipe to Run


[Check Hydra Example Files for Grid-Based Five-Phase Daylight Recipe](https://hydrashare.github.io/hydra/index.html?keywords=HoneybeePlus_Grid-Based Five-Phase Daylight Recipe)