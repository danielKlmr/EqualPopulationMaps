# Equal Population Maps

These notebooks allow you to take a country's population data and create a dataset where the country is divided into a specified number of areas with the same population.

I have used them to create equal population maps for Austria, but by changing the input data, the code can be used for any country or any other type of administrative area.

![Austria](/figures/equal_population_austria_flag_en.png "Austria")

## How to Use

After downloading the input data, Use the Jupyter notebook _"./notebooks/1-processing.ipynb"_ to prepare the dataset. This also describes which input data you need to download. The dataset can then be used in _"./notebooks/2-create_map.ipynb"_ to create the resulting map.

The last section of the file can be used to create files for animations like below.

![Animation](/figures/equal_population_austria_animated_en.gif "Animation")

The result is saved in _"./data/result/country_splitted.gpkg"_, which can be opened with GIS software such as QGIS.

## Sources

The data sources for the Austrian Equal Population Map are listed below.

- Eurostat (2024): Population and housing census 2021 - population grids. www.ec.europa.eu/eurostat/statistics-explained/index.php?title=Population_and_housing_census_2021_-_population_grids.
- Runfola, D. et al. (2020) geoBoundaries: A global database of political administrative boundaries. www.geoboundaries.org/.