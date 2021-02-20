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
@article{xu_legacies_nodate,
	title = {Legacies of {Institutionalized} {Redlining}: {A} {Comparison} {Between} {Speculative} and {Implemented} {Mortgage} {Risk} {Maps} in {Chicago}},
	copyright = {All rights reserved},
	issn = {2152-050X},
	doi = {10.1080/10511482.2020.1858924},
	journal = {Housing Policy Debate},
	author = {Xu, Wenfei},
	note = {Publisher: Routledge},
	annote = {doi: 10.1080/10511482.2020.1858924}
}
```
