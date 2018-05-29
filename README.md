# Processing German Capacities
Script to preprocess german energy capacities.

## About this script

This notebook pre-processes German energy capacities from the [*Open Power System Data*](https://open-power-system-data.org/) project.


The district heating data is derived from the [*AGFW | Der Energieeffizienzverband für Wärme, Kälte und KWK e. V.*](https://www.agfw.de/).


Further, the script applies different lifetime assumptions for each technology and plots the results per fuel and technology until 2050.


The user can choose from different levels of aggregation that take the current electricity grid bottlenecks into accout.
All necessary output directories are automatically created and the conventional and renewable power plants tables are directly downloaded to the input folder.


## Sources

All further used sources to the above mentioned are stated within the script.
