# FSA Access mapping
Foward sortation areas are defined by the first 3 characters in a postal code, and are a common unit of spatial analysis, especially when issues of PII are concerned. However, FSAs have issues that complicate their usage in spatial analysis: they are mutable, of varying sizes, and are often constituted of multi-part polygons.

This analysis focuses on comparing three metrics of assessing spatial assets:

1. Centroids
2. Homogenous zonal stats
3. Population weighted zonal statistics

The comparison will be evaluated through an assessment of travel time to nearest long term facility.

# Data

1. Long-term care facilities
2. Global friction surface
3. WorldPop gridded population
4. FSAs

![Map of population and FSAs](https://github.com/bpstewar/FSA_Access/blob/main/Documents/NS_population_FSAs_Health_Facilities.png)
![Map of traveltime to facilities](https://github.com/bpstewar/FSA_Access/blob/main/Documents/tt_longterm_care.png)
