# Feature Selection
## Using Boruta in Random Forest

Feature Selection = The process of finding relevant meteorological characteristics and discarding unnecessary features for the study

This method assisted to identify the important attributes and whether those attributes were relevant to be 
used for study

Some packages need to be installed to use Boruta techniques:
- `Boruta`
- `mlbench`
- `caret`
- `randomForest`

`doTrace` argument controls the amount of output printed to the console.
<br> `TentativeRoughFix` used to get the significant attributes. 
- `TentativeRoughFix` will handle tentative qualities that are either extremely important or extremely insignificant and will classify them accordingly.

<br> `attStats` used to return a data frame with the Z score statistics for each attribute as well as the percentage of random forest runs in which this attribute was more significant than the most important shadow attribute
- Show whether the variables were confirmed or rejected. The Z scores referred to the importance values.
- By comparing the median Z score of the characteristics with the median Z score of the best shadow attribute, the tentative attributes will either be confirmed or rejected.
