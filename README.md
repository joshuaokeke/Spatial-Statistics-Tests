# Introduction
This repository contains the R Markdown document and associated files for the spatial statistics lab exercise. The exercise covers various spatial statistics techniques using R, including GAM, Kulldorff’s spatial scan statistics, Besag and Newell's Statistic for Spatial Clustering, and Stone test.

## Libraries Used

```R
library(sp)
library(spatstat)
library(sf)
library(spatstat.geom)
library(ctv)
library(terra)
library(spdep)
library(rgdal)
library(RColorBrewer)
library(classInt)
library(epitools)
library(DCluster)
```

## Instructions

1. Clone or download this repository to your local machine.
2. Open the `Spatial_Statistics_Lab7.Rmd` file in RStudio.
3. Install any required R packages mentioned in the document.
4. Run the code chunks sequentially to execute the analysis steps.
5. Read the explanations provided in the document to understand each step of the analysis.

## Analysis Steps
1. **Loading Sids Data**: Loading and preprocessing spatial data.
2. **GAM using the centroids of the areas in data**: Performing Generalized Additive Models (GAM) and visualizing the results.
3. **Kulldorff’s Spatial Scan Statistics**: Implementing Kulldorff’s spatial scan statistics and visualizing the results.
4. **Besag and Newell's Statistic for Spatial Clustering**: Performing Besag and Newell’s test for spatial clustering and visualizing the results.
5. **Stone Test**: Conducting Stone's test for a specific county and interpreting the results.

## Questions and Discussion

1. Describe the pattern observed in the GAM analysis.
2. Describe the differences between the GAM results obtained at alpha levels 0.002 and 0.05.
3. Describe the pattern observed in the Kulldorff’s spatial scan statistics analysis.
4. Describe the differences in patterns between Kulldorff’s spatial scan statistics results obtained at different population fractions.
5. Describe the patterns observed in the Besag and Newell’s Statistic for Spatial Clustering analysis for different values of K.
6. Compare the results of the Besag and Newell’s Statistic for Spatial Clustering with those from the local Getis G* and local Moran’s I analyses conducted in Lab 6.
7. Describe the pattern observed in the Stone test for a specific county.

