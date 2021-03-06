
## Codes for *Leberger et al., 2018. Mediterranean wetland conservation in the context of climate and land cover change.*

## I. Climate data processing from Chelsa https://www.wsl.ch/lud/chelsa/data/timeseries/

### 1.1. Download monthly climate data
Download prec, tmax, tmin, and tmean from 1986 to 1995 and from 2001 to 2010.\
***Code:** 1.1.Download_climate_data.R*

### 1.2. Process climate data
Use the download variables to generate the yearly variables : tmean, tmax, tmin, tseas, pmean, pdry, pwet, pseas.\
***Code:** 1.2.Process_climate_data.R*

## II. Partial Triadic Analysis (PTA)
**Climatic PTA:** *2.1.PTA_climate.R*\
**Land-cover PTA:** *2.2.PTA_land_cover.R*\
**Climatic and Land-cover PTA:** *2.3.PTA_clim_lc.R*

## III. Statistics: Kruskal-Wallis tests

Use Kruskal-Wallis on all set of variables to test for differences accross protection coverage classes.\
**Code:** *3.Kruskal_Wallis_PAs.R*

## IV. Models: glm Poisson, beta-regression, linear model

Use model on natural wetlands loss, beta-Sorensen and Simpson diversity to test for influence from different variables.\
**Natural wetlands:** *4.1.Model_Natwet_glm.R*\
**Beta-Sorensen:** *4.2.Model_BetaSor_betareg.R*\
**Simpson diversity:** *4.3.Model_SimpDiv_lm.R*

## V. Figures
*5.FigS5_boxplot_KW_location.R*
