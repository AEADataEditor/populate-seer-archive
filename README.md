# SEER U.S. Population Data - 1969-2019

Released February 2021

## Remark

The files in this deposit were downloaded from the SEER website at [https://seer.cancer.gov/popdata/download.html](https://seer.cancer.gov/popdata/download.html) on July 28, 2021 by the AEA Data Editor. They are archived here because the NIH National Cancer Institute does not assign permanent identifiers, nor explicitly guarantee the preservation of these files. 

Other than downloading these files, they are unmodified. 

## License

These files are produced by the U.S. Federal Government and are in the public domain.

------
The following text was taken verbatim from the SEER website at [https://seer.cancer.gov/popdata/](https://seer.cancer.gov/popdata/) on July 28, 2021, and is presented as-is, unless [*otherwise indicated*].

------

## U.S. Population Data - 1969-2019

Released February 2021

The county population estimates currently used in the SEER\*Stat software to calculate cancer incidence and mortality rates are available for download (see [Download U.S. Population Data](https://seer.cancer.gov/popdata/download.html)). They represent a modification of the intercensal and Vintage 2019 annual time series of July 1, county population estimates by age, sex, race, and Hispanic origin produced by the [U.S. Census Bureau's Population Estimates Program](https://www.census.gov/data/datasets/time-series/demo/popest/2010s-counties-detail.html), in collaboration with the National Center for Health Statistics, and with support from the NCI through an interagency agreement. The modifications made by the NCI to the Census Bureau estimates are documented in [Population Estimates Used in NCI’s SEER\*Stat Software](https://seer.cancer.gov/popdata/methods.html) [*local copy: "Estimates Used in SEER\*Stat Software - SEER Population Data.pdf"*] and are summarized below.

- The population estimates incorporate intercensal (for July 1, 2000-2009) and Vintage 2019 (for July 1, 2010- 2019) bridged race estimates that are derived from the original multiple race categories in the 2000 and 2010 Censuses. The bridged race estimates and a description of the methodology used to develop them appear on the National Center for Health Statistics Web site.
- A modification that NCI has made to the Census Bureau estimates only affects population estimates for the state of Hawaii. Based on concerns that the native Hawaiian population has been vastly undercounted in previous censuses, the Epidemiology Program of the [Hawaii Cancer Research Center](http://www.uhcancercenter.org/) has recommended an adjustment to the populations for their state. The "Hawaii-adjustment" to the Census Bureau’s estimates has the net result of reducing the estimated white population and increasing the estimated Asian and Pacific Islander population for the state. The estimates for the total population, black population, and American Indian and Alaska Native populations in Hawaii are not modified.
- Two sets of population estimates are available for 2005: the standard set based on July 1 populations and another set adjusted for population shifts due to hurricanes Katrina (August 29) and Rita (September 24). These estimates are lower for counties/parishes that had direct hurricane impact and higher for counties/parishes that were destinations for those displaced. See [Adjusted Populations for the Counties/Parishes Affected by Hurricane Katrina and Rita](https://seer.cancer.gov/popdata/hurricane_adj.html) for more information.

Single year of age population estimates by county are available ([Download U.S. Population Data](https://seer.cancer.gov/popdata/download.html)). The methods used to create these estimates are described in [Single Year of Age County Population Estimates](https://seer.cancer.gov/popdata/singleages.html) [*local copy: SEER Single Year of Age County Population Estimates - SEER Population Data.pdf*].

------
The following text was taken verbatim from the SEER website at [https://seer.cancer.gov/popdata/download.html](https://seer.cancer.gov/popdata/download.html) on July 28, 2021, and is presented as-is, unless [*otherwise indicated*].

------

## Notes

The U.S. Census Bureau annually releases [unbridged population estimates for five-year age groups and race at the county level](https://www.census.gov/programs-surveys/popest.html). The Census Bureau does not release bridged race estimates by single year of age at the county level due to concerns about the reliability of these estimates. However, these estimates are provided to the National Cancer Institute to meet programmatic needs such as the creation of age groupings that differ from the standard groupings used by the Census Bureau. Users of the single-year-of-age county-level bridged race population estimates should carefully consider the limited reliability of these estimates.

Annual data releases include both an additional year of data and updates to previous estimates for all years going back to the last decennial census (see [Population Estimates Used in NCI's SEER*Stat Software](https://seer.cancer.gov/popdata/methods.html)).

## Available Files

Populations are available for the following time periods and "races":

- 1969-2019 County-level: White, Black, Other;
- 1990-2019 County-level: Expanded Races (White, Black, American Indian/Alaska Native, Asian/Pacific Islander) by Origin (Hispanic, Non-Hispanic);

County-level population files with 19 age groups (<1, 1-4, ..., 80-84, 85+) and with 86 single-year age groups (<1, 1, 2, ..., 84, 85+) are provided below.

For the All States Combined and four states (Alabama, Louisiana, Mississippi, and Texas), two sets of population estimates are available for 2005: the standard set based on July 1 populations and a set that has been adjusted for the population shifts due to hurricanes Katrina (August 29) and Rita (September 24). For more information, see [Adjusted Populations for the Counties/Parishes Affected by Hurricanes Katrina and Rita](https://seer.cancer.gov/popdata/hurricane_adj.html).

## Data Files for Download

The data are stored in text files and provided here as [] gzip files. File format information is provided in the [Population Data Dictionary](https://seer.cancer.gov/popdata/popdic.html) [*local copy: [SEER Data Dictionary for U.S. Population Estimates - SEER Population Data.pdf](SEER Data Dictionary for U.S. Population Estimates - SEER Population Data.pdf)*]. The files are grouped by the following categories:

-   County-level Population Files - 19 Age Groups
-   County-level Population Files -Single-year Age Groups

----
[*The following list was modified from the original version. Only files present in this repository are listed.*]

----

### County-Level Population Files - 19 Age Groups

| State | 1969-2019 White, Black, Other | 1990-2019 4 Expanded Races by Origin |
|-------|-------------------------------|-------------------------------------------------|
| All States Combined (adjusted) | us.1969_2019.19ages.adjusted..gz | us.1990_2019.19ages.adjusted..gz |
| All States Combined | us.1969_2019.19ages.gz | us.1990_2019.19ages.gz |

[*(state-level files not archived)*]


### County-Level Population Files - Single-year Age Groups

| State | 1969-2019 White, Black, Other | 1990-2019 4 Expanded Races by Origin |
|-------|-------------------------------|-------------------------------------------------|
| All States Combined (adjusted) | us.1969_2019.singleages.adjusted..gz | us.1990_2019.singleages.adjusted..gz |
| All States Combined | us.1969_2019.singleages.gz | us.1990_2019.singleages.gz |

[*(state-level files not archived)*]

