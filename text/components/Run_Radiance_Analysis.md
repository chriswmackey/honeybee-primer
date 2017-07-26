## ![](../../images/icons/Run_Radiance_Analysis.png) Run Radiance Analysis

![](../../images/components/Run_Radiance_Analysis.png)

Run Radiance Analysis

#### Inputs
* ##### analysisRecipe [Required]
Radiance analysis recipe. You can find the recipes under
* ##### HBObjects [Required]
A flatten list of Honeybee surfaces and zones.
* ##### radScene [Optional]
A honeybee radiance scene that will be considered as the context
* ##### folder [Default]
An optional folder to save the files for this analysis.
* ##### name [Default]
An optional name for this analysis.
* ##### write [Required]
Set to True to write the files to the folder.
* ##### run [Optional]
Set to True to run the analysis. You can only run the analysis if

#### Outputs
* ##### readMe!
Reports, errors, warnings, etc.
* ##### legendPar
Suggested legend parameters based on the recipe.
* ##### results
Results of the analysis. Results can be a list of images or


[Check Hydra Example Files for Run Radiance Analysis](https://hydrashare.github.io/hydra/index.html?keywords=HoneybeePlus_Run Radiance Analysis)