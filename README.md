# Equal Population Maps

These notebooks allow you to take a country's population data and create a dataset where the country is divided into a specified number of areas with the same population.

I have used them to create equal population maps for Austria, but by changing the input data, the code can be used for any country or any other type of administrative area.

## How to Use

After downloading the input data, use the Jupyter notebook "./notebooks/1-processing.ipynb" to prepare the dataset. The dataset can then be used in "./notebooks/2-create_map.ipynb" to create the resulting map. The last section of the file can also be used to create files for animations.

The result is saved in "./data/result/country_splitted.gpkg", which can be opened with GIS software such as QGIS.

## Sources

The data sources for the Austrian Equal Population Map are listed below.

- Eurostat (2024): Population and housing census 2021 - population grids. www.ec.europa.eu/eurostat/statistics-explained/index.php?title=Population_and_housing_census_2021_-_population_grids.
- Runfola, D. et al. (2020) geoBoundaries: A global database of political administrative boundaries. www.geoboundaries.org/.