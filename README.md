# Remote Sensing Project

## Project objectives

- Determine which GEOS API endpoints would provide soil data.

- Explore those endpoints by retrieving data to see what types of soil data is available to enable data science team to further explore useful applications with the data.

## About the scripts
- To retrieve both structured and unstructured soil data via (GEOS/Swagger) API, 2 python scripts have been written to make the API requests or "call".

- Each script uses different endpoints and different input data to make API requests, and each script ran would receive different types of soil data from the API requests made.

- Script 1 takes in the choice of dates and coordinates of polygonal farms to acquire tiff images (unstructured data) of the farms when making API requests.

- Script 2 takes in the farms' centroid values, i.e. a pair of lat-lon coordinates, to get soil layers and its data (structured data) when making API requests.
