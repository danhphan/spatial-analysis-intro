# Spatial Analysis Introduction

An introduction on spatial analysis with python. 

This project uses a study case to introduce basic geometry operations and fundemental spatial analysis skills for newcomers.

## We going to explore the crime rate in Victora.

The crime index is calculated for every postcode, similar to [the burglarystatistics at racv website](https://www.racv.com.au/in-your-home/in-your-home/burglary-statistics.html#postCode=3168).

### Datasets

The datasets are publicly available from following websites:

[Crime statistics in Vic in postcodes](https://www.crimestatistics.vic.gov.au/crime-statistics/latest-victorian-crime-data/download-data-0)

[Community profile by postcodes from ABS census](https://datapacks.censusdata.abs.gov.au/datapacks/)
https://www.racv.com.au/in-your-home/in-your-home/burglary-statistics.html#postCode=3168

## Table of Content
| <!-- -->                          | <!-- -->                         |
| --------------------------------  | -------------------------------- |
| Geometry with Shapely           | [01_It-starts-with-a-point.ipynb](https://github.com/danhphan/spatial-analysis-intro/blob/main/notebooks/01_It-starts-with-a-point.ipynb) |
| Tabular analysis with Pandas    | [02_Tabular-analysis-with-pandas.ipynb](https://github.com/danhphan/spatial-analysis-intro/blob/main/notebooks/02_Tabular-analysis-with-pandas.ipynb) |
| Spatial analysis with Geopandas | [03_Spatial-analysis-with-geopandas.ipynb](https://github.com/danhphan/spatial-analysis-intro/blob/main/notebooks/03_Spatial-analysis-with-geopandas.ipynb) | 
| Victoria household info         | [04_Melbourne_households.ipynb](https://github.com/danhphan/spatial-analysis-intro/blob/main/notebooks/04_Melbourne_households.ipynb) |
| Victoria crime index            | [05_Melbourne-crime-index.ipynb](https://github.com/danhphan/spatial-analysis-intro/blob/main/notebooks/05_Melbourne-crime-index.ipynb)| 
| Visualising spatial data        | [06_Visualise_spatial_data.ipynb](https://github.com/danhphan/spatial-analysis-intro/blob/main/notebooks/06_Visualise_spatial_data.ipynb) | 


## Installation notes

Following this tutorial will require recent installations of:

- Python >= 3.6
- requests
- numpy
- shapely
- matplotlib
- pandas
- geopandas >= 0.3.0
- matplotlib
- rtree
- PySAL
- xlrd
- openpyxl
- folium
- seaborn
- mapclassify
- [Jupyter Notebook](http://jupyter.org)

If you do not yet have these packages installed, it is recommended to use the [conda](http://conda.pydata.org/docs/intro.html) package manager to install all the requirements 
(you can install [miniconda](http://conda.pydata.org/miniconda.html) or install the (larger) Anaconda
distribution, found at https://www.anaconda.com/download/).

Once this is installed, the following command will install all required packages in your Python environment:

```
conda create -n spatial python=3.7

conda activate spatial

pip install -r requirements.txt

```


#### Fix the error when read excel files using Pandas
!pip install xlrd
!pip install openpyxl