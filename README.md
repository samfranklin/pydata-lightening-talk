PyData Geospatial Lightening Talk
---

### Overview

This repo supports a 5-minute lightening talk "Getting Geospatial Work Done with the PyData Stack" I did at PyData Bristol in November 2019.

I give a walk through of the geopandas python pacakge, which extends the popular pandas package and allows visualisation of geographic data as well as performing geographic operations on data.

### Repo Contents
* pydata-slides.ipynb - jupyter notebook used to render the slides.
* pydata-slides.slides.html - rendered slides for talk
* data/london_boroughs.* - 'geospatial vector file presenting the London boroughs administrative areas, sourced from ...
* data/london-crime-data-july-2018.csv - csv table of crime data for July 2019, sourced from ...
* environment.yaml - conda yaml file for building the environment

If you have any queries, send me a message over on twitter https://twitter.com/SamRFranklin or raise an issue on the github repo. 

### Build

Recommend you use conda to build the python environment

```
# creat the env
conda env create --file ./envrionment.yml

# activate the environment
conda activate gpdenv

# start the jupyter notebook server
python notebook
```