## ![](../../images/icons/Image-Based_Recipe.png) Image-Based Recipe

![](../../images/components/Image-Based_Recipe.png)

Image-based Recipe.

#### Inputs
* ##### sky [Required]
A radiance sky. Find honeybee skies under 02::Daylight::Light Sources.
* ##### views [Required]
A list or a datatree of points. Each branch of the datatree
* ##### analysisType [Default]
Analysis type. [0] illuminance(lux), [1] radiation (kwh),
* ##### radiancePar [Default]
Radiance parameters for Grid-based analysis. Find Radiance

#### Outputs
* ##### analysisRecipe
Grid-based analysis recipe. Connect this recipe to


[Check Hydra Example Files for Image-Based Recipe](https://hydrashare.github.io/hydra/index.html?keywords=HoneybeePlus_Image-Based Recipe)