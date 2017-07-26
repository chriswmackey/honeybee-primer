## ![](../../images/icons/Grid-Based_Recipe.png) Grid-Based Recipe

![](../../images/components/Grid-Based_Recipe.png)

Grid-based Recipe.

#### Inputs
* ##### sky [Required]
A radiance sky. Find honeybee skies under 02::Daylight::Light Sources.
* ##### analysisGrids [Required]
A list or a datatree of points. Each branch of the datatree
* ##### analysisType [Default]
Analysis type. [0] illuminance(lux), [1] radiation (kwh),
* ##### radiancePar [Default]
Radiance parameters for Grid-based analysis. Find Radiance

#### Outputs
* ##### analysisRecipe
Grid-based analysis recipe. Connect this recipe to


[Check Hydra Example Files for Grid-Based Recipe](https://hydrashare.github.io/hydra/index.html?keywords=HoneybeePlus_Grid-Based Recipe)