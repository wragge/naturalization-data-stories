# Naturalization data stories

This repository includes data and code relating to the article:

Kate Bagnall and Tim Sherratt. 'Missing Links: Data Stories from the Archive of British Settler Colonial Citizenship', *Journal of World History*, vol. 32, no. 2, 2021, pp. 281-300. <[http://doi:10.1353/jwh.2021.0025](https://doi.org/10.1353/jwh.2021.0025)>.

## Data by jurisdiction

### New South Wales

* [NSW naturalizations data from NSW State Archives](nsw_naturalisations.ipynb)
* [CSV file](nsw_country_counts.csv) with count of records by `NativePlace` field
* [CSV file](nsw_from_china.csv) with records where `NativePlace` is in China and region
* [CSV file](nsw_deduped_with_country.csv) with deduplicated records

### Queensland

* [Adding series information to the Naturalisations index from Queensland State Archives](qld_add_series_info_to_naturalisations_index.ipynb)
* [Exploring the Queensland naturalisation index from Queensland State Archives](qld_explore_naturalisation_index.ipynb)
* [CSV file](qsa_naturalisations_index_with_series.csv) containing naturalisation index entries with series identifiers

### South Australia

* [Harvest South Australian naturalization records in the National Archives of Australia](naa_south_australia_harvesting.ipynb)
* [Explore South Australian naturalization records in the National Archives of Australia](naa_south_australia.ipynb)
* [CSV file](naa_south_australia_combined.csv) containing details of harvested items

### Tasmania

* [Explore Tasmanian Naturalisations (1835-1904)](tas_exploring_naturalisations.ipynb)

### Victoria

* [Harvest Victorian naturalization records in the National Archives of Australia](naa_victoria_harvesting.ipynb)
* [Explore Victorian naturalization records in the National Archives of Australia](naa_victoria.ipynb)
* [CSV file](naa_victoria_combined.csv) containing details of harvested items

### New Zealand

* Data from Series 8333 in Archives New Zealand was saved using the [Archway harvesting notebook](https://glam-workbench.net/archway/) in the GLAM Workbench.
* [Exploring naturalization records in Archives New Zealand](nz_exploring_8333.ipynb)
* [CSV file](series8333_naturalisation_1840_1905.csv) containing records harvested from Series 8333 – using keywords 'naturalisation' or 'naturalization' between 1840 and 1905.

### Canada

* Full details of harvesting data from the Library and Archives Canada database of naturalization records are included in the [LAC section](https://glam-workbench.net/lac/) of the GLAM Workbench.
* [Exploring Canadian naturalization records, 1915 to 1946](lac_canada_naturalisations.ipynb)
* [CSV file](https://github.com/GLAM-Workbench/library-archives-canada/blob/master/lac-naturalisations-china.csv) containing records where `country` is listed as 'China'
* [CSV file](lac-naturalisations-china-with-families.csv) containing records where `country` is listed as 'China', supplemented with wives and children where possible.




