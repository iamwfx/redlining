## Census Data processing for HOLC maps
Jupyter notebook outlines how the census data was processed and labeled
- ` 00_AllData_CleanandCombine.ipynb`: Reads, cleans, and concats the Census and HOLC data. 
- `01_Census_LabelingandCrosswalk.ipynb`: Details method for crosswalk to 1940s Census tract boundaries and labeling tracts with HOLC grade.

## Data 
- The Census data used fhere is from the [IPUMS National Historical GIS database](https://www.nhgis.org/), which you can download from the site (and cite accordingly!).
- The HOLC data is from the [Mapping Inequality](https://dsl.richmond.edu/panorama/redlining) project. You can [contact them](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58&text=contactUs) to request the ata. 

## Citation 
If you would like to use the code from this repo, please use the following citation:

```
@article{doi:10.1080/10511482.2020.1858924,
author = {Wenfei Xu},
title = {Legacies of Institutionalized Redlining: A Comparison Between Speculative and Implemented Mortgage Risk Maps in Chicago, Illinois},
journal = {Housing Policy Debate},
volume = {0},
number = {0},
pages = {1-26},
year  = {2021},
publisher = {Routledge},
doi = {10.1080/10511482.2020.1858924},

URL = { 
        https://doi.org/10.1080/10511482.2020.1858924    
}
```
