# Movies-ETL

## Resources
- Python 3.7.6
- Jupyter Notebook
- pgAdmin 4
- PostgreSQL 12.7
- Movie data from Wikipedia, IMDB, Kaggle

## Overview
The purpose of this project was to create an automated ETL (extract, transfrom, load) pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. 

## Steps & Results

### Extract
This step of the process included using Python to retrieve and read the data (e.g. JSON, CSV) from various sources such as Kaggle, IMDB and Wikipedia.

![Extract](https://user-images.githubusercontent.com/82347825/121813402-e01aff80-cc39-11eb-8068-af696df9353d.png)

### Transform
This step involved cleaning the data by removing and formatting corrupt data, locating null values, merging and filtering data points, and classifying data types.

![Transform](https://user-images.githubusercontent.com/82347825/121815598-4b1e0380-cc45-11eb-8972-47298ac8129b.png)

### Load
In this step we loaded the clean data into a SQL database.
![Load1](https://user-images.githubusercontent.com/82347825/121815694-ac45d700-cc45-11eb-9c96-344d59934f43.png)
![Load2](https://user-images.githubusercontent.com/82347825/121815696-af40c780-cc45-11eb-82f3-698e93878cf2.png)
![Load3](https://user-images.githubusercontent.com/82347825/121815697-b10a8b00-cc45-11eb-8a77-7819c5a51436.png)



